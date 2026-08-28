# AI 训练平台的数据风险：Mercor 2026 安全事件

> **截至 2026-08-28。状态：REVISED。** Mercor 已确认 2026 年 3 月受 LiteLLM 供应链攻击影响，并在 6 月公布调查结果。黑客组织声称窃取 4TB 数据等说法未获 Mercor 证实，本文不会把这些声称写成既定事实。

AI 训练平台经常被讨论成“谁给模型做数据”“一小时多少钱”。但平台还有另一层角色：它们集中保存大量劳动者的身份、招聘、合同和任务信息。

2026 年 Mercor 的安全事件让这个问题第一次非常清楚地暴露出来。

## 一、平台为什么会集中大量劳动者数据

Mercor 连接专业人士与 AI 训练项目。为了筛选和安排工作，平台需要处理的不只是匿名任务结果，还可能包括：

- 候选人资料；
- 专业经历；
- 招聘和面试信息；
- 承包关系与付款资料；
- 项目权限；
- 与客户和模型训练任务有关的敏感信息。

Mercor 在 2026 年 6 月的官方更新中称，其网络接近 500 万名 experts。[^1]

这意味着一个训练平台既是劳动中介，也是一个大规模的**劳动者数据集中点**。

## 二、2026 年 3 月发生了什么

Mercor 3 月底确认，自己受到开源工具 LiteLLM 供应链攻击影响。恶意版本被设计用来窃取 credentials，攻击随后可能通过被盗凭据进入其他系统。[^1][^2]

Mercor 称其迅速控制事件，并与 Mandiant、Latacora 等外部专家和执法机构进行调查。[^1]

## 三、官方调查确认了什么

Mercor 6 月 25 日公布调查结论称：

- 在接近 500 万名 experts 中，只有“very limited subset”的敏感信息受到影响；
- 公司称没有证据表明这些数据被用于欺诈；
- 公司开始直接通知受影响人员，并提供身份保护服务；
- 公司称员工数据没有受到影响；
- 客户信息影响“very limited”。[^1]

这些都是**公司调查结论和公司自述**，应按这个身份引用。

## 四、什么仍然是未经确认的声称

攻击发生后，一个黑客组织声称获取了约 4TB Mercor 数据，并声称其中包括个人信息、客户信息、源代码等。TechCrunch 当时报道了这一声称，同时明确指出 Mercor 没有证实这些数据的真实性和完整范围。[^3]

因此不能写成“Mercor 泄露了 4TB 劳动者数据”。正确写法只能是：**攻击者如此声称，但公开证据不足以确认。**

多名承包者随后提起诉讼，指控个人数据暴露。TechCrunch 报道过相关诉讼；这些仍是诉讼主张，不是法院已经确认的事实。[^3]

## 五、为什么这是劳动问题，不只是网络安全问题

如果一家普通 SaaS 公司泄露客户账户，这是数据安全事故。

AI 训练平台更特殊，因为它同时保存了劳动市场和模型供应链两边的信息：

- 谁拥有什么专业技能；
- 谁通过什么方式被筛选；
- 谁正在做哪些训练任务；
- 劳动者获得什么项目权限；
- 模型实验室正在采购什么知识。

这些数据一旦集中，劳动者承担的风险不只包括身份盗用，还可能包括职业隐私、项目保密和未来求职信息暴露。

而很多专家训练者又是独立承包商，他们获得的数据保护、申诉渠道和组织保障不一定等同于正式员工。

## 六、安全事故还能直接影响工作量

WIRED 在事件发生后报道称，Meta 暂停了与 Mercor 的合作，同时其他实验室评估风险。[^4]

这种暂停意味着：平台安全事件不仅可能伤害隐私，还可能突然让依赖某个客户项目的承包者失去任务。

需要注意，Mercor 后来在 6 月官方更新中称，所有 frontier labs 在过去几个月增加了与公司的合作。[^1] 这说明安全事件后的客户关系继续变化，不能把 4 月的一次暂停写成永久结果。

## 七、我们不知道什么

- 没有公开完整清单说明究竟哪些 expert 字段被访问。
- 攻击者声称的 4TB 数据规模没有被 Mercor 独立证实。
- 诉讼尚未给出最终责任认定。
- “very limited subset”没有在官方页面给出具体人数。
- 目前没有系统研究说明这次事件给承包者造成了多少实际经济损失。

## 评曰

AI 训练劳动看起来很“无形”：一个专家坐在家里，打开网页，评价模型输出。

但平台背后却形成了高度集中的基础设施。它知道谁会什么、谁被分到哪个项目、谁拿多少钱、谁能访问什么。

当专业知识本身成为训练材料时，**关于专业劳动者的数据也同时变成高价值资产。**

所以 AI 劳工保护不能只问“时薪多少”。还要问：平台保存了什么？保存多久？谁能访问？发生事故时谁通知劳动者？任务因为客户暂停突然消失时，谁承担风险？

---

[^1]: Mercor, “Update on Mercor security incident,” 2026-06-25. https://www.mercor.com/blog/update-on-mercor-security-incident/
[^2]: TechCrunch, “Mercor says it was hit by cyberattack tied to compromise of open source LiteLLM project,” 2026-03-31. https://techcrunch.com/2026/03/31/mercor-says-it-was-hit-by-cyberattack-tied-to-compromise-of-open-source-litellm-project/
[^3]: TechCrunch, “After data breach, $10B-valued startup Mercor is having a month,” 2026-04-09. https://techcrunch.com/2026/04/09/after-data-breach-10b-valued-startup-mercor-is-having-a-month/
[^4]: WIRED, “Meta Pauses Work With Mercor After Data Breach Puts AI Industry Secrets at Risk,” 2026-04-03. https://www.wired.com/story/meta-pauses-work-with-mercor-after-data-breach-puts-ai-industry-secrets-at-risk/
