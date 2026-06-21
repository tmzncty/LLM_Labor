# Who Is Fighting Back

> Not everyone is quietly accepting AI's arrival. Some fight in court, accusing AI companies of stealing their work; some protest at the keyboard, tagging every piece they create with "NO AI"; some take to the streets with signs and strike; some develop poisons in the lab, making it impossible for AI to learn from their art. Resistance takes many forms, but all point to the same question: where does AI's training data come from? Who has the right to use human creations?

## I. The Legal Wars: Copyright Litigation

AI companies need data to train models. This data—text, images, code, music—comes almost entirely from human creations (see *Transformation: Who Trains AI*). The question is: did these creators consent?

**Getty Images vs. Stability AI (January 2023):**

Getty Images is the world's largest commercial image library. In January 2023, Getty sued Stability AI in both the UK and US, alleging that Stability used over 12 million Getty images without authorization to train Stable Diffusion.[^1]

Getty's lawsuit presented key evidence: AI-generated images occasionally bore Getty's watermark—a semi-transparent "Getty Images" logo.[^2] This wasn't AI "remembering" and copying images—it was AI learning the watermark as part of the image and then "hallucinating" the watermark when generating new images.

Stability AI's defense strategy centered on "fair use": training an AI model constitutes "transformative use" of data, not copying.[^3]

As of late 2025, this case remains in litigation.

**Sarah Andersen et al. vs. Stability AI / Midjourney / DeviantArt (January 2023):**

In January 2023, three artists—Sarah Andersen, Kelly McKernan, and Karla Ortiz—filed a class-action lawsuit against Stability AI, Midjourney, and DeviantArt.[^4]

This was the first time artists collectively took to the courtroom. Their core allegation: AI image generation models were trained on billions of images without authorization. These images came from platforms like ArtStation, DeviantArt, and Instagram—where artists uploaded their work to showcase it, not to train AI.

In October 2023, Judge Orrick dismissed most of the claims, finding that the plaintiffs had not provided sufficient evidence that AI-generated images were "substantially similar" to their specific works.[^5] But the judge allowed the plaintiffs to amend and resubmit the complaint.

In August 2024, the amended complaint was resubmitted with additional evidence.[^6] As of late 2025, this case is still ongoing.

**NYT vs. OpenAI / Microsoft (December 2023):**

In December 2023, *The New York Times* sued OpenAI and Microsoft—making it one of the largest copyright lawsuits facing generative AI.[^7]

*The New York Times*' allegations were more specific than the artists': it demonstrated that ChatGPT could reproduce *NYT* articles nearly verbatim.[^8] In testing, given the opening paragraphs of an *NYT* article, ChatGPT could continue generating text nearly identical to the full original.

This wasn't "learning"—this was "memorizing" and "copying."

OpenAI's response was that training constitutes "fair use," and that ChatGPT's output is "transformative."[^9] But the *NYT*'s evidence made this defense difficult—if an AI can output copyrighted articles word for word, where does the boundary of "fair use" lie?

**More Lawsuits:**

- **Music industry**: Universal Music Group (UMG) and other music rights holders sued Anthropic in 2024, alleging unauthorized use of lyrics to train models[^10]
- **Book publishing**: The Authors Guild filed a class-action lawsuit against OpenAI in 2023, alleging use of copyrighted books to train GPT models[^11]
- **News industry**: Multiple news organizations (including The Intercept, Raw Story) sued OpenAI[^12]

As of late 2025, almost none of these lawsuits have reached a final verdict. There is no consensus in the legal community on whether "AI training constitutes fair use."

## II. Community Resistance: User Backlash

**ArtStation "NO AI" Protest (December 2022):**

ArtStation is the world's largest platform for digital artists to showcase their work—concept designers, illustrators, 3D artists use it to display portfolios and find jobs. In December 2022, when AI-generated images began flooding the platform, artists erupted in protest.[^13]

The protest method was simple: thousands of artists simultaneously uploaded black-and-white images on ArtStation reading "NO AI ART" or "NO TO AI GENERATED IMAGES." These images overwhelmed ArtStation's homepage, rendering the platform nearly unusable.

The artists' demands were clear:
- ArtStation should ban AI-generated images
- ArtStation should prohibit the use of user works for AI training
- ArtStation should provide artists with an "opt out of AI scraping" option

ArtStation's response disappointed the artists: the platform announced it would not ban AI-generated images, citing "technological neutrality" and "creative freedom."[^14] The platform later added a "No AI Training" metadata tag, but this tag has no legal force—it merely "requests" compliance from crawlers rather than "prohibiting" them.

