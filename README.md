# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

## SCENARIO
You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

Accuracy

Coherence

Simplicity

Speed

User experience

## OUTPUT

Prompt engineering plays a crucial role in:

Prompt engineering refers to the art and science of designing input instructions to guide AI models toward desired outputs. The same AI model can produce vastly different results depending on prompt structure, clarity, and context.

Importance of Prompt Engineering
* Enhances output accuracy
* Controls tone and depth
* Aligns content with target audience
* Reduces hallucinations
* Improves reproducibility Controlling depth and tone
* Improving factual correctness
* Reducing ambiguity
* Enhancing readability for specific audiences

## DESCRIPTION OF THE SOURCE ARTICLE

* Definition of blockchain
* Distributed ledger concept
* Blocks, hashes, and chaining
* Consensus mechanisms
* Advantages such as security and transparency
* Applications in cryptocurrency, supply chain, and finance

The article contains **technical terminology**, making it suitable for evaluating summarization clarity for undergraduate students.


## PROMPTING TECHNIQUES

## 1. Zero-Shot Prompting

Zero-shot prompting involves providing a **direct instruction without examples**.

**Characteristics:**

* Fast and simple
* Minimal guidance
* Output quality depends entirely on model capability

**Advantages:**

* Quick execution
* Suitable for general tasks

**Limitations:**

* Inconsistent depth
* May be too technical or too brief

## 2. Few-Shot Prompting

Few-shot prompting includes **one or more sample summaries** to guide the AI.

**Characteristics:**

* Provides structure and tone
* Improves consistency

**Advantages:**

* Better alignment with desired style
* Improved clarity

**Limitations:**

* Requires more prompt preparation
* Slightly slower response

### 3. Chain-of-Thought Prompting

Chain-of-thought prompting encourages the AI to **reason step by step before generating the final summary**.

**Characteristics:**

* Emphasizes logical sequencing
* Preserves technical accuracy

**Advantages:**

* High factual correctness
* Well-structured summaries

**Limitations:**

* Outputs may be longer
* Sometimes too complex for beginners

## 4. Role-Based Prompting

Role-based prompting assigns a **specific role** to the AI.

**Characteristics:**

* Strong control over tone and audience
* High readability

**Advantages:**

* Excellent for educational content
* Improves engagement and simplicity

**Limitations:**

* Depends on role clarity

## AI PLATFORMS USED

## ChatGPT

* Strong natural language generation
* Excellent instructional alignment
* Performs well with role-based and few-shot prompts

## Gemini

* Fast response time
* Good general summaries
* Less depth with complex concepts

## Claude

* Exceptional coherence and reasoning
* Produces detailed and logically ordered summaries
* Slightly verbose for undergraduate level

## Copilot

* Primarily optimized for productivity tasks
* Basic summarization capability
* Less effective for educational simplification

## EVALUATION METRICS

## Accuracy
Measures factual correctness, including correct explanation of:
* Distributed ledger
* Hash linking
* Consensus mechanisms

## Coherence
Assesses:
* Logical flow
* Smooth transitions
* Clear paragraph structure

## Simplicity
Evaluates:
* Vocabulary level
* Sentence length
* Ease of comprehension

## Speed
Measured as perceived response time.

## User Experience
Considers:
* Readability
* Usefulness
* Overall satisfaction

## EVALUATION CRITERIA

| Parameter       | Description                                   |
| --------------- | --------------------------------------------- |
| Accuracy        | Correct representation of blockchain concepts |
| Coherence       | Logical flow and readability                  |
| Simplicity      | Ease of understanding for undergraduates      |
| Speed           | Response time                                 |
| User Experience | Overall usefulness and clarity                |

## COMPARATIVE ANALYSIS

| Platform | Best Prompt Type      | Key Strength            | Key Limitation   |
| -------- | --------------------- | ----------------------- | ---------------- |
| ChatGPT  | Role-based + Few-shot | Clear, student-friendly | None significant |
| Claude   | Chain-of-Thought      | Highly accurate         | Slightly complex |
| Gemini   | Zero-shot             | Fast execution          | Limited depth    |
| Copilot  | Zero-shot             | Quick summaries         | Low clarity      |


## RESULT


<img width="441" height="411" alt="image" src="https://github.com/user-attachments/assets/0f348a5f-f780-45f7-b244-d64466ed74b7" />




The experiment conclusively shows that effective prompt design is critical for high-quality AI-generated summaries. Among all tested combinations, ChatGPT with role-based and few-shot prompting delivered the most accurate, coherent, simple, and user-friendly summaries for undergraduate students.

AI-powered summarization is a powerful tool for educational content delivery when used correctly. This experiment highlights that prompting strategy selection is as important as platform choice. Role-based and few-shot prompting techniques significantly enhance learning-oriented summaries, making AI a valuable assistant in modern education systems.
The experiment demonstrates that **prompting technique significantly affects summarization quality**, often more than the AI platform itself.

* **Role-based prompting** produced the most readable summaries.
* **Few-shot prompting** improved structural consistency.
* **Chain-of-thought prompting** enhanced accuracy but reduced simplicity.
* **Zero-shot prompting** was fastest but least reliable.
