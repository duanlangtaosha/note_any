\> 本文由 \[简悦 SimpRead\](http://ksria.com/simpread/) 转码， 原文地址 \[blog.csdn.net\](https://blog.csdn.net/AI\_Conf/article/details/109603572?spm=1000.2115.3001.4128)

> [AMiner 平台](https://www.aminer.cn/)由清华大学计算机系研发，拥有我国完全自主知识产权。平台包含了超过 2.3 亿学术论文 / 专利和 1.36 亿学者的科技图谱，提供学者评价、专家发现、智能指派、学术地图等科技情报专业化服务。系统 2006 年上线，吸引了全球 220 个国家 / 地区 1000 多万独立 IP 访问，数据下载量 230 万次，年度访问量超过 1100 万，成为学术搜索和社会网络挖掘研究的重要数据和实验平台。

  

### [IJCAI 2020](https://www.aminer.cn/conf/ijcai2020) 论文推荐

**Set and Rebase: Determining the Semantic Graph Connectivity for Unsupervised Cross-Modal Hashing**

无监督的跨模态哈希的无标签性质阻碍了模型利用精确的语义数据相似性。现有研究通常在原始特征空间中通过启发式几何先验来模拟语义。但是，由于原始特征不能完全代表底层的多视图数据关系，因此这会给模型带来严重偏差。  
为了解决上述问题，作者提出了一种新的无监督哈希方法，称为基于语义的跨模态哈希（SRCH）。定义了一种新颖的 “设置 - 重构” 过程，以初始化和更新训练数据的跨模态相似度图。特别是，作者根据模态内特征的几何基础设置图，然后根据哈希结果交替对其进行基础调整，以更新图中的边缘。  
作者开发了一个交替优化的例程来对图进行重基，并以闭式解来训练哈希自动编码器，从而有效地训练整个框架。在基准数据集上的实验结果证明了该模型相对于最新算法的优越性。

论文链接：[https://www.aminer.cn/pub/5ef96b048806af6ef277205a?conf=ijcai2020](https://www.aminer.cn/pub/5ef96b048806af6ef277205a?conf=ijcai2020?f=cs)

![](https://img-blog.csdnimg.cn/img_convert/8c5bc8cb2db0f536593086716b1c8c94.png#pic_center)  
  

**Why We Go Where We Go: Profiling User Decisions on Choosing POIs**

尽管兴趣点（POI）推荐已成为热门研究话题，但在理解人们为何以及如何做出选择 POI 的决策方面进展甚微。  
在本文中，作者提出了一个名为 PROUD 的用户决策分析框架，该框架可以识别人们选择 POI 的决策中的关键因素。具体来说，作者将每个用户决策视为一组因素，并提供了一种学习因素嵌入的方法。该方法的独特视角是通过新颖的标量投影最大化目标来识别关键因素，同时无缝保留决策结构。由于稀疏性的限制，精确地求解目标并非易事。为了解决这个问题， PROUD 采用了自投影注意力和 L2 正则化的稀疏激活来直接估计每个因素成为关键因素的可能性。  
最后，对真实数据的大量实验证明了 PROUD 在保存用户决策结构方面的优势。此外，作者的案例研究表明，确定的关键决策因素可以帮助提供更多可解释的建议和分析。

论文链接：[https://www.aminer.cn/pub/5e5e193693d709897ce5ca82?conf=ijcai2020](https://www.aminer.cn/pub/5e5e193693d709897ce5ca82?conf=ijcai2020?f=cs)

![](https://img-blog.csdnimg.cn/img_convert/b5e2e7815cfeee4a11d39e0eaea665a0.png#pic_center)

  

### [NeurIPS 2020](https://www.aminer.cn/conf/neurips2020) 论文推荐

**Can graph neural networks count substructures?**

检测和计数图中某些子结构的能力对于解决图结构数据的许多任务非常重要，尤其是在计算化学和生物学以及社会网络分析的背景下。  
受此启发，作者建议通过图神经网络对归属图子结构进行计数的能力来研究其表达能力，并扩展最近在图同构测试中检验它们的能力的工作。作者区分两种类型的子结构计数：匹配计数和包含计数，并为各种 GNN 架构建立主要的否定答案。具体来说，作者证明了消息传递神经网络（MPNNs），Weisfeiler-Lehman（WL）和 2-Invariant Graph Networks (2-IGNs) 无法执行由 3 个或更多节点组成的子结构的匹配计数，但它们可以对星形子结构进行包含计数。作者还提供了 k-WL 和 k-IGN 的部分结果。  
然后，作者进行了支持某些理论结果的实验，并证明受 Murphy 等人启发的局部关系池策略对子结构计数更有效。此外，我们证明了 WL 和 2-IGN 在区分非同构图方面是等效的，部分回答了 Maron 等人提出的一个开放问题。

论文链接：[https://www.aminer.cn/pub/5e427c903a55acbff4c40b1d?conf=neurips2020](https://www.aminer.cn/pub/5e427c903a55acbff4c40b1d?conf=neurips2020?f=cs)

![](https://img-blog.csdnimg.cn/img_convert/2a6267db1232b03516451c9441b8eb8f.png#pic_center#pic_center)

  

**A Benchmark for Systematic Generalization in Grounded Language Understanding**

人类语言使用者很容易解释描述由熟悉的部分组成的陌生情境的表达方式（“在摩天轮旁迎接粉色雷龙”）。相比之下，现代神经网络难以解释训练中看不到的成分。  
在本文中，作者引入了一个新的基准 gSCAN，用于评估情境语言理解模型中的成分泛化。作者从形式语言学中意义构成的标准模型中汲取灵感。 gSCAN 超越了早期针对泛化语法方面的相关基准，定义了一种基于网格世界状态的语言。这使作者能够构建新颖的泛化任务，以探究语言动机规则的获得。例如，代理人必须了解相对于当前世界状态如何解释形容词（例如 “小”）或如何将副词（例如 “谨慎”）与新动词结合。  
作者测试了一个强大的多模态基线模型和一个最新的合成方法，发现在大多数情况下，当泛化需要系统的合成规则时，它们会严重失败。

论文链接：[https://www.aminer.cn/pub/5e6a084591e011c28fff6f60?conf=neurips2020](https://www.aminer.cn/pub/5e6a084591e011c28fff6f60?conf=neurips2020?f=cs)

![](https://img-blog.csdnimg.cn/img_convert/4af109963f5c98bfe1752c335b216f8d.png#pic_center)  
  

### [EMNLP 2020](https://www.aminer.cn/conf/emnlp2020) 论文推荐

**Optimus: Organizing Sentences via Pre-trained Modeling of a Latent Space**

经过有效训练后，变分自动编码器（Variational Autoencoder , VAE）既可以成为强大的生成模型，又可以成为自然语言的有效表示学习框架。  
在本文中，作者提出了第一个大规模语言 VAE 模型 Optimus。首先在大型文本语料上对句子的通用潜在嵌入空间进行预训练，然后针对各种语言生成和理解任务进行微调。与 GPT-2 相比，Optimus 支持使用潜在矢量从抽象级别生成引导语言；与 BERT 相比，Optimus 的平滑潜在空间结构可以更好地泛化低资源语言理解任务。  
在各种语言任务上的大量实验结果证明了 Optimus 的有效性。它在 VAE 语言建模基准上达到了新的最先进水平。

论文链接：[https://www.aminer.cn/pub/5e8ef2ae91e011679da0f219?conf=emnlp2020](https://www.aminer.cn/pub/5e8ef2ae91e011679da0f219?conf=emnlp2020?f=cs)

![](https://img-blog.csdnimg.cn/img_convert/f29f42132907bae778ad2bb9ebf15168.png#pic_center)  
  

**Imitation Attacks and Defenses for Black-box Machine Translation Systems**

作者考虑了一个旨在窃取或攻击黑盒机器翻译（Machine Translation, MT）系统的对手，以获取经济利益或利用模型错误。作者首先展示了黑盒 MT 系统可以通过用单语言句子查询它们并训练模型来模仿它们的输出而被窃取。通过模拟实验，作者证明了即使模仿模型的输入数据或架构与其受害者不同，也可以窃取 MT 模型。  
应用这些思想，作者在高资源和低资源语言对上训练了三个生产 MT 系统的模型不超过 0.6 BLEU 的模仿模型。然后，作者利用模仿模型的相似性将对抗性示例转移到生产系统。作者使用基于梯度的攻击，这些攻击会暴露输入，从而导致语义错误的翻译、内容删除以及庸俗的模型输出。为了减轻这些漏洞，作者提出了一种防御措施，修改翻译输出，以误导模仿模型的优化。这种防御会降低模仿模型的 BLEU 和攻击转移率，但会降低 BLEU 和推理速度。

论文链接：[https://www.aminer.cn/pub/5eabf34c91e011664ffd2a39?conf=emnlp2020](https://www.aminer.cn/pub/5eabf34c91e011664ffd2a39?conf=emnlp2020?f=cs)

![](https://img-blog.csdnimg.cn/img_convert/02ed2b6665747a6e8def89655d2b43a8.png#pic_center)  
  

_想要查看更多精彩会议论文合集，请移步 [AMiner 顶会](https://aminer.cn/conf)_