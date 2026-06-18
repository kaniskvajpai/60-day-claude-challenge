# Day 5: Comparing Prompting Strategies — Context Engineering Exercise

## Overview

In this exercise, you will run two different prompts through an LLM (Claude), observe the outputs, and analyze how subtle differences in prompt structure affect the quality and nature of the response. This demonstrates a core principle of **context engineering**: the information you place in the context window — and *how* you structure it — fundamentally shapes the model's output.

---

## Objective

- Understand how **prompt structure** influences LLM behavior.
- Compare a **generic/minimal prompt** vs. a **structured, role-and-context-rich prompt**.
- Observe differences in tone, depth, format, and usefulness of responses.
- Reflect on how context engineering principles apply beyond simple prompting.

---

## Instructions

### Step 1: Read the Resources

Before starting, read the following foundational resources on Context Engineering:

- [Effective Context Engineering for AI Agents — Anthropic](https://www.anthropic.com/engineering/effective-context-engineering-for-ai-agents)
- [Context Engineering Guide — PromptingGuide.ai](https://www.promptingguide.ai/guides/context-engineering-guide)
- [The New Skill in AI is Not Prompting, It's Context Engineering — Phil Schmid](https://www.philschmid.de/context-engineering)

### Step 2: Open a New Conversation

Start a fresh conversation with Claude (or your chosen LLM) to avoid any carryover context from previous chats.

### Step 3: Run Prompt A

Copy and paste the following prompt exactly as written:

> **Prompt A:**
>
> *Explain how context engineering works in AI.*

**Generate the output.** Save or screenshot the result for later comparison.

### Step 4: Start a New Conversation

Open a **fresh** new conversation with the LLM.

### Step 5: Run Prompt B

Copy and paste the following prompt, replacing the bracketed `[...]` information with your own details:

> **Prompt B:**
>
> *You are an expert AI educator and technical writer with 10+ years of experience explaining complex AI concepts to non-technical audiences.*
>
> *Your task is to explain the concept of "context engineering" in AI systems. Context engineering refers to the strategies for curating and maintaining the optimal set of tokens (information) during LLM inference — including system prompts, retrieved documents, conversation history, and tool definitions.*
>
> *Your audience is **[your role, e.g., "a product manager with basic AI knowledge"]** who needs to understand:*
> - *What context engineering is*
> - *How it differs from prompt engineering*
> - *Why it matters for building reliable AI applications*
>
> *Structure your response with clear headings and a practical example. Use plain language — avoid jargon without explanation.*

**Generate the output.** Save or screenshot the result.

### Step 6: Compare the Outputs

Place both outputs side by side and observe the differences.

---

## Observation Framework

Use this table to systematically compare the two outputs:

| Dimension | Prompt A Output | Prompt B Output |
|---|---|---|
| **Tone** | | |
| **Depth of explanation** | | |
| **Structure (headings, lists, etc.)** | | |
| **Use of examples** | | |
| **Audience awareness** | | |
| **Clarity for a beginner** | | |
| **Length / Detail** | | |
| **Accuracy / correctness** | | |

### Questions for Reflection

1. **Which output was more immediately useful?** Why?
2. **What specific elements in Prompt B caused the difference?** (Consider: role assignment, audience specification, structural guidance, definition provision)
3. **How does this exercise demonstrate context engineering vs. prompt engineering?** (Prompt engineering optimizes the input text; context engineering considers the full context window — role, audience, format, prior knowledge.)
4. **If you were building an AI-powered application, which approach would you use for your system prompt?** Why?
5. **What additional context could you add to Prompt B to make the output even better?**

---

## Key Takeaways

| Concept | Explanation |
|---|---|
| **Prompt engineering** | Optimizing the wording of the user's input to get a better response. |
| **Context engineering** | Curating **everything** in the context window — system instructions, retrieved documents, conversation history, tool descriptions, and user input — to shape model behavior. |
| **Role assignment** | Giving the model a persona (e.g., "expert educator") activates relevant knowledge and adjusts tone appropriately. |
| **Audience specification** | Telling the model *who* it's talking to changes depth, vocabulary, and structure. |
| **Structural cues** | Requesting headings, examples, or a specific format guides the model's output organization. |

> **"Prompt engineering is asking the right question. Context engineering is building the right mind."**

---

## Bonus: Try Your Own Variations

Once you've completed the comparison, experiment further:

1. **Swap the audience** — change Prompt B's audience to "a 12-year-old" or "a senior software engineer."
2. **Remove the definition** — see what happens when you don't provide the definition of context engineering in the prompt.
3. **Add constraints** — e.g., "Respond in exactly 5 bullet points" or "Do not use technical terms."
4. **Add few-shot examples** — provide an example of a good explanation for a different topic to prime the model.

---

## Further Reading

- [Context Engineering vs. Prompt Engineering — Elastic](https://www.elastic.co/search-labs/blog/context-engineering-vs-prompt-engineering)
- [LLM Context Engineering Bootcamp (YouTube Playlist)](https://www.youtube.com/playlist?list=PLPTV0NXA_ZSj-E8A1DBvbWIYGxC46u-Hd)
- [Five Levels of Context Engineering — LinkedIn (Vitaly Friedman)](https://www.linkedin.com/posts/vitalyfriedman_five-levels-of-context-engineering-how-activity-7439221673633030144-Citz)

---

*Last updated: June 18, 2026*
claude chat link 1 :https://claude.ai/share/efd7c919-726b-46c1-bd1c-e186975451b8
clude chat link 2:https://claude.ai/share/46ef5b3f-0c3f-44e0-b18f-b523e101ff31
