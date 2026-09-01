# MTurk and Crowdwork: An Institutional Ancestor of AI Gig Platforms

> **As of 2026-09-01. Status: REVISED.** Amazon Mechanical Turk is no longer the center of frontier-model training, but it remains crucial for understanding the institutional design inherited by Remotasks, Outlier and similar AI work platforms: microtasking, piece rates, unpaid search and qualification time, and highly asymmetric control over acceptance and reputation. Amazon has confirmed that MTurk will **permanently close on September 30, 2026**. That gives this institutional form a clear historical endpoint at one of its earliest major platforms, but Amazon has not attributed the closure to AI automation, so it should not be written as “AI killed MTurk.”

Amazon launched Mechanical Turk in 2005. Requesters post Human Intelligence Tasks (HITs), while workers remotely perform classification, transcription, surveys and other small jobs.

Its most important contribution was organizational: human judgment became a resource that could sit behind an API. The requester saw completed labels; the worker saw a task queue, qualifications, prices, rejection risk and time spent looking for work.

## 2026: the platform enters its final month

Amazon's official MTurk closure FAQ states that **Mechanical Turk will permanently close on September 30, 2026**. Workers will still be paid for completed and approved HITs under existing payment schedules. Requesters can process submitted work and award bonuses until October 30, and transaction history remains available until January 28, 2027.[^2]

AWS also tells SageMaker customers that still use the MTurk workforce option to migrate affected workflows before September 30.[^3]

An important boundary is easy to lose in secondary coverage: **MTurk's closure is not the same as SageMaker Ground Truth shutting down in full on September 30.** Amazon's FAQ says the **Amazon Mechanical Turk Worker type** will cease to be available for Ground Truth labeling jobs and Amazon Augmented AI human-review workflows. Current Ground Truth documentation separately says that the service is closed to new customers but remains available to existing customers, including workflows using private workforces.[^2][^4]

For labor history, the closure matters because an open microtask market that operated for more than two decades is leaving the field. For workers who still depend on it, this is a real platform exit and loss of an income channel; for requesters it is a forced migration of human-work workflows.

But the primary sources do **not** provide a labor-market causal explanation. Amazon does not publish a current active-worker count in the closure notice and does not say that generative AI, specialist data vendors, demand decline, or any other single factor caused the decision. The closure itself is documented; “AI caused the closure” is not.

## What workers actually earned

A major study by Hara et al. recorded 2,676 workers completing about 3.8 million tasks. When unpaid time spent searching, attempting rejected work and other overhead was included, the **median effective hourly wage was about $2**, and only about 4% earned more than the U.S. federal minimum wage of $7.25.[^1]

This finding matters because nominal task rates are not the same thing as realized earnings. Workers also spend time reading instructions, qualifying, refreshing queues and dealing with rejection.

## Platform power

The classic crowdwork structure gives requesters or platform rules control over task design, acceptance, reputation and future access. Modern AI-data platforms add more layers—outsourcers, model companies, project managers, automated quality control and account-security systems—but the asymmetry remains recognizable.

## What changed in frontier AI

Modern model-training work can require long-form factual review, coding, mathematics, science, red teaming and domain expertise. Some projects therefore pay far more than old MTurk microtasks.

Higher rates, however, do not erase platform risk. Workers may still bear unpaid onboarding, learning and waiting costs, while project access can disappear abruptly. MTurk's closure makes another layer of that risk visible: the platform itself can exit, and qualifications, reputation and access accumulated there do not automatically transfer to another marketplace.

## Why MTurk still belongs in AI labor history

MTurk established a durable organizational pattern: break human judgment into tasks, hide the labor behind an interface, buy it piece by piece, and govern access through ratings and qualifications.

The platform's 2026 closure does not make that pattern disappear. Much of it has migrated into more specialized and higher-value AI training and evaluation markets.

The historical point is therefore not that every AI-labor platform will follow the same trajectory. It is that MTurk lets us trace an organizational form from emergence and expansion through inheritance by later platforms and, finally, the exit of one of its earliest major carriers.

## Evidence boundaries

- The ~$2 median is a historical MTurk estimate, not a universal wage for all crowdworkers.
- It should not be applied to 2026 expert AI-training projects.
- Not all crowdwork has identical conditions.
- MTurk's September 2026 closure does not establish that generative AI was the primary cause; Amazon does not make that causal claim.
- The loss of the MTurk Worker type does not mean SageMaker Ground Truth itself closes on September 30.
- Advertised task rates should still not be confused with realized hourly earnings, and platform-exit risk should not be ignored.

---

[^1]: Kotaro Hara et al., “A Data-Driven Analysis of Workers' Earnings on Amazon Mechanical Turk,” CHI 2018 / arXiv:1712.05796. https://arxiv.org/abs/1712.05796
[^2]: Amazon Mechanical Turk, “Closure FAQs,” accessed 2026-09-01. https://www.mturk.com/help
[^3]: AWS, “Using the Amazon Mechanical Turk Workforce,” Amazon SageMaker AI documentation, accessed 2026-09-01. https://docs.aws.amazon.com/sagemaker/latest/dg/sms-workforce-management-public.html
[^4]: AWS, “Assign IAM Permissions to Use Ground Truth,” Amazon SageMaker AI documentation, accessed 2026-09-01. https://docs.aws.amazon.com/sagemaker/latest/dg/sms-security-permission.html
