# Essay · The Hypocrisy of AI Ethics: Selective Morality and the Excluded Workers

> In 2018, Google published its "AI Principles"—seven guidelines, promising to "responsibly develop AI." That same year, OpenAI was founded with the mission of "ensuring AGI benefits all of humanity." In 2023, Anthropic launched "Constitutional AI," claiming to embed safety into model design. Three companies, three ethics frameworks, three resounding promises. But if you dissect these frameworks clause by clause, you will find a meticulous absence: they discuss safety, bias, privacy, existential risk—but they do not discuss annotators' hourly wages, outsourced workers' psychological trauma, displaced workers' unemployment, or the human cost throughout the entire supply chain. **The mainstream AI ethics frameworks are not "incomplete"—they have been meticulously designed to be "incomplete."** The excluded portions happen to be the most costly portions.

---

## I. The Mainstream AI Ethics Frameworks: What They Say

Before discussing the hypocrisy of AI ethics, let us honestly examine what these frameworks say.

**Google AI Principles (2018).** Seven guidelines: socially beneficial, avoid bias, built for safety, accountable to people, incorporate privacy design, uphold high standards of scientific excellence, and be made available for uses that accord with these principles.[^1] Six of the seven focus on model outputs—AI should not produce bias, should not violate privacy, should be safe and reliable. Only one ("accountable to people") mentions "people"—but it refers to users and the public affected by AI, not the workers who produce AI.

**OpenAI's mission statement.** "Ensuring artificial general intelligence (AGI) benefits all of humanity." From its founding in 2015 to its pivot toward for-profit in 2023, OpenAI's public narrative has consistently revolved around two themes: AGI's potential and safety's challenge.[^2] "Safety" is defined as "AI should not destroy humanity"—this is an extreme, long-term, probabilistic risk. Yet "annotators' PTSD" is a specific, immediate, certain risk—but it is not included in OpenAI's definition of safety.

**Anthropic's Constitutional AI (2022).** Anthropic was founded by former OpenAI executives with "safety" as its core selling point. Constitutional AI's design philosophy is: using a set of principles (a "constitution") to guide AI behavior, enabling AI to self-criticize and self-correct, reducing reliance on manual annotation.[^3] These principles cover "harmlessness," "honesty," "helpfulness"—but they focus on AI's behavior toward users, not the impact of AI's production process on workers. An interesting detail: Constitutional AI is promoted as having "reduced the need for manual annotation"—presented as ethical progress. But its implicit message is: annotators are not subjects to be "protected" but objects to be "eliminated."

**EU AI Act (2024).** As the world's first comprehensive AI regulatory framework, the EU AI Act classifies AI systems by risk level—from "unacceptable risk" (such as social credit scoring) to "high risk" (such as medical diagnostics, recruitment screening) to "limited risk" (such as chatbots).[^4] The Act requires high-risk AI systems to undergo transparency assessments, data quality assessments, and human oversight. But the subject of assessment is model output—not model training. A "safe" model trained by low-paid annotators' traumatic labor can be fully compliant under the EU AI Act—because the Act does not examine the labor conditions of the training process.

These frameworks share a common structure: **they define "ethics" as an output attribute of AI—fairness, safety, transparency—rather than a labor attribute of AI's production process.** This is like inspecting a shirt's "quality" (whether durable, whether attractive) without inspecting whether the factory that produced it used child labor. The quality inspection is real, but it sidesteps the more fundamental question.

---

## II. The Selectivity of Frameworks: What They Do Not Say

What AI ethics frameworks do not say speaks louder than what they do say.

**They do not discuss annotators.** Google's AI Principles are over 2,000 words; the words "annotator," "data annotation," and "outsourced labor" appear zero times. OpenAI's technical papers list the names of hundreds of researchers—annotators' names are not among them. Anthropic's Constitutional AI paper discusses in detail how to use AI to replace manual annotation—but does not discuss what replaced annotators should receive.[^3]

