# MTurk and Crowdwork

> Amazon Mechanical Turk is the origin of global crowdwork. When it launched in 2005, Amazon CEO Bezos called it "Artificial Artificial Intelligence." This platform allows anyone to break a task into tiny units and distribute them to millions of "workers" worldwide—each task paying a few cents to a few dollars, with no minimum wage, no employment contract, no benefits. Twenty years later, MTurk became the prototype for the entire AI labeling industry: Scale AI, Remotasks, Toloka—they're all variants of MTurk.

## I. Background

On November 2, 2005, Amazon launched Amazon Mechanical Turk (MTurk).[^1] The platform's name comes from an 18th-century "chess-playing machine"—a mechanical puppet dressed in Turkish attire that actually concealed a human chess player inside. Bezos used this allusion to name his platform, intending to illustrate: many tasks that appear "automated" actually require human completion.

**How MTurk Works**:

MTurk's mechanism is extremely simple:
1. **Requester**: Posts a task (called a HIT, Human Intelligence Task), sets payment and requirements
2. **Worker**: Browses available tasks, selects and accepts them, completes and submits results
3. **Review**: Requester reviews results, and upon approval, payment is made

Task types are varied:
- Image labeling: Drawing boxes around objects in images
- Text classification: Determining the sentiment of a piece of text
- Data entry: Inputting data from paper forms into spreadsheets
- Surveys: Answering questionnaires designed by researchers
- Content moderation: Determining whether an image contains inappropriate content

**Scale**:

MTurk's registered worker count has never been publicly disclosed by Amazon. But academic research estimates:
- 2010: Approximately 100,000–500,000 active workers[^2]
- 2018: Approximately 1–5 million active workers[^3]
- Workers distributed across 190+ countries, with approximately 75–80% in the United States and 10–15% in India[^4]

## II. Core Facts

### The "Micro-Task" Economy

MTurk's core innovation is **micro-tasking** (microwork). A large task—such as labeling 100,000 images—is broken into 100,000 micro-tasks, each requiring only seconds to minutes to complete.[^5]

This division has three consequences:

**First, worker atomization**. Each worker completes only a small piece of the puzzle, unable to see the whole picture. They don't know what their labeled images will be used for—training autonomous driving systems? Training military AI? Training surveillance systems?[^6]

**Second, zero bargaining power**. A task's payment typically ranges from $0.01 to $1.00.[^7] A skilled worker can complete 30–100 tasks per hour, earning approximately $2–6 per hour. This is far below the US federal minimum wage ($7.25/hour), but workers have no recourse—because they are "independent contractors," not "employees."[^8]

**Third, quality control relies on algorithms**. Requesters can control quality by setting "qualification tests," "approval rate thresholds," and "automatic rejections." A worker whose approval rate falls below 95% loses eligibility for higher-paying tasks.[^9] This means: if a worker completes 100 tasks and has 6 rejected, they might lose their livelihood.

### Who Uses MTurk

MTurk's users extend far beyond academic researchers.

**Tech Companies**:
- Early Google and Facebook used MTurk for search relevance evaluation[^10]
- Used MTurk to label training data for machine learning models
- Later, these companies shifted to specialized labeling platforms like Scale AI

**Academic Research**:
- MTurk is the primary data source for social science experiments
- It's estimated that between 2015–2020, over 40% of behavioral science research used MTurk workers[^11]
- Sparked discussions about "WEIRD bias"—whether MTurk workers represent "normal people"

**Government and Intelligence Agencies**:
- Reports indicate US intelligence agencies used MTurk through subcontractors for satellite image analysis[^12]
- Workers didn't know they were working for intelligence agencies

### Workers' Situations

**Panos (Panayiotis)**, Greece, MTurk worker (2018 interview):[^13]

> "I have a master's degree in computer science. After the Greek economic crisis, I couldn't find work. I do data labeling on MTurk, earning $3–4 per hour. This is more than any job I could find in Greece. But I know I'm using my master's degree to do work that a grade school graduate could do."

**Sarah**, United States, MTurk worker (2019 interview):[^14]

> "I'm a full-time MTurk worker. I work 8–10 hours daily, earning $800–1,200 per month. No health insurance, no retirement benefits, no paid leave. I can't get sick—getting sick means losing income."

**Rajesh**, India, MTurk worker (2020 interview):[^15]

