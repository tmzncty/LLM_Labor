# Table · LLM Environmental Impact Data

> Compiled by: Ptilopsis | Updated: 2026-06-21
> Data sources: See footnotes in each table

---

## 1. LLM vs. Human Environmental Impact Comparison

Functional unit: generating one page (~500 words) of content. Based on life cycle assessment methodology (ISO 14040/14044), conservatively estimated by multiplying operational environmental footprint ×2 to account for embodied carbon emissions.

| Metric | Llama-3-70B (per page) | US Human (per page) | European Human (per page)[^a] | Human/LLM Ratio (US) | Human/LLM Ratio (Europe) |
|--------|----------------------|--------------------|------------------------------|---------------------|-------------------------|
| Energy consumption (kWh) | 0.020 | 0.85 | ~0.50 | 44 | ~25 |
| Carbon emissions (g CO₂) | 15 | 800 | ~360 | 53 | ~24 |
| Water consumption (L) | 0.14 | 5.7 | ~3.2 | 40 | ~23 |
| Economic cost ($) | 0.08 | 12.1 | ~9.0 | 150 | ~113 |

> **Comparison with Indian residents**: A typical LLM's human/LLM ratio is only 3.4–16; a lightweight LLM (Gemma-2B-it) is 130–1100.[^3] The gap narrows dramatically.

[^a]: European data is estimated based on per-capita energy consumption / carbon emission coefficients; the original source did not directly provide European comparisons. US data from [^3]; European estimates reference IEA 2024 EU average carbon intensity of 0.36 kg CO₂/kWh and Eurostat per-capita energy consumption data.
[^3]: Shaolei Ren et al., "Reconciling the contrasting narratives on the environmental impact of large language models," *Nature Scientific Reports*, 2024-11-01. https://www.nature.com/articles/s41598-024-76682-6

---

## 2. Environmental Impact Comparison Across Models

| Model | Parameters | Energy (kWh/page) | Carbon (g CO₂/page) | Water (L/page) | Cost ($/page) | Human/LLM Ratio (carbon, vs US) |
|-------|-----------|------------------|---------------------|---------------|--------------|-------------------------------|
| Llama-3-70B | 70B | 0.020 | 15 | 0.14 | 0.08 | 53 |
| Gemma-2B-it | 2B | 0.00024 | 0.18 | 0.0017 | 0.01 | 4,400 |
| GPT-4 (estimated)[^b] | ~1.8T (MoE) | ~0.03–0.06 | ~20–50 | ~0.2–0.5 | ~0.03–0.06 | ~16–40 |

> **Inference energy breakdown**: Llama-3-70B single inference GPU energy ~0.008 kWh, plus ~40% non-GPU overhead (cooling, networking, storage), total ~0.017 kWh. Gemma-2B-it ~0.0002 kWh.[^3]

> **Training vs. Inference**: GPT-3 (175B parameters) single training run ~1,300 MWh.[^1] Inference's total compute demand can far exceed training—when a model is queried billions of times, total inference-stage energy consumption can be several times the training cost.[^3]

[^b]: GPT-4 is a closed-source model; OpenAI has never disclosed training/inference energy data. Estimates here are based on Llama-3-70B data extrapolated by parameter count, accounting for the MoE architecture's actual activated parameter ratio. Estimate ranges are wide, with high uncertainty.
[^1]: The Verge, "Training a single AI model can emit as much carbon as five cars in their lifetimes," 2019-06-06. https://www.theverge.com/2019/6/6/18655362/ai-climate-change-energy-emissions
[^3]: Shaolei Ren et al., *Nature Scientific Reports*, 2024-11-01.

---

## 3. Data Center Water Usage Issues

Major tech companies are building data centers at scale in water-scarce regions worldwide, with cooling demands intensifying local water stress.