This is not an oversight. In any AI ethics framework drafting process, someone would ask: "Do we need to mention supply chain labor conditions?" Every time, the answer is "no." The logic of this judgment is clear: if annotators are included in the ethics framework, labor conditions must be disclosed; if labor conditions are disclosed, low wages and high harm will be exposed; if low wages and high harm are exposed, public questioning and regulatory pressure will follow. **Not discussing annotators is not an omission—it is risk management.**

**They do not discuss outsourcing structures.** AI companies universally hire annotators through third-party outsourcing companies—Sama, Scale AI, Appen, Toloka. The function of this outsourcing structure is not merely "reducing costs" (though it does reduce costs) but "transferring responsibility." When TIME exposed OpenAI's annotation conditions in Kenya, OpenAI's response was: the annotation work was managed by Sama; we were merely the client.[^5] This response is technically accurate—and morally evasive. **Outsourcing is the institutionalized tool of responsibility transfer—it places two or three layers of intermediaries between the beneficiary (AI company) and the cost-bearer (annotator), ensuring that "responsibility" evaporates in the chain.**

**They do not discuss displaced workers.** When Klarna replaced 700 customer service representatives with AI, no AI ethics framework commented. When IBM announced AI would replace 7,800 positions, no AI ethics committee conducted an assessment. When Artisan put up its "Stop Hiring Humans" advertisement, no AI ethics organization issued a condemnation.[^6] The "stakeholder" lists of AI ethics frameworks typically include: users, society, the environment, future generations—but not displaced workers. As if AI's impact only occurs in the instant of "model output," and not in every day after "enterprise deployment."

**They do not discuss profit distribution.** AI companies' ethics reports do not include the following information: What are annotators' hourly wages? What are outsourcing companies' profit margins? What percentage of total R&D costs does the AI company spend on annotation? What is the unemployment rate of displaced workers?—the absence of this information is not because of "trade secrets" (though companies will use this as a reason to refuse disclosure), but because disclosing them would destroy the credibility of the ethics narrative. **If Google's AI Principles were accompanied by an annotator hourly wage table, the phrase "responsible AI" would seem rather irresponsible.**

This selectivity reveals the true function of AI ethics frameworks: **they are not meant to constrain AI companies' behavior—they are meant to manage AI companies' image.** AI ethics frameworks are public relations tools, not governance tools. Their goal is not "to make AI more ethical" but "to make the public believe AI is ethical." The difference is: the former requires changing behavior, the latter only requires changing the narrative.

---

## III. The Rhetoric of "Responsible AI": Divert, Delay, Defend

"Responsible AI" is this industry's core rhetoric. Let us disassemble it.

**Diverting attention.** When the public begins to worry about AI's impact, AI companies' response is to publish ethics frameworks, establish ethics committees, and fund ethics research. The function of these actions is to divert public attention from "concrete harm" to "abstract principles." What the public wants to ask is: "Why are you paying annotators $1.32/hour?" The company's answer is: "We are committed to building responsible AI." The question is displaced—from "what did you do" to "what did you say."

A textbook case: after TIME's 2023 report on OpenAI's Kenyan annotation scandal, OpenAI's public response was not to disclose annotator wages, improve labor conditions, or establish supply chain auditing—but to publish a blog post about "AI safety," emphasizing their commitment to safety.[^7] Safety—not annotators' safety, but model safety. **The scandal was about workers; the response was about technology. The subject was replaced.**

**Delaying regulation.** The core message of the "responsible AI" narrative is: "We are self-regulating, so external regulation is unnecessary." The effect of this message on policymakers is: slowing the pace of regulation. If AI companies "are already doing the right thing," legislators feel less urgency. The timing of Google's AI Principles (2018) coincided precisely with GDPR coming into force and global discussions about AI regulation beginning—this is not a coincidence. **Ethics frameworks are buffers against regulatory pressure—they signal to policymakers: "We have the capacity for self-discipline; we do not need laws to constrain us."**

