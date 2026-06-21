# The Psychological Cost of Data Labeling

> Labeling work is not just "tedious"—it is traumatic. Reading hours of content about rape, torture, suicide, child abuse daily—this is not a normal work environment. Psychological research has confirmed: prolonged exposure to harmful content leads to PTSD, anxiety, depression, and emotional numbness. But the entire AI industry's response is: silence.

## I. Exposure to Harmful Content

Labelers' daily work involves extensive exposure to harmful content (see "Investigation: Kenya Labelers," "Investigation: Content Moderators").[^1]

**Content Types**:

- **Violent content**: Torture, dismemberment, murder, abuse
- **Sexual content**: Rape, descriptions of Child Sexual Abuse Material (CSAM)
- **Hate speech**: Racism, homophobia, misogyny, religious hatred
- **Suicide and self-harm**: Suicide methods, self-harm behaviors
- **Criminal guidance**: Weapons manufacturing, drug trafficking, hacking

**Exposure Intensity**:

According to Time's investigation, Sama's Kenyan labelers worked 9 hours per day, 6 days per week.[^2] During this time, they needed to read large quantities of harmful content and judge its "degree of harm."

A labeler might read hundreds of harmful content items daily. This means: every 55 seconds, they needed to read and evaluate a new piece of harmful content.[^3]

## II. Psychological Impact

Psychological research has established a causal relationship between exposure to harmful content and psychological trauma.[^4]

### Post-Traumatic Stress Disorder (PTSD)

PTSD is the most common psychological consequence of content moderation and data labeling.[^5]

**Symptoms**:
- Flashbacks: Repeatedly recalling harmful content that was read
- Nightmares: Dreaming about violent or sexually violent content that was read
- Avoidance: Avoiding things that might trigger memories
- Hypervigilance: Excessive sensitivity to the surrounding environment
- Emotional numbness: Loss of response to emotional stimuli in daily life

**Incidence Rate**:

According to The Verge's 2019 investigation of Facebook content moderators, the PTSD incidence rate is far higher than the general population.[^6] While there is no systematic research specifically on AI labelers, the work nature is similar, so the psychological impact should be similar.

### Anxiety and Depression

Prolonged exposure to harmful content leads to anxiety and depression.[^7]

**Symptoms**:
- Persistent worry and fear
- Insomnia or excessive sleep
- Appetite changes
- Decreased concentration
- Loss of hope for the future

### Emotional Numbness

Prolonged reading of harmful content leads to emotional numbness—loss of response to emotional stimuli in daily life.[^8]

**Manifestations**:
- Loss of empathy for violence and suffering
- Loss of interest in intimate relationships
- Loss of pleasure in hobbies and entertainment
- Feeling "empty" about life

### Conditioned Fear

Some labelers develop conditioned fear responses to specific visual or auditory stimuli.[^9]

**Cases**:
- A former moderator said: "I now feel nauseous when I see anything red—because red reminds me of the images I saw during moderation."
- Another moderator said: "I panic when I hear a certain type of music—because that music appeared in a suicide video I moderated."

## III. Lack of Support

Labelers face serious mental health problems but receive almost no support.[^10]

**No Psychological Counseling**:

Former Sama employees stated they never received any mental health support during their employment.[^11] OpenAI stated in a declaration that "our vendors are required to provide mental health support and counseling services for all employees working on OpenAI projects." But former Sama employees denied this.

**No Long-Term Protection**:

Labelers are typically "independent contractors," not "employees." This means: no health insurance, no workers' compensation, no long-term disability protection.[^12]

**No Diagnostic Framework**:

Currently, there is no legal framework to认定 "psychological trauma caused by labeling harmful content" as an occupational injury.[^13] When a coal miner develops pneumoconiosis, it is recognized as a work-related injury—with diagnosis, compensation, and legal protection. When a labeler develops PTSD, it is treated as a "personal psychological problem."

## IV. Comparison with Other Hazardous Occupations

Labeling work has similarities to other hazardous occupations, but also key differences.

