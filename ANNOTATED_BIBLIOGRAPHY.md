# Annotated Bibliography — Human Trust in Conversational AI Search Agents

**Curated for:** the lab's new research direction on how much people trust the answers they get from conversational AI search agents.
**Prepared:** for Friday's group meeting.
**Selection criteria:** empirical studies (user studies / experiments) on trust, reliance, or perceived credibility in LLM-based or conversational search, including how the presentation interface shapes those perceptions. Every entry below was read from the full text (not abstract-only). Titles, author lists and arXiv IDs are reproduced exactly as returned by the arXiv lookups.

---

## 1. From Search Agents to Dissemination Interfaces: Understanding Human Trust in Health Information from Conversational Search *(anchor paper)*

- **arXiv ID:** 2608.21177 (v1) — <https://arxiv.org/abs/2608.21177>
- **Full title:** From Search Agents to Dissemination Interfaces: Understanding Human Trust in Health Information from Conversational Search
- **Authors:** Xin Sun, Rongjun Ma, Xiaochang Zhao, Janne Lindqvist, Jan de Wit, Zhuying Li, Abdallah El Ali, Jos A. Bosch
- **Venue note:** the manuscript states it has been accepted for publication in the journal *Behaviour & Information Technology (BIT)*.

**What the study did and found.** This paper asks how much people trust health information delivered by LLM-powered conversational search, and how the interface disseminating it changes that trust, framing the work with the MAIN model of trust in technology. It integrates two mixed-methods studies, each a lab session plus semi-structured interviews. Study 1 (N=21, within-subjects, order counterbalanced) compared Google against ChatGPT (GPT-4, no web browsing) across three types of health search tasks — general health, treatment-related, and symptoms-and-diagnosis. Participants trusted health information from ChatGPT significantly more than from Google (trust in information M=4.05, SD=.47 vs. M=3.77, SD=.64; trust in the agent M=3.58 vs. 3.31), and the type of health question had no significant effect, so the conversational advantage held across all task types. Strikingly, trust in the information correlated with trust in the agent only for Google — for ChatGPT the two were decoupled, meaning users judged synthesized answers on intrinsic presentation (logical flow, professional wording, tailoring) rather than on the agent's reputation. Study 2 (N=20) then held the LLM constant (GPT-4o for all conditions) and varied only the dissemination interface: a text-based web chatbot, a speech-based Amazon Echo Dot, and a custom embodied agent with a physical body and smartphone face. Trust in information differed significantly across interfaces, with the text-based CUI rated most trustworthy (4.19 vs. 4.13 speech and 4.00 embodied), and usability fully mediated the interface-to-trust relationship. Interviews across both studies identified the trust drivers — source credibility, participants' search autonomy (moderated by prior knowledge), familiarity, usability, interaction style, and modality — with voice and embodiment adding privacy concerns, authenticity doubts, and low tolerance for small glitches such as avatar expression lag.

**Why it matters for our project.** It is the anchor because it cleanly separates the two levers we care about — *who* generates the answer (search agent) versus *how* it is delivered (dissemination interface) — and shows both independently move trust, with the counterintuitive result that the plainest, most familiar text channel was the most trusted even when every interface spoke with the same model.

---

## 2. Trusting the Search: Unraveling Human Trust in Health Information from Google and ChatGPT

- **arXiv ID:** 2403.09987 (v1) — <https://arxiv.org/abs/2403.09987>
- **Full title:** Trusting the Search: Unraveling Human Trust in Health Information from Google and ChatGPT
- **Authors:** Xin Sun, Rongjun Ma, Xiaochang Zhao, Zhuying Li, Janne Lindqvist, Abdallah El Ali, Jos A. Bosch

**What the study did and found.** This is the predecessor study by the same group and is essentially the design behind the anchor paper's Study 1. It reports a mixed-methods, within-subjects lab study (N=21) exploring how interactions with two search agents — ChatGPT versus Google — across three health search tasks influence participants' trust judgments of both the search results and the agents themselves. Four key findings: (a) trust levels in ChatGPT were significantly higher than in Google for health information seeking; (b) there was a significant correlation between trust in the health-related information and trust in the search agent, but only for Google; (c) the type of search task did not affect participants' perceived trust; and (d) participants' prior knowledge, the style of information presentation, and the interactive manner of using the search agents were the key determinants of trust in health-related information. The authors highlight the role LLMs can play as "stepping stones" for further search rather than as final authorities, and contribute factors and considerations for reliable personal health information seeking in the age of generative AI.