| Company | Data Center Location (Water-Scarce Region) | Est. Annual Water Usage | Drought Status | Source |
|---------|------------------------------------------|----------------------|---------------|--------|
| Amazon (AWS) | USA · Arizona (Phoenix) | Billions of gallons/year[^c] | Extreme drought; Colorado River levels continuously declining | [^4] |
| Amazon (AWS) | Spain (Aragon) | Undisclosed | Mediterranean climate arid zone; persistent drought 2023–2025 | [^4] |
| Google | USA · Texas (Dallas) | Undisclosed | Semi-arid; severe drought in 2022 | [^4] |
| Google | Chile (Santiago) | Undisclosed | Climate change-driven long-term drought | [^4] |
| Microsoft | USA · Arizona | Billions of gallons/year[^c] | Extreme drought | [^4] |
| Microsoft | Ireland (Dublin) | 6 billion liters/year (2024)[^d] | Relatively water-abundant, but highest data center density globally | [^d] |

> **Scale perspective**: Llama-3-70B consumes 0.14 liters of water per page.[^3] At 100 million daily queries, daily water consumption would be ~140,000 liters—equivalent to the annual water usage of 56 standard swimming pools.

[^c]: Specific AI water usage figures are not separately disclosed by companies; only overall data center water usage data is available.
[^4]: The Guardian, "Revealed: Big tech's new datacentres will take water from the world's driest areas," 2025-04-09. https://www.theguardian.com/technology/2025/apr/09/big-tech-datacentres-water-drought
[^d]: Microsoft 2024 Sustainability Report; The Irish Times 2024 reporting.

---

## 4. AI Carbon Emissions Trend (2020–2030 Forecast)

| Year | AI Training Cost Trend | AI Inference Cost Trend | Total Emissions Trend (Scenario) | Key Events |
|------|----------------------|------------------------|--------------------------------|-----------|
| 2020 | GPT-3 training: ~1,300 MWh; only few lab-scale models | Daily inference requests: millions level | Low | GPT-3 released; AI in lab stage |
| 2022 | Training costs rising: larger models, larger datasets | Inference requests surging after ChatGPT release | Moderate | ChatGPT 100M MAU; inference energy beginning to accumulate |
| 2024 | Per-training cost continues rising; efficiency gains partially offset | Daily inference requests: billions level | Medium-High | GPT-4, Llama-3 commercialized; enterprise-scale deployment |
| 2026 (current) | Training efficiency improving (MoE, quantization); but model scale continues growing | Inference cost declining due to efficiency gains; but total request volume continues rising | High | Multi-modal models, Agent systems further driving up inference demand |
| 2028 (forecast) | Possible training cost inflection point (synthetic data, distillation) | Inference total could be several times that of 2024 | High–Very High | Rebound effect: lower costs stimulate more use cases |
| 2030 (forecast) | Highly uncertain | Highly uncertain | Very High (worst scenario)[^e] | If renewable energy does not replace at scale, carbon emissions will continue rising |

> **Key uncertainty**: 2030 forecasts vary dramatically across scenarios—from "carbon emissions plateau" to "carbon emissions multiply several times"—depending on: (1) renewable energy share; (2) model efficiency optimization speed; (3) AI usage growth rate.[^7]

> **Core warning**: "The energy-intensive nature of LLMs may lead to increased carbon emissions, with more severe impact if energy sources are non-renewable."[^8]

[^e]: "Nearly all scenarios point in the same direction: total energy consumption is growing."[^7]
[^7]: T Xiao et al., "Environmental impact and net-zero pathways for AI," *Nature*, 2025.
[^8]: V Mishra et al., "Sustainability in large language model supply chains," *Nature*, 2025.

---

## 5. Information Black Box: Hidden Data

| Data Item | Disclosure Status | Notes |
|-----------|------------------|-------|
| GPT-4 training energy | **Not disclosed** | OpenAI has never disclosed |
| GPT-5 training energy | **Not disclosed** | Same as above |
| Actual PUE values for each company's data centers | **Not separately disclosed** | Only overall sustainability data provided |
| Renewable energy share in AI energy consumption | **Unknown** | Companies claim "carbon neutral" but provide no AI-specific data |
| Carbon offset effectiveness | **Not independently verified** | Voluntary carbon market credit quality varies |

> As of mid-2026, no country in the world requires AI companies to disclose their models' environmental impact.[^5][^6]

[^5]: Nature News, "How much energy will AI really consume? The good, the bad and the unknown," 2025-03-05. https://www.nature.com/articles/d41586-025-00582-4
[^6]: UNESCO, "Environmental contradictions of large language models in higher education," 2026-01-06.