The historical analogy is the tobacco industry's "responsible smoking" campaigns. When regulatory pressure increased, tobacco companies did not accept regulation—they launched "self-discipline" campaigns, promising "responsible marketing" and funding "smoking and health" research. The function of these activities was to delay actual regulatory legislation—giving the industry additional decades of profit windows.[^8] The AI industry's "responsible AI" movement is structurally isomorphic: trading self-discipline promises for regulatory delay, using ethical discourse to defend profit margins.

**Defending profits.** The implicit premise of "responsible AI" is: AI development is inevitable and broadly beneficial—the question is merely "how to develop responsibly." This premise accepts AI industry profit structures as given facts and does not ask "how should profits be distributed." It restricts ethical discussions to the scope of "how technology can be made safer," excluding the inquiry into "how economic relationships can be made more just."

The effect of this rhetorical strategy is clearly visible in financial data. In 2023, OpenAI's investment in "AI safety" research (including the superalignment team's budget) was approximately 20% of total R&D spending—this percentage is frequently cited to demonstrate the company's commitment to safety.[^7] But during the same period, OpenAI's total spending on outsourced annotation was never publicly disclosed. Safety research has a budget, reputation, and papers; annotation labor has—$1.32/hour. **"Responsible" budgets flow to Silicon Valley researchers; "unmentioned" budgets flow to Kenyan annotators.** The distribution of ethics investments is itself a mapping of ethical choices: who is invested in is who is valued.

A more subtle rhetorical operation is the substitution of "long-term risk" for "present harm." AI companies devote enormous attention and resources to "existential risk"—whether AI will destroy humanity. OpenAI's superalignment team, Anthropic's long-term benefit committee, DeepMind's safety research—all focus on "when AGI arrives, how to ensure it doesn't destroy humanity." This topic is real—but its rhetorical effect is: **shifting public anxiety from "harm happening now" to "possible catastrophe in the future."** Annotators' PTSD is present, certain, and quantifiable; AGI destroying humanity is future, hypothetical, and unquantifiable. By placing the center of ethical discussion on the latter, AI companies have successfully decoupled "safety" from "labor."