**DeviantArt User Protest:**

DeviantArt is another artist community platform. In November 2022, DeviantArt launched its own AI image generation tool, "DreamUp," based on Stable Diffusion.[^15]

The artists' outrage was clear: DreamUp was trained on their work—they were not asked, not compensated, and not even informed.

Thousands of artists posted protest messages on DeviantArt, and some deleted all their works from the platform.[^16]

**Reddit and Stack Overflow's Data Protection Moves:**

In 2023, Reddit and Stack Overflow—two of the internet's largest knowledge communities—began charging for AI training data.[^17]

Reddit announced it would charge for API access, after AI companies had been freely obtaining massive volumes of Reddit conversation data through the API for training purposes.[^18] This decision directly affected the training data acquisition costs for companies like OpenAI and Google.

Stack Overflow also announced it would charge AI companies.[^19] As the world's largest programming Q&A community, Stack Overflow's data is a critical training source for code-oriented AI models.

These moves weren't "resistance"—they were more like "awakening": platforms finally recognizing that user-generated content has value, and that this value was being extracted by AI companies without compensation.

## III. Union Action: The Hollywood Strikes

**The 2023 Hollywood Writers' Strike (WGA Strike):**

On May 2, 2023, the Writers Guild of America (WGA) went on strike—Hollywood's first writers' strike in 15 years.[^20]

One of the strike's core demands was **restricting AI's use in screenwriting**. The WGA's specific demands included:[^21]
- AI cannot be used to write or rewrite screenplays
- AI cannot be used to generate "literary material"
- AI-generated content cannot be used as source material for screenwriters
- Studios cannot require screenwriters to use AI
- Screenwriters' original works cannot be used to train AI models

This was the first time an AI threat became a **direct cause of a major strike**.

On September 27, 2023, the WGA reached an agreement with the studios. The final terms included:[^22]
- AI cannot be granted "writer" status
- AI-generated content is not considered "literary material" or "source material"
- Screenwriters may choose to use AI as a tool (but cannot be compelled to)
- Studios cannot require screenwriters to use AI
- Screenwriters' original works cannot be used to train AI (without screenwriter consent)

This was the world's first formal collective agreement on AI and labor relations.

**The SAG-AFTRA Actors' Strike:**

In July 2023, the Screen Actors Guild (SAG-AFTRA) also joined the strike.[^23] The actors' core AI concern: studios might use AI to scan actors' appearances, create "digital doubles," and then use these digital doubles without the actors' participation.

SAG-AFTRA reached an agreement with studios in November 2023, which included provisions on AI use:[^24]
- Studios cannot use AI to replicate actors' appearances without consent
- Using AI digital doubles requires the actor's explicit consent and compensation
- AI use involving deceased actors requires consent from their estate

**Other Union Actions:**

- **News industry**: The NewsGuild began incorporating AI clauses into labor contract negotiations with media companies in 2024[^25]
- **Voice actors**: Voice actors' unions in Japan and the US began opposing AI voice acting[^26]
- **Music industry**: The American Federation of Musicians (AFM) began demanding AI clauses in collective agreements[^27]

## IV. Technical Resistance: Fighting Code with Code

**Glaze (University of Chicago, 2023):**

In February 2023, the SAND Lab at the University of Chicago released Glaze—a "style protection" tool designed for artists.[^28]

Glaze works by adding nearly imperceptible micro-perturbations to an artist's work ("style cloaking"), causing AI models to misidentify the style when learning from the image. For example, a realistic oil painting, after Glaze processing, would be classified by AI as abstract style.[^29]

Glaze's significance: it gave artists a means of **active defense**. Previously, artists could only protest passively; now, they could protect their work while publishing it.

Glaze has been downloaded over 2 million times since launch.[^30]

**Nightshade (University of Chicago, October 2023):**

In October 2023, the same team released Nightshade—a more radical tool.[^31]

Nightshade isn't about "defense"—it's about "attack." It embeds a kind of "poison" into images: when AI trains on Nightshade-processed images, the model learns incorrect knowledge. For example, Nightshade can make AI learn "dog" as "cat"—not an occasional error, but a systematic one.[^32]

Nightshade's design intent: if AI companies use artists' works without authorization, those works become "poison" for AI models, destroying model quality from within.

This sparked heated debate: supporters argued it was artists' legitimate right to protect themselves; opponents called it "sabotage."[^33]

**Limitations of Technical Protection:**

Glaze and Nightshade's effects are real—but they face a fundamental problem: **adversarial attack and defense is an arms race.**

