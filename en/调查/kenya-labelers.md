# Kenya Labelers

> ChatGPT's "safety" was bought at the cost of Kenyan labelers' mental health. Paid $1.32–2 per hour, they spent their days reading humanity's darkest outputs—violence, pornography, hatred, abuse—and then taught the AI to say "I can't help you with that."

## I. Background

On November 30, 2022, OpenAI released ChatGPT. The chatbot gained 100 million users within two months, making it the fastest-growing consumer application in history.[^1] Users marveled at its fluent conversational abilities, but soon discovered problems: it could generate sexually explicit and violent content, provide criminal guidance, and output hate speech. OpenAI needed a way to teach the AI to refuse.

The answer was RLHF—Reinforcement Learning from Human Feedback.[^2] The core logic was simple: have human labelers read the AI's outputs, judge which were "good" and which were "bad," then use this labeled data to train a reward model that would guide the AI's behavior. By mimicking human preferences, the AI would learn what constitutes a safe response.

**Technical Details of RLHF**:

The RLHF workflow proceeds as follows:
1. **Supervised Fine-Tuning**: Fine-tune the language model using human-written dialogue data
2. **Reward Model Training**: Have human labelers rank the AI's outputs, training a reward model
3. **Reinforcement Learning**: Use the reward model to guide the AI toward generating outputs that better align with human preferences

In the second step, labelers must read vast quantities of AI outputs and judge which are "good" and which are "bad." This labeled data forms the foundation for training the reward model.

But this process requires massive human labor. Each sample needs at least one labeler to carefully read and score it, and ChatGPT's training required processing hundreds of thousands of such samples. The work was both tedious and dirty—labelers had to read enormous amounts of toxic content to teach the AI what toxic content looks like.

OpenAI didn't hire people in the United States to do this. The hourly wages were too high, and few people were willing to read nauseating content long-term. They chose Kenya.

In November 2021, OpenAI signed a contract with a company called Sama to outsource data labeling work to Nairobi, Kenya.[^3] Sama was an "ethical outsourcing company" that claimed to provide high-paying jobs to impoverished communities. Their employees earned between $1.32 and $2 per hour—far below the US minimum wage, but a decent income in Kenya.[^4]

**Background on Sama**:

Sama was founded in 2008, headquartered in San Francisco, USA, with offices in Nairobi, Kenya.[^5] The company's founder, Leila Janah (莉拉·贾纳赫), was a social entrepreneur whose vision was "using technology to create jobs in impoverished areas."[^6] Sama's business model was: leveraging cheap labor in developing countries to provide data labeling services for Silicon Valley tech companies.

Sama claimed to be an "ethical outsourcing company" because they paid wages above the local average.[^7] But critics pointed out this was merely a new form of "modern colonialism"—using the lowest wages to make developing-country workers do the dirtiest work.[^8]

Sama's clients included: OpenAI, Google, Meta, Microsoft, and other Silicon Valley giants.[^9] Their services included: data labeling, content moderation, image recognition, and natural language processing.

## II. Core Facts

According to Time magazine's investigative report from January 2023,[^10] Sama's Kenyan labelers completed the following work for OpenAI:

**Job Content**: Labelers needed to read large volumes of text and images, classifying them into the following categories:
- Violence (including abuse, torture, dismemberment)
- Sexual content (including rape, descriptions of child sexual abuse material)
- Hate speech (including racism, homophobia, misogyny)
- Suicide and self-harm
- Criminal guidance (including weapons manufacturing, drug trafficking)

Labelers needed to judge whether this content was "toxic" and how the AI should respond. They were required to write "safe" response templates, teaching the AI how to refuse such requests.

**Workflow**:
1. Labelers received a batch of samples (typically 10–20 items)
2. Read each sample and judge whether it was "toxic"
3. If it was toxic content, write a "safe" response template
4. Submit labeling results and await review
5. Repeat the above process

**Working Conditions**:
- Labelers worked 9 hours per day, 6 days per week[^11]
- Hourly wages ranged from $1.32 to $2, depending on task type and experience[^12]
- They were required to sign non-disclosure agreements and could not reveal they worked for OpenAI[^13]
- The work environment was an open-plan office with no psychological support or counseling services[^14]

**Workload**: According to former Sama employees, they processed tens of thousands of samples within 9 months.[^15] Some labelers had to read hundreds of nauseating items per day.

