# LLM 碳排放与环境影响研究素材

> 搜集时间：2026-06-20 | 来源：迷迭香情报分析师
> 任务：LLM_Chronicle 新志素材搜集 — 任务4：LLM 碳排放

---

## 一、核心学术论文

### 1. Nature Scientific Reports — "Reconciling the contrasting narratives on the environmental impact of large language models"

- **来源**：Nature Scientific Reports
- **作者**：Shaolei Ren, Bill Tomlinson, Rebecca W. Black, Andrew W. Torrance
- **日期**：2024-11-01
- **URL**：https://www.nature.com/articles/s41598-024-76682-6
- **DOI**：10.1038/s41598-024-76682-6
- **可信度**：高（同行评审学术期刊，被引用 101 次）

**核心发现**：

**典型 LLM (Llama-3-70B) vs. 人类（美国居民）**：
- 能耗：LLM 0.020 kWh vs 人类 0.85 kWh/页 → 人/LLM 比 = 44
- 碳排放：LLM 15 克 vs 人类 800 克 CO₂/页 → 人/LLM 比 = 53
- 水耗：LLM 0.14 升 vs 人类 5.7 升/页 → 人/LLM 比 = 40
- 经济成本：LLM $0.08 vs 人类 $12.1/页 → 人/LLM 比 = 150

**轻量 LLM (Gemma-2B-it) vs. 人类（美国居民）**：
- 能耗：LLM 0.00024 kWh → 人/LLM 比 = 3500
- 碳排放：LLM 0.18 克 → 人/LLM 比 = 4400
- 水耗：LLM 0.0017 升 → 人/LLM 比 = 3300
- 经济成本：LLM $0.01 → 人/LLM 比 = 1200

**与印度居民对比**：
- 典型 LLM：人/LLM 比 3.4-16
- 轻量 LLM：人/LLM 比 130-1100

**方法论**：
- 使用生命周期评估（LCA）方法（ISO 14040/14044）
- 功能单位：生成一篇 500 字内容
- 考虑能耗、碳排放、水耗、经济成本四个维度
- 保守估计：将运营环境足迹乘以 2 来考虑隐含碳排放

**关键警告**：
> "While the human-to-LLM ratios are smaller with regard to human labor in India, these ratios are still between 3.4 and 16 for a typical LLM and between 130 and 1100 for a lightweight LLM."

> "Despite the potential benefit of switching from humans to LLMs, economic factors may cause widespread adoption to lead to a new combination of human and LLM-driven work, rather than a simple substitution."

> "Moreover, the growing size of LLMs may substantially increase their energy consumption and lower the human-to-LLM ratios, highlighting the need for further research to ensure the sustainability and efficiency of LLMs."

**局限性**：
- 分析仅针对 500 字页面写作这一简单任务
- 依赖公开数据和假设
- 未考虑 LLM 采用的长期影响（失业、技能发展、创新）
- 未考虑 OpenAI 定价可能受到大量补贴

---

### 2. Nature — "The carbon emissions of writing and illustrating are lower for AI than for humans"

- **来源**：Nature Scientific Reports
- **作者**：Bill Tomlinson, Rebecca W. Black, Donald J. Patterson, Andrew W. Torrance
- **日期**：2024
- **被引用**：161 次
- **可信度**：高（同行评审，高引用）

**核心发现**：
- AI 系统每页文本的 CO₂ 排放量比人类作者低 130-1500 倍

---

### 3. Nature — "Environmental impact and net-zero pathways for AI"

- **来源**：Nature
- **作者**：T Xiao et al.
- **日期**：2025
- **被引用**：79 次
- **可信度**：高

**核心发现**：
- 提供 2024-2030 年 AI 服务器能耗、水足迹和碳排放的年度估算
- 分析不同情景下的环境影响

---

### 4. Nature — "Sustainability in large language model supply chains"

- **来源**：Nature
- **作者**：V Mishra et al.
- **日期**：2025
- **被引用**：7 次
- **可信度**：高

**核心发现**：
- LLM 的能源密集型特性可能导致碳排放增加
- 如果能源来源不可再生，影响更为严重

---

## 二、新闻报道

