# LLM Carbon Emissions

> In November 2024, four scholars published a paper in Nature Scientific Reports claiming that Llama-3-70B's carbon emissions per page of generated text are only one fifty-third of those of a human author. This figure has been widely cited by the tech industry as the "green argument" for AI expansion. But the paper itself acknowledges: the analysis is limited to 500-word page writing, does not consider complete amortization of training costs, does not consider rebound effects, and does not answer a fundamental question—who actually enjoys the carbon emissions saved by AI?

## I. Background

After ChatGPT's release in 2022, public attention to AI's environmental costs surged dramatically. A widely circulated figure was: training GPT-3 (175 billion parameters) once requires approximately 1,300 megawatt-hours of electricity, equivalent to the lifetime energy consumption of five cars.[^1] As larger models like GPT-4, Llama-3, and Claude 3 were released successively, "AI eats electricity" became a regular media headline.

But tech companies quickly found their counter-narrative. In early 2024, Shaolei Ren (任少磊) from the University of California, Riverside and collaborators published a paper in Nature Scientific Reports with a straightforward title: "The Carbon Emissions of Writing and Illustrating Are Lower for AI Than for Humans."[^2] The paper claimed AI systems emit 130 to 1,500 times less carbon per page of text than human authors. This article was cited 161 times, becoming the tech industry's most frequently cited "green defense."

However, the 130 to 1,500 times range was too broad, sparking academic质疑. In November 2024, the original author team published a follow-up paper in the same journal, with a more cautious title: "Reconciling the Contrasting Narratives on the Environmental Impact of Large Language Models."[^3] The paper recalculated using newer models, provided more detailed data, and acknowledged more limitations.

Meanwhile, another narrative was unfolding. In April 2025, The Guardian published an investigative report revealing that Amazon, Google, and Microsoft were massively building data centers in water-scarce regions across five continents.[^4] In March 2025, Nature News追问: how much energy will AI really consume? The conclusion was "uncertainty remains significant."[^5] In early 2026, UNESCO指出 that universities were racing to adopt AI, even as its environmental costs continued to rise.[^6]

The debate around LLM carbon emissions has never been purely technical. It is a political question about cost allocation: who benefits from AI, and who pays for AI's environmental costs?

## II. Core Facts

### 2.1 Human vs. LLM Carbon Emission Comparison

The November 2024 Nature Scientific Reports paper[^3] adopted a life cycle assessment methodology (ISO 14040/14044), using "generating one page of 500-word content" as the functional unit, comparing LLM and human authors' environmental footprints across four dimensions: energy consumption, carbon emissions, water consumption, and economic cost.

**Comparison between typical LLM (Llama-3-70B) and US residents:**

| Metric | Llama-3-70B (per page) | US Human (per page) | Human/LLM Ratio |
|--------|------------------------|---------------------|-----------------|
| Energy consumption | 0.020 kWh | 0.85 kWh | 44 |
| Carbon emissions | 15 g CO₂ | 800 g CO₂ | 53 |
| Water consumption | 0.14 liters | 5.7 liters | 40 |
| Economic cost | $0.08 | $12.1 | 150 | [^3]

**Comparison between lightweight LLM (Gemma-2B-it) and US residents:**

| Metric | Gemma-2B-it (per page) | US Human (per page) | Human/LLM Ratio |
|--------|------------------------|---------------------|-----------------|
| Energy consumption | 0.00024 kWh | 0.85 kWh | 3,500 |
| Carbon emissions | 0.18 g CO₂ | 800 g CO₂ | 4,400 |
| Water consumption | 0.0017 liters | 5.7 liters | 3,300 |
| Economic cost | $0.01 | $12.1 | 1,200 | [^3]

**Compared with developing country residents, the gap narrows sharply:**

Compared with Indian residents, the typical LLM's human/LLM ratio is only 3.4 to 16, and the lightweight LLM is 130 to 1,100.[^3] The paper authors noted:

> "Despite the potential benefits of transitioning from humans to LLMs, economic factors may lead to widespread adoption bringing a new hybrid human-LLM work model rather than simple substitution."[^3]

### 2.2 Training vs. Inference Energy Consumption Breakdown

Carbon emission calculations must distinguish between two phases.

**Training phase** (one-time investment): GPT-3 (175 billion parameters) approximately 1,300 megawatt-hours.[^1] Data for GPT-4 and Llama-2 have not been publicly disclosed.

**Inference phase** (per query): Llama-3-70B approximately 0.008 kWh (GPU), plus approximately 40% non-GPU overhead, totaling approximately 0.017 kWh. Gemma-2B-it approximately 0.0002 kWh.[^3]