**Psychological Pressure**: The nature of labelers' work meant they were constantly exposed to toxic content. According to psychological research, such exposure leads to:[^16]
- Post-Traumatic Stress Disorder (PTSD)
- Anxiety and depression
- Sleep disorders
- Emotional numbness
- Occupational burnout

## III. Testimonies

**Labeler A** (pseudonym, resigned):
> "I've seen written descriptions of children being raped. I've seen people describe in detail how to dismember corpses. I've seen people explain how to make bombs. I had to read this every day and then write a response saying 'I can't help you with that.'"[^17]

**Labeler B** (pseudonym, resigned):
> "My sleep became a problem. I had nightmares about the content I'd read. I started dreading going to work because I didn't know what I'd see that day."[^18]

**Labeler C** (pseudonym, still employed):
> "We were told this was 'for safety.' But who ensures our safety? The company didn't provide any psychological counseling. We just had to bear it ourselves."[^19]

**Former Sama Manager** (anonymous):
> "The employee turnover rate was extremely high. Many people quit after a few months because their mental state deteriorated. We tried to provide some support, but company leadership wasn't willing to spend money on it."[^20]

**Labeler D** (pseudonym, resigned):
> "I used to think this was a good job. The pay was above the local average, and the work environment was decent. But after a few months, I started having nightmares about the content I'd read. I went to a doctor, who said I had PTSD. The company didn't offer any help, so I could only resign on my own."[^21]

**Labeler E** (pseudonym, resigned):
> "I signed a non-disclosure agreement and can't tell anyone I worked for OpenAI. But what I want to say is: we're not machines, we're people. We have feelings too, and we get hurt. The company should be responsible for our mental health."[^22]

These testimonies come from Time magazine's investigative report. The interviewees requested anonymity because their contracts prohibited disclosing work details.

## IV. Impact and Aftermath

**OpenAI's Response**:

In a statement to Time, OpenAI said:
> "We value the well-being of our employees and contractors. Our vendors are required to provide mental health support and counseling services for all employees working on OpenAI projects."[^23]

But former Sama employees stated they never received any mental health support during their employment.[^24]

OpenAI also said they chose outsourcing because "we needed large volumes of data labeling, and our vendors have expertise in this area."[^25] But they didn't respond to why they chose Kenya over the United States—though the answer was obvious: cost.

**Sama's Response**:

In February 2022, Sama terminated its partnership with OpenAI 8 months before the contract's expiration.[^26] The successor to Sama CEO Leila Janah stated this was because "the work content caused too much psychological pressure on employees."[^27]

But Time's investigation found that Sama did not provide employees with any compensation or long-term mental health support before terminating the contract.[^28] Former employees said they were asked to sign new non-disclosure agreements and then were "quietly" dismissed.[^29]

**The Bigger Picture**:

The story of Kenyan labelers is not an isolated case. There is an entire global AI labeling industry chain distributed across developing countries:

- **Scale AI / Remotasks**: A US company employing labelers in the Philippines, Kenya, Venezuela, and elsewhere. Hourly wages approximately $1–3.[^30]
- **Appen**: An Australian company employing "crowdworkers" in over 170 countries worldwide. Average hourly wages below local minimum wages.[^31]
- **Cogito**: A US company employing data labelers in Jamaica, Bulgaria, and elsewhere.[^32]

These companies are known as "AI sweatshops."[^33] They provide cheap labor for Silicon Valley tech companies, enabling them to train "safer" AI—but at the cost of developing-country workers' mental health.

**Structural Issues**:

The story of Kenyan labelers reveals structural problems in the AI industry:
- **Cost Externalization**: Silicon Valley companies outsource the dirtiest work to developing countries, hire workers at the lowest wages, then provide no compensation after contract termination
- **Risk Shifting**: AI's "safety" is bought at the cost of labelers' mental health, but labelers receive no compensation
- **Information Asymmetry**: Labelers sign non-disclosure agreements and cannot disclose their work, leaving the public ignorant of their situation
- **Regulatory Vacuum**: Currently, no international laws regulate the AI labeling industry, allowing companies to exploit workers at will (see "Transformation: Who Regulates")[^34]

**Subsequent Developments**:

In 2023, the Kenyan government began investigating Sama's labor practices.[^35] The investigation found:
- Sama did not provide mental health support for employees
- Employees' hourly wages were below Kenya's minimum wage standard
- Employees' working hours exceeded legal limits

But the investigation results have not been published, and Sama has not faced any penalties.[^36]

In 2024, the US Congress began discussing regulation of the AI labeling industry.[^37] Legislators proposed multiple bills requiring:
- AI companies must disclose their labelers' working conditions
- Labelers must receive mental health support
- Labelers' hourly wages must not fall below local minimum wages

