![twin_flame](https://github.com/user-attachments/assets/07ed4b8d-ae1b-4117-ae6e-05d7013133fa)

## 1️⃣ The WFGY ecosystem

> We build **WFGY**, an open-source reasoning and debugging ecosystem for AI systems.  
> One lineage, multiple public entry points. Not a random collection of tools.
>
> Over a year of focused development, now fully open sourced under the **MIT License**.

### Quick navigation

* ⭐️ **[Problem Map](https://github.com/onestardao/WFGY/blob/main/ProblemMap/README.md)**: fastest practical entry for broken RAG and agent pipelines.
* ⭐️ **[Global Debug Card](https://github.com/onestardao/WFGY/blob/main/ProblemMap/wfgy-rag-16-problem-map-global-debug-card.md)**: image-first triage layer on top of the Problem Map.
* ⭐️ **[Ecosystem Map](https://github.com/onestardao/WFGY/blob/main/ECOSYSTEM_MAP.md)**: canonical map of how the public WFGY system fits together.
* ⭐️ **[WFGY 3.0](https://github.com/onestardao/WFGY/blob/main/TensionUniverse/EventHorizon/README.md)**: frontier reasoning and long-horizon evaluation surface.

---

## 2️⃣ Who is WFGY for?

> WFGY is for people who need structured debugging and serious reasoning, not just another prompt recipe.
>
> - **RAG and agent teams**: pipelines run, infra looks healthy, but answers are still wrong or unstable.
> - **Infra and platform owners**: you need a way to audit reasoning behavior across models, tenants, or deployments.
> - **Researchers and evaluation teams**: you study long-horizon reasoning, safety, or stress tests and want concrete observables.
> - **Founders, PMs, and domain experts**: you hold a few difficult questions in finance, climate, AI, or society and want to see how a structured system treats them.
>
> If you do not fit neatly into any of the above, you can still start with the **Problem Map** or the **Global Debug Card** and use them as diagnostic checklists for your own systems.

### Entry points

* ⭐️ **[WFGY RAG 16 Problem Map](https://github.com/onestardao/WFGY/blob/main/ProblemMap/README.md)**: 16-problem RAG failure checklist and fix map for broken RAG and agent pipelines.
* ⭐️ **[WFGY Global Debug Card](https://github.com/onestardao/WFGY/blob/main/ProblemMap/wfgy-rag-16-problem-map-global-debug-card.md)**: image-first triage layer for diagnosing a single failing run.
* ⭐️ **[WFGY 1.0](https://github.com/onestardao/WFGY/blob/main/legacy/README.md)**: earliest public conceptual foundation.
* ⭐️ **[WFGY 2.0](https://github.com/onestardao/WFGY/blob/main/core/README.md)**: current reasoning and diagnostic kernel.
* ⭐️ **[WFGY 3.0](https://github.com/onestardao/WFGY/blob/main/TensionUniverse/EventHorizon/README.md)**: frontier TXT-based reasoning and evaluation surface.

---

## 3️⃣ Why WFGY looks like an ecosystem

> WFGY is not a single page or a single claim.
>
> The public system is easiest to read as:
>
> - **one version lineage**: WFGY 1.0 → WFGY 2.0 → WFGY 3.0
> - **one strong practical wedge**: Problem Map, Global Debug Card, Semantic Clinic, and Global Fix Map
> - **one wider application and evaluation surface**: TXTOS, related modules, and WFGY 3.0
> - **one public proof and collaboration layer**: Adopters, Case Evidence, Recognition Map, Evidence Timeline, Work with WFGY, and Support
>
> The goal is simple: make reasoning failures visible, reproducible, and fixable.

If WFGY helps your workflow or thinking, a star on the repo helps others discover it.

---

## 4️⃣ Public proof and ecosystem integration

* ⭐️ **[Adopters](https://github.com/onestardao/WFGY/blob/main/ADOPTERS.md)**: shortest public adoption summary.
* ⭐️ **[Case Evidence](https://github.com/onestardao/WFGY/blob/main/CASE_EVIDENCE.md)**: interpretation layer explaining what those integrations imply in real systems.
* ⭐️ **[Recognition Map](https://github.com/onestardao/WFGY/blob/main/recognition/README.md)**: broader ecosystem record of integrations, citations, curated lists, and public mentions.
* ⭐️ **[Evidence Timeline](https://github.com/onestardao/WFGY/blob/main/EVIDENCE_TIMELINE.md)**: historical timeline of how WFGY became public, usable, and externally legible.

Representative integrations:

| Project | Stars | Segment | How it uses WFGY ProblemMap | Proof (PR / doc) |
| --- | --- | --- | --- | --- |
| [RAGFlow](https://github.com/infiniflow/ragflow) | [![GitHub Repo stars](https://img.shields.io/github/stars/infiniflow/ragflow?style=social)](https://github.com/infiniflow/ragflow) | Mainstream RAG engine | Introduced a RAG failure modes checklist guide in the docs, adapted from the WFGY 16-problem map for step-by-step RAG pipeline diagnostics. | [PR #13204](https://github.com/infiniflow/ragflow/pull/13204) |
| [LlamaIndex](https://github.com/run-llama/llama_index) | [![GitHub Repo stars](https://img.shields.io/github/stars/run-llama/llama_index?style=social)](https://github.com/run-llama/llama_index) | Mainstream RAG infra | Integrates the WFGY 16-problem RAG failure checklist into official RAG troubleshooting docs as a structured failure-mode reference. | [PR #20760](https://github.com/run-llama/llama_index/pull/20760) |
| [FlashRAG](https://github.com/RUC-NLPIR/FlashRAG) | [![GitHub Repo stars](https://img.shields.io/github/stars/RUC-NLPIR/FlashRAG?style=social)](https://github.com/RUC-NLPIR/FlashRAG) | Academic lab / RAG research toolkit | Adapts the WFGY ProblemMap as a structured RAG failure checklist in documentation to support reproducible debugging and systematic failure-mode reasoning. | [PR #224](https://github.com/RUC-NLPIR/FlashRAG/pull/224) |
| [ToolUniverse (Harvard MIMS Lab)](https://github.com/mims-harvard/ToolUniverse) | [![GitHub Repo stars](https://img.shields.io/github/stars/mims-harvard/ToolUniverse?style=social)](https://github.com/mims-harvard/ToolUniverse) | Academic lab / tools | Provides a `WFGY_triage_llm_rag_failure` tool that wraps the 16-mode map for incident triage. | [PR #75](https://github.com/mims-harvard/ToolUniverse/pull/75) |
| [LightAgent](https://github.com/wanxingai/LightAgent) | [![GitHub Repo stars](https://img.shields.io/github/stars/wanxingai/LightAgent?style=social)](https://github.com/wanxingai/LightAgent) | Agent framework | Incorporates WFGY ProblemMap concepts into docs via a “Multi-agent troubleshooting (failure map)” section for role drift and coordination failures. | [PR #24](https://github.com/wanxingai/LightAgent/pull/24#event-23265428525) |
| [Rankify (Univ. of Innsbruck)](https://github.com/DataScienceUIBK/Rankify) | [![GitHub Repo stars](https://img.shields.io/github/stars/DataScienceUIBK/Rankify?style=social)](https://github.com/DataScienceUIBK/Rankify) | Academic lab / system | Uses the 16 failure patterns in RAG and re-ranking troubleshooting docs. | [PR #76](https://github.com/DataScienceUIBK/Rankify/pull/76) |
| [Multimodal RAG Survey (QCRI LLM Lab)](https://github.com/llm-lab-org/Multimodal-RAG-Survey) | [![GitHub Repo stars](https://img.shields.io/github/stars/llm-lab-org/Multimodal-RAG-Survey?style=social)](https://github.com/llm-lab-org/Multimodal-RAG-Survey) | Academic lab / survey | Cites WFGY as a practical diagnostic resource for multimodal RAG. | [PR #4](https://github.com/llm-lab-org/Multimodal-RAG-Survey/pull/4) |

Most current public references point to the **WFGY ProblemMap / 16-problem failure checklist** line.  
A smaller but growing set also uses **WFGY 3.0** as a long-horizon, TXT-based reasoning and evaluation surface.

This does not mean every project uses the full WFGY ecosystem.  
In most cases, WFGY appears first as a ProblemMap-style diagnostic layer for RAG and agent pipelines.

---

## 5️⃣ Work with or support WFGY

> If you maintain an AI system, research project, or infra platform and want to explore collaboration around WFGY, start here:
>
> * ⭐️ **[Work with WFGY](https://github.com/onestardao/WFGY/blob/main/WORK_WITH_WFGY.md)**: entry point for pilots, audits, and structured collaboration.
> * ⭐️ **[Pilot Offer One-Pager](https://github.com/onestardao/WFGY/blob/main/PILOT_OFFER_ONE_PAGER.md)**: compact view of what a WFGY pilot can look like.
> * ⭐️ **[Sample Deliverable](https://github.com/onestardao/WFGY/blob/main/SAMPLE_DELIVERABLE.md)**: sample structure of a WFGY pilot return package.
>
> If you want to help sustain the public ecosystem instead:
>
> * ⭐️ **[Support WFGY](https://github.com/onestardao/WFGY/blob/main/SUPPORT.md)**: support the continued development of the public WFGY ecosystem.
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
