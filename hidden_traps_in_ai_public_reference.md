# Hidden Traps in AI: Public Reference Guide


This document serves as a reference for the information discussed in my youtube video and presents credible, verifiable sources supporting the views and claims made about AI risks, limitations, and hidden costs.


## AI hallucinations

AI systems can generate fluent but false outputs, including fabricated citations, invented case law, and incorrect factual claims.[cite:31][cite:34][cite:37]

| Topic | Verified point | Source |
|---|---|---|
| Legal hallucinations in general chatbots | Stanford-related reporting says general-purpose chatbots produced hallucinations on 58% to 82% of legal queries.[cite:31][cite:34][cite:40] | [JD Supra](https://www.jdsupra.com/legalnews/do-legal-ai-tools-that-use-rag-still-2595011/), [Legal Dive](https://www.legaldive.com/news/legal-genai-tools-mislead-17-percent-of-time-stanford-HAI-hallucinations-incorrect-law-citations/), [Stanford RegLab](https://reglab.stanford.edu/publications/hallucination-free-assessing-the-reliability-of-leading-ai-legal-research-tools/) |
| Specialized legal AI tools | Leading legal AI research tools still hallucinated between 17% and 33% of the time.[cite:37][cite:40] | [Stanford RegLab](https://reglab.stanford.edu/publications/hallucination-free-assessing-the-reliability-of-leading-ai-legal-research-tools/) |
| Hallucination case tracking | Damien Charlotin maintains a public database of AI hallucination cases in law, and secondary reporting says it passed 1,400 entries by early 2026.[cite:45][cite:42] | [Damien Charlotin database](https://www.damiencharlotin.com/hallucinations/), [GC.ai](https://gc.ai/blog/ai-legal-cases) |
| Public failures | Real-world misuse includes fake citations and false legal authorities presented as genuine.[cite:42][cite:45] | [GC.ai](https://gc.ai/blog/ai-legal-cases), [Damien Charlotin database](https://www.damiencharlotin.com/hallucinations/) |

## Bias and discrimination

Bias remains one of the clearest hidden traps in AI because models and screening systems can inherit or amplify patterns from historical data.[cite:32][cite:2][cite:3]

| Topic | Verified point | Source |
|---|---|---|
| Workday lawsuit | A federal court allowed a nationwide collective action over alleged age discrimination related to Workday’s AI hiring tools in 2025.[cite:32] | [Holland & Knight](https://www.hklaw.com/en/insights/publications/2025/05/federal-court-allows-collective-action-lawsuit-over-alleged) |
| Disparate impact theory | Reporting says the court recognized a plausible ADEA disparate-impact claim against Workday’s platform.[cite:32][cite:38] | [Holland & Knight](https://www.hklaw.com/en/insights/publications/2025/05/federal-court-allows-collective-action-lawsuit-over-alleged), [HR Dive](https://www.hrdive.com/news/workday-partial-loss-judge-refuses-claims-dismissal/814227/) |
| Broader ethical bias concerns | UNESCO documents discriminatory outcomes, embedded bias, and lack of neutrality in AI systems.[cite:3] | [UNESCO](https://www.unesco.org/en/artificial-intelligence/recommendation-ethics/cases) |
| Sector harms | A peer-reviewed review on AI drawbacks discusses bias, opacity, and unfair outcomes in sensitive settings such as healthcare.[cite:2] | [PMC review](https://pmc.ncbi.nlm.nih.gov/articles/PMC9908503/) |

## Environmental and energy costs

The environmental cost of AI is increasingly tied to data-centre electricity demand, water use, hardware manufacturing, and emissions from accelerated compute.[cite:36][cite:39][cite:29]

| Topic | Verified point | Source |
|---|---|---|
| Data-centre electricity demand | The IEA projects global data-centre electricity use could reach about 945 TWh by 2030, more than double 2024 levels.[cite:33][cite:36][cite:39] | [Economic Times summary of IEA](https://energy.economictimes.indiatimes.com/news/power/global-electricity-demand-from-ai-data-centres-set-to-cross-945-twh-by-2030-iea/120193101), [Nature](https://www.nature.com/articles/d41586-025-01113-z), [EU Energy](https://energy.ec.europa.eu/news/focus-data-centres-energy-hungry-challenge-2025-11-17_en) |
| Current baseline | Data centres used about 415 TWh in 2024, roughly 1.5% of global electricity consumption.[cite:36][cite:39] | [Nature](https://www.nature.com/articles/d41586-025-01113-z), [EU Energy](https://energy.ec.europa.eu/news/focus-data-centres-energy-hungry-challenge-2025-11-17_en) |
| Broader environmental impact | Generative AI has environmental impacts across both training and inference, including electricity and water use.[cite:29] | [MIT News](https://news.mit.edu/2025/explained-generative-ai-environmental-impact-0117) |

## Copyright and privacy risks

Copyright and privacy risks are central AI concerns because model training often depends on large datasets collected from public web content, licensed sources, user interactions, or scraped material, and these practices are being tested in court.[cite:47][cite:41][cite:2]

| Topic | Verified point | Source |
|---|---|---|
| New York Times v. OpenAI/Microsoft | Reuters reports that The New York Times sued OpenAI and Microsoft in 2023, alleging the use of millions of Times articles without permission for training, and that the case survived at least in part in 2025.[cite:47][cite:50] | [Reuters 2025](https://www.reuters.com/legal/litigation/judge-explains-order-new-york-times-openai-copyright-case-2025-04-04/), [Reuters 2023 archive](https://web.archive.org/web/20231230163134/https:/www.reuters.com/legal/transactional/ny-times-sues-openai-microsoft-infringing-copyrighted-works-2023-12-27/) |
| Andersen v. Stability AI | Artists sued Stability AI, Midjourney, and DeviantArt over copyrighted works in training datasets, and some copyright claims were allowed to proceed.[cite:41] | [NYU JIPEL](https://jipel.law.nyu.edu/andersen-v-stability-ai-the-landmark-case-unpacking-the-copyright-risks-of-ai-image-generators/) |
| Early court posture | Reporting in 2023 said the judge dismissed many claims but allowed one copyright count against Stability AI related to registered works to move forward.[cite:44] | [Artnet](https://news.artnet.com/art-world/federal-judge-sides-with-ai-companies-in-artists-copyright-dispute-2387654) |
| Privacy example | A peer-reviewed review discusses healthcare-data privacy concerns and references the transfer of 1.6 million patient records without consent in the Google DeepMind case.[cite:2] | [PMC review](https://pmc.ncbi.nlm.nih.gov/articles/PMC9908503/) |

## Overreliance and skill erosion

Another hidden trap is cognitive offloading: users may trust AI outputs too quickly, verify less, and rely less on independent reasoning.[cite:43][cite:46][cite:49]

| Topic | Verified point | Source |
|---|---|---|
| Cognitive engagement | A 2025 study summary reports excessive reliance on generative AI reduced EEG activation, recall accuracy, and critical-thinking scores.[cite:43] | [Ideas/RePEc abstract](https://ideas.repec.org/a/bhx/ojtjts/v7y2025i6p18-34id3185.html) |
| Brain activity in writing tasks | Secondary reporting on an MIT Media Lab study says users writing with ChatGPT showed the lowest brain engagement of the tested groups.[cite:46][cite:49] | [ANSI summary](https://blog.ansi.org/ansi/is-ai-eroding-our-critical-thinking-skills/), [EdUHK summary](https://flassnews.eduhk.hk/preview_article/July_2025_ISSUE_12/Be%20wise%20when%20the%20AI%20threat%20looms%20large) |

## Job displacement and economic effects

AI can automate tasks and reshape work, but claims in this area should be tied to focused labor-market sources such as ILO, OECD, IMF, WEF, or Stanford HAI before being used as hard evidence.[cite:27]

## Public-use wording guidance

The following claims are well-supported for public-facing content.[cite:31][cite:32][cite:36][cite:47]

- Legal AI tools still hallucinate, even when they are specialized.[cite:37][cite:40]
- AI hiring systems can create legal exposure through disparate impact.[cite:32][cite:38]
- AI’s environmental cost is rising fast; the IEA says data-centre electricity demand could reach about 945 TWh by 2030.[cite:33][cite:36]
- Major publishers and artists are actively challenging AI training practices in court.[cite:41][cite:47]
- Heavy AI reliance may reduce cognitive engagement and verification behavior, though wording should stay cautious when citing early-stage studies.[cite:43][cite:46]

## Source-quality notes

For the strongest public documentation, prefer court filings, peer-reviewed papers, government or intergovernmental reports, UNESCO, IEA, MIT, Stanford, and Reuters over commentary blogs or unsourced summaries.[cite:2][cite:3][cite:36][cite:47]