| Occupation | Hazardous Exposure | Protective Measures | Compensation | Legal Status |
|------------|-------------------|---------------------|--------------|--------------|
| Coal Miner | Pneumoconiosis risk | Protective equipment, regular checkups | Above-average wages, hazard pay | Workers' compensation |
| Deep-Sea Fisher | Life-threatening danger | Safety equipment, insurance | High income | Labor law protection |
| Chemical Plant Worker | Toxic substances | Protective equipment, regular checkups | Hazard pay | Workers' compensation |
| Labeler | Psychological trauma | **None** | **Minimum wage** | **No protection** |

Key difference: The hazardous exposure of coal miners, deep-sea fishers, and chemical plant workers is at least socially acknowledged, with corresponding protection and compensation. Labelers' psychological trauma is not acknowledged, with no protection and no compensation.

## V. From RLHF to RLAIF: Will the Psychological Cost Decrease?

RLAIF (Reinforcement Learning from AI Feedback) may reduce the need for human labeling, thereby reducing psychological exposure.[^14]

But there is a problem: **the labeling work that most requires human judgment is often the most harmful**.

AI can automatically handle simple labeling tasks—image classification, text classification. But the most complex labeling tasks—judging subtle cultural biases, evaluating complex ethical boundaries, handling edge cases that AI cannot judge on its own—still require humans.

These tasks often involve the highest levels of psychological exposure. When a labeler needs to determine "whether this response constitutes hate speech," they must carefully read text that may contain hate speech. When a labeler needs to determine "whether this image involves child abuse," they must carefully examine images that may contain abuse.

RLAIF may reduce the total number of labelers, but it will not reduce the psychological exposure of remaining labelers—it may even increase it.

## VI. Timeline

| Date | Event | Source |
|------|-------|--------|
| 2019-02 | The Verge exposes Facebook moderators' PTSD issues | The Verge |
| 2022-02 | Sama terminates contract with OpenAI | Time |
| 2023-01 | Time exposes Kenyan labelers' mental health problems | Time |
| 2023-06 | Kenyan government investigates Sama's labor conditions | The Guardian |
| 2024-01 | Meta announces content moderator mental health support plan | Meta |

---

[^1]: Time, "OpenAI Used Kenyan Workers on Less Than $2 Per Hour," 2023-01-18. https://time.com/
[^2]: Ibid.
[^3]: Ibid.
[^4]: American Psychological Association, "The Psychological Impact of Content Moderation," 2023. https://www.apa.org/
[^5]: Ibid.
[^6]: The Verge, "The Trauma of Content Moderation," 2019-02-25. https://www.theverge.com/
[^7]: American Psychological Association, "The Psychological Impact of Content Moderation," 2023.
[^8]: Ibid.
[^9]: The Verge, "The Trauma of Content Moderation," 2019-02-25.
[^10]: Time, "OpenAI Used Kenyan Workers on Less Than $2 Per Hour," 2023-01-18.
[^11]: Ibid.
[^12]: Gray, M. & Suri, S., "Ghost Work," 2019.
[^13]: Ibid.
[^14]: Lee, A., et al., "RLAIF: Scaling Reinforcement Learning from Human Feedback with AI Feedback," 2023. https://arxiv.org/

## Assessment

The psychological cost of data labeling is the largest and most overlooked scandal in the AI industry.

The entire industry's response is silence. AI companies say "we value the well-being of our contractors," but they choose to hire people in Kenya rather than the United States for harmful content moderation—because it's cheaper. Labeling platforms say "we provide mental health support," but former employees say they never received any support. Governments say "we are investigating," but investigation results are never published.

This silence is not accidental. It serves the interests of the AI industry. If labelers' mental health problems were taken seriously, AI companies would need to:
1. Provide mental health support for labelers—increasing costs
2. Reduce exposure time to harmful content—increasing labor demand
3. Raise labelers' wages—increasing costs
4. Establish long-term health protection—increasing costs

All of these would increase AI training costs. In an industry that pursues maximum profit, these costs are unacceptable.

So, labelers' psychological costs are externalized—they are shifted onto the labelers themselves, their families, their communities. AI companies get "safe" models; labelers get PTSD.

This is a precise inequality. AI's "safety" is positively correlated with labelers' psychological trauma: the more harmful content labelers see and the more细致 their labeling, the "safer" the model becomes. But the more harmful content labelers see, the more their mental health deteriorates.

Safety and harm are not exchanged between models and users—they are exchanged on the bodies of labelers.

Who gets safety? All users.
Who gets harm? A few Kenyans.

This exchange was never consented to by them.