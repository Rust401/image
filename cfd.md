# 一、背景
## 涂装废气
涂装行业主要污染物为漆雾（颗粒物）和VOCs（挥发性有机物）。漆雾颗粒微小（绝大部分在10μm以下）、黏度大、易黏附在物质表面，可以采用漆雾干式和漆雾湿式净化技术去除漆雾。涂装有机废气主要成分为苯、甲苯、二甲苯、非甲烷总烃等挥发性有机物，可引起急性和慢性中毒，造成中枢神经系统及造血系统损害。[1]  
国外对涂装废气VOCs的处理进行了广泛的研究。主要处理方法主要有：吸收法、吸附法、燃烧法、冷凝法、吸附-催化燃烧法。[2]吸收法的净化率较低，为60%-80%,一般难以达到国家排放标准，且存在油雾夹带和二次污染等问题。活性炭吸附法净化率可达95%以上，但存在吸附饱和造成二次污染的风险。催化燃烧法适合于处理高浓度、小风量且废气温度较高的有机废气。喷漆废气中的三苯浓度一般低于300mg/m3，因此催化燃烧法也不适用。  
## 光催化
近年来，在有机废气处理的新技术中，光催化已成为具有前景的重要技术之一。光催化氧化（photocatalytic oxidation,PCO)是一种新兴的很具有应用前景的气体净化处理技术[3]。PCO空气净化技术通常是采用纳米半导体催化剂和紫外光（UV）将空气红的有机化合物转化成无害无害无气味的二氧化碳和水蒸气的混合物[3]。
## 等离子体
低温等离子体发生场具有强电离和离解特性，可诱导生成电子、中间体、自由基等活性物种，从而发生复杂的化学反应，目前多用于恶臭废气的处理。[6]在对低浓度VOCs的处理中，等离子场对VOCs完全氧化的选择性低，导致产生多种不完全氧化产物。此外，等离子体同时会产生大量的臭氧。[7]然而，臭氧只能降解特定的有机污染物，不能彻底矿化有机物。
最近有研究将低温等离子体与光催化氧化协同去除多组分、低浓度VOCs。低温等离子场的介入显著提升催化反应效果，两者之间产生显著的协同效应，特别是在对于低浓度VOCs的处理上，复合反应较单一等离子体和光催化技术有显著的提高，更具有传统VOCs处理技术所不具备的技术优势，应用前景良好。[8]将光催化与臭氧联用去除污染物也是一种很有前景的处理技术，臭氧可作为电子捕获剂，降低空穴与电子的复合率，提高光催化的效率；光催化则可提高臭氧分子利用效率和活性物种的产率。[9]
## 光催化反应器简介
PCO去除VOCs实际是一个表面反应过程，共包含两个主要的步骤：第一步是VOCs必须传递到光催化剂表面；第二部是VOCs在光催化剂表面发生降解反应。因此，VOCs的对流扩散传质速率，反应动力学速率和反应比表面积是PCO反应器非常重要的三个性能指标参数。由于影响PCO去除VOCs的性能的因素众多，单纯靠实验研究比较困难，因此需要模拟仿真的手段研究VOCs去除性能与影响因素之间的关系。  
Hossain et al.[12]将质量传递与反应动力学结合，首次提出了三维对流-扩散-反应模型来分析研究稳态情况下蜂窝PCO反应器中单个蜂窝通道对VOCs去除的性能，模拟结果与实验结果吻合较好。Hall et al.[10]提出了一个可以描述光催化蜂窝反应器的简化模型，同时还讨论了传质和反应速率控制。为了研究反应面积，质量传递，反应动力学速率和其它影响因素之间的相互作用关系，Zhang et al.[13],Yang et al.[14],Mo et al.[15]提出了一系列机理模型。Mo er al.[15]最终提出了一个一般化的模型来描述复杂的几何形状。他们分析得出反应器有效性能的术语（传质单元数NTUm）：几何参数，传质坦顿数和“反应效率”这三个参数进行线性运算的产物。对于PCO反应器，VOCs的转化率epsilon可以表示为[13，15]:  

    epsilon = (c_in-c_out)/c_in = 1 - exp(-NTUm)
    NTUm = A_r/Ac*Stm*eta = A_star*Stm*eta

