# conversational-search-trust-review

A curated, annotated reading list on **human trust in conversational AI search agents** — how much people trust the answers they get from LLM-powered search, and how the interface delivering those answers changes that trust.

## What this list is for

This repository backs our lab's new research direction on trust in conversational AI search, and was assembled as the shared reading list for the group meeting. It is meant to be skimmed in one sitting before the meeting and argued with during it: the anchor paper defines the framing, and the remaining five papers each supply one piece the anchor leaves out — population-scale causal evidence, actual verification behaviour, the underlying mental models, and a boundary condition on embodiment.

## The reading list

Start with [`ANNOTATED_BIBLIOGRAPHY.md`](ANNOTATED_BIBLIOGRAPHY.md). One section per paper, anchor paper first, each with the arXiv ID, full title, authors, a summary of what the study did and found (written from the full text, not the abstract), and a note on why it matters for our project.

| # | Paper | arXiv ID | Role in the list |
|---|-------|----------|------------------|
| 1 | From Search Agents to Dissemination Interfaces: Understanding Human Trust in Health Information from Conversational Search | 2608.21177 | **Anchor** — agents vs. dissemination interfaces, two mixed-methods studies |
| 2 | Trusting the Search: Unraveling Human Trust in Health Information from Google and ChatGPT | 2403.09987 | Companion/predecessor study; qualitative trust factors |
| 3 | Human Trust in AI Search: A Large-Scale Experiment | 2504.06435 | Population-scale causal test of interface features on trust |
| 4 | The Decision to Verify: How Warmth and User Characteristics Shape Reliance on Conversational Agents for Information Search | 2605.28498 | Behavioural consequence: who actually checks answers |
| 5 | Understanding Mental Models of Generative Conversational Search and The Effect of Interface Transparency | 2506.03807 | Mechanism: user mental models and transparency vectors |
| 6 | To Embody or Not: The Effect Of Embodiment On User Perception Of LLM-based Conversational Agents | 2506.02514 | Boundary condition: embodiment vs. sycophancy |

## Anchor paper

**From Search Agents to Dissemination Interfaces: Understanding Human Trust in Health Information from Conversational Search** — arXiv:[2608.21177](https://arxiv.org/abs/2608.21177) [cs.HC], by Xin Sun, Rongjun Ma, Xiaochang Zhao, Janne Lindqvist, Jan de Wit, Zhuying Li, Abdallah El Ali and Jos A. Bosch. The manuscript states it has been accepted for publication in the journal *Behaviour & Information Technology (BIT)*.

## Repository structure

- [`ANNOTATED_BIBLIOGRAPHY.md`](ANNOTATED_BIBLIOGRAPHY.md) — the shareable annotated reading list (one section per paper, anchor first).
- `papers/` — per-paper reading notes, one file per paper, named by arXiv ID (e.g. `papers/2608.21177.md`).
- Issues — open research questions for the lab meeting, plus earlier per-paper digest issues with follow-up sub-issues for the next steps each paper suggests.

## Why this project

LLM-powered conversational agents are replacing list-of-links search as the default way many people look up information. How much people *trust* that information — and whether the interface that delivers it (text, speech, embodied) changes that trust — is the core question this review follows.
