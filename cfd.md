# Computer Network(2018-2019Spring_Summer)HW1
```shell
Student Name:   Zhaodong Hu
Student ID  :   21714069
Major       :   Environmental Engineering
Email       :   zhaodonghu94@zju.edu.cn
phone       :   15700080428
```
(1)
In network use the 1000 instead of 1024  
$(7*10^9*8bit)/(150*10^6bit/s)=5.6km$
```
 Distance smaller than 5.6km is ok.
    (i) critical point is 11.2km
    (ii) critical point is 11.2km
    (iii) critical point is 5.6km
```
(5)  
The distance between LA and NY is 3932.8km and we assume its 4000km.
$(4000km*1000m/km)/(2*10^8m/s)=0.02s=20ms$  
It's much **bigger** than 10 microsecond.

(10)
```
advantage:
(i) Each layer can be replace or added with no influence to other layer.
(ii) Simplify the design
disadvantage:
(i) Low performance, much overhead, need computing
```
(15)  
$E=(1-p)*1+(1-p)*p*2+(1-p)^2*p*3+...(1-p)^k*p*(k+1)...$   
$\Rightarrow$  
$E=1/(1-p)$  


(17)  
```
                                TCP                             UDP
Congestion Control              Y                               N
Established Connection          Y                               N
State                           Y                               N
Head length                     20 Bytes                        8 Bytes             
```

(22)  
$(2*10^8m/s)/(10*10^7bit/s)=20m/bit$  
(28)  
The change does nothing to the `k+1` layer and may influence the capacity and concurrency of the `k-1` layer.  
(30)  
```
    (i) Overhead of cell headers.
    (ii) wasted bandwidth on padding small pockects.
```
(33)
```sh
root@PC201606142047:~# ping berkeley.edu
PING berkeley.edu (35.163.72.93) 56(84) bytes of data.
64 bytes from ec2-35-163-72-93.us-west-2.compute.amazonaws.com (35.163.72.93): icmp_seq=1 ttl=35 time=239 ms

root@PC201606142047:~# ping mit.edu
PING mit.edu (23.217.168.218) 56(84) bytes of data.
64 bytes from a23-217-168-218.deploy.static.akamaitechnologies.com (23.217.168.218): icmp_seq=1 ttl=47 time=267 ms

root@PC201606142047:~# ping vu.nl
PING vu.nl (37.60.194.64) 56(84) bytes of data.
64 bytes from 37.60.194.64: icmp_seq=1 ttl=233 time=286 ms

root@PC201606142047:~# ping www.usyd.edu
PING www.usyd.edu (129.78.5.11) 56(84) bytes of data.
64 bytes from eicc.bio.usyd.edu.au (129.78.5.11): icmp_seq=1 ttl=229 time=252 ms

root@PC201606142047:~# ping www.uct.ac.za
PING ecm-vip-prd.uct.ac.za (137.158.154.230) 56(84) bytes of data.
^C
--- ecm-vip-prd.uct.ac.za ping statistics ---
58 packets transmitted, 0 received, 100% packet loss, time 57029ms

root@PC201606142047:~# ping baidu.com
PING baidu.com (123.125.115.110) 56(84) bytes of data.
64 bytes from 123.125.115.110: icmp_seq=1 ttl=52 time=29.9 ms

```



