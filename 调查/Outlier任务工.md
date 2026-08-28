# Outlier 任务工：模型后训练时代的承包平台

> **截至 2026-08-28。状态：REVISED。** 平台条款可以确认 Outlier 如何定义 contributor 与任务关系；媒体调查可以确认部分任务工报告了无薪培训/资格测试、任务波动和监控；但“独立承包商”是合同标签，不自动等于劳动法上的最终身份。美国联邦 worker-classification 标准在 2026 年仍处于重新制定阶段。

Scale AI 早期最知名的众包品牌是 Remotasks。到大模型后训练时代，Outlier 成为更显眼的平台：它面向有大学或更高专业背景的贡献者，提供生成提示词、比较模型回答、改写答案、专业评测等任务。

这不是传统企业里的“AI 训练师职位”，而是一种平台化承包劳动。

## 一、平台自己如何定义劳动关系

Outlier 2026 年 5 月生效的 Terms of Use 明确写明，参与任务的人以**独立承包商**身份提供服务，不构成雇佣关系，也不获得雇员福利。[^1]

平台 FAQ 则说明，专家贡献者可能：

- 生成提示词；
- 对模型输出进行排序；
- 改进模型回答；
- 执行其他帮助提升模型表现的任务。[^2]

项目长度和任务供应根据客户需求变化，并不保证持续存在。[^2]

这几个条款一起勾勒出了平台希望建立的劳动模型：**平台提供任务入口，贡献者出售专业判断，项目是否存在取决于下游客户。**

但必须区分“合同怎么写”和“法律最终怎么认定”。

## 二、合同写 contractor，不代表法律问题已经结束

美国劳工部对 FLSA 下 employee / independent contractor 的官方说明强调，劳动者是否属于 employee 要看实际的 **economic realities**：如果一个人在经济现实上依赖某个企业获得工作，可能属于受 FLSA 保护的 employee；如果真正为自己经营业务，则更接近 independent contractor。劳动者不能仅靠签合同或自愿声明就放弃本来依法享有的最低工资、加班等权利。[^7][^8]

而且这套联邦判断框架在 2026 年仍然处于变化中。美国劳工部 2026 年 2 月提出新规则，拟撤销 2024 年规则，改用五因素 economic-reality analysis，并把**控制程度**与**获利/亏损机会**作为核心因素；该方案在本文截止日仍是 proposed rule，不是已经完成的新最终规则。[^7]

因此，对 Outlier 只能写：

- 平台合同把 contributor 定义为 independent contractor；
- 这会影响福利、税务与平台日常管理方式；
- **仓库不能仅凭 Terms 就宣布法院或劳工部门已经认定所有 Outlier taskers 都合法属于独立承包商。**

同样，也不能反过来仅凭媒体采访宣布他们已经被法院认定为 employee。

## 三、为什么它和早期众包不同

早期众包常把任务切得尽可能简单，让大量没有专业背景的人也能完成。

Outlier 的公开招募则强调领域知识：很多机会要求本科层级知识，并偏好研究生、硕士或博士背景。[^3]

模型越强，简单判断越容易自动化；但同时，模型会在更复杂的数学、代码、法律、科学和写作问题上暴露更隐蔽的错误。因此后训练平台开始采购：

- 更难的问题；
- 更细的评分标准；
- 专业错误解释；
- 长链条任务的结果验证。

这使“数据工”的画像从纯低技能劳动扩展成从学生到博士都可能参与的分层市场。

## 四、无薪资格测试和培训争议：可以确认什么

The Guardian 2026 年 4 月调查采访多名 Outlier 任务工。受访者描述了项目突然消失、价格变化、Hubstaff 监控、资格测试，以及他们认为属于**无薪培训或无薪 onboarding** 的时间。报道还记录了部分工人担忧，这些训练/资格任务本身可能对 AI 项目具有生产价值。[^4]

这里必须非常谨慎。

媒体采访能支持：

- **有受访者报告自己做过未付费的培训或资格测试；**
- 任务工认为其中一些活动与真实项目工作高度相似；
- 项目资格和任务供应会直接影响收入。

但这还不能支持：

- “法院已认定 Outlier 系统性 wage theft”；
- “所有资格测试依法都必须按雇员工时支付”；
- “所有培训数据都被 Scale 用作客户训练数据”。

这些更强结论需要具体案件中的合同、实际控制关系、工作内容和法院/监管认定。

## 五、为什么无薪时间在平台劳动里特别重要

按任务计费会让很多劳动时间落在任务价格之外：

- 找项目；
- 阅读新项目规则；
- 做资格测试；
- 等待任务释放；
- 处理身份验证或账户申诉；
- 学习新的评分 rubric；
- 因项目关闭重新寻找下一批任务。

如果只统计“成功完成并结算的 task 时薪”，这些时间可能完全消失。

这和传统雇员的一个重要区别是：平台贡献者经常需要自己承担**可工作性维护成本**——保持账号合规、不断通过新项目门槛、适应规则切换，却没有持续工时保证。