AI researchers can develop "de-poisoning" techniques to neutralize Nightshade's effects. Every Nightshade update triggers a corresponding defense update from AI companies. It's an endless technical cat-and-mouse game.

Moreover, Glaze and Nightshade can only protect **new** works. For the billions of historical works already scraped and trained on, these tools are powerless.

## V. Another Voice: Embracing AI

Not all creators are fighting back. Some chose to embrace.

**The Rise of AI Artists:**

Some artists began using AI as a creative tool rather than viewing it as an enemy:
- Refik Anadol uses AI to generate large-scale installation art, exhibited at the Museum of Modern Art (MoMA) in New York[^34]
- Holly Herndon uses AI to synthesize her own voice for musical works[^35]
- Some illustrators began incorporating AI into their creative workflow, shifting from "purely handmade" to "human-machine collaboration"

**"The New Tool Theory":**

These people hold a "new tool theory" perspective: AI is like the camera, Photoshop, or 3D printer of its era—a new tool that will displace some people but also create new opportunities.

Opponents respond: cameras didn't learn from other people's paintings. Photoshop didn't scrape the world's images without permission. This analogy ignores the **data source** problem in AI training.

---

[^1]: The Verge, "Getty Images Sues Stability AI for Copying 12 Million Images," 2023-01-17. https://www.theverge.com/
[^2]: The Verge, "AI-Generated Images Are Getting Watermarks from Getty," 2023-01-17. https://www.theverge.com/
[^3]: Stability AI, "Response to Getty Images Lawsuit," 2023-02-15.
[^4]: The Verge, "Artists Sue AI Image Generators for Copyright Infringement," 2023-01-16. https://www.theverge.com/
[^5]: The Verge, "Judge Dismisses Most Claims in AI Art Copyright Lawsuit," 2023-10-30. https://www.theverge.com/
[^6]: Reuters, "AI Art Copyright Case Revived with Amended Complaint," 2024-08-12. https://www.reuters.com/
[^7]: The New York Times, "The New York Times Sues OpenAI and Microsoft Over AI Use of Copyrighted Work," 2023-12-27. https://www.nytimes.com/
[^8]: 同上。诉状中展示了 ChatGPT 可以续写《纽约时报》文章的测试结果。
[^9]: OpenAI, "OpenAI and Journalism," 2024-01-08. https://openai.com/
[^10]: Billboard, "Universal Music and Other Publishers Sue Anthropic Over Lyrics," 2023-10-18. https://www.billboard.com/
[^11]: The Verge, "Authors Sue OpenAI for Copyright Infringement," 2023-09-20. https://www.theverge.com/
[^12]: The Intercept, "The Intercept Sues OpenAI Over Copyright," 2024-02-28. https://theintercept.com/
[^13]: The Verge, "Artists Are Revolting Against AI Art on ArtStation," 2022-12-15. https://www.theverge.com/
[^14]: ArtStation, "Our Policy on AI-Generated Content," 2022-12-20. https://www.artstation.com/
[^15]: The Verge, "DeviantArt Launches AI Image Generator Sparking Artist Backlash," 2022-11-11. https://www.theverge.com/
[^16]: Kotaku, "DeviantArt Users Are Deleting Their Accounts Over AI Art," 2022-11-14. https://kotaku.com/
[^17]: The Verge, "Reddit and Stack Overflow Want to Be Paid for AI Training Data," 2023-06-01. https://www.theverge.com/
[^18]: The Verge, "Reddit Will Charge for Access to Its API," 2023-04-18. https://www.theverge.com/
[^19]: The Verge, "Stack Overflow Will Charge AI Companies for Training Data," 2023-04-28. https://www.theverge.com/
[^20]: The Hollywood Reporter, "Writers Guild of America Goes on Strike," 2023-05-02. https://www.hollywoodreporter.com/
[^21]: Writers Guild of America, "WGA Negotiations: AI Proposals," 2023-05-01. https://www.wga.org/
[^22]: Writers Guild of America, "2023 WGA MBA: Summary of the Agreement," 2023-09-27. https://www.wga.org/
[^23]: The Hollywood Reporter, "SAG-AFTRA Goes on Strike, Joining WGA on Picket Lines," 2023-07-14. https://www.hollywoodreporter.com/
[^24]: SAG-AFTRA, "2023 TV/Theatrical Contract Summary," 2023-11-09. https://www.sagaftra.org/
[^25]: Nieman Lab, "NewsGuild Pushes for AI Protections in Media Contracts," 2024-03-01. https://www.niemanlab.org/
[^26]: The Guardian, "Voice Actors Fear AI Will Take Their Jobs," 2023-08-15. https://www.theguardian.com/
[^27]: American Federation of Musicians, "AI and the Music Industry," 2024-01-15. https://www.afm.org/
[^28]: SAND Lab, University of Chicago, "Glaze: Protecting Artists from Style Mimicry," 2023-02-01. https://glaze.cs.uchicago.edu/
[^29]: 同上。技术原理详见论文。
[^30]: MIT Technology Review, "This Tool Could Protect Artists from AI Mimicry," 2023-02-08. https://www.technologyreview.com/
[^31]: SAND Lab, University of Chicago, "Nightshade: Prompt-Specific Poisoning Attacks on Text-to-Image Models," 2023-10-01. https://nightshade.cs.uchicago.edu/
[^32]: 同上。技术原理详见论文。
[^33]: The Verge, "Nightshade: The Tool That 'Poisons' AI Models," 2023-10-24. https://www.theverge.com/
[^34]: MoMA, "Refik Anadol: Unsupervised," 2022-11-19. https://www.moma.org/
[^35]: The Guardian, "Holly Herndon: The Musician Who Embraced AI," 2023-05-01. https://www.theguardian.com/

