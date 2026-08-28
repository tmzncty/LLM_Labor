# AI Red Teams and Safety-Evaluation Labor: Someone Has to Push the Model Toward the Worst Case

> **As of 2026-08-28. Status: REVISED.** AI red teaming and safety evaluation are becoming distinct forms of work. Testers actively search for jailbreaks, elicit dangerous behavior, construct adversarial environments, and decide whether safeguards fail. The work may be performed by in-house safety researchers, platform contractors, or independent evaluators; those labor relationships are not interchangeable.

To demonstrate that a model will not easily produce dangerous guidance, someone first has to try to make it do exactly that.

This is the central paradox of red-team labor: **making an AI system safer requires people to repeatedly think like hostile users.**

## Adversarial work rather than passive moderation

Business Insider reported in April 2025 on leaked Scale AI / Outlier training materials instructing contributors to write, evaluate, and revise both benign and harmful prompts involving self-harm, hate, domestic violence, crime, weapons, and other sensitive categories. Testers were taught to embed harmful requests in roleplay or fictional scenarios to probe safety filters.[^1]

This is not simple classification. Red-team work can involve inventing unexpected attack paths, understanding policy boundaries, designing repeatable failures, and checking whether mitigations actually remove the underlying vulnerability.

It depends on **adversarial creativity**.

## Contract red teams as platform labor

One Scale/Outlier freelancer told Business Insider they were paid **$55 an hour** for red-team work.[^1] That is one case, not an industry wage.

Two contributors told BI that they could not selectively opt out of individual harmful categories while remaining on the same project. Scale said contributors received advance notice, could leave projects, and had access to wellness support.[^1]

The accounts are not identical, so the archive does not resolve the disagreement beyond what each side stated.

What is clear is that deliberate generation of harmful test content has been organized as outsourced, project-based platform labor.

## A distinct mental-health risk mechanism

The 2025 paper *When Testing AI Tests Us* describes red teaming as **interactional labor**. Unlike passive review of existing harmful material, red teamers repeatedly interact with a system as adversaries and intentionally guide it toward dangerous states. The authors argue that this can create distinctive psychological burdens and recommend adapting safeguards used in content moderation, mental-health work, conflict reporting, and related fields.[^2]

The paper is about risk mechanisms and protective practices. It is **not** an epidemiological estimate of PTSD prevalence among red teamers.

## Important safety work can still be unstable work

Business Insider reported in September 2025 that twelve Scale AI Red Team contractors had their assignments terminated. Scale described them as contingent workers and a small fraction of the team, saying the cuts were not part of a broader restructuring.[^3]

Two former team members said workloads had fallen after changes in Scale's customer relationships. One former worker estimated the twelve represented about half of the team, but Scale did not confirm total team size.[^3]

The evidence supports a narrower conclusion: specialized safety expertise does not automatically create stable employment. Project demand and client concentration can directly affect red-team contractors.

## Independent evaluators face access and legal risks

A separate labor form is independent safety evaluation outside the model developer's employment structure.

The 2024 “Safe Harbor for AI Evaluation and Red Teaming” proposal argues that terms of service, anti-abuse enforcement, account suspension, and possible legal exposure can deter good-faith safety researchers. Its authors call for legal and technical safe harbors for public-interest evaluation.[^4]

Unlike platform contractors, these evaluators may not receive assignments or wages from the model company. Their risk is that realistic testing can resemble precisely the behavior that platforms normally prohibit.

## Agentic systems make evaluation more infrastructural

OpenAI's 2026 summary of third-party evaluation practice notes that frontier systems increasingly use tools, retain state across multiple steps, and operate within larger workflows. Evaluation therefore depends on environments, scaffolding, permissions, and system setup rather than only single prompt-response pairs.[^5]

This is a developer's methodology document, not labor-condition research. It nevertheless shows how evaluator skill requirements are changing from “prompt and score” toward building environments, configuring tools, designing multi-step attacks, preserving logs, and reproducing agent failures.

## Three different red-team labor structures

| Type | Organizer | Typical labor relationship | Main risks |
|---|---|---|---|
| In-house model red team | model developer | employee / specialist researcher | high-pressure safety work, capability race, organizational conflicts |
| Contract/platform red team | data/evaluation supplier | contractor / contingent / gig | project volatility, harmful content, weaker benefits and recourse |
| Independent third-party evaluation | universities, institutes, independent teams | research labor / grant-funded work | access restrictions, suspension, contractual or legal risk |

Calling all three “high-paid AI safety experts” hides major differences.

## What we cannot say

- One $55/hour case is not an average red-team wage.
- Not all red teamers encounter the same severity of harmful material.
- A plausible mental-health risk mechanism is not a measured prevalence rate.
- Twelve Scale contractor terminations do not represent the whole AI-safety labor market.
- Former workers' explanation of declining workload is not a company-confirmed cause.
- Safe-harbor proposals are not universal legal protection already in force.
- OpenAI's evaluation guidance is not an industry-wide binding standard.

## Analysis

Every model refusal may have a hidden labor history: someone spent time asking how to trick the model into doing the prohibited thing anyway.

Red-teamers are valuable because they temporarily abandon the mindset of a normal user and search for the system's worst possibilities.

That labor also needs protection. If workers repeatedly enter violent, self-harm, fraud, or abuse scenarios while being treated as disposable contractors—or if independent evaluators bear the access and legal risk of discovering problems—then “AI safety” protects users and models without fully protecting the people who produce the evidence of safety.

---

[^1]: Business Insider, “How do you stop AI from spreading abuse? Leaked docs show how humans are paid to write it first,” 2025-04-04. https://www.businessinsider.com/scale-ai-outlier-training-harmful-ai-prompts-2025-04
[^2]: Pendse et al., “When Testing AI Tests Us: Safeguarding Mental Health on the Digital Frontlines,” 2025. https://arxiv.org/abs/2504.20910
[^3]: Business Insider, “Scale AI just made another round of cuts to its workforce after Meta's $14 billion investment,” 2025-09-08. https://www.businessinsider.com/scale-ai-makes-cuts-to-key-team-after-meta-investment-2025-9
[^4]: Longpre et al., “A Safe Harbor for AI Evaluation and Red Teaming,” 2024. https://arxiv.org/abs/2403.04893
[^5]: OpenAI, “A shared playbook for trustworthy third party evaluations,” 2026-05-29. https://openai.com/index/trustworthy-third-party-evaluations-foundations/
