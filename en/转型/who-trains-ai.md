# Who Trains AI

> When you use ChatGPT, you might think it "taught itself" to answer questions. But the truth is: behind every "safe" answer, there is a real human doing annotation. Behind every "helpful" response, there is a real human ranking preferences. AI didn't become intelligent on its own—it was taught by humans, one item at a time. Who are these "teachers"? How much are they paid? What are their working conditions?

## I. AI's "Teachers"

AI model training can be divided into three stages, each requiring human participation:

### Stage One: Pre-training Data Preparation

Large model pre-training requires massive volumes of text data. This data comes from the internet—websites, books, papers, code, social media posts.[^1]

But raw data cannot be used directly. It needs to be cleaned and annotated:
- **Deduplication**: Removing duplicate content
- **Filtering**: Removing harmful content, low-quality content, personal privacy information
- **Classification**: Categorizing content by topic
- **Annotation**: Labeling language, sentiment, entities, and more

Most of this work is done by annotators. They earn $1-3 per hour, sitting at computers judging item by item: "Is this text harmful?" "What is the topic of this text?" "What is the sentiment of this text?"[^2]

### Stage Two: Supervised Fine-Tuning (SFT)

After pre-training, the model needs to "learn how to have conversations." This process is called Supervised Fine-Tuning.

The method: have humans write large volumes of conversation examples—a user asks a question, and the AI gives a "good" answer. These examples are used to fine-tune the model, teaching it to "converse like a human."[^3]

Who writes these examples? Primarily:
- Annotators at outsourcing annotation companies (such as Sama, Scale AI)
- Professional AI trainers (freelancers)
- AI companies' own employees

According to *Time*'s reporting, OpenAI paid Sama $12.50/hour, but annotators received only $1.32-$2/hour.[^4]

### Stage Three: RLHF (Reinforcement Learning from Human Feedback)

This is the critical step that "aligns" AI with human preferences. The method:
1. Have the model generate multiple responses
2. Have human annotators rank these responses ("which is better")
3. Use the rankings to train a "reward model"
4. Use the reward model to guide the model's learning

The annotator's role here is that of "referee"—they judge whether AI responses are safe, helpful, and honest.[^5]

This work requires judgment, moral intuition, and cultural sensitivity. But the market prices it at $1-3/hour.

## II. Different Tiers of "AI Teachers"

AI's "teachers" can be divided into several tiers, with vast disparities in working conditions and compensation.

### Bottom Tier: Data Annotators

**Work content:**
- Image classification ("Is this a cat or a dog?")
- Text annotation ("Is this passage positive or negative?")
- Content moderation ("Does this image contain violence?")
- Audio transcription ("Transcribe this recording to text")

**Working conditions:**
- Hourly wage: $1-3 (developing countries), $7-15 (United States)
- No employment contract, no benefits
- Unstable work, volatile income
- High exposure risk to harmful content

**Number:**
An estimated 5-10 million data annotators worldwide.[^6]

### Middle Tier: RLHF Preference Annotators

**Work content:**
- Ranking AI outputs ("Response A and Response B—which is better?")
- Judging the safety of AI responses
- Evaluating the accuracy and helpfulness of AI responses

**Working conditions:**
- Hourly wage: $3-15 (varies by region)
- Requires higher judgment and language skills
- Higher exposure risk to harmful content
- Significant psychological pressure

**Number:**
An estimated 100,000-500,000 RLHF annotators worldwide.[^7]

### Top Tier: Professional AI Trainers

**Work content:**
- Writing high-quality conversation examples
- Designing AI behavioral guidelines and boundaries
- Evaluating AI capability in specialized domains (law, medicine, programming, etc.)
- Developing annotation guidelines and quality standards

**Working conditions:**
- Hourly wage: $20-100+
- Usually contract-based or full-time
- Requires deep professional knowledge
- Relatively less harmful content exposure

**Number:**
An estimated 10,000-50,000 professional AI trainers worldwide.[^8]

## III. The Dilemmas of AI Teachers

### Dilemma One: You Don't Know Who You're Teaching

Annotators typically don't know where their labor is being used. They sign non-disclosure agreements and cannot reveal their work content.[^9]

Annotator A (pseudonym, Kenya):

> "I annotate hundreds of images every day. I don't know what these images will be used for. Training autonomous driving? Surveillance systems? Military AI? I only know that for every image I annotate, I earn $0.02."

### Dilemma Two: You're Teaching AI to Replace You

RLHF annotators' job is to judge whether AI responses align with human preferences. But the result of these judgments is: AI learns to better mimic human preferences. Once AI has learned, it no longer needs annotators to teach it.[^10]

This is a structural self-obsolescence: annotators use their own labor to cultivate the technology that replaces them.

### Dilemma Three: You Suffer Psychological Harm, but No One Cares