The result: AI companies can simultaneously claim "responsible" and "profit-maximizing"—because "responsible" has been tailored to precisely not affect profits. You can publish an ethics framework (cost: a PR team's time); you don't need to raise annotators' wages (cost: tens of millions of dollars). You can fund AI ethics research (cost: a few million in donations); you don't need to build a transition fund for displaced workers (cost: possibly billions). **The "cost" of ethics is controlled within the PR budget—this is the precise meaning of "responsible."**

---

## IV. The Performativity of Ethics Committees: Who Is In, Who Is Out

AI companies' ethics committees are the institutionalized expression of the "responsible AI" narrative. Let us examine their composition.

**Google Advanced Technology External Council (ATEAC).** Established in 2019, dissolved within weeks—because employees protested the inclusion of Heritage Foundation's Kay Coles James (a conservative figure with anti-LGBTQ stances) on the committee.[^9] The dissolution was presented as "Google listened to employees' voices"—but it also exposed another problem: the committee's formation was itself a political decision, not an ethical one. Who was invited onto the committee represented which voices Google considered "worth hearing."

**OpenAI's Safety Committee.** In 2024, OpenAI established a Safety and Security Committee—its members included CEO Sam Altman and other company executives.[^10] The absurdity of this arrangement is: the people responsible for overseeing safety are simultaneously the people responsible for profit maximization. Having the CEO supervise whether his own company is "safe" is like having a chef evaluate whether his own food is delicious. Of course it's delicious—the evaluation criteria are his own.

**Anthropic's Long-Term Benefit Trust.** Anthropic established an independent committee to oversee whether the company fulfills its mission of "benefiting humanity."[^11] This is the arrangement closest to "independent oversight" in the current AI industry—but the committee's focus is on "long-term existential risk" (whether AGI will destroy humanity), not "present labor conditions" (whether annotators are being harmed). **Long-term, hypothetical risks are placed under ethical oversight; present, certain harms are excluded from oversight.**

The common feature of these committees is: **their agendas are set by the company, members are chosen by the company, and boundaries of authority are defined by the company.** Committees do not audit supply chain labor conditions, do not assess the social impact of layoffs, and do not track annotators' mental health data. What they examine is: whether model outputs are biased, whether they could be misused, whether they comply with regulatory requirements—these are all "product safety" issues, not "labor justice" issues.

The true function of ethics committees is "legitimacy production." Their existence proves that "the company cares about ethics"—what they actually do is less important. A company without an ethics committee is "irresponsible"; a company with an ethics committee that doesn't examine labor conditions is "responsible." **The name itself does the work of legitimacy—content is secondary.**

More noteworthy is who is not on the committee. Annotators are not there. Displaced workers are not there. Labor rights advocates from the Global South are not there. Representatives of platform worker unions are not there. **The composition of ethics committees is the answer to the question "who is permitted to define ethics"—and the answer is: Silicon Valley elites, university professors, former government officials.** They have research on bias, papers on safety, frameworks on privacy—but they have no experience of reading harmful texts for eight hours a day. This is not to say they are not smart enough—it is to say that their experiential structure determines that they cannot see certain problems.

---

## V. What True Ethics Should Look Like: Labor Justice, Global Justice, Intergenerational Justice

If existing AI ethics frameworks are selective and performative—what should a non-hypocritical AI ethics include?

**First, labor justice.** The ethical audit of AI systems should not stop at model output—it should extend to the entire production process. Specifically:

- **Supply chain transparency**: When AI companies publish models, they should—like listed companies disclosing their supply chains—disclose the labor conditions of their training data annotation: annotator wage ranges, working hours, mental health support, outsourcing company selection criteria. This is not a trade secret—this is workers' basic information.
- **Compensation principles for hazardous work**: Workers annotating harmful content should receive compensation commensurate with their degree of psychological trauma—not the minimum wage determined by market supply and demand, but fair compensation based on risk assessment. Just as miners receive hazard pay, workers annotating harmful content should receive a "psychological risk premium."
- **Transition responsibility for displaced workers**: Every time a company uses AI to replace a position, it should bear that position's worker's transition costs—retraining, severance compensation, social security linkage. "Efficiency" gains should not be enjoyed exclusively by companies; "efficiency" costs should not be borne exclusively by workers.

**Second, global justice.** The profit-risk inversion in the AI supply chain is not only a labor problem—it is the digitized form of global inequality. AI companies in core nations set standards and take profits; annotators in peripheral nations execute standards and bear risks. A truly responsible AI ethics framework should ask:

- Is annotator compensation based on a local decent standard of living as a floor, rather than local minimum wage as a ceiling?
- Are annotation skills transferable—are annotators accumulating monetizable capabilities, or consuming irrecoverable time?
- Are AI companies using labor cost differentials in the Global South to systematically circumvent labor protections—is this essentially "regulatory arbitrage"?

**Third, intergenerational justice.** The impact of AI replacing labor is not one-time—it will alter the career prospects of the next generation. When junior programmers are replaced by Copilot, what is lost is not just current positions—what is lost is the growth pathway for future senior engineers. When freelance translators are replaced by DeepL, what is lost is not just current income—what is lost is the possibility for the next generation to become professional translators. A truly responsible AI ethics framework should assess: **is AI deployment creating a "talent gap"—denying the next generation the opportunity to acquire skills and experience?**

**A non-hypocritical ethics framework must also ask a deeper question: who has the right to define "ethics"?**

In the current landscape, the power to define "AI ethics" is concentrated in three groups: AI companies (defining their own ethical standards), academia (producing ethics research and frameworks), and governments (formulating regulations). These three groups share a common feature: none of them include direct victims. Annotators do not write papers, do not attend hearings, and do not formulate company policies. Displaced customer service representatives do not participate in ISO standard-setting. Freelance translators are not listed as stakeholders in AI Act deliberations. **The people who define "ethics" and the people who bear the consequences of "unethical behavior" are entirely different groups—this separation is the institutional root of AI ethics' hypocrisy.**

Analogies to other industries are instructive. In food safety, the definition of "ethics" includes consumer health—because consumers have the right to choose. In construction safety, the definition of "ethics" includes workers' hard hats—because workers have the right to refuse unsafe working environments. In the pharmaceutical industry, the definition of "ethics" includes clinical trial subjects' informed consent—because those being tested have the right to know the risks. **In all these fields, ethics frameworks cover "those who pay the price for the product"—because society acknowledges that those who pay the price have the right to participate in defining the reasonableness of that price.** AI ethics frameworks uniquely exclude "those who pay the price for AI"—annotators, displaced workers, users who contribute data without compensation. This is not because the AI industry is "special"—but because the AI industry's power structure makes the absence of cost-bearers possible.

These three dimensions—labor justice, global justice, intergenerational justice—share a common point: they all ask about "cost." Who is paying the price for AI? Is the price fair? Is the price reversible? And existing AI ethics frameworks precisely avoid these three questions—because answering them requires confronting the inequality of profit distribution, which is the topic AI companies are least willing to touch.

An AI ethics framework that truly includes these three dimensions will not be born in Silicon Valley meeting rooms—because what it demands is a fundamental challenge to existing profit structures. It requires workers' voices (annotators, the displaced), perspectives from the Global South (Kenya, the Philippines, India), and intergenerational considerations (the rights of future workers). **And these voices and perspectives are, in current AI ethics discussions, precisely the ones that are absent.** Absence is not coincidence—absence is the product of power structures.

The EU AI Act may be the closest attempt to a "comprehensive ethics framework"—but it also reveals the failure of global justice. European legislators defined AI ethics standards, but the targets of these standards are primarily companies operating in Europe; the Global South nations where annotators are located participated neither in standard-setting nor have the capacity to enforce these standards.[^4] The globalization of ethics remains empty rhetoric—it is set in the Global North and absent in the Global South.

---

## Assessment

This diviner projects three rounds.

**First round: the factual level.** AI companies' ethics frameworks are real documents—Google has seven principles, OpenAI has a mission statement, Anthropic has Constitutional AI, the EU has an AI Act. These documents do exist, and their commitments do have binding force (at least at the legal level). But they share one precise absence: **labor.** Annotators, outsourced workers, displaced workers—none fall within the coverage of any ethics framework. This is not because there "wasn't time to write it in"—AI ethics discussions began in 2016; a decade is enough to write much. It is because including it would destroy the narrative's internal consistency.

**Second round: the mechanism level.** The function of AI ethics frameworks is not "constraining behavior"—but "managing image." They use the "responsible AI" rhetoric to accomplish a threefold operation: diverting attention (from workers to technology), delaying regulation (self-discipline preferred over external regulation), and defending profits (ethics costs controlled within the PR budget). Ethics committees are the institutionalized expression of this rhetoric—agendas set by the company, members chosen by the company, labor issues systematically excluded. This mechanism is not an AI industry invention—the tobacco industry, oil industry, and pharmaceutical industry have all used the same strategy: trading self-discipline promises for regulatory delay, using ethical discourse to defend profit margins.

**Third round: the hypocrisy level.** This is the core argument of this essay—and the reason the word "hypocrisy" is not rhetorical exaggeration.

Hypocrisy is not "saying the wrong thing"—hypocrisy is "saying one thing and doing another." AI companies say "responsible" but do not audit supply chain labor conditions. AI companies say "benefiting humanity" but annotators' PTSD is not included in the definition of "humanity." AI companies say "safety" but "safety" refers only to model output safety, not production process safety. AI companies say "fairness" but "fairness" refers only to algorithmic result fairness, not profit distribution fairness. **Every ethical keyword has been precisely trimmed—the trimming technique is: keep the parts that do not affect profits, remove the parts that do.**

This is not conspiracy theory—this is the inevitable product of the incentive structure. AI companies are profit-maximizing entities—ethics frameworks are tools for finding balance between "profit maximization" and "social legitimacy." When the two conflict, profits come first. This is not because company managers are bad people—but because their duty is to maximize shareholder returns within the existing institutional framework. The system allows them to not discuss annotators—so they don't. The system requires them to discuss safety—so they do. **Hypocrisy is not an individual moral defect—it is the product of institutional incentives.**

But "institutional" does not mean "inevitable." Institutions are designed by people—they can be redesigned. AI ethics frameworks were designed to exclude labor issues—they can also be designed to include them. The question is not "can they" but "who has the power."

The current power distribution is: AI companies define ethics frameworks, governments adopt (or don't adopt) the frameworks defined by companies, and the public expresses scattered dissatisfaction outside the framework. In this power structure, workers—annotators, displaced customer service representatives, squeezed freelance translators—are not at any table. They are not in Google's meeting rooms, not at EU hearings, not on academic journal editorial boards. **Their absence is not accidental—it is the precondition for AI ethics being designed as hypocritical.** If annotators sat at the table, "responsible AI" could not avoid discussing wages.

So, "the hypocrisy of AI ethics" is not an accusation about individuals—it is a structural diagnosis. The structure enables ethics frameworks to systematically exclude the most central ethical questions while maintaining a "responsible" public image. This structure is not unchangeable—but the first step in changing it is naming it.

This diviner hereby names it: **the hypocrisy of AI ethics lies not in what it says—but in what it meticulously chooses not to say.**

---

*This essay was compiled by the LLM Labor theoretical framework: Fu Xuan (Head of Theoretical Framework).*

---

[^1]: Google, "AI at Google: Our Principles", 2018-06-07. https://ai.google/responsibility/principles/ 七条准则：社会有益、避免偏见、为安全而设计、对人负责、隐私设计、科学卓越、按原则使用。
[^2]: OpenAI, "Our Mission", 2015（2023年修订）。"Our mission is to ensure that artificial general intelligence—AI systems that are generally smarter than humans—benefits all of humanity." 2023年从非营利转向"capped-profit"结构，2024年进一步讨论转为完全营利性公司。
[^3]: Bai, Yuntao, et al., "Constitutional AI: Harmlessness from AI Feedback", arXiv:2212.08073, 2022-12. 提出用"宪法"原则指导 AI 自我批评，减少对人工标注的依赖。
[^4]: European Parliament, "Regulation (EU) 2024/1689 — Artificial Intelligence Act", 2024-06-13. https://eur-lex.europa.eu/eli/reg/2024/1689/oj 按风险等级分类监管 AI 系统。
[^5]: Perrigo, Billy, "OpenAI Used Kenyan Workers on Less Than $2 Per Hour to Make ChatGPT Less Toxic", TIME, 2023-01-18. https://time.com/6247678/openai-chatgpt-kenya-workers/ OpenAI 对标注条件的回应主要强调其通过合法外包渠道操作。
[^6]: Klarna AI 客服替代（2024）；IBM CEO 声明 AI 替代岗位（2023）；Artisan "Stop Hiring Humans" 广告（2024）。详见《论·劳动正义》脚注 [^9]-[^12]。
[^7]: OpenAI, "How we think about safety and alignment", 2023-04-05. https://openai.com/index/how-we-think-about-safety-and-alignment/ 在 TIME 标注丑闻后发布的安全博客文章。
[^8]: Brandt, Allan M., *The Cigarette Century: The Rise, Fall, and Deadly Persistence of the Product That Defined America*, Basic Books, 2007. 详细记录了烟草业如何通过"自律"运动推迟监管立法。
[^9]: Wakabayashi, Daisuke, "Google Cancels A.I. Ethics Board After Backlash", *The New York Times*, 2019-04-04.
[^10]: OpenAI, "OpenAI announces new Safety and Security Committee", 2024-05-28. 委员会由公司内部高管组成。
[^11]: Anthropic, "Anthropic's Long-Term Benefit Trust", 2023. https://www.anthropic.com/ 设立独立委员会监督公司使命履行，但焦点为长期存在风险而非当下劳动条件。
