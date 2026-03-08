![twin_flame](https://github.com/user-attachments/assets/07ed4b8d-ae1b-4117-ae6e-05d7013133fa)

## 1️⃣ The WFGY ecosystem

> We build **WFGY**, an open-source reasoning and debugging engine for AI systems.  
> One architecture, different depths. Not a random collection of tools.
> 
> Over a year of focused development, now fully open sourced under the **MIT License**.

---

## 2️⃣ Who is WFGY for?

> WFGY is for people who need structured debugging and serious reasoning, not just another prompt recipe.
>
> - **RAG and agent teams**: pipelines run, infra looks healthy, but answers are still wrong or unstable.
> - **Infra and platform owners**: you need a way to audit reasoning behavior across models, tenants, or deployments.
> - **Researchers and evaluation teams**: you study long-horizon reasoning, safety, or stress tests and want concrete observables.
> - **Founders, PMs, and domain experts**: you hold a few high-tension questions in finance, climate, AI, or society and want to see how a structured engine treats them.
>
> If you do not fit neatly into any of the above, you can still start with the **Problem Map** or the **Global Debug Card** and use them as diagnostic checklists for your own systems.

### Entry points (choose your depth)

* ⭐️ **[WFGY RAG 16 Problem Map](https://github.com/onestardao/WFGY/blob/main/ProblemMap/README.md)**: 16-problem RAG failure checklist and fix map for broken RAG and agent pipelines.
* ⭐️ **[WFGY Global Debug Card](https://github.com/onestardao/WFGY/blob/main/ProblemMap/wfgy-rag-16-problem-map-global-debug-card.md)**: image-first triage layer on top of the 16 Problem Map.
* ⭐️ **[WFGY 3.0 · Frontier TXT engine](https://github.com/onestardao/WFGY/blob/main/TensionUniverse/EventHorizon/README.md)**: TXT-based tension reasoning engine built on a 131 S-class backbone.

---

## 3️⃣ Philosophy: fix-first reasoning

> Unlike traditional tools, **WFGY is an ecosystem of fix-first reasoning components**.
>
> Every artifact here started from a real failure:
>
> - a broken RAG pipeline that refused to stabilize,
> - an agent stack that looked fine at the infra level but still collapsed in edge cases,
> - long-horizon questions that generic benchmarks do not touch.
>
> The goal is simple: make reasoning failures visible, reproducible, and fixable.
>
> If WFGY helps your workflow or thinking, a star on the repo helps others discover it.

---

## 4️⃣ Recognition and ecosystem integration

* ⭐️ **[WFGY Adopters](https://github.com/onestardao/WFGY/blob/main/ADOPTERS.md)**: shortest public adoption summary of where the WFGY Problem Map has been integrated.
* ⭐️ **[WFGY Case Evidence](https://github.com/onestardao/WFGY/blob/main/CASE_EVIDENCE.md)**: interpretation layer explaining what those integrations imply for real systems.
* ⭐️ **[WFGY Recognition Map](https://github.com/onestardao/WFGY/blob/main/recognition/README.md)**: continuously maintained ecosystem record of curated lists, academic references, and public mentions.

> As of 2026-03, the **WFGY RAG 16 Problem Map** line has been adopted or referenced by **20+ frameworks, academic labs, and curated lists** in the RAG and agent ecosystem.

Some representative integrations:

| Project | Stars | Segment | How it uses WFGY ProblemMap | Proof (PR / doc) |
| --- | --- | --- | --- | --- |
| [RAGFlow](https://github.com/infiniflow/ragflow) | [![GitHub Repo stars](https://img.shields.io/github/stars/infiniflow/ragflow?style=social)](https://github.com/infiniflow/ragflow) | Mainstream RAG engine | Introduced a RAG failure modes checklist guide in the docs, adapted from the WFGY 16-problem map for step-by-step RAG pipeline diagnostics. | [PR #13204](https://github.com/infiniflow/ragflow/pull/13204) |
| [LlamaIndex](https://github.com/run-llama/llama_index) | [![GitHub Repo stars](https://img.shields.io/github/stars/run-llama/llama_index?style=social)](https://github.com/run-llama/llama_index) | Mainstream RAG infra | Integrates the WFGY 16-problem RAG failure checklist into official RAG troubleshooting docs as a structured failure-mode reference. | [PR #20760](https://github.com/run-llama/llama_index/pull/20760) |
| [FlashRAG](https://github.com/RUC-NLPIR/FlashRAG) | [![GitHub Repo stars](https://img.shields.io/github/stars/RUC-NLPIR/FlashRAG?style=social)](https://github.com/RUC-NLPIR/FlashRAG) | Academic lab / RAG research toolkit | Adapts the WFGY ProblemMap as a structured RAG failure checklist in documentation to support reproducible debugging and systematic failure-mode reasoning. | [PR #224](https://github.com/RUC-NLPIR/FlashRAG/pull/224) |
| [ToolUniverse (Harvard MIMS Lab)](https://github.com/mims-harvard/ToolUniverse) | [![GitHub Repo stars](https://img.shields.io/github/stars/mims-harvard/ToolUniverse?style=social)](https://github.com/mims-harvard/ToolUniverse) | Academic lab / tools | Provides a `WFGY_triage_llm_rag_failure` tool that wraps the 16-mode map for incident triage. | [PR #75](https://github.com/mims-harvard/ToolUniverse/pull/75) |
| [LightAgent](https://github.com/wanxingai/LightAgent) | [![GitHub Repo stars](https://img.shields.io/github/stars/wanxingai/LightAgent?style=social)](https://github.com/wanxingai/LightAgent) | Agent framework | Incorporates WFGY ProblemMap concepts into docs via a “Multi-agent troubleshooting (failure map)” section for role drift and coordination failures. | [PR #24](https://github.com/wanxingai/LightAgent/pull/24#event-23265428525) |
| [Rankify (Univ. of Innsbruck)](https://github.com/DataScienceUIBK/Rankify) | [![GitHub Repo stars](https://img.shields.io/github/stars/DataScienceUIBK/Rankify?style=social)](https://github.com/DataScienceUIBK/Rankify) | Academic lab / system | Uses the 16 failure patterns in RAG and re-ranking troubleshooting docs. | [PR #76](https://github.com/DataScienceUIBK/Rankify/pull/76) |
| [Multimodal RAG Survey (QCRI LLM Lab)](https://github.com/llm-lab-org/Multimodal-RAG-Survey) | [![GitHub Repo stars](https://img.shields.io/github/stars/llm-lab-org/Multimodal-RAG-Survey?style=social)](https://github.com/llm-lab-org/Multimodal-RAG-Survey) | Academic lab / survey | Cites WFGY as a practical diagnostic resource for multimodal RAG. | [PR #4](https://github.com/llm-lab-org/Multimodal-RAG-Survey/pull/4) |

Most external references today point to the **WFGY ProblemMap / 16-problem failure checklist**.  
A smaller but growing set also uses **WFGY 3.0 · Singularity Demo** as a long-horizon, TXT-based stress test.

This does not mean every project is using the full WFGY ecosystem. In most cases, WFGY appears as a ProblemMap-style diagnostic layer for RAG and agent pipelines.

---

## 5️⃣ How to work with WFGY

> If you maintain an AI system, research project, or infra platform and want to explore collaboration around WFGY, start here:
>
> * ⭐️ **[Work with WFGY](https://github.com/onestardao/WFGY/blob/main/WORK_WITH_WFGY.md)**: entry point for pilots, audits, and ecosystem partnerships.
>
> You can also:
>
> - open an issue describing your system and current failure modes,
> - reference the matching **WFGY ProblemMap** number if you already know it,
> - or reach out via Discord for exploratory discussion.
>
> We are especially interested in:
>
> - **RAG or agent teams** testing WFGY diagnostics in production-like environments,
> - **research groups** designing stress tests or observables on the 131-problem atlas,
> - **platform owners** exposing WFGY-style diagnostics to their users.
>
> The long-term goal is simple: make reasoning and debugging layers a normal, visible part of AI systems.
