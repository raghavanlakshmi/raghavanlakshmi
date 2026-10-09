### Hi, I'm Lakshmi Raghavan 👋

I build **evaluated, safety-first AI systems for healthcare** — agents and retrieval pipelines that show
their evidence, measure their failures, and keep a human in the loop where decisions matter.

What I care about: designing for the failure case first, measuring before claiming, and saying plainly
what didn't work.

---

#### Projects

| Project | What it is | Headline result |
|---|---|---|
| **[TrialMatch AI](https://github.com/raghavanlakshmi/TrialMatch_AI)** · [live demo](https://trialmatch-ai.streamlit.app/) | Clinical-trial prescreening: patient documents → source-verified facts → criterion-by-criterion assessment for a human reviewer | 97% criterion accuracy, **zero unsafe clearances**; 192 tests |
| **[VerdeBowl](https://github.com/raghavanlakshmi/VerdeBowl)** | Red-teamed an LLM support bot, then hardened it across five defense layers | Attack success **10.4% → 1.9%**; IDOR fixed in the backend, not the prompt |
| **[Nexus](https://github.com/raghavanlakshmi/nexus)** | 5-agent LangGraph co-pilot that turns a discharge summary into a 30-day recovery plan | Tiered escalation with human approval for clinical messages |
| **[Hub](https://github.com/raghavanlakshmi/hub)** | Nexus collapsed to two agents to measure what multi-agent orchestration really costs | Same quality and cost with 40% fewer graph nodes; escalation accuracy 90% → 96.7% |
| **[nexus-hub-eval](https://github.com/raghavanlakshmi/nexus-hub-eval)** | 30-case golden-dataset evaluation of both systems with LangSmith and an LLM judge | Found the real risk: keyword triage under-tiers paraphrased emergencies |
| **[escalation-classifier-finetune](https://github.com/raghavanlakshmi/escalation-classifier-finetune)** | LoRA fine-tune of Qwen3-1.7B to replace the LLM triage call | 88.2% accuracy, 93.3% emergency recall with a keyword safety floor |

Nexus → Hub → eval → fine-tune is one story: build a multi-agent system, measure what the
architecture actually buys, find where the risk really is, then make the fix cheaper.

---

#### Toolbox

- **Agents & LLMs:** LangGraph · Claude · OpenAI · Nebius · LoRA fine-tuning (LLaMA Factory, Qwen3)
- **Retrieval:** Chroma · Pinecone · BM25 · reciprocal rank fusion · sentence-transformers
- **Evaluation & safety:** LangSmith · LLM-as-judge · golden datasets · promptfoo red-teaming · guardrails
- **Building:** Python · Streamlit · Pydantic · pytest · GitHub Actions

📫 [LinkedIn](https://www.linkedin.com/in/lakshmi-raghavan)
