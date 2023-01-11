# Forrester：2022年安全分析平台厂商评估

> 本文摘录自公众号：Benny Ye 专注安管平台
> 原文地址：https://mp.weixin.qq.com/s/p1U1M0UvzdaNccVqt7914g

---

时隔两年后，2022年12月，Forrester再次发布了最新一期的安全分析平台（Security Analytics Platform）厂商评估报告（Forrester Wave），对全球14个厂商进行了矩阵分析。

这次，Forrester的SAP市场报告主笔分析师也发生了变化，Allie Mellen进入Forrester后迅速成为了安全运营领域的主要分析师，成为了包括SAP、SOAR、XDR在内的多个细分市场相关报告的主笔。因此，WAVE矩阵相较于上次变化不小。

Forrester将SAP定义为：

> SAP将汇聚来自网络、身份、端点、应用和其它相关来源的日志，生成高保真的行为告警，以实现快速的事件分析、调查与响应。

> A security analytics (SA) platform converges logs from network, identity, endpoint, application, and other security relevant sources to generate high-fidelity behavioral alerts and facilitate rapid incident analysis, investigation, and response.

Forrester分析师Allie Mellen表示，Forrester发明SAP这个术语正是想要表达传统的SIEM功能已不能满足安全运营团队所需，SAP则集成了包括SIEM在内的分析、调查、自动化、编排、威胁猎捕、仪表板和报告等更多功能，以改善分析师体验（AX）。在Forrester2022年8月发布的《[2022年安全分析平台市场格局报告](http://mp.weixin.qq.com/s?__biz=MzUyNzMxOTAwMw==&mid=2247484513&idx=1&sn=36739ae447e070bbe70ba52a3f73f274&chksm=fa002ed5cd77a7c3609048c1c346c21d1808b5da9e7da06ace4ae5031faf778ad3ded9cf8484&scene=21#wechat_redirect)》中，详细阐述了SAP的定义和上述理念。

从这个意义上来看，Forrester所定义的SAP更接近国内的SOC平台的概念。其实，Gartner定义的Modern SIEM（现代SIEM）也差不多是这个意思。

《报告》建议客户在选择SAP供应商的时候要关注以下几个因素：

1）连接的深度优先于广度。

日志源支持的多，或者SOAR集成的应用多并非对你有价值，关键是适合你，并且每个你所需的都能支持到位。

![图片](https://mmbiz.qpic.cn/mmbiz_png/t7v7zyOTkMcCVbOKwsLDNRDwWiaeUF2xvc0DIgWNficS846iaenT83LpvodkeGW9jAC7UTM4fxXCZ3Pu624JrQ4Xg/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)

2）要注重提升分析师体验。

分析师体验（AX）是Forrester最新造出来的一个概念，在用户体验（UX）基础上推进了一层。分析师体验同时位居客户5大挑战和厂商五大计划增强的功能之列。

![图片](https://mmbiz.qpic.cn/mmbiz_png/t7v7zyOTkMcCVbOKwsLDNRDwWiaeUF2xvam87t4gO2iaETK4ibF7bRdI4X1KekSpmJ5FuQw5TYERZzH0P6pLW01hw/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)

【笔者注：SAP的核心是运营，而运营时最大的问题就是使用者（分析师）用起来不爽。这种不爽不仅是指UED（UI，交互等等），还有业务层面的，譬如如何将情境感知，响应流程嵌入到日常工作中去，如何助力分析师实现发现、探索、分类、决断和执行的闭环。这个问题就是所谓的”分析师体验“问题。回想一下，国内近些年来做了很多面向领导者体验的努力——各种态势大屏，但却未能给真正干活的分析师们提供点什么。事实上，SOC平台产品要用起来、用好，很关键就在于运营，而天天运营的人是分析师（运营工程师）而不是领导，也不是个别安全专家！这方面，笔者认为SOAR的引入恰恰大大增强了SAP的分析师体验过程。想想看，SOAR才是真正的贴近广大安全分析师的交互层，而传统SAP的分析层（组件）更加面向个别安全专家。】

3）具备独特的产品愿景和有力的执行路径

![图片](https://mmbiz.qpic.cn/mmbiz_png/t7v7zyOTkMcCVbOKwsLDNRDwWiaeUF2xvYiaXg5Un22SA2h4UwaibS0ZyWT8zQiaV7FT7KDJGLBxsaCib90Ffb3iayYg/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)

现在的SAP市场已经成熟，竞争十分激烈，大家的技术都在趋同，想要与众不同比较困难。大部分厂商还是聚焦安全运营，也有一些厂商提出了诸如自主SOC、XDR的概念，但并未有实质性的不同。客户应该评估那些供应商的产品发展愿景和路线图。

【笔者注：Allie Mellen对于自主SOC（autonomous SOC）概念（Devo和PAN正在鼓吹）持反对态度，表示太过遥远、不切实际（原话是”pipe dream白日梦“）。对此，笔者表示赞同，安全运营平台最终赋能的是人，是增强人运营的效率，安全运营的过程就是一个持续对抗的过程，本质上还是人与人之间的对抗。尽管ChatGPT/OpenAI等AI技术展现了强大的能力，但安全运营还是一个man-on-the-loop的过程。】

下面是今年的WAVE矩阵。Forrester采用了28个指标来评估入选的14个厂商。其中技术相关指标包括：分析能力、UEBA、关联分析、调查能力、SOAR、威胁猎捕、威胁情报、机器学习、ATT&CK映射、仪表板和报告、合规能力、分析师体验、日志采集器、案例管理、架构、业务功能、部署模式、管理控制、产品自身安全。值得注意的是，在SOAR这个指标维度，IBM、Splunk都得到了满分（因为他们都收购并整合了SOAR产品）。Sumo Logic（收购了DFLabs）也得到了高于平均分的表现。

![图片](https://mmbiz.qpic.cn/mmbiz_png/t7v7zyOTkMcCVbOKwsLDNRDwWiaeUF2xvQSiaUTksG9pViaFTfic49hGqcPf1wicR4K4fyJtjxeDkzgDK7TrDbC3Z2A/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)

对比一下上份报告（2020年）：

![图片](https://mmbiz.qpic.cn/mmbiz_png/t7v7zyOTkMf8Iib2O9cLtG9v3rgpYp2P8BBYMiblVUacS3rFFs5G55Qic9SBWNFOZOku2886p9AVMfuR6D3hbM6lg/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)

可以发现：

1）Splunk和Microsoft继续保持在领导者阵营，且微软实力继续增强。Forrester认为Splunk作为SAP市场的龙头并非无懈可击，其过失的定价模型使得其它厂商有机可乘。而微软凭借强大的综合实力以及在云安全方面的积累不断巩固在这个市场的领导者地位。

2）Elastic首次上榜就迈入领导者阵营，这跟Gartner的评估差异较大。Forrester对Elastic的分析能力、调查能力都给了满分，尤其是Elastic的分析师体验这个维度，是唯一获得满分的厂商。

3）IBM、Securonix、Exabeam都不同程度有所退步，退出领导者阵营，Exabeam尤其大退步。同时，Micro Focus（Arcsight）、Logrhythm还在继续退步，并在向云SIEM转型的路上继续前行。

4）包括Elastic在内的Sumo Logic、Devo、Logpoint等四个新上榜的SAP厂商都是主打SaaS模式的SIEM厂商，在对于云SIEM的未来趋势判断上跟Gartner保持一致。

建议大家结合笔者[2022年的Gartner SIEM MQ分析文章](http://mp.weixin.qq.com/s?__biz=MzUyNzMxOTAwMw==&mid=2247484530&idx=1&sn=af1537ab8fe4503a0b10fb133d507096&chksm=fa002ec6cd77a7d01239618b95446d54a2fd0b83c1e6b16c22a1bbb2718df271fc94a6fb3abe&scene=21#wechat_redirect)来看这个报告，尤其是厂商分析部分。

【参考】

[Forrester：2022年安全分析平台市场格局报告](http://mp.weixin.qq.com/s?__biz=MzUyNzMxOTAwMw==&mid=2247484513&idx=1&sn=36739ae447e070bbe70ba52a3f73f274&chksm=fa002ed5cd77a7c3609048c1c346c21d1808b5da9e7da06ace4ae5031faf778ad3ded9cf8484&scene=21#wechat_redirect) 

[Forrester：2020年安全分析平台厂商评估](http://mp.weixin.qq.com/s?__biz=MzUyNzMxOTAwMw==&mid=2247484260&idx=1&sn=64b4bcc40cbd2a49b9463aa47b4d67cc&chksm=fa0029d0cd77a0c6dcfb950ddb31a07eeee8893748fef729561080a19eea1a9612a658425835&scene=21#wechat_redirect)

[Forrester：2018年度安全分析平台厂商评估](https://blog.51cto.com/yepeng/2296531)

[Forrester：2017年度安全分析平台厂商评估](https://blog.51cto.com/yepeng/1905181)

[Gartner：2022年SIEM（安全信息与事件管理）市场分析](http://mp.weixin.qq.com/s?__biz=MzUyNzMxOTAwMw==&mid=2247484530&idx=1&sn=af1537ab8fe4503a0b10fb133d507096&chksm=fa002ec6cd77a7d01239618b95446d54a2fd0b83c1e6b16c22a1bbb2718df271fc94a6fb3abe&scene=21#wechat_redirect)

[Gartner：2021年SIEM（安全信息与事件管理）市场分析](http://mp.weixin.qq.com/s?__biz=MzUyNzMxOTAwMw==&mid=2247484351&idx=1&sn=ff83fa4e2b4286a301a541ccc971c3cf&chksm=fa00290bcd77a01d7b917fd6c9041ef12b5f2300916212d0dd74fe836c78bcffc1887ed11520&scene=21#wechat_redirect)

[Gartner：2019年SIEM（安全信息与事件管理）市场分析](http://mp.weixin.qq.com/s?__biz=MzUyNzMxOTAwMw==&mid=2247484022&idx=1&sn=e39ec5ac122c698f201e94df81d6d7f3&chksm=fa0028c2cd77a1d442b08e857f98863b9be1894f56ef98615d4d588cbdb90e5ae3270fc4eb78&scene=21#wechat_redirect)

[Gartner：2018年SIEM（安全信息与事件管理）市场分析](http://mp.weixin.qq.com/s?__biz=MzUyNzMxOTAwMw==&mid=2247483705&idx=1&sn=575fd73452bccf2dbfd4612f93aabf1c&chksm=fa002b8dcd77a29bdabd04ba1e2819b3cf710bd98412c45e6b036433b24b3605bfbc1060843e&scene=21#wechat_redirect)

[Gartner：2017年SIEM（安全信息与事件管理）市场分析](http://mp.weixin.qq.com/s?__biz=MzUyNzMxOTAwMw==&mid=2247483705&idx=2&sn=893002cafd46ae55c1f932435ac81fbb&chksm=fa002b8dcd77a29bdef3b56239692999329f32a80eb6ad6ab98ad901e7e1b54460297293c211&scene=21#wechat_redirect)

[浅析IDC全球SIEM市场预测（2022-2026）](http://mp.weixin.qq.com/s?__biz=MzUyNzMxOTAwMw==&mid=2247484524&idx=1&sn=cac5a8d1fe5cec250e4ce7bbdeb70b92&chksm=fa002ed8cd77a7cedb552b234cf884475bb70409e21e8060b05e72cc6f648400ddc6f29e9241&scene=21#wechat_redirect)

[SIEM的未来](http://mp.weixin.qq.com/s?__biz=MzUyNzMxOTAwMw==&mid=2247484500&idx=1&sn=91a3a818e697213a9b46ac7b5559944e&chksm=fa002ee0cd77a7f6503c923d308c43d53b0cdd2e6725326b24fd49915c33e9f3b1ba9a42af05&scene=21#wechat_redirect)

[SANS 2022年SOC调查报告解读](http://mp.weixin.qq.com/s?__biz=MzUyNzMxOTAwMw==&mid=2247484450&idx=1&sn=27c3c6e51febebd4ed1a13fa2f85307d&chksm=fa002e96cd77a780251bdec3b12e2fbea2e013d19495d01c33b7aaac9323cbabe4274077e999&scene=21#wechat_redirect)