The key point is: total inference computation需求 can far exceed training.[^3] When a model receives billions of queries, the total energy consumption of the inference phase may be several times the training cost. The paper authors used a conservative estimate: multiplying operational environmental footprint by 2 to account for embodied carbon emissions from hardware manufacturing and data center construction.

### 2.3 Data Centers' Water Crisis

Beyond carbon emissions, water consumption is another overlooked dimension.

In April 2025, The Guardian's investigative report[^4] revealed a fact: Amazon, Google, and Microsoft were building data centers in water-scarce regions globally. These data centers require大量 water to cool servers, and they are deployed precisely in the world's most water-stressed regions.

The Nature Scientific Reports paper's data corroborates this concern: Llama-3-70B consumes 0.14 liters of water per page,[^3]虽然远低于人类的 5.7 liters, but when query volumes reach billions, the absolute water consumption becomes不可忽视.

### 2.4 Information Black Box

Regarding AI's environmental impact, the最大的困难 is lack of data. Training energy consumption for closed-source models like GPT-4 and GPT-5 has never been publicly disclosed.[^3] The actual Power Usage Effectiveness (PUE) values of major companies' data centers are undisclosed. The proportion of renewable energy in AI energy consumption is unknown. The effectiveness of carbon offset measures has not been independently verified.

A 2025 Nature paper[^7] attempted to estimate AI servers' energy consumption, water footprint, and carbon emissions from 2024 to 2030, but the figures varied dramatically across different scenarios. Another paper published the same year[^8] warned: LLMs' energy-intensive nature may lead to increased carbon emissions, "with more severe impacts if energy sources are non-renewable."

## III. Testimonies

### Researchers' Voices

**Shaolei Ren** (Associate Professor, University of California, Riverside; first author)[^3] is a pioneer in AI water consumption research. In the November 2024 paper, he attempted to "reconcile contrasting narratives"—responding to both the criticism that "AI is a carbon emission monster" and pointing out limitations in the argument that "AI is more environmentally friendly than humans." The warning at the paper's conclusion deserves full quotation:

> "Continued growth in LLM scale may substantially increase their energy consumption and降低 the human/LLM ratio, highlighting the need for further research to ensure LLM sustainability and efficiency."[^3]

**Bill Tomlinson** (Professor, University of California, Irvine; co-author)[^2][^3] is an environmental informatics researcher. The earlier paper he参与 claimed AI carbon emissions are 130 to 1,500 times lower than humans,[^2] but the follow-up paper明显收紧 its表述.

### Tech Industry's Silence

Notably, major companies developing closed-source models—OpenAI, Anthropic, Google DeepMind—have几乎未 publicly disclosed their models' environmental impact data. Nature News pointed out in March 2025 that researchers希望 companies would more transparently disclose AI's electricity需求, but these呼吁至今未得到实质回应.[^5] GPT-4 and GPT-5's training energy consumption has never been公布.

### UNESCO's Warning

In January 2026, UNESCO published a report指出 that universities were racing to adopt AI, even as its environmental costs continued to rise.[^6] The report title's term "environmental contradictions" precisely概括了 the现状: educational institutions advocate for sustainable development while大规模 deploying energy-intensive AI tools.

## IV. Impact and Aftermath

### 4.1 Propagation and Misuse of the "Green Argument"

The paper claiming "AI carbon emissions are 130 to 1,500 times lower than humans"[^2] was cited 161 times, becoming the tech industry's most frequently cited "green defense." But this figure has serious methodological problems: the 130 to 1,500 times range意味着 uncertainty spans an order of magnitude; the comparison baseline is US residents—one of the world's highest per-capita carbon emitting groups.

Using Americans' carbon emissions as the comparison baseline is itself a精心选择的参照系. The paper's comparison data with Indian residents shows the typical LLM's human/LLM ratio is only 3.4 to 16.[^3] If AI替代的是 developing country workers' writing, the environmental benefits would大幅缩水.

### 4.2 Rebound Effects

The paper contains a widely overlooked warning: "Economic factors may lead to widespread adoption bringing a new hybrid human-LLM work model rather than simple substitution."[^3]

This is the "rebound effect" in economics: when a technology reduces the cost of an activity, the total volume of that activity often doesn't decrease but increases. LLMs make text generation cheap, resulting not in people writing less, but in more writing—more emails, more reports, more marketing copy.

The 2025 Nature paper[^7] attempted to estimate AI's total energy consumption from 2024 to 2030, with dramatically different figures across scenarios, but nearly all scenarios pointed in the same direction: total energy consumption is growing.

### 4.3 The Model Scale Arms Race

