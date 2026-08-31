# MTurk 与众包劳动：AI 零工平台的制度祖先

> **截至 2026-09-01。状态：REVISED。** Amazon Mechanical Turk（MTurk）不是 2026 年前沿大模型训练的中心，但它是理解今天 Remotasks、Outlier 等 AI 任务平台的关键制度祖先：把工作切成微任务、按件计酬、让劳动者承担找任务与资格考试的无薪时间，并把评价权集中在请求方和平台。Amazon 已确认 MTurk 将于 **2026 年 9 月 30 日永久关闭**；这一事实为这种平台组织形式提供了一个明确的历史终点，但 Amazon 没有把关闭原因归因于 AI 自动化，因此不能写成“AI 淘汰了 MTurk”。

## 一、为什么 MTurk 重要

Amazon 在 2005 年推出 Mechanical Turk。平台允许请求方发布 Human Intelligence Tasks（HITs），劳动者远程完成图像分类、文本判断、问卷、转录等任务。

它最重要的创新不是某一种任务，而是**把人的判断力做成 API 背后的可调用资源**。请求方看到的是一批完成的标签，劳动者看到的是任务列表、资格门槛、单价、拒付风险和不断刷新页面找活。

后来 AI 数据产业的大量平台都继承了这套结构，只是任务从简单分类变成了模型偏好比较、代码评估和专业知识判断。

## 二、2026：这个制度祖先进入关闭阶段

Amazon 的 MTurk 官方 FAQ 已明确写明：**MTurk 将于 2026 年 9 月 30 日永久关闭。**劳动者在关闭前完成并获批准的 HIT 仍按既有付款计划结算；请求方可在 10 月 30 日前处理已提交任务并发放奖金，交易历史将保留到 2027 年 1 月 28 日。[^2]

AWS 的 SageMaker 文档同时要求仍在使用 MTurk workforce 的客户在 9 月 30 日前迁移到其他 workforce。[^3]

这里需要纠正一个容易被二手报道放大的说法：**MTurk 关闭不等于 SageMaker Ground Truth 在 9 月 30 日整体关闭。**Amazon 的 FAQ 说的是 Ground Truth 和 Amazon Augmented AI 中的 **MTurk Worker type** 将不再可用；AWS 当前 Ground Truth 文档仍明确写着，该服务虽已不再向新客户开放，但现有客户可以继续使用，并且可以使用 private workforce 等方式。[^2][^4]

从劳动史看，这一节点重要，因为一个从 2005 年延续二十余年的开放式微任务市场将退出。对仍依赖它获得收入的劳动者来说，这是一个真实的平台退出和收入渠道消失事件；对请求方来说，则是人工工作流迁移事件。

但现有一手材料**没有给出关闭的劳动因果解释**。Amazon 没有公布当前活跃劳动者规模，也没有说关闭是因为生成式 AI、专门数据供应商、需求下降或其他单一因素。因此目前可以确认“平台关闭”，不能确认“AI 导致平台关闭”。

## 三、经典工资研究：为什么“单价”不是实际时薪

Hara 等研究者记录了 2,676 名 MTurk 工人完成约 380 万个任务的过程。研究发现，按包含找任务、做了却没提交、被拒付等时间计算，劳动者的**中位实际时薪约为 2 美元**，只有约 4% 的劳动者实际时薪超过当时美国联邦最低工资 7.25 美元。[^1]

研究同时发现，一个容易被忽略的原因是“无薪劳动”：

- 找合适任务；
- 阅读说明；
- 做资格测试；
- 处理被拒任务；
- 等待或刷新任务池。

因此，“这个 HIT 按完成速度折算可以赚 10 美元/小时”并不等于劳动者一天真的能赚到 10 美元/小时。

## 四、平台权力：谁决定一份劳动算不算完成

众包平台的典型不对称包括：

1. 请求方定义任务；
2. 请求方或自动规则验收；
3. 拒绝任务会影响劳动者评级；
4. 评级又决定未来能否进入更好的任务；
5. 劳动者很难直接接触最终使用自己劳动的公司。

这套结构后来在 AI 数据平台中变得更复杂：除了 requester，还有外包商、模型公司、项目经理、自动质量控制和账号风控。

## 五、MTurk 与今天的 AI 训练平台有什么不同

不能把 MTurk 直接当成今天 Outlier 的同义词。

前沿大模型的数据工作越来越需要：

- 长文本比较和事实核查；
- 数学、代码和科学问题；
- 红队、安全和模型评估；
- 领域专家设计困难任务。

因此，部分项目费率远高于传统 MTurk 微任务。但平台劳动的老问题并没有自动消失：**有薪任务之外仍有准入、等待、学习规则和项目切换成本；任务供给也可能突然停止。**MTurk 的关闭又增加了一个更彻底的平台风险：平台本身可以退出，劳动者此前积累的资格、声誉和工作入口不能自动迁移到另一家市场。

见《调查·ScaleAI外包体系》和《调查·Outlier任务工》。

## 六、为什么把它记进 AI 劳动史

如果只看模型史，MTurk 很容易被当作一个老旧网站。但从劳动史看，它建立了一套延续至今的组织方式：

> 把人类判断拆碎 → 隐藏在产品背后 → 按任务购买 → 用评分系统治理劳动者。

2026 年的关闭并没有让这套制度随之消失。相反，微任务平台的许多组织逻辑已经迁移到更专业化、更高价值的 AI 训练与评测市场。

所以 MTurk 的历史意义不在于证明“所有 AI 劳动都会走向同一结局”，而在于让我们看到一种劳动组织形式如何出现、扩张、被后来的平台继承，最终又由其最早的大型载体退出。

## 七、不能据此推出什么

- 约 2 美元/小时来自特定时期、特定样本的 MTurk 研究，不代表所有平台、所有年份；
- 不能把 MTurk 工资直接套到 2026 年专家型 AI 训练任务；
- 不能把所有众包劳动都称为“血汗工厂”；不同任务、地区和工人差异巨大；
- 不能因为 MTurk 在 2026 年关闭，就断言生成式 AI 是关闭的主要原因；Amazon 没有提供这样的因果解释；
- 不能把 MTurk Worker type 的退出写成 SageMaker Ground Truth 在 9 月 30 日整体关闭；
- 但也不能只引用平台标价而忽略无薪搜索、准入时间与平台退出风险。

---

[^1]: Kotaro Hara et al., “A Data-Driven Analysis of Workers' Earnings on Amazon Mechanical Turk,” CHI 2018 / arXiv:1712.05796. https://arxiv.org/abs/1712.05796
[^2]: Amazon Mechanical Turk, “Closure FAQs,” accessed 2026-09-01. https://www.mturk.com/help
[^3]: AWS, “Using the Amazon Mechanical Turk Workforce,” Amazon SageMaker AI documentation, accessed 2026-09-01. https://docs.aws.amazon.com/sagemaker/latest/dg/sms-workforce-management-public.html
[^4]: AWS, “Assign IAM Permissions to Use Ground Truth,” Amazon SageMaker AI documentation, accessed 2026-09-01. https://docs.aws.amazon.com/sagemaker/latest/dg/sms-security-permission.html