因此研究平台工资时，真正值得问的不是广告上的“每小时最高多少”，而是：

> **从开始找任务到最终拿到钱，劳动者总共投入了多少时间？**

目前没有公开独立数据能给出 Outlier 全平台这个“有效时薪”。

## 六、Scale 与 Meta 的关系变化

2025 年 6 月，Meta 对 Scale AI 进行约 143 亿美元投资，Reuters 报道其取得约 49% 股权；Scale 官方则强调公司仍保持独立运营。[^5][^6]

这件事本身不意味着 Outlier 任务都服务于 Meta。Scale 仍服务多个客户，因此不能根据股权关系推断某个具体任务的最终客户。

这恰好说明数据劳动研究为什么需要区分：**平台所有权、客户关系和具体项目**是三层不同事实。

## 七、劳动者面临的典型不确定性

根据平台结构和公开报道，可以确认以下风险类型存在，但严重程度因项目而异：

- **任务空窗**：有账号不等于一直有活；
- **资格门槛**：项目可能要求额外测试或 onboarding；
- **不可计费时间**：部分受访者报告培训/资格活动未获报酬；
- **价格差异**：不同专业、地区与项目报价不同；
- **客户不可见**：贡献者未必知道最终模型或产品；
- **账户与合规风险**：身份、地区和平台规则决定能否继续接单；
- **福利缺失**：按平台合同，贡献者不是雇员且不享有传统雇员福利；
- **法律身份不确定**：合同标签与具体劳动法身份并非同一个问题。

## 八、我们不知道什么

1. 没有公开独立数据能给出 Outlier 全平台的典型时薪或包含等待/测试时间后的有效时薪。
2. 媒体报道中的负面案例不能代表所有贡献者体验。
3. 平台宣传的高薪岗位也不能代表大多数任务。
4. 无法仅凭任务描述判断贡献数据最终进入哪个模型。
5. Meta 对 Scale 的投资不能用于推断每个 Outlier 项目的客户身份。
6. 目前不能写“Outlier taskers 已被统一法律认定为 employee”或“已被统一认定为合法 independent contractors”。
7. 美国劳工部 2026 年独立承包商规则仍在变化，联邦、州和具体案件还可能适用不同标准。

## 九、为什么 Outlier 值得长期跟踪

Outlier 代表了 AI 数据产业的一个阶段变化：

**从“把廉价重复劳动外包”走向“把专业判断也平台化”。**

而平台化的不只是任务本身，还包括风险：项目等待、资格成本、收入波动、福利缺失和法律身份争议，都可能被拆散到劳动者个人承担。

当律师、程序员、语言学家、数学研究者都可以按任务出售几分钟专业判断时，最重要的统计未必是平台报出的 hourly rate，而是**一年里到底有多少小时真正可以按那个 rate 卖出去。**

## 评曰

平台最擅长把连续职业拆成离散任务。Uber 拆一次行程，外卖平台拆一单配送，AI 后训练平台拆一次判断。

但一份工作从来不只有“执行那一下”。

人在任务前要学习、等待、过资格；任务后还要处理审核和账号风险。如果平台只为中间那几分钟付钱，劳动史就需要把两边那些看不见的时间重新捡回来。

至于这些人法律上到底是不是 employee，不能由仓库替法院提前判。

我们能做的是把**合同标签、实际工作方式、工人主张和法律标准**分别保存下来，等事实继续长出来。

---

[^1]: Outlier AI, Terms of Use, effective 2026-05-11. https://outlier.ai/legal/terms-of-use
[^2]: Outlier AI, FAQ, accessed 2026-08-28. https://outlier.ai/faq
[^3]: Outlier AI, homepage/qualifications, accessed 2026-08-28. https://outlier.ai/
[^4]: The Guardian, “Porn, dog poo and social media snaps: the 'taskers' scraping the internet for AI firm part-owned by Meta,” 2026-04-07. https://www.theguardian.com/technology/2026/apr/07/meta-scale-ai-social-media-technology
[^5]: Reuters, “Meta poaches 28-year-old Scale AI CEO after taking multibillion dollar stake in startup,” 2025-06-13. https://www.reuters.com/business/finance/meta-finalizes-investment-scale-ai-valuing-startup-29-billion-2025-06-13/
[^6]: Scale AI, “Scale AI Announces Next Phase of Company’s Evolution,” 2025-06-12. https://scale.com/blog/scale-ai-announces-next-phase-of-company-evolution
[^7]: U.S. Department of Labor, “Questions and Answers — NPRM: Employee or Independent Contractor Status,” 2026-02-26. https://www.dol.gov/agencies/whd/flsa/misclassification/2026rulemaking/faqs
[^8]: U.S. Department of Labor, Fact Sheet 13, “Employment Relationship Under the Fair Labor Standards Act,” accessed 2026-08-28. https://www.dol.gov/agencies/whd/fact-sheets/13-flsa-employment-relationship