**Why it matters for our project.** It gives us the published, standalone record of the agent-comparison experiment and supplies the qualitative code set (prior knowledge, presentation style, interaction manner) that any follow-up study of ours should either reuse or deliberately extend.

---

## 3. Human Trust in AI Search: A Large-Scale Experiment

- **arXiv ID:** 2504.06435 (v1) — <https://arxiv.org/abs/2504.06435>
- **Full title:** Human Trust in AI Search: A Large-Scale Experiment
- **Authors:** Haiwen Li, Sinan Aral

**What the study did and found.** This is the large-scale, causal counterpart to the small lab studies above. The authors first executed roughly 12,000 search queries across seven countries, generating approximately 80,000 real-time GenAI and traditional search results (11,372 queries and 79,604 results reported in the text), to document the extent of current global exposure to generative search. They then ran a preregistered, randomized experiment with 4,927 participants representative of the adult U.S. population, randomly assigning them to GenAI and traditional search conditions across nine predefined queries and presenting identical information as either generative or conventional search output, with design variations (reference links/citations, uncertainty highlighting, social feedback). Findings: participants trusted GenAI search less than traditional search on average; reference links and citations significantly increased trust in GenAI — even when those links and citations were incorrect or hallucinated; uncertainty highlighting, revealing GenAI's confidence in its own conclusions, made people less willing to trust and share generative information whether confidence was high or low; positive social feedback increased trust while negative feedback reduced it. Trust varied by topic and by users' demographics, education, industry employment, and GenAI experience, identifying which sub-populations are most vulnerable. Trust, in turn, predicted behavior: those who trusted GenAI more clicked more and spent less time evaluating results.

**Why it matters for our project.** It is the only study here that causally identifies *which interface features* move trust — and it shows the uncomfortable result that the most trusted affordances (citations, social proof) can raise trust in content that is actually wrong, which is precisely the miscalibration risk our lab direction is about.

---

## 4. The Decision to Verify: How Warmth and User Characteristics Shape Reliance on Conversational Agents for Information Search

- **arXiv ID:** 2605.28498 (v1) — <https://arxiv.org/abs/2605.28498>
- **Full title:** The Decision to Verify: How Warmth and User Characteristics Shape Reliance on Conversational Agents for Information Search
- **Authors:** Mert Yazan, Frederik Bungaran Ishak Situmeang, Suzan Verberne

**What the study did and found.** This paper examines overreliance under the hybrid search paradigm that now dominates — conversational AI plus web search simultaneously available. The authors ran a mixed-subjects question-answering experiment (n=199) in which participants interacted with a helper chatbot whose answer correctness was randomized (each participant saw correct answers about half the time), were randomly assigned to a warm or a neutral chatbot, and were free to use other sources. Rather than relying on self-reports, the authors tracked actual behaviour with a custom browser extension recording visited URLs, so verification could be measured in both frequency and type. Findings: reliance persisted despite users having access to both conversational AI and web search; the decision to verify was driven primarily by existing user perceptions (e.g., prior trust in chatbots) rather than by properties of the answer itself — thematic coding split participants into three groups, with 33 always fact-checking, 51 never mentioning fact-checking, and 115 conditional fact-checkers. Warm conversational style had an indirect but critical effect: it increased agreement with the chatbot specifically when the chatbot was incorrect. Consulting additional AI sources predicted higher accuracy, while traditional web search did not.

**Why it matters for our project.** It shows that simply giving users the tools to check an answer does not make them check it — trust is set by who the user is and how warm the agent sounds, not by the verifiability of the answer, which reframes our project from "how much do people trust" to "what determines whether trust ever gets tested."

---

## 5. Understanding Mental Models of Generative Conversational Search and The Effect of Interface Transparency

- **arXiv ID:** 2506.03807 (v1) — <https://arxiv.org/abs/2506.03807>
- **Full title:** Understanding Mental Models of Generative Conversational Search and The Effect of Interface Transparency
- **Authors:** Chadha Degachi, Samuel Kernan Freire, Evangelos Niforatos, Gerd Kortuem

