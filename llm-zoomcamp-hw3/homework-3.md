# Homework 03 — Orchestration

Instructions: https://github.com/DataTalksClub/llm-zoomcamp/blob/main/cohorts/2026/03-orchestration/homework.md

## Questions

**1. After trying the same prompt in ChatGPT vs Kestra AI Copilot, what is the primary reason AI Copilot generates better Kestra flows? (1 point)**
- AI Copilot uses a more powerful model
- AI Copilot has access to current Kestra plugin documentation
- AI Copilot uses more tokens
- AI Copilot has internet access

**Answer:** AI Copilot has access to current Kestra plugin documentation

---

**2. The non-RAG response about Kestra 1.1 features is best described as: (1 point)**
- Accurate and specific, matching the actual release notes
- Vague, generic, or fabricated — the model guesses from training data
- Empty — the model refuses to answer without context
- Identical to the RAG version

**Answer:** Vague, generic, or fabricated — the model guesses from training data

---

**3. What is the approximate output token count for `multilingual_agent` when running with `summary_length = short`? (1 point)**
- 5-15 tokens
- 60-100 tokens
- 200-400 tokens
- 500+ tokens

**Answer:** 60-100 tokens

---

**4. With `summary_length = long`, roughly how many times more output tokens does `multilingual_agent` use compared to the short summary? (1 point)**
- About the same (within 20%)
- 2-5x more
- 10-20x more
- 50x more

**Answer:** 2-5x more

---

**5. After changing `english_brevity` to ask for 3 sentences instead of 1, how does the output token count compare to the original 1-sentence version? (1 point)**
- About the same (within 20%)
- 2-4x more
- 5-10x more
- 10x+ more

**Answer:** 2-4x more

---

**6. For production workflows requiring deterministic, repeatable results with strict compliance requirements, which approach is most appropriate? (1 point)**
- Always use AI agents for maximum flexibility and adaptation
- Use traditional task-based workflows for predictability and auditability
- Use only RAG without agents for better performance
- Use web search tools exclusively to ensure current data

**Answer:** Use traditional task-based workflows for predictability and auditability.