## Assessment

Has resistance been effective?

**The legal wars**: As of late 2025, not a single landmark case has reached a final verdict. Getty vs. Stability AI, NYT vs. OpenAI, the artists' class-action—all remain unresolved. Courts seem to be waiting for legislation; legislators seem to be waiting for the courts. It's a cycle of buck-passing.

Can copyright lawsuits win? Perhaps. *The New York Times*' evidence is the strongest—ChatGPT can output copyrighted articles verbatim, which is hard to defend as "fair use." But even if they win, the damages may be negligible relative to AI companies' profits. The gears of law turn too slowly, while AI advances too fast.

Can technical protection last? Glaze and Nightshade are brilliant inventions, but they are defensive—they can only protect new works, not recover losses already sustained. Moreover, they face a fundamental dilemma: an arms race. AI companies' resources vastly outmatch those of a single university laboratory.

What about union action? The Hollywood strike was the only resistance to achieve substantive results—the WGA's agreement is the world's first formal collective agreement on AI and labor relations. But the writers' union won because Hollywood's creative workforce has a **union tradition** and **collective bargaining rights**. Freelance illustrators, translators, programmers—they have no unions, no collective bargaining rights, and often no colleagues.

This is the structural dilemma of resistance: **AI replaces individuals, but effective resistance requires collectives.**

An illustrator uploading a "NO AI" image on ArtStation—that's a cry. Ten thousand illustrators uploading simultaneously—that's a movement. But even a movement of ten thousand illustrators, ArtStation can ignore it, because the platform knows: even if these people leave, their works are already on the internet, and AI has already learned from them.

This reveals a deeper problem: **internet content is irrevocable.**

Every painting you upload to the internet, every article, every piece of code—they will exist forever, copied, cached, archived by countless servers. You can delete the original post, but you cannot delete data already trained into AI models. You cannot "withdraw" your contribution.

So the fundamental dilemma of resistance isn't about "rights"—everyone acknowledges creators have rights. The dilemma is **enforcement**. You have the right to stop others from using your work, but you lack the ability to stop them. The internet makes works uncontrollable; AI makes that uncontrollability irreversible.

Is AI's advance unstoppable?

History's answer is complex. The Industrial Revolution destroyed the livelihoods of hand-weavers, but the Luddite movement was ultimately suppressed. Cars replaced horse-drawn carriages, photography replaced portrait painters—every technological revolution had its losers, and the losers' resistance ultimately failed.

But this time may be different. Because this time's "technology" isn't a new tool—it's a **learning ability**. A camera has no learning ability; it merely records. A car has no learning ability; it merely transports. But AI has learning ability—it learns human creations, then replicates them.

When a technology can learn everything about humans, what remains for humanity?

No one can answer this question. But every creator—every painter, writer, programmer, customer service agent—is searching for an answer in their own way.

Some fight in court, some protest at the keyboard, some strike in the streets, some build poisons in the lab, some embrace AI and become new creators.

Whatever choice they make, they all refuse one thing: **silent acceptance.**

Perhaps that is the true meaning of resistance. Not to win—the odds of winning are slim. But to say: **our work has value, our labor has dignity, our voices should be heard.**

In a world where AI can generate everything, "refusing to be silent" is itself an act of resistance.