The most cited sentence from the paper may be: "Continued growth in LLM scale may substantially increase their energy consumption and降低 the human/LLM ratio."[^3] This is not hypothetical but a fact in progress. Llama-3-70B's 70 billion parameters are already considered "typical," but Meta subsequently released Llama-3.1-405B—nearly six times the parameter count. If the human/LLM ratio decreases as model scale increases, the "53 times" advantage could be eroded within a few years.

### 4.4 Regulatory Absence

As of mid-2026, no country globally requires AI companies to disclose their models' environmental impact.[^5][^6] The EU's AI Act focuses on safety and transparency, mentioning carbon emissions not at all. Microsoft and Google mention total data center energy consumption in their annual sustainability reports but refuse to单独列出 AI training and inference energy consumption.[^5]

## Assessment

This investigation's core finding can be浓缩为 a single number: 53 times. Every page a human writes emits 53 times more carbon than Llama-3-70B. This figure comes from a peer-reviewed academic journal, with traceable methodology and reproducible data.

But numbers don't speak for themselves. The question behind the number is: whose carbon emissions are being saved? Whose costs are being transferred?

The answer to the first question is clear. LLMs替代的是 knowledge workers' writing—white-collar workers, teachers, journalists, analysts. These people's work locations are primarily in developed countries, where carbon emission baselines are already high. Using LLMs to替代 an American white-collar worker's writing reduces carbon emissions 53 times;替代 an Indian worker's writing reduces them 3.4 to 16 times.[^3] The saved carbon emissions primarily benefit developed-country enterprises—operating costs decrease, profits increase.

The answer to the second question is more隐蔽. The carbon emissions saved by LLMs haven't disappeared; they've been converted into data center energy and water consumption, concentrated in specific geographic regions. Amazon, Google, and Microsoft are building data centers in water-scarce areas,[^4] affecting local communities and ecosystems. When a Silicon Valley engineer uses ChatGPT to write an email, it消耗的是 Arizona's groundwater. This geographic转移 of costs is precisely what environmental justice researchers call the "sacrifice zone" phenomenon.

The deeper question is the rebound effect. LLMs make text generation cheap, resulting not in humans writing less, but in more writing. Every AI-generated marketing email, every AI批量-produced press release, every AI-filled piece of废话—all represent新增 carbon emissions. If AI's total usage increases tenfold due to falling costs, even if unit carbon emissions decrease 53 times, total carbon emissions still represent净增长.

Finally, we must追问 the立场 of this academic discussion itself. The two Nature Scientific Reports papers are rigorous. But when an academic paper is大规模 cited by the tech industry as a "green defense," a gap emerges between researchers' intentions and the paper's social effects. When the 130 to 1,500 times figure is传播, the paper's paragraphs about "limitations" and "uncertainty" are systematically忽略.[^2]

The allocation of carbon emission costs has never been a technical problem but a power problem. When tech companies use an academic paper to defend their expansion while refusing to disclose their own models' energy consumption data,[^5] "53 times" ceases to be a scientific discovery and becomes a rhetorical tool.

True emission reduction doesn't lie in using LLMs to替代 human writing, but in追问: do we need this much text? Do we need models this large? Do we need to train a 70-billion-parameter model for 500-word page writing? These questions, the paper didn't answer, tech companies don't want to answer, and we—every person who uses AI—refuse to answer.

---

[^1]: The Verge, "Training a single AI model can emit as much carbon as five cars in their lifetimes," 2019-06-06. https://www.theverge.com/2019/6/6/18655362/ai-climate-change-energy-emissions
[^2]: Bill Tomlinson, Rebecca W. Black, Donald J. Patterson, Andrew W. Torrance, "The carbon emissions of writing and illustrating are lower for AI than for humans," Nature Scientific Reports, 2024. https://www.nature.com/articles/s41598-024-55566-3
[^3]: Shaolei Ren, Bill Tomlinson, Rebecca W. Black, Andrew W. Torrance, "Reconciling the contrasting narratives on the environmental impact of large language models," Nature Scientific Reports, 2024-11-01. https://www.nature.com/articles/s41598-024-76682-6
[^4]: The Guardian, "Revealed: Big tech's new datacentres will take water from the world's driest areas," 2025-04-09. https://www.theguardian.com/technology/2025/apr/09/big-tech-datacentres-water-drought
[^5]: Nature News, "How much energy will AI really consume? The good, the bad and the unknown," 2025-03-05. https://www.nature.com/articles/d41586-025-00582-4
[^6]: UNESCO, "Environmental contradictions of large language models in higher education," 2026-01-06.
[^7]: T Xiao et al., "Environmental impact and net-zero pathways for AI," Nature, 2025.
[^8]: V Mishra et al., "Sustainability in large language model supply chains," Nature, 2025.