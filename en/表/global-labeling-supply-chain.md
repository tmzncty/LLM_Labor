# Table · Global Annotation Supply Chain Map

> Compiled by: Ptilopsis | Updated: 2026-06-21

## 1. Annotation Industry Panorama

```
┌─────────────────────────────────────────────────────────────────┐
│                        AI Companies (Clients)                    │
│  OpenAI · Google · Meta · Anthropic · Microsoft · US DoD         │
└──────────────────────────┬──────────────────────────────────────┘
                           │ Procure annotated data
                           ▼
┌─────────────────────────────────────────────────────────────────┐
│                    Annotation Platforms (Intermediaries)          │
│  Scale AI/Remotasks · Sama · Appen · Cogito · Surge AI · Toloka  │
└──────────────────────────┬──────────────────────────────────────┘
                           │ Employ / Crowdsource
                           ▼
┌─────────────────────────────────────────────────────────────────┐
│                    Secondary Outsourcing (Local Agents)           │
│  Local recruitment firms · Training agencies · Social media ads   │
└──────────────────────────┬──────────────────────────────────────┘
                           │ Recruit
                           ▼
┌─────────────────────────────────────────────────────────────────┐
│                    Annotation Workers (Bottom Tier)               │
│  Kenya · Philippines · Venezuela · India · Uganda · Pakistan      │
│  Hourly wage: $0.50 - $3.00                                      │
└─────────────────────────────────────────────────────────────────┘
```

## 2. Major Annotation Platform Comparison

| Platform | Parent Company | HQ | Worker Scale | Major Markets | Major Tasks | Hourly Wage Range | Source |
|----------|---------------|-----|-------------|--------------|-------------|-------------------|--------|
| Scale AI / Remotasks | Scale AI | USA · San Francisco | 100,000+ | Philippines, Venezuela, Kenya | Text/image annotation, RLHF | $1-3 | Forbes 2024 |
| Sama | Sama (independent) | USA · San Francisco | 10,000-20,000 | Kenya | Image annotation, content moderation | $1.32-2 | Time 2023 |
| Appen | Appen Ltd. | Australia · Sydney | 1,000,000+ (crowdsource pool) | 170+ countries globally | Search relevance, RLHF | $1-5 | Appen 2023 Annual Report |
| Cogito Tech | Cogito | USA · New York | 5,000-10,000 | Jamaica, Bulgaria, India | Image annotation, content moderation | $2-5 | Company website |
| Surge AI | Surge AI | USA · San Francisco | 1,000-5,000 | USA, India | RLHF, safety annotation | $5-15 | The Information 2023 |
| Toloka | Toloka AI | Netherlands · Amsterdam | 200,000+ (crowdsource pool) | Russia, Eastern Europe, India | Search annotation, NLP | $0.50-3 | Toloka 2023 |

## 3. Geographic Distribution of Annotation Workers

| Country/Region | Est. Worker Count | Major Platforms | Major Languages | Avg. Hourly Wage | Local Avg. Hourly Wage | Ratio | Source |
|---------------|------------------|----------------|----------------|-----------------|----------------------|-------|--------|
| Philippines | 50,000-100,000 | Remotasks, Appen | English, Filipino | $1.50-3 | $2-4 | 0.75x | Rest of World 2023 |
| Kenya | 10,000-30,000 | Sama, Remotasks, Appen | English, Swahili | $1.32-2.50 | $1-2 | 1.25x | Time 2023 |
| Venezuela | 20,000-50,000 | Remotasks | Spanish | $1-2 | $0.50-1 | 2x | The Guardian 2023 |
| India | 10,000-30,000 | Appen, Remotasks, Toloka | English, Hindi | $1-3 | $1-2 | 1.5x | Bloomberg 2023 |
| Uganda | 5,000-10,000 | Remotasks, Appen | English | $1-2 | $0.50-1 | 2x | ACM 2026 |
| Pakistan | 5,000-15,000 | Remotasks, Appen | English, Urdu | $1-2 | $0.50-1 | 2x | Industry hearsay |

## 4. Annotation Task Types and Unit Prices

| Task Type | Skill Requirement | Psychological Risk | Unit Price | Hourly Output | Hourly Wage | Source |
|-----------|------------------|-------------------|-----------|--------------|------------|--------|
| Image classification | Low | Low | $0.01-0.05/image | 60-120 images | $1-3 | Vice 2022 |
| Text classification | Low-Medium | Low | $0.02-0.10/item | 30-60 items | $1-3 | Vice 2022 |
| Content moderation | Medium | **Extremely High** | $0.05-0.20/item | 20-40 items | $1-3 | The Verge 2019 |
| RLHF preference ranking | Medium-High | Medium | $0.10-0.50/pair | 10-30 pairs | $1-5 | Anthropic 2023 |
| Speech transcription | Medium | Low | $0.10-0.50/min | 10-20 min | $1-3 | Industry hearsay |
| Point cloud annotation (autonomous driving) | Medium-High | Low | $0.05-0.20/frame | 20-40 frames | $1-3 | Scale AI website |
| Specialized domain annotation (legal/medical) | High | Low-Medium | $0.50-2.00/item | 5-15 items | $3-10 | Industry hearsay |

## 5. Profit Distribution Structure

| Segment | Role | Est. Revenue Share | Typical Margin | Source |
|---------|------|-------------------|---------------|--------|
| AI Company | Data buyer | Pays $0.10-0.50/image (classification) | 20-50% | Industry analysis |
| Annotation Platform | Intermediary | Charges $0.10-0.50/image, pays $0.01-0.05/image | 30-50% | MIT Tech Review 2022 |
| Secondary Outsourcing | Local agent | Receives share from platform | 10-20% | Industry hearsay |
| Annotation Worker | Final executor | Actual take: $0.01-0.05/image | N/A | — |

**Typical Profit Margin Example** (image classification task):

| Segment | Amount | Share |
|---------|--------|-------|
| AI company pays platform | $0.30/image | 100% |
| Platform deduction | $0.24/image | 80% |
| Annotator actual take | $0.06/image | 20% |

## 6. AI Company–Annotation Platform Relationships

| AI Company | Annotation Platform Used | Cooperation Content | Source |
|-----------|-------------------------|-------------------|--------|
| OpenAI | Sama (terminated), Scale AI | RLHF, safety annotation | Time 2023 |
| Google | Appen, Sama | Search relevance, image annotation | Bloomberg 2023 |
| Meta | Appen, Scale AI | Content moderation, RLHF | The Verge 2023 |
| Anthropic | Surge AI | Constitutional AI, safety annotation | Company announcement |
| Microsoft | Appen | Search annotation, speech annotation | Appen Annual Report |
| US Department of Defense | Scale AI | Satellite imagery, target recognition | Defense One 2020 |

## 7. Data Source Notes

- **Industry Reporting**: Time, The Verge, The Guardian, Bloomberg, Vice, Rest of World
- **Company Data**: Annual reports, company websites, investor reports
- **Academic Research**: ACM Digital Library, Nature, MIT Technology Review
- **Industry Hearsay**: Annotator communities, Glassdoor, Blind

> Note: Annotator counts and wages are estimates and fluctuate significantly (under the crowdsourcing model). Data from different sources may vary.

## 8. Cross-References

- Detailed investigations: See "Investigation · Kenyan Labelers," "Investigation · ScaleAI Outsourcing System," "Investigation · MTurk and Crowdsourcing Labor"
- Theoretical analysis: See "Essay · Labor Justice," "Essay · The Global South"
- Impacted professions: See "Table · Impacted Professions List"
