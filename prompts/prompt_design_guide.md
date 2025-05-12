# How to Design Better Prompts for Structured Thinking

This guide helps you go beyond asking, "What prompt should I use?" and instead focus on:

- What decision are you trying to make?
- What evaluation criteria apply?
- What exactly should the LLM do?

This is designed to help you work with LLMs not just as content generators, but as structured decision support systems.

---

## Step 1: Define the Purpose – What are you trying to decide?

- What do you want to conclude, evaluate, or compare?
- What kind of answer are you expecting? (e.g., a winner, a recommended strategy, a risk level)

**Example questions:**
- Do we have a technical advantage over the competitor?
- Which technology approach is more scalable?

---

## Step 2: Define the Evaluation Criteria – What makes that decision valid?

- What are the measurable or interpretable elements to judge this decision?
- How can the information be broken down into categories or aspects?

**Example:**
- Divide into Functional Purpose, Technical Uniqueness, and Strategic Value.
- For each one, determine who has the advantage.

---

## Step 3: Define the LLM’s Role – What should the model actually do?

- Should the LLM make a decision, or just summarize facts?
- Should it follow a rule (e.g., majority rule)? Should it explain its reasoning?

**Example instructions:**
- For each aspect, the LLM must choose either "Samsung" or "Competitor".
- After three evaluations, the one with two or more wins is the final decision.
- The LLM should explain the reason in one sentence.

---

# Prompt Design Matrix

| Objective             | Evaluation Breakdown                        | Prompt Instruction Format                      |
|----------------------|---------------------------------------------|------------------------------------------------|
| Technical Superiority | Functional, Technical, Strategic aspects    | Choose winner per aspect, then majority rule   |
| Strategic Direction   | Tech summary + similarity + positioning     | Synthesize into 2–3 sentence recommendation     |
| Implementation Gap    | Aspect-by-aspect implementation comparison | Summarize technical differences holistically   |
| Risk Identification   | Similarity + value + strategic overlap      | Flag high-risk combinations; suggest response  |

---

## Question Refinement Examples

| Basic Question                         | Refined Prompt Thinking                  |
|----------------------------------------|------------------------------------------|
| What prompt should I use?              | What is the decision structure I want to guide the LLM to follow? |
| Should I ask for a summary?            | Should the LLM extract the contrast, then summarize or classify it by rule? |

---

This mindset leads to more consistent, explainable, and decision-oriented outputs from LLMs.
