## [Functional Specialization in the Attention Network](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7026883/)
>推送来源：[综述长文|注意网络的功能分离](https://mp.weixin.qq.com/s?__biz=MzIzMjIyMjQwNQ==&mid=2247484104&idx=1&sn=3d5d0250f462ff120a9cd0c5be762c80&chksm=e8997962dfeef0747caff85996f8a7353c58fdc890484118dff7c99ccfed655dd2547cf5d9e3&scene=126&sessionid=1616506603&key=b29dc7ac64daae53ed4cd1834611426353c313c67b6fd8c92b62b052e47a41e08947afcd0cfe87789d236566e4c909d9545a6a6d1b86359c6d38e47a1c7765bf5e20c297b16911a75911ea9c249c77344f7a15467d48bcf82444b5a95728ea3a08d5367ca4f4d478145acb7c1b2e3e8fbcc98c9d459fb968e1bc1642538d9afb&ascene=1&uin=NzE4NTkwNDg1&devicetype=Windows+10+x64&version=63000039&lang=zh_CN&exportkey=A%2Bx1pOrFlexW%2BrtPkmnPOBU%3D&pass_ticket=vIxK6NVAvmEpzTDJz090g5a8T64%2FI4H9rNQsm4T%2Fekmm7RTGUQM%2BWQ7bVXaa0S5Z&wx_header=0)
>1. 在视觉场景中，对目标位置的优先处理会引起相应的神经活动的变化和行为反应的改善。
>2. 注意网络是一个由皮层和皮层下结构组成的大规模网络，指导着对目标位置的优先处理(即空间注意)，该网络的不同节点与不同的注意相关功能相关联。
>3. 注意会受到自上而下的控制（额、顶叶高阶脑区调制感觉皮层的信息加工），此外，特定脑区对注意分配的引导还受到不同的加工阶段(engagement vs disengagement)和行为情境（刺激驱动注意vs目标导向注意）等因素的影响。
>4. 低频神经振荡（theta振荡）会暂时性地将注意网络的感觉功能和运动功能分隔开，在采样(sampling, 感觉功能)和转移(shifting, 运动功能)之间节律性地重新调整功能连接。
>5. 注意的选择和控制不仅基于皮层的计算，还来自于皮层下节点，如丘脑枕和上丘。
>6. 注意相关过程具有时间动态，注意网络中各个节点的功能贡献不断动态调整，从而和自然环境中的行为振荡相匹配。

### 摘要
空间注意由促进行为相关位置的感觉加工，且过滤竞争信息的神经机制构成。本综述探究脑网络中对这种感觉处理有偏好的功能特异性的区域。这种注意网络包括皮层（如额顶叶）和皮层下区域（上丘和枕核）。电生理和成像研究让我们认为，注意通过振荡对各个节点功能分离。各个维度（如不同的加工阶段和行为情境）上存在功能特异性，空间注意在这个过程中是动态的。注意网络每个节点功能上的作用会随时间改变，使我们对动态的环境具备认知灵活性。

### 引言
我们知道，人脑的加工资源是非常有限的，而外界的环境刺激繁多。因此，大脑需要有一个过滤装置来筛选出对当前最有用的信息加以关注和加工，这个机制被统称为“选择性注意”（selective attention），这一机制既是对任务相关信息的增强关注，也是对无关干扰信息的过滤或抑制。

空间注意常被类比为聚光灯。自然情境中，空间注意常伴随眼球的运动，我们注意看到的东西。然而隐喻Metaphorical的“聚光灯”（空间注意）也可以不需要眼球的运动，此时眼睛仅是注视着某个位置。实验室的设计中，空间注意总是内部的covert，这有助于将注意Attention-related的感觉加工和运动有关Motor-related的加工（如扫视）分离开来。

#### 我们如何设计实验来研究空间注意？

在实验室研究中，两类任务被经常用来作为研究空间注意的实验范式。第一类是线索范式，由于该任务最早由Posner发明，因此也被叫做Posner任务或Posner-like任务。在线索范式中，研究者常使用线索（cue）来引导个体的视觉注意。通过比较cued location (有视觉注意) 和uncued location （没有视觉注意）上的行为和神经反应可以发现视觉注意的作用。已有研究表明，给予视觉注意可以提高行为的正确率和速度，同时视觉注意也会影响知觉、提高分辨能力和对比敏感性等。

图A为Posner任务（可细分为Exogenous cue和Endogenous cue，两者分别侧重自下而上的引导和自上而下的引导）。

第二种常见的实验范式是Treisman的视觉搜索范式（图B），即从一系列视觉刺激中找到目标刺激。Treisman著名的的特征整合理论提出，自下而上的刺激物理属性和自上而下的行为目标都会驱动视觉注意。在视觉搜索任务中，当刺激物具有明显独特的特征时（如黑色"X"中找橙色“X”），搜索可以自动化、快速的完成，不依赖于刺激的数目（这种Pop-out的搜索是由自下而上的特征控制的，如salience）。反之，当目标和干扰物共享某些特征时（如要找的"X"和干扰物"O"都是橙色），视觉搜索需要受意识控制地逐个搜索完成，完成时间与刺激数目正相关（受自上而下加工控制）。


#### 注意网络中的功能专门化/功能分离*
>注：Functional Specialization，即different areas in the brain are specialized for different functions

无论是Posner任务还是视觉搜索任务，他们都涉及到大规模神经网络的活动。注意网络包括了视觉皮层、顶叶和额叶，也包括上丘、丘脑枕等皮层下结构（图C）。注意网络的每一个节点都有其功能和局部计算。由于空间注意这一心理过程可以被分解为多种认知操作（如从当前参与的位置脱离、转移到一个新的位置，以及在那个新的位置参与等），每一种操作都可能有不同的神经基础，这是注意网络分布广泛的可能原因之一。

<div align=center><img src="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7026883/bin/nihms-1553234-f0001.jpg"  height="360px" width="700px" ></div>


人类脑成像和脑损伤的研究是初步探索了大脑关于选择性注意相关脑区的功能分离，而之后在非人灵长类中做的电生理研究首次关注到了大脑注意网络单个节点的微观结构（如特定细胞的功能贡献）。这些电生理研究了空间注意如何通过改变发放率和感受野特性来影响神经元的信号。例如下图A展现了猴子在使用视觉注意时（在cue-target delay中）且感受野与cue位置重合时，其注意网络多个节点所放电活动(spiking)的增加。这说明节点参与了对线索位置的空间注意。最近，电生理研究也已经开始描述脑区间相互作用的神经特征。这些研究探讨了注意网络节点在不同功能和行为环境下如何动态交互过滤感官信息。


<div align=center><img src="https://www.ncbi.nlm.nih.gov/pmc/articles/instance/7026883/bin/nihms-1553234-f0002.jpg" ></div>


>图A为猴子额叶眼动区frontal eye fields (FEF), 顶内沟lateral intraparietal area(LIP)和中鼻窦mediodorsal pulvinar(mdPul)的Population peristimulus time histograms (PSTHs)。其中，LIP与 [眼球运动](https://en.wikipedia.org/wiki/Lateral_intraparietal_cortex) 有关，mdPul之前被认为在空间注意中 [协调额顶网络](https://www.nature.com/articles/s41467-018-08151-4)。
>图B：刺激猴子的FEF会导致视觉皮层(V4)中的活动注意力的增加。红色是刺激FEF的条件，黑色是没有刺激的。
>图C：颅内脑电的结果，高阶脑区活动的潜伏期早于视觉皮层，说明空间注意过程中的区域间同步是由高阶皮质引导或启动的
>（IPS即顶内沟，IPS0, intraparietal sulcus, area 0; IPS1-2, intraparietal sulcus, areas 1 and 2;IPS3, intraparietal sulcus, area 3; 
>LO/VO, lateral occipital背侧枕叶and ventral occipital腹侧枕叶;TO, cytoarchitectonic area细胞结构区 in anterior temporal cortex前颞叶; 
>V1c1, visual area 1, early component; V1c2, visual area 1, late component; V2, visual area 2; V3, visual area 3; V3A, visual area 3A; V3B, visual area 3B.）


在这里，我们将讨论各个节点的功能是如何动态变化的，而这种动态甚至发生在任务需求不变的情况。最近的证据表明，空间注意的特征在于功能的瞬时变化，这些变化给注意相关的采样过程提供了灵活性。

### 不同处理阶段的功能专门化

#### 注意控制的自上而下模型

神经影像学研究表明，额叶和顶叶皮质是产生与注意力相关的调节信号的来源，然后这些信号反馈给视觉皮层。额叶和顶叶皮层的注意相关激活发生在cue-target delay中，这种激活在没有视觉刺激的时候也会存在，说明额顶叶具有维持和控制空间注意的功能。

相反，视觉区的激活主要由感觉刺激驱动；当刺激在注意的位置(cued)呈现时，视觉区会有一个增强的激活，但是在delay阶段的激活相对弱一些。因此，成像结果表明，注意网络的高阶节点（如额顶叶）能够直接调节视觉区域的感觉加工。

这种自上而下的注意力控制模型在非人类灵长类动物的因果(causal)操作中得到了进一步的支持。例如，在额叶区域（如frontal eye field, FEF）对神经元进行电刺激，会导致视觉皮层神经活动的注意力样变化和行为表现的改善（如上图B）。这表明高阶皮层区域的微刺激可以模拟空间注意对视觉加工的影响。

猴子提供了TD的证据，而Dorsolateral Prefrontal Cortex(DLPFC背外侧前额叶皮质)损坏的人类的ERP研究提供了补充证据。相比于控制组，脑损伤病人同时有着对侧半视野的行为缺陷（比如不能发现target）和视觉反应的缺陷。这种神经和行为的缺陷与DLPFC的损坏是一致的。


高阶脑区（额顶叶）和视觉区的同步记录研究也揭示了额顶叶的自上而下控制。多位点记录通常通过检查神经活动潜伏期 (i.e., the order in which attention-related changes in neural activity occur across regions)或格兰杰因果（即一个区域的神经信号如何预测另一个区域的神经信号）来推断神经活动的方向性。在猴子和最近在人类的电生理记录研究表明，与注意力相关的效应在高阶皮质出现的时间早于视觉皮质(如图C)，且在高阶皮质（额顶叶）出现的幅度更大。这些结果表明，与注意相关的神经加工变化是从高阶皮层传播到感觉皮层。对猴子的电生理研究进一步证明，空间注意过程中的区域间同步是由高阶皮质引导或启动的。比如，空间注意中FEF和V4间的同步由额叶启动。

总的来说，研究注意力控制的神经影像学和电生理研究表明，注意力网络至少可以分为**两个部分**：控制空间注意力的**高阶节点(如额叶和顶叶皮层)** 和在感觉处理中与注意力相关的变化似乎发生的 **低阶节点 (例如,感觉皮层)**。