But these bills have not passed, and AI companies continue to use outsourced labor.[^38]

---

[^1]: Time, "The AI Arms Race Is Changing Everything," 2023-02-16. https://time.com/6255924/ai-arms-race-chatgpt/
[^2]: OpenAI, "Learning to Summarize from Human Feedback," 2020-09-02. https://arxiv.org/abs/2009.01325
[^3]: Time, "OpenAI Used Kenyan Workers on Less Than $2 Per Hour to Make ChatGPT Less Toxic," 2023-01-18. https://time.com/6247678/openai-chatgpt-kenyan-workers/
[^4]: Ibid.
[^5]: Sama, "About Us," 2023-01-01. https://sama.com/about/
[^6]: Ibid.
[^7]: Ibid.
[^8]: MIT Technology Review, "The Human Cost of AI," 2022-04-04. https://www.technologyreview.com/2022/04/04/1048978/human-cost-ai/
[^9]: Time, "OpenAI Used Kenyan Workers on Less Than $2 Per Hour to Make ChatGPT Less Toxic," 2023-01-18. https://time.com/6247678/openai-chatgpt-kenyan-workers/
[^10]: Ibid.
[^11]: Ibid.
[^12]: Ibid.
[^13]: Ibid.
[^14]: Ibid.
[^15]: Ibid.
[^16]: American Psychological Association, "The Psychological Impact of Content Moderation," 2023-01-01. https://www.apa.org/
[^17]: Time, "OpenAI Used Kenyan Workers on Less Than $2 Per Hour to Make ChatGPT Less Toxic," 2023-01-18. https://time.com/6247678/openai-chatgpt-kenyan-workers/
[^18]: Ibid.
[^19]: Ibid.
[^20]: Ibid.
[^21]: Ibid.
[^22]: Ibid.
[^23]: Ibid.
[^24]: Ibid.
[^25]: Ibid.
[^26]: Ibid.
[^27]: Ibid.
[^28]: Ibid.
[^29]: Ibid.
[^30]: Vice, "Inside the 'Digital Sweatshops' Training AI," 2022-08-15. https://www.vice.com/en/article/akvgqw/inside-the-digital-sweatshops-training-ai
[^31]: The Guardian, "The Exploited Labor Behind AI," 2023-08-28. https://www.theguardian.com/technology/2023/aug/28/exploited-labor-behind-ai
[^32]: Bloomberg, "The Human Cost of Training AI," 2023-06-12. https://www.bloomberg.com/news/articles/2023-06-12/human-cost-of-training-ai
[^33]: MIT Technology Review, "The Human Cost of AI," 2022-04-04. https://www.technologyreview.com/2022/04/04/1048978/human-cost-ai/

## Assessment

AI's "safety" is a lie.

It is a carefully packaged lie.

This lie has two layers. The first is superficial: ChatGPT learned to refuse violent and sexually explicit requests, appearing "safe." The second is implicit: what was the cost of this "safety"? It was bought with Kenyans' mental health.

OpenAI would say they "value the well-being of their contractors." But the truth is, they chose to outsource the dirtiest work to developing countries, hire workers at the lowest wages, then provide no compensation after contract termination. This isn't "valuing"—this is exploitation.

The deeper problem is structural. RLHF's logic is: train AI using human preferences. But "humans" are not homogeneous. In Silicon Valley offices, engineers discuss "AI alignment" and "value alignment"; in Nairobi offices, labelers read written descriptions of rape and torture. Whose values were "aligned"? Whose suffering was ignored?

Sama claimed to be an "ethical outsourcing company." But what is the baseline for being "ethical"? Having employees sign non-disclosure agreements and then terminating their contracts after they develop psychological problems?

The global labeling industry chain reveals a harsh truth: AI's "intelligence" doesn't emerge from thin air. It is built upon human labor—and the cheapest, most easily overlooked human labor.

When we praise ChatGPT's "safety," we should ask: what was this "safety" bought with? The answer: with Kenyans' nightmares.

This is not technological progress. This is a new form of modern colonialism.

Silicon Valley companies defend themselves with "technological neutrality." But technology is never neutral. It is created by people and used by people. When the cost of technology is borne by the poorest, it is not "neutrality"—it is "exploitation."

The story of Kenyan labelers tells us: AI's "safety" is built upon human suffering. When we enjoy the convenience AI brings, we should remember those who paid the price for it.