理想情况下，PCO反应器的结构应该具有较高的比表面积，高的传质速率，以及UV光源直接照射在反应表面。通常情况下，PCO反应器的结构包含两个部分：反应结构支撑部分和UV灯源部分。其中的反应结构支撑不仅起到催化剂载体作用，还构成了气体流动的通道。因此，`A_star`和`Stm`的数值取决于反应器结构，UV灯源决定了了`eta`的数值。在绝大多数PCO反应器中，反应结构部分和UV灯源部分是彼此分开的，进而导致PCO过程会受到传质或者反应的影响[14]。这将会导致低的VOC去除效率和反应的不完全。由于缺乏反应结构和UV光源二者之间的互相协调，导致了PCO反应器设计的困难。 
有一种方法采用UV透明的材料作为反应结构。光纤采用裸露的可穿透UV光源的石英作为材质，并将此光纤作为光催化剂`TiO2`的支撑物，这样的结构设计将UV光源和反应结构整合成为一个整体。但使用这种反应器，`TiO2`涂层的厚度和光纤的长度会严重影响污染物的降解[18]。另一种有前景的PCO反应器设计是采用UV-LED建立一种蜂窝结构[19]。这种新设计的反应器克服了传统蜂窝反应器的缺点，其可提供较高的UV光强度。

# 二、数值模拟现状
由于光催化技术处理气体污染物与传统处理技术相比，其还是一种比较新的技术手段，现在还主要停留在实验基础研究阶段，现有的光催化反引起商业化应用程度不高，主要原因在于缺少健全和可行的能够用于光催化反应器放大，设计及优化的工具。计算流体力学技术已经被越来越多的研究人员采用，对光催化反应器进行研究。
## 计算流体力学简介
任何流体的流动行为都必须遵守三个基本的物理定律：  
* 质量守恒
* 牛顿第二定律
* 能量守恒

这些基本的物理定律可以用基本数学方程表示，大多是积分方程或者偏微分方程。计算流体力学（Computational Fluid Dynamics,CFD),是将这些数学方程中的积分项或者偏导数项替换为离散代数形式，通过求解这些离散代数形式的方程获得一系列时间或空间中每个离散点处有关流体流动变量的数据值。CFD最终实质得到的是一系列数据值的集合。近年来，随着计算机的发展，CFD得到了实质的发展应用。

## 基本控制方程
* 质量守恒方程（连续性方程）
* 动量守恒方程（NS方程）
* 能量方程
* 组分运输方程

## 求解方法
如何求解控制方程成为重点。鉴于这些控制方程的复杂性和非线性，直接求解这些偏微分方程已不现实。CFD采用数值数值计算的方法（即离散化方法）求解这些控制方程，常用的离散方法主要有有限差分、有限体积和有限元法。目前常用的CFD商业软件主要有`ANSYS FLUENT`、`CFX`、`PHOENICS`、`STAR-CD`。这些商用软件所采用的数值计算方法是有限体积法，有限体积法是一种特殊的有限差分方法。数值算法通常由一下三部分组成：  
* 对流动控制方程在计算域的所有有限控制体积内积分
* 将积分后的方程转换成代数方程
* 利用迭代方法对代数方程求解

该数值方法中的关键在于离散方程的导出过程中需要对目标函数及其导数的分布做出某种形式的假定。常用的差分格式有一阶迎风格式、二阶迎风格式、QUICK格式、中心差分格式、指数格式。

