# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## AIM :
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

## SCENARIO :
You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

Accuracy

Coherence

Simplicity

Speed

User experience

---

## INTRODUCTION

Artificial Intelligence platforms such as ChatGPT, Gemini, Claude, and Copilot are widely used for text summarization tasks. Prompt engineering plays an important role in improving the quality of AI responses. Different prompting strategies can significantly affect how clearly and accurately information is summarized.

In this experiment, a technical article on “The Basics of Blockchain Technology” was summarized using multiple prompting techniques across different AI platforms to determine the best overall combination.

---

## AI PLATFORMS USED

| Platform | Description                                               |
| -------- | --------------------------------------------------------- |
| ChatGPT  | Conversational AI developed by OpenAI                     |
| Gemini   | AI model developed by Google                              |
| Claude   | AI assistant developed by Anthropic                       |
| Copilot  | Microsoft AI assistant integrated with productivity tools |

---

## PROMPTING TECHNIQUES

## 1. Zero-shot Prompting

The AI is directly asked to summarize the article without examples.

### Example:

“Summarize the following article in simple language for undergraduate students.”

---

## 2. Few-shot Prompting

The AI is provided with sample summaries before the task.

### Example:

“Here is an example summary format. Now summarize the following article similarly.”

---

## 3. Chain-of-Thought Prompting

The AI is instructed to reason step-by-step before summarizing.

### Example:

“Analyze the article step-by-step and then generate a concise summary.”

---

## 4. Role-based Prompting

The AI is assigned a specific role.

### Example:

“You are a university lecturer explaining blockchain basics to first-year students.”

---

## ARTICLE USED FOR SUMMARIZATION

### Topic:

**The Basics of Blockchain Technology**

### Key Concepts Covered:

* Distributed ledger
* Decentralization
* Blocks and hashing
* Cryptography
* Consensus mechanisms
* Applications in cryptocurrency and security

---

## METHODOLOGY

## Step 1: Select AI Platforms

The experiment was conducted using:

* ChatGPT
* Gemini
* Claude
* Copilot

## Step 2: Apply Prompting Techniques

Each platform was tested using:

* Zero-shot
* Few-shot
* Chain-of-Thought
* Role-based prompts

## Step 3: Generate Summaries

The same blockchain article was summarized using each prompt type.

## Step 4: Evaluate Outputs

The summaries were evaluated based on:

* Accuracy
* Coherence
* Simplicity
* Speed
* User Experience

---

## EVALUATION TABLE

| Platform | Prompt Type      | Accuracy  | Coherence | Simplicity | Speed    | User Experience |
| -------- | ---------------- | --------- | --------- | ---------- | -------- | --------------- |
| ChatGPT  | Role-based       | Excellent | Excellent | Excellent  | Fast     | Excellent       |
| ChatGPT  | Chain-of-Thought | Excellent | Very Good | Good       | Moderate | Very Good       |
| Gemini   | Few-shot         | Very Good | Good      | Very Good  | Fast     | Good            |
| Claude   | Role-based       | Very Good | Excellent | Excellent  | Moderate | Excellent       |
| Copilot  | Zero-shot        | Good      | Good      | Moderate   | Fast     | Good            |

---


## ADVANTAGES OF PROMPT ENGINEERING

* Improves response quality
* Enhances clarity and simplicity
* Reduces ambiguity
* Produces audience-specific outputs
* Increases AI efficiency

---

## LIMITATIONS

* Results vary across platforms
* Longer prompts may increase response time
* Some AI systems oversimplify technical content
* AI-generated summaries may occasionally omit important details

---

---
## OUTPUT

<img width="1694" height="929" alt="image" src="https://github.com/user-attachments/assets/0c824f7e-ec1c-4d29-bfb5-37e2bde094d3" />

---

## RESULT

The experiment showed that the combination of **Role-based Prompting with ChatGPT** provided the best balance of accuracy, coherence, simplicity, and user experience for educational text summarization.

Chain-of-Thought prompting produced highly logical summaries, while Few-shot prompting improved consistency. Overall, prompt engineering significantly enhanced AI summarization performance across all platforms.

---

## CONCLUSION

This experiment demonstrated that prompting strategies greatly influence the quality of AI-generated summaries. Different AI platforms respond uniquely to various prompt styles. Role-based prompting proved most effective for generating understandable summaries for undergraduate students.

The study highlights the importance of prompt engineering in educational content generation and shows how AI platforms can assist in simplifying technical information efficiently.

---