**What the study did and found.** This study asks what users actually believe is happening inside a generative conversational search system, and whether making the system more transparent changes those beliefs. The authors ran a within-subject mixed-methods study (interview, think-aloud, and self-report survey) with 16 participants, who each completed four search tasks using four conversational interfaces graded from no transparency vectors to three, using three textual transparency vectors drawn from prior work: attribution (sources), query transformation, and confidence signals. The analysis found that most participants' mental models were too abstract to support explaining individual search instances, with many models inaccurate, incomplete, or both — participants could hold contradictory notions, for example conceptualising the information source as both an unstructured corpus and a structured database simultaneously. Amid that uncertainty, participants were very concerned with both real and imagined system limitations and attempted to compensate by constructing hybrid conversational-web search workflows of their own. Source attribution was the most strongly noticed transparency vector; participants reacted very positively to it and often used the links to verify output or explore further, though sources did not strongly convey the "online retrieval" function of the system.

**Why it matters for our project.** It offers a mechanism for the anchor paper's trust-decoupling finding — if users cannot form an accurate model of where an LLM answer comes from, their trust has nothing to attach to except surface presentation — and it tests the transparency interventions we would want to evaluate as trust-calibration levers.

---

## 6. To Embody or Not: The Effect Of Embodiment On User Perception Of LLM-based Conversational Agents

- **arXiv ID:** 2506.02514 (v2) — <https://arxiv.org/abs/2506.02514>
- **Full title:** To Embody or Not: The Effect Of Embodiment On User Perception Of LLM-based Conversational Agents
- **Authors:** Kyra Wang, Abhinaba Roy, Boon-Kiat Quek, Jessica Goh, Dorien Herremans

**What the study did and found.** This paper directly interrogates the embodiment condition from the anchor paper's Study 2. The authors conducted an exploratory, mixed-methods within-subjects study (N=20) on how users perceive LLM-based conversational agents in non-hierarchical cooperative tasks — survival-scenario prioritization tasks such as deciding which items to salvage after a crash — comparing an embodied agent against a non-embodied one, both powered by the identical locally-hosted LLaMA 3.1 8B Instruct model with identical prompts. The embodied agent used MetaHuman technology with NVIDIA Audio2Face for real-time lip-syncing; the non-embodied agent was a simple text interface. Results showed the non-embodied agent received significantly better quantitative appraisals for competence than the embodied agent despite identical reasoning capabilities (a large observed effect, r=.71, for competence), and qualitative feedback indicated many participants believed the embodied agent was more sycophantic. The authors argue that the typically positive impact of embodiment on perceived credibility can become detrimental in the presence of LLM sycophancy, because visual "humanization" raises authenticity expectations and heightens the perceived mismatch. They are explicit about limitations: the pilot's small sample (N=20), embodiment not crossed with scenario, sycophancy inferred rather than measured, a single avatar design, and recruitment from a single university in Singapore.

**Why it matters for our project.** It independently reproduces the anchor paper's counterintuitive embodied-interface result with a completely different task and model, and adds a candidate explanation — sycophancy amplified by anthropomorphism — that links directly to the warmth-driven overreliance found in the verification study.

---

## How the papers fit together

- **Anchor + companion (2608.21177, 2403.09987):** small-N, deep, mixed-methods evidence that conversational agents are trusted more than traditional search for health, and that the delivering interface (text > speech > embodied) shifts trust with the LLM held constant.
- **Causal large-N evidence (2504.06435):** identifies the specific interface features that move trust at population scale — and shows citations and social proof raise trust even in wrong answers.
- **Behavioural consequence (2605.28498):** shows that access to verification tools does not produce verification; prior dispositions and agent warmth drive reliance, including agreement with incorrect answers.
- **Mechanism (2506.03807):** explains why trust has nothing solid to attach to — user mental models of generative search are abstract, inaccurate, or contradictory — and tests transparency vectors as a remedy.
- **Boundary condition on "humanization" (2506.02514):** replicates the text-beats-embodied pattern and proposes sycophancy-plus-anthropomorphism as the driver.

Together they cover the agent, the interface, the population, the behaviour, and the mechanism — but leave the questions in the issue tracker open.