## 光催化数值模拟进展
Mosheni and Taghipour[20]采用CFD模拟和实验方法研究环形反应器中一氯乙烯的去除。实验工作包含使用工作包含使用微分反应器测量得到一氯乙烯氧化动力学数据，以及环形反应器中去除一氯乙烯。并将实验结果与模拟结果进行比较。从微型反应器获得的动力学数据被用于CFD模型预测环形反应器的性能。结果表明，模拟值和实验值吻合得较好，证明CFD可以被用于预测一氯乙烯得光催化反应。同时，CFD模拟可以提供反应器内部得流动信息，为反应器设计和优化提供理论依据。Taghipour and Mohseni[21]采用上述模拟方法还研究了三氯乙烯表面光催化反应，涉及不同反应器入口浓度、流场和反应器长度。同时也对环形光催化反应器得操作条件进行了优化设计。  
Salvado-Estivil et al.[22]将反应器内流体流动得CFD模拟与光源辐射场和光催化反应三者相结合，提出了一种严格得模型来预测平板反应器处理室内气体。使用这种模拟方法模拟光催化降解三氯乙烯过程，同时还直接从积分反应器动力学推导出动力学参数。模拟和实验设计不同的光照强度、入口浓度和流速条件下的三氯乙烯降解过程。模拟结果与在微分反应器中的实验结果相比较，表明污染物的动力学参数与反应器结构、辐射场和流体状态没有关系。因此，这些动力学参数可以被广泛用于设计和放大光催化反应器。Salvado-Estivil et al.[17]还提出了采用二维模型去模拟研究潘板反应器光催化降解三氯乙烯。将非稳态下二位对流扩散连续性返程与辐射场模拟和光催化反应动力学相结合，模拟反应器瞬态和稳态性能。由三维反应器CFD模型获得动力学参数，用于二位模型的模拟。通过与不同实验条件下的对比，二维的模拟结果与实验值很接近，同时也与三维的模拟结果很吻合。因此，二维模型可以减少计算的开销。  
Hossain et al.[12]提出了三维对流-扩散-反应模型模拟蜂窝单个通道中甲醛的氧化反应。该模型假设稳态操作，忽略轴向扩散和均相反应，并且严格考虑了流体流动的入口效应，并且采用作者之前提出的辐射场子模型模拟蜂窝通道中的UV光通量。在一定范围的甲醛入口浓度、湿度、蜂窝通道长度和蜂窝/灯源组合条件下，模拟预测结果与实验甲醛转化率测量结果吻合较好。经过进一步验证证明，文章提出的模型能够被用于 PCO 反应器设计和优化。  
Queffeulou et al.[23] 采用 CFD 方法模拟流体动力学和乙醛光催化反应。其中，模拟光催化反应所需输入的动力学数据是通过前期在间歇反应器中的动力学实验获得的。由于本证动力学参数与流体动力学、反应器结构和光强无关，因此可将这些参数用于不同构型反应器的模拟中。通过对比乙醛转化率，模拟结果与实验结果吻合地较好。Queffeulou et al.[24]还提出了模拟含有光催化空气净化装置的封闭空间内 VOC 时空浓度分布的模型。该装置是为处理室内空气而设计的。本征动力学参数是在另外单独的完全混合间歇式反应器实验获得的。之后再采用CFD 模拟封闭空间中流体的流动，并通过边界条件设置化学反应来计算VOC浓度时空分布。该模型提供了一种专为处理室内空气装置设计的方法。Wang et al.[25]模拟了以UV-LED为光源的新型光催化反应器。模拟的关键是UV-LED光源所形成的辐射场模拟，其自己建立了数学模型，并单独计算了辐射场。通过边界条件将辐射场的模拟结果引入到CFD求解器中，进而实现了描述反应器内流体流动和化学反应方程的同时求解。该模拟方法提供了一个基于LED光源光催化反应过程模拟的，同时也为反应器中的光源设计优化提供指导。  
Passalía et al.[26]还模拟了波纹状平板反应器中光催化氧化甲醛。首先根据动力学实验获得动力学参数，其次将这些动力学参数应用于波纹状平板反应器的模拟。反应器中光源发出的光强分布场采用表面发射模型单独计算，采用射线追踪法和视角因子计算。反应器内流体速度场和污染物浓度场的计算是通过商用CFD软件进行的。甲醛转化率的模拟结果与实验结果相比，其均方根误差在4%以内。  


