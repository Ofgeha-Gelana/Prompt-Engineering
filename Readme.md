# Advanced Prompt Engineering with Gemini API

This project demonstrates the use of **advanced prompting techniques** with the **Gemini API** to solve real-world problems. It includes implementations of five advanced techniques: Few-Shot Learning, Chain-of-Thought (CoT) Prompting, Self-Consistency, Generate Knowledge Prompting, and Program-aided Language Models (PAL).

## Table of Contents
- [Overview](#overview)
- [Setup](#setup)
- [Use Cases](#use-cases)
- [Advanced Techniques](#advanced-techniques)
  - [Few-Shot Learning](#few-shot-learning)
  - [Chain-of-Thought (CoT) Prompting](#chain-of-thought-cot-prompting)
  - [Self-Consistency](#self-consistency)
  - [Generate Knowledge Prompting](#generate-knowledge-prompting)
  - [Program-aided Language Models (PAL)](#program-aided-language-models-pal)
- [Contributing](#contributing)
- [License](#license)

---

## Overview
This project showcases how to use the **Gemini API** to implement advanced prompting techniques for various tasks, such as customer support classification, math problem-solving, fact verification, and code generation. Each technique is explained with a use case and example implementation.

---


**Description of Output:**  
The model generates a Python function to calculate the factorial of a number using recursion. The output demonstrates how PAL enables the model to write functional code for specific tasks.

---

### Summary of Outputs
| **Technique**               | **Output Description**                                                                 |
|-----------------------------|---------------------------------------------------------------------------------------|
| Few-Shot Learning           | Classifies a new email as "General Inquiry" based on provided examples.               |
| Chain-of-Thought (CoT)      | Solves a math problem step-by-step, calculating weekly revenue for a bakery.          |
| Self-Consistency            | Verifies a false statement using two distinct reasoning paths.                        |
| Generate Knowledge Prompting| Explains quantum computing in simple terms with key points.                           |
| Program-aided Language Model| Generates Python code to calculate the factorial of a number using recursion.         |

---

## Setup
To run this project locally, follow these steps:

1. **Install the Gemini library**:
   ```bash
   pip install google-generativeai