

### Github ID：[lidanqing](https://github.com/lidanqing-intel)
在为PaddlePaddle贡献代码期间期间，我重点实践了从数学层面的优化和量化方法，比如随机梯度下降、PCA与异常值处理，并结合主流数学库（如MKL、MKLDNN）为算子加速和融合提供基础支持，同时在模型层面推动多个模型的算子量化。通过自下而上与自上而下的工程实践，我对深度学习与大模型的本质与优势有了深入理解。

在为百度PaddlePaddle贡献代码期间，我重点实践了深度学习中的数学优化方法及量化技术，结合英特尔MKL、MKLDNN等高性能数学库，为计算算子提供加速和融合支持。在模型层面推动多模型算子量化，提升推理效率。为了适应大模型在端的部署，在性能，内存，精度多方面反复优化。通过自下而上与自上而下的工程实践，我对深度学习与大模型的本质与优势有了深入理解。

在此期间，我曾组织过面向三千人的量化技术分享会，并支持PaddleScience分子动力学模型从TensorFlow迁移到PaddlePaddle，实现基于英特尔MKL的实际加速落地。

我们在软件层面的努力，让我深刻体会到硬件对深度学习的限制，同时云平台和大规模部署对于训练和预测非常重要。后续，我获得了Microsoft AI Associate和Cloud Associate认证，帮助欧洲中小企业完成流程云化，并参与开发多个新产品，收获了一千多名免费用户和一批BuyMeCoffee支持者。

百度PaddlePaddle深耕国内模型平台，拥有丰富的实际落地经验。期待未来能实现多个AI agent的流水线协作，在更多工业和生活场景中落地应用。最憧憬家务机器人如Mobile ALOHA早日量产走进千家万户——让AI助力美好生活、解放每个人的时间和创造力。

### PR 贡献（必填）

- PR 合并次数：109 / [查询链接](https://github.com/search?q=author%3Alidanqing-intel+org%3APaddlePaddle+type%3Apr+merged%3A2018-10-01..2025-01-17&type=pullrequests)
- 代表性 PR 展示：
  - [MKLDNN develop fake data tester](https://github.com/PaddlePaddle/PaddleSlim/pull/943/files)
  - [Do not quantize X and Y if both are output](https://github.com/PaddlePaddle/Paddle/pull/43297)
### ISSUE 贡献（必填）

- ISSUE 提交次数：51 / [查询链接](https://github.com/search?q=author%3Alidanqing-intel+org%3APaddlePaddle+type%3Aissue+created%3A2018-10-01..2025-01-17&type=issues)
- 代表性 ISSUE 展示：

### 评论贡献（必填）

- 评论 ISSUE 次数：158 / [查询链接](https://github.com/search?q=commenter%3Alidanqing-intel+org%3APaddlePaddle+type%3Aissue+created%3A2018-10-01..2025-01-17&type=issues)
- 评论 PR 次数：398 / [查询链接](https://github.com/search?q=commenter%3Alidanqing-intel+org%3APaddlePaddle+type%3Apr+created%3A2018-10-01..2025-01-17&type=pullrequests)

### 代码审查贡献（必填）

- 评审次数：256 / [查询链接](https://github.com/search?q=type%3Apr++reviewed-by%3Alidanqing-intel++org%3APaddlePaddle+created%3A2018-10-01..2025-01-17&type=pullrequests)（注意替换 author 值）
- 代码审查贡献简述：主要参与模型在MKLDNN库基础上算子优化，算子融合，INT8量化相关代码评审
### 生态贡献（加分项）

- 开源布道：如发布关于开源的专著、文章、公众号等，或是受邀参加技术峰会、开发者大会等，或是在相关会议、活动上推广开源文化等（对活动形式和参与次数进行描述）
- 社区活动：组织或参与社区SIG会议、技术交流、成员单位meetup、开源校源行等（对活动形式和参与次数进行描述）

### 自荐理由 （必填）

评审结果不仅是比较每项指标数量上的差异，将结合每位开发者贡献产生的影响力予以客观公正的评价。申请人可对每项提供数据的指标，进行影响力、活跃度、代码质量、项目效果等方面进行补充描述，字数不限。

Github ID：NKNaN
(个人介绍)

PR 贡献（必填）
PR 合并次数：113 / 查询链接
代表性 PR 展示：【Hackathon 7th No.20】为 Paddle 新增 Tensor.resize_  docs#7026
ISSUE 贡献（必填）
ISSUE 提交次数：2 / 查询链接
代表性 ISSUE 展示：logsoftmax kernel 当输入中有 -inf 时在cpu和gpu上计算结果存在不一致 Paddle#69859
评论贡献（必填）
评论 ISSUE 次数：5 / 查询链接
评论 PR 次数：53 / 查询链接
代码审查贡献（必填）
评审次数：46 / 查询链接
代码审查贡献简述：主要是对已提交pr的review结果的反馈
生态贡献（加分项）
开源布道：无
社区活动：第七届黑客松及护航计划，飞桨科学计算工具组件开发大赛一等奖
自荐理由 （必填）
在2024下半年持续参与了护航计划的框架API易用性提升项目，在上一期的基础上进一步对飞桨框架底层代码有了更深入的了解，并且参与了PaConvert工具的维护，使用户能够获得更好的体验，更容易从pytorch框架迁移到paddle。另一方面也参与了PaddleScience的工具组件开发大赛，在为飞桨迁移torch-scatter赛道荣获一等奖，整个过程提升了将科学计算API迁移至飞桨后端的能力，以及自定义C++算子及工具包打包的能力。个人觉得飞桨社区的活动经历，不仅提供给我了一个为国内深度学习框架做贡献的机会，也让我迅速成长，弥补了许多没有接触过的开发知识。