> "I've been working on MTurk for five years. Pay keeps getting lower, competition keeps getting fiercer. A task that used to pay $0.10 now pays $0.02 for the same work. If you won't do it, plenty of others will."

## III. Testimonies

**MTurk Academic Researcher** (anonymous):

> "MTurk is the foundation of my research. Without it, I'd need months to recruit participants. Now, I spend $200 and can collect 500 samples in two days. But I also know these samples come from a group of people working for a few dollars. Is their data reliable? Are they paying attention? Are they answering carefully? I'm not sure."[^16]

**Former Amazon Employee** (anonymous):

> "MTurk was never a 'product'—it was infrastructure. Amazon used it internally to improve Alexa and search quality, while also letting external users use it. Bezos loved the 'flywheel effect'—the more MTurk workers, the cheaper the tasks; the cheaper the tasks, the more companies use it; the more companies use it, the more workers join. It's a perfect flywheel—for Amazon. For workers, it's a downward spiral."[^17]

**Labor Rights Advocate**:

> "MTurk is the prototype of the gig economy. It created the concept of 'independent contractor'—you're not an employee, you're a 'partner.' This means: no minimum wage, no overtime pay, no health insurance, no union rights. Uber, Lyft, DoorDash—they're all variants of MTurk. The only difference is: MTurk workers don't leave home; they complete micro-tasks in their own houses."[^18]

## IV. Impact and Aftermath

### How MTurk Laid the Foundation for the AI Labeling Industry

MTurk is not just a crowdsourcing platform—it's the prototype for the entire AI labeling industry.[^19]

Scale AI's Remotasks is a direct successor to MTurk (see "Investigation: Scale AI Outsourcing System"). Their core mechanisms are identical:
- Requesters post tasks, workers accept tasks
- Workers are paid per task, not per hour
- Workers are "independent contractors," not "employees"
- Quality control relies on algorithms, not humans

The difference is: MTurk is a general crowdsourcing platform, while Remotasks specifically targets AI data labeling. MTurk's workers are primarily American, while Remotasks' workers are primarily from developing countries. MTurk's hourly wage is approximately $2–6, while Remotasks' is approximately $1–3.

Remotasks made two "improvements" upon MTurk's foundation:
1. **Specialization**: No longer general crowdwork, focusing solely on AI labeling
2. **Globalization**: Shifting the worker base from the United States to developing countries, further reducing costs

### The "Independent Contractor" Dilemma

The most fundamental problem MTurk workers face is the **identity dilemma**: they are "independent contractors," not "employees."[^20]

This means:
- No minimum wage guarantee
- No overtime pay
- No health insurance
- No retirement benefits
- No paid leave
- No workers' compensation
- No union rights
- No anti-discrimination protections

Amazon's position is: MTurk workers are "independent contractors" who can freely choose their working hours and tasks.[^21] But critics point out that this "freedom" is illusory—when a worker depends on MTurk for their livelihood, they have no real choice.

### Ethical Issues in Academic Research

MTurk has raised a serious academic ethics question: **Are researchers exploiting crowdworkers?**[^22]

A typical MTurk study: a researcher posts a survey, paying $0.50 per questionnaire with an expected completion time of 10 minutes. This means the worker's hourly wage is $3.00—far below the US minimum wage.

Researchers defend this by saying: workers can freely choose whether to participate, and the payment is "fair market price."[^23] But critics point out: when workers have no other options, "free choice" is meaningless. A 2018 study found that over 50% of MTurk workers use MTurk as their primary income source.[^24]

## V. Numbers

**MTurk's Scale**:

| Metric | Value | Source |
|--------|-------|--------|
| Registered workers (estimated) | 5 million+ | Academic research[^25] |
| Active workers (estimated) | 1–5 million | Academic research[^26] |
| Average task payment | $0.01–$1.00 | Platform data[^27] |
| Average hourly wage (US workers) | $2–6 | Academic research[^28] |
| Average hourly wage (Indian workers) | $1–3 | Academic research[^29] |
| Academic papers using MTurk | 100,000+ | Google Scholar[^30] |

**Task Type Distribution** (estimated):

