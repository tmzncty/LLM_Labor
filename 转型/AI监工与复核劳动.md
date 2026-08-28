# AI 监工与复核劳动：当工作从“自己做”变成“盯着 Agent 做”

> **截至 2026-08-28。状态：REVISED。** 本文使用“AI 监工/复核劳动”作为分析性统称，不把它冒充成已经标准化的正式职业名称。2026 年新增证据显示，这类工作正在从“检查输出”扩展到权限控制、事故处置和法律责任承接。

生成式 AI 最初进入办公室时，常被描述成“助手”：帮你写邮件、补代码、总结材料。

Agent 化之后，另一种工作形态开始出现：机器先完成更长的任务链，人类不再逐步执行，而是负责设目标、授权、检查结果、处理异常、承担责任。

这类劳动可以暂时统称为**AI 监督/复核劳动**。

## 一、Meta 的组织实验说明了什么

Reuters 2026 年 8 月调查报道了 Meta 内部一项面向“AI-native”组织的重构尝试。报道描述，公司曾希望用 AI Agent 承担更多日常工作、缩小团队并让少数员工借助 AI 获得更高产出，但计划遭遇员工反弹、工具可靠性和安全问题，部分重构随后被放缓或取消。[^1]

这件事最有价值的地方不是“Meta 有没有成功裁人”，而是它把一个组织问题公开化了：

**如果 Agent 能执行更多步骤，人类员工应该站在哪一层？**

可能的答案包括：

- 给 Agent 拆目标；
- 选择工具和权限；
- 检查关键中间结果；
- 发现幻觉或越权；
- 处理机器无法完成的边缘案例；
- 对最终结果签字或承担责任。

## 二、复核不一定比自己做更轻松

The Guardian 2026 年 2 月采访了多类劳动者，其中一名编辑描述：公司先让 AI 预编辑文本，再由人类纠错，结果她认为复核 AI 错误反而比从头编辑更耗时，而报酬却下降。[^2]

这只是单个采访案例，不能代表整个编辑行业。但它揭示一个常见误区：

> 自动生成降低了“第一稿成本”，不等于降低了“可靠成品成本”。

如果 AI 错误很稀疏、很隐蔽，复核者必须保持高度注意力，甚至需要重新推演机器为什么错。

## 三、监督劳动包含哪些新任务

可以把它拆成五层：

1. **编排**：决定哪些步骤交给哪个模型或 Agent，如何接工具、数据库和外部系统。
2. **权限控制**：决定 Agent 能读什么、写什么、能否发邮件、改数据库、调用支付或生产系统。
3. **质量复核**：检查事实、代码、合同、数据和输出是否达到标准。
4. **异常处理**：模型在大多数普通案例里自动运行，人只接手最难、最奇怪、风险最高的少数案例。
5. **责任承接**：系统可以生成或执行动作，但组织仍必须决定谁为最终结果负责。

## 四、企业正在把 Agent 当成“数字员工”管理

Reuters 2026 年 7 月报道华尔街银行部署 agentic AI 时提到，BNY 把部分 AI 系统当作“digital employees”，给它们独立登录身份并指定管理者；多家银行同时强调，高风险或面向客户的任务仍需要人类监督。[^3]

这里真正新的是管理对象发生了变化。

传统管理链条是：

**经理 → 员工 → 工具。**

Agent 化以后可能变成：

**经理 → 人类负责人 → Agent → 多个业务系统。**

Cisco 2026 年关于“agentic workforce”安全的官方材料甚至直接提出：Agent 上岗前需要身份、权限和职责边界，并映射到一个**accountable human manager**。[^4]

这不是一条行业统一规则，而是一家公司对自身风险模型的设计。但它说明“谁对 Agent 负责”已经从哲学问题进入企业访问控制和身份治理。

## 五、Agent 真出事时，责任不会自动转给机器

Reuters 2026 年 8 月采访法律专家讨论自主 Agent 越权、网络攻击和其他损害时指出，潜在责任可能落在模型开发者、部署企业或其他相关主体；现有侵权、疏忽和网络安全法律仍可能被用于追究责任。[^5]

这意味着“AI 自己做的”目前并不是一个可以自动免除人的法律答案。

对劳动组织而言，这会制造一种新的责任工作：

- 谁在部署前批准 Agent 权限？
- 谁设定可预见的失败边界？
- 谁监控异常行为？
- 谁有权立即停机或撤销权限？
- 谁保存日志供事故复盘？
- 谁在事后向客户、监管者或法院解释？

当执行越来越自动化，**责任记录、权限设计和事故复盘反而可能增加。**

## 六、“只处理异常”为什么可能更累

自动化经常先接管最规则的部分。人留下的队列因此更容易集中：

- 信息缺失；
- 多系统冲突；
- 客户情绪激烈；
- 规则无法覆盖；
- 风险极高；
- 需要专业经验。

所以人工处理数量下降，并不保证认知负荷同比下降。

如果一个人同时监督多个 Agent，还会出现新的注意力分配问题：正常运行时工作似乎很轻，一旦多个异常同时发生，人工接管能力可能瞬间成为瓶颈。

## 七、欧盟开始把“人工监督”写成制度义务

欧盟 AI Act 对高风险 AI 系统的 human oversight 要求非常具体。Article 14 要求系统允许自然人理解能力与局限、识别异常、防止 automation bias，并在必要时忽略、覆盖、逆转或停止系统输出。Article 26 又要求部署方把人工监督交给具有**能力、培训、权限和支持**的人。[^6]

对职场相关高风险 AI，雇主还需要在使用前告知受影响劳动者及其代表。[^6]

相关高风险系统的严格义务按欧盟当前实施时间表从 2027 年 12 月 2 日起进入适用阶段。[^7]

这给“AI 复核劳动”提供了一个比“有人看一眼”更严格的尺度：

> **监督者必须既看得懂，又真的有权叫停。**

如果员工被要求为 Agent 结果负责，却没有足够时间、系统可见性或停止权限，那么“human in the loop”可能只是责任转嫁，而不是真正的监督。

## 八、我们不知道什么

1. “AI 监工”尚不是统一职业分类，现有证据更多是工作内容变化。
2. Meta、银行和 Cisco 的实践不能代表所有企业。
3. 监督 Agent 是否比自己执行更高效，取决于错误率、任务风险和工具成熟度。
4. 很多企业仍不公开人工接管率、Agent 事故率、复核工时和事故成本。
5. 现有法律对自主 Agent 的具体责任分配仍在演化；Reuters 的法律讨论不能当作已经形成统一判例。
6. 这种模式可能创造新的高级岗位，也可能把更多责任压给更少的人，净效应未知。

## 评曰

自动化经常被想象成人消失。现实更可能是：人的手从操作杆上移开，却仍然盯着仪表盘，并在机器出错时负责把事情救回来。

到了 Agent 时代，“谁在盯”还不够。

更重要的问题是：**谁能看懂、谁有权限叫停、谁保留证据、谁在事故以后负责。**

如果机器拿走执行权，而人只剩责任，这不叫完全自动化；它只是把劳动从操作变成了监督和担责。

---

[^1]: Reuters, “Mark Zuckerberg had a bold plan to replace Meta staff with AI. Here's how it imploded,” 2026-08-26. https://www.reuters.com/investigations/mark-zuckerberg-had-bold-plan-replace-meta-staff-with-ai-heres-how-it-imploded-2026-08-26/
[^2]: The Guardian, “Keen bosses, strange mistakes and a looming threat: workers on training AI to do their jobs,” 2026-02-26. https://www.theguardian.com/technology/2026/feb/26/workers-training-ai-to-do-their-jobs
[^3]: Reuters, “Wall Street banks ramp up digital assistants in bid to win productivity race,” 2026-07-13. https://www.reuters.com/business/finance/wall-street-banks-ramp-up-digital-assistants-bid-to-win-productivity-race-2026-07-13/
[^4]: Cisco, “Cisco Reimagines Security for the Agentic Workforce,” 2026-03. https://newsroom.cisco.com/c/r/newsroom/en/us/a/y2026/m03/cisco-reimagines-security-for-the-agentic-workforce.html
[^5]: Reuters, “Who is liable when AI goes rogue? Lawyers see new risks,” 2026-08-07. https://www.reuters.com/business/who-is-liable-when-ai-goes-rogue-lawyers-see-new-risks-2026-08-07/
[^6]: Regulation (EU) 2024/1689, Articles 14 and 26, consolidated text accessed 2026-08-28. https://eur-lex.europa.eu/eli/reg/2024/1689/2026-07-27/eng
[^7]: European Commission, “AI Act,” implementation timeline accessed 2026-08-28. https://digital-strategy.ec.europa.eu/en/policies/regulatory-framework-ai