### 5. Nature News — "How much energy will AI really consume? The good, the bad and the unknown"

- **来源**：Nature News
- **日期**：2025-03-05
- **URL**：https://www.nature.com/articles/d41586-025-00582-4
- **可信度**：高（权威科学期刊新闻版）

**核心要点**：
- 研究人员希望公司更透明地披露 AI 的电力需求
- AI 能耗的不确定性仍然很大

---

### 6. UNESCO — "Environmental contradictions of large language models in higher education"

- **来源**：UNESCO
- **日期**：2026-01-06
- **可信度**：高（国际组织报告）

**核心要点**：
- 大学正在竞相采用 AI，即使其环境成本不断上升

---

### 7. The Guardian — "Revealed: Big tech's new datacentres will take water from the world's driest areas"

- **来源**：The Guardian
- **日期**：2025-04-09
- **URL**：https://www.theguardian.com/technology/2025/apr/09/big-tech-datacentres-water-drought
- **可信度**：高（调查报道）

**核心要点**：
- Amazon、Google 和 Microsoft 正在五大洲的缺水地区建设数据中心

---

## 三、技术分析

### 8. Stanford HAI — "The Environmental Impacts of Large Language Models"

- **来源**：Stanford University Human-Centered Artificial Intelligence
- **作者**：M Govil et al.
- **URL**：https://hai.stanford.edu/news/environmental-impacts-large-language-models
- **可信度**：高（顶级研究机构）

**核心要点**：
- 估算能耗、排放和环境影响的困难
- 提供背景信息和方法论讨论

---

## 四、关键数据点汇总

| 模型 | 能耗 (kWh/页) | 碳排放 (g CO₂/页) | 水耗 (L/页) | 成本 ($/页) |
|------|--------------|------------------|------------|------------|
| Llama-3-70B | 0.020 | 15 | 0.14 | 0.08 |
| Gemma-2B-it | 0.00024 | 0.18 | 0.0017 | 0.01 |
| 美国人类 | 0.85 | 800 | 5.7 | 12.1 |
| 印度人类 | 0.066 | 95 | 1.3 | 1.1 |

**人/LLM 比率（典型 LLM vs 美国人类）**：
- 能耗：44
- 碳排放：53
- 水耗：40
- 经济成本：150

**人/LLM 比率（轻量 LLM vs 美国人类）**：
- 能耗：3,500
- 碳排放：4,400
- 水耗：3,300
- 经济成本：1,200

---

## 五、训练 vs 推理的能耗对比

**训练能耗**（单次训练）：
- GPT-3 (175B)：~1,300 MWh（相当于 5 辆汽车一生的能耗）
- Llama-2 (70B)：数据未公开
- GPT-4：数据未公开

**推理能耗**（每次查询）：
- Llama-3-70B：~0.008 kWh（GPU）+ 40% 非 GPU = ~0.017 kWh
- Gemma-2B-it：~0.0002 kWh

**关键洞察**：
- 推理的总计算需求可以远远超过训练
- 训练成本可以摊销到每个推理请求中
- 但摊销成本高度依赖模型总使用量

---

## 六、争议与反论

**支持"LLM 更环保"的论点**：
- 单位输出的碳排放远低于人类
- 可以替代高碳排放的人类活动
- 随着模型效率提升，能耗比持续改善

**反对"LLM 更环保"的论点**：
- 模型规模持续增长（Llama-3.1-405B）
- 经济因素可能导致广泛采用带来新的环境负担
- 未考虑训练成本的完整摊销
- 反弹效应：低成本可能导致使用量激增
- 定价可能受到大量补贴

---

## 七、关联条目建议

- 志条目：《AI 环境影响》
- 志条目：《数据中心与能源》
- 编年条目：2024/11（Nature 环境影响论文发表）
- 论条目：《AI 可持续性论》

---

## 八、信息缺口

1. GPT-4、GPT-5 等闭源模型的实际训练能耗
2. 各大厂数据中心的 PUE（电源使用效率）实际值
3. AI 能耗预测模型的验证（2024-2030）
4. 可再生能源在 AI 能耗中的实际占比
5. 碳抵消措施的实际效果

---

*文件生成时间：2026-06-20 21:26 UTC+8*