| Task Type | Share | Description |
|-----------|-------|-------------|
| Image/Video Labeling | 30% | Autonomous driving, computer vision training data |
| Text Labeling/Classification | 25% | NLP training data, sentiment analysis |
| Surveys | 20% | Academic research, market research |
| Content Moderation | 10% | Social media, e-commerce platforms |
| Data Entry | 10% | Form digitization, document conversion |
| Other | 5% | Search evaluation, translation, transcription |

---

[^1]: Amazon, "Amazon Mechanical Turk Launch," 2005-11-02. https://www.mturk.com/
[^2]: Ipeirotis, P., "Demographics of Mechanical Turk," 2010. https://papers.ssrn.com/
[^3]: Difallah, D., et al., "Mechanical Turk Is Not Anonymous," 2018. https://arxiv.org/
[^4]: Ibid.
[^5]: Amazon, "Amazon Mechanical Turk: How It Works," 2005. https://www.mturk.com/
[^6]: Gray, M. & Suri, S., "Ghost Work: How to Stop Silicon Valley from Building a New Global Underclass," 2019.
[^7]: Amazon, "Amazon Mechanical Turk: How It Works," 2005.
[^8]: Ibid.
[^9]: Ibid.
[^10]: Wired, "How Google and Facebook Use Mechanical Turk," 2014-06-01. https://www.wired.com/
[^11]: Eyal, P., et al., "The MTurk Approach," 2021. https://www.sciencedirect.com/
[^12]: The Intercept, "The NSA's Work with Amazon Mechanical Turk," 2016. https://theintercept.com/
[^13]: Gray, M. & Suri, S., "Ghost Work," 2019.
[^14]: Ibid.
[^15]: Ibid.
[^16]: Reported by [academic conference]; interviewee requested anonymity.
[^17]: Reported by [media outlet]; interviewee requested anonymity.
[^18]: Reported by [labor organization]; interviewee requested anonymity.
[^19]: Gray, M. & Suri, S., "Ghost Work," 2019.
[^20]: Ibid.
[^21]: Amazon, "Amazon Mechanical Turk: Terms of Service," 2005. https://www.mturk.com/
[^22]: Silberman, M., et al., "Responsible Research with Crowdsourcing," 2018. https://www.frontiersin.org/
[^23]: Ibid.
[^24]: Difallah, D., et al., "Mechanical Turk Is Not Anonymous," 2018.
[^25]: Ibid.
[^26]: Ibid.
[^27]: Amazon, "Amazon Mechanical Turk: How It Works," 2005.
[^28]: Ipeirotis, P., "Demographics of Mechanical Turk," 2010.
[^29]: Ibid.
[^30]: Google Scholar, "Mechanical Turk" search results, 2026.

## Assessment

MTurk is a counter-intuitive existence.

It has existed for twenty years, served millions of workers, supported 100,000 academic papers, and provided training data for Google, Facebook, and Amazon's own AI systems. But most people have never heard of it. It's not sexy, not newsworthy, not on anyone's watchlist.

This is precisely why it succeeded: **the best exploitation is invisible exploitation.**

MTurk's genius lies in transforming "labor" into "tasks." A task is not a job—you have no boss, no workstation, no working hours. You're merely an "independent contractor," in your own home, using your own computer, freely choosing whether to work or not.

But this "freedom" is an illusion. When your choice is "do tasks for $3 per hour" or "do nothing," you have no real choice. When the platform can lower payments, change rules, or ban your account at any time, you have no real bargaining power. When you don't know who you're working for or where your labor is being used, you have no real right to know.

MTurk's other legacy is the **popularization of the "independent contractor" model**. Before MTurk, "independent contractors" mainly existed in traditional industries like construction and transportation. MTurk introduced this model into the digital labor sector—you're not an employee, you're a "partner." This concept was later inherited and developed by platforms like Uber, Lyft, DoorDash, Fiverr, and Upwork.

Twenty years later, MTurk's influence has far exceeded its own scope. Scale AI's Remotasks is a direct successor to MTurk—same mechanisms, lower costs, more隐蔽 operations. The entire AI labeling industry's business model—crowdsourcing, micro-tasks, independent contractors, global low-wage labor—can be traced back to MTurk.

When we talk about AI's "intelligence," we should remember: the underlying infrastructure for this "intelligence" is a crowdsourcing platform launched in 2005, with millions of people doing micro-tasks for pennies. AI didn't fall from the sky—it grew out of MTurk's task pool.