Content moderation and harmful content annotation can cause severe psychological trauma—PTSD, anxiety, depression, emotional numbness (see *Investigation: The Psychological Cost of Data Annotation*).[^11] But annotators receive virtually no mental health support.

Former Sama annotator:

> "I've read written descriptions of children being raped. I've read detailed suicide methods. I've read descriptions of torture. The company provided no counseling. I had to carry it all myself. After I quit, I had nightmares for a very long time."

## IV. From RLHF to RLAIF: The Future of AI Teachers

The AI industry is developing techniques that don't require human annotation—RLAIF (Reinforcement Learning from AI Feedback).[^12]

Anthropic's Constitutional AI is a representative example: using a set of "constitutional" principles to enable AI self-criticism and self-correction, reducing reliance on human annotation.[^13]

DeepSeek-R1-Zero goes further: using pure reinforcement learning with rule-based rewards to develop reasoning capabilities without any human-annotated data.[^14]

If this trend continues, what is the outlook for annotators?

**The optimistic narrative**: Annotators will no longer need to do harmful content moderation, no longer need to train models while suffering PTSD. AI can self-evolve, and annotators can move on to more meaningful work.

**The pessimistic narrative**: Tens of thousands of workers who depend on annotation work for survival will be cast into the flood of unemployment. The AI industry's response will most likely be silence.

**A third possibility**: AI won't fully replace human annotation, but will push annotators into even more fine-grained, more hidden, more unprotected positions. The remaining annotation work will be the most difficult—judging subtle cultural biases, evaluating complex ethical boundaries—but the pay may not be higher.[^15]

---

[^1]: Brown, T., et al., "Language Models are Few-Shot Learners," 2020. https://arxiv.org/
[^2]: Time, "OpenAI Used Kenyan Workers on Less Than $2 Per Hour," 2023-01-18. https://time.com/
[^3]: Ouyang, L., et al., "Training Language Models to Follow Instructions with Human Feedback," 2022. https://arxiv.org/
[^4]: Time, "OpenAI Used Kenyan Workers on Less Than $2 Per Hour," 2023-01-18.
[^5]: 同上。
[^6]: Oxford Insights, "The Global AI Workforce," 2024. https://www.oxfordinsights.com/
[^7]: 同上。
[^8]: 同上。
[^9]: Time, "OpenAI Used Kenyan Workers on Less Than $2 Per Hour," 2023-01-18.
[^10]: Lee, A., et al., "RLAIF: Scaling Reinforcement Learning from Human Feedback with AI Feedback," 2023. https://arxiv.org/
[^11]: The Verge, "The Trauma of Content Moderation," 2019-02-25. https://www.theverge.com/
[^12]: Lee, A., et al., "RLAIF: Scaling Reinforcement Learning from Human Feedback with AI Feedback," 2023.
[^13]: Bai, Y., et al., "Constitutional AI: Harmlessness from AI Feedback," 2022. https://arxiv.org/
[^14]: DeepSeek, "DeepSeek-R1: Incentivizing Reasoning Capability in LLMs via Reinforcement Learning," 2025. https://arxiv.org/
[^15]: Gray, M. & Suri, S., "Ghost Work: How to Stop Silicon Valley from Building a New Global Underclass," 2019.

## Assessment

AI's "teachers" are a systematically overlooked group.

We speak of AI's "learning ability" as if it were a self-taught genius. We speak of AI's "emergent behaviors" as if they were miracles conjured from thin air. But the truth is: every capability of AI—from answering questions to identifying images to refusing harmful requests—was taught by humans, one item at a time.

Who are these "teachers"?

They are not Stanford professors, not DeepMind researchers, not Silicon Valley engineers. They are Kenyan annotators earning $1.32/hour; Filipino crowdworkers earning $0.02 per image; Venezuelan engineers forced by economic crisis to turn to data annotation.

The AI industry's "learning narrative" is a carefully constructed myth. It says AI "learned" human knowledge, but it doesn't say who was "teaching." It says AI "aligned" with human preferences, but it doesn't say whose preferences, and at what cost.

The function of this myth is **to conceal labor**. When you see ChatGPT give a "safe" answer, you don't think: this answer's "safety" was bought with a Kenyan person's mental health. When you see Midjourney generate a beautiful image, you don't think: this image's "creativity" was trained on the works of millions of artists who received no compensation.

The answer to "who trains AI" reveals a brutal fact: AI's "intelligence" is built upon large-scale invisible labor. This labor is outsourced to developing countries, priced at the lowest levels, and hidden behind non-disclosure agreements.

If we push the question "who trains AI" to its extreme, we find a paradox: annotators are teaching AI how to replace them. They use their own judgment to train AI to have judgment, their own moral intuition to train AI to have moral intuition. Once AI has learned, the annotators are no longer needed.

This is not a story of technological progress. This is a story of labor being discarded.