# 三、实验系统
图`3-1`所示的是自制等离子体（PLASMA)与光催化(POC）组合工艺实验装置流程图。载气与VOCs进入预混罐后先经等离子体工艺（图`3-2`）处理，之后与雾化的臭氧一同进入光催化反应段（图`3-3`），最终进入尾气处理装置后排空。等离子段及光催化段进出口分别设置检测点用来测定工艺过程中各节点的VOCs转化率及矿化率。该协同工艺先由PLASMA段高压产生的等离子体对VOCs进行轰击，通过对分子键的作用将大分子VOCs转化为小分子VOCs再交由光催化段处理。PLASMA产生的粒子除臭氧外，存活时间均较短，因此臭氧随着被部分分解的VOCs在载气的运输下与雾化后的过氧化氢发生初步混合后进入POC段。POC段选取185nm+254nm的双波段紫外灯管作为光源，催化剂负载于环形反应器的壁面。  
![The System 3-1](https://raw.githubusercontent.com/Rust401/image/master/Total.png "The System 3-1")
![The plasma 3-2](https://raw.githubusercontent.com/Rust401/image/master/Plasma.png "The Plasma 3-2")
![The POC 3-3](https://raw.githubusercontent.com/Rust401/image/master/POC.png "The POC 3-3")
## 工艺及设备参数
        There is a list
## PLASMA段分析
PLASMA段的结构见图3-2，外部是一个圆柱形封闭容器，内部为双层中空圆柱形放电管，其两端接高压电源。运行时活性粒子从内外壁产生，与水平流过的内外侧气流相互作用发生反应。  
PLASMA段臭氧及其余活性粒子贴着双面管壁产生，但反应器尚未对活性粒子与进气的混合作出任何的优化。因此设想通过模拟测试不同的反应器尺寸、进气速度、扰动构件下的活性粒子与待处理气体的混合程度，来优化PLASMA段对VOCs污染物的去除效率。
## 光催化段分析
POC段结构见图3-3，外部是圆柱形封闭容器，内部为紫外灯管，与外部容器中心轴线同心，催化剂通过涂覆于瓦楞纸上布置在容器壁面。雾化后的过氧化氢与PLASMA段的出口气体进入反应器后在管中推进。紫外光照射催化剂下的催化剂形成空穴及自由基，并伴有臭氧产生，与前端的进气互相作用，VOCs在这个过程中部分被分解为小分子有机物，部分直接碳化。
由于尚未设置扰流构件，进气与催化剂的接触效率比较有限。因此考虑模拟不同的反应器尺寸，加装不同的扰流构件及设置不同的气体流速来优化反应器内部气体的混合，从而提高POC部分对VOCs的去除率及矿化率。  








[1] M. Kang, B.-J. Kim, S. M. Cho, C.-H. Chung, B.-W. Kim, G. Y. Han, K. J. Yoon, Decomposition of toluene using an atmospheric pressure plasma/TiO2 catalytic system. J. Mol. Cata. A- Chem., 2002, 180, 125-132.
[2] G. R. Pannar, N N. E. Rao, Control technologies for volatile organic compounds, Crit. Rev. Solid State Mater. Sci. 2009, 39, 41-78.  
[3] J. Mo, Y. Zhang, Q. Xu, J. J. Lamson, R. Zhao, Photocatalytic purification of volatile organic compounds in indoor air: A literature review, Atmos. Environ., 2009, 43, 2229-2246.  
[4] G. Liu, L. Wang, H. G. Yang, H.-M. Cheng, G.-Q. Lu, Titania-based photocatalysts-crystal growth, doping and heterostructuring, J. Mater. Chem., 2010, 20, 831-843.  
[5] C. Y. Chan, S. Tao, R. Dawson etc. Treatment of a-trazine by integrating photocatalytic and biological processes. Environ. Pollut., 2004, 131, 45-54.  
[6] T. Ochiai et al., An effective method for a separation of smoking area by using novel   
photocatalysis-plasma synergistic air-cleaner, Chem. Eng. J., 2012. 209, 313-317.
[7] C.W. Kwong, Y. H. C. Christopher, K. S. Hui, M. P. Wan, Removal of VOCs from indoor environment by ozonation over different porous materials, Atmos. Environ., 2008, 48, 2300-2311.  
[8] F. Thevenet, L. Sivachandiran, O. Guaitella, C. Barakat, A. Rousseau, Plasma-catalyst coupling for volatile organic compound removal and indoor air treatment: a review, J. Phys. D. Appl. Phys., 2014. 47, 224011.  
[9] F. J. Rivas, F. J. Beltrán, A. Encinas, Removal of emergent contaminants: integration of ozone and photocatalysis, J. Environ. Manage, 2012, 100, 10–15.   
[3]Tompkins  D  T.  Evaluation  of  photocatalytic  air  cleaning  capability: a literature review and engineering analysis. ASHARE Research Project RP-1134, 2001  
[10]Hall R T, Bendfeldt P, Obee T N, et al. Computational and experimental studies 
of UV/titania photocatalytic oxidation of VOCs in honeycomb monoliths. Journal of 
Advanced Oxidation Technologies, 1998, 3: 243–251  
[11]Yoneyama H, Torimoto T. Titanium dioxide/adsorbent hybrid photocatalysts for 
photodestruction  of  organic  substances  of  dilute  concentrations.  Catalysis  Today, 
2000, 58: 133–140   
[12]Hossain  M  M,  Raupp  G  B,  Hay  S  O,  et  al.  Three-dimensional  developing  flow 
model for photocatalytic monolith reactors. AIChE Journal, 1999, 45: 1309–1321   
[13]Zhang  Y  P,  Yang  R,  Zhao  R  Y.  A  model  for  analyzing  the  performance  of 
photocatalytic  air  cleaner  in  removing  volatile  organic  compounds.  Atmospheric 
Environment, 2003, 37: 1195–3399   
[14]Yang  R,  Zhang  Y  P,  Zhao  R  Y.  An  improved  model  for  analyzing  the 
performance  of  photocatalytic  oxidation  reactors  in  removing  volatile  organic 
compounds and its application. Journal of the Air & Waste Management Association, 
2004, 54: 1516–1184   
[15]Mo  J  H,  Zhang  Y  P,  Yang  R.  Novel  insight  into  VOC  removal  performance  of 
photocatalytic oxidation reactors. Indoor Air, 2005, 15: 291–300   
[16]Mo J H, Zhang Y P, Yang R, et al. Influence of fins on formaldehyde removal in 
annular photocatalytic reactors. Building and Environment, 2008, 43: 238–245   
[17]Salvado-Estivill  I,  Brucato  A,  Puma  G  L.  Two-dimensional  modeling  of  a 
flat-plate  photocatalytic  reactor  for  oxidation  of  indoor  air  pollutants.  Industrial  & 
Engineering Chemistry Research, 2007, 46: 7489–7496  
[18]Wang W, Ku Y, Ma C M., et al. Modeling of the photocatalytic decomposition of 
gaseous  benzene  in  a  TiO2  coated  optical  fiber  photoreactor.  Journal  of  Applied 
Electrochemistry, 2005, 35: 709–714   
[19]Yang  R,  Mo  J  H,  Zhang  Y  P,  et  al.  Patent:  a  kind  of  surface-light-source 
photocatalytic germicidal air purification device. P.R. China. 2006.   
[20]Mohseni  M,  Taghipour  F.  Experimental and CFD analysis of photocatalytic  gas 
phase  vinyl  chloride  (VC)  oxidation.  Chemical  Engineering  Science,  2004,  59: 
1601-1609   
[21]Taghipour  F,  Mohseni  M.  CFD simulation  of UV photocatalytic  reactors for air 
treatment. American Institute of Chemical Engineers, 2005, 51: 3039-3047   
[22]Salvado-Estivill  I,  Hargreaves  D  M,  Puma  G  L.  Evaluation  of  the  intrinsic 
photocatalytic  oxidation  kinetics  of  indoor  air  pollutants.  Environmental  Science  & 
Technology, 2007, 41: 2028-2035  
[23]Queffeulou  A,  Geron  L,  Archambeau  C,  et  al.  Kinetic  study  of  acetaldehyde 
photocatalytic  oxidation  with  a  thin  film  of  TiO2  coated  on  stainless  steel  and  CFD 
modeling  approach.  Industrial  &  Engineering  Chemistry  Research,  2010,  49: 
2690-6897   
[24]Queffeulou  A,  Geron  L,  Schaer  E.  Prediction  of  photocatalytic  air  purifier 
apparatus  performances  with  a  CFD  approach  using  experimentally  determined 
kinetic parameters. Chemical Engineering Science, 2010, 65: 5025-5074   
[25]Wang  Z,  Liu  J,  Dai  Y,  et  al.  CFD  modeling  of  a  UV-LED  photocatalytic  odor 
abatement  process  in  a  continuous  reactor.  Journal  of  Hazardous  Materials,  2012, 
215-216: 25-31   
[26]Passalía C, Alfano O M, Brandi R J. Modeling and experimental verification of a 
corrugated plate photocatalytic reactor using computational fluid dynamics. Industrial 
& Engineering Chemistry Research, 2011, 50: 9077-9086 




