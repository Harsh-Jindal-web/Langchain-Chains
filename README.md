
# LangChain-Chains

This repository provides an interactive and practical guide to using **Chains in LangChain**, a foundational component for building complex, multi-step workflows with language models. It includes code examples, different chain architectures, and summarized notes for a comprehensive understanding.

## 🧠 Overview

Chains in LangChain allow developers to **combine multiple components**—such as prompts, LLM calls, and output parsers—into structured sequences for handling more complex AI tasks. 

This project explores:

1. **SimpleChain** – Basic linear execution using prompt and model.
2. **SequentialChain** – Executes chains in a defined sequence, passing outputs along.
3. **ParallelChain** – Runs multiple chains simultaneously and combines their outputs.
4. **ConditionalChain** – Branches logic dynamically based on conditions.

For a structured summary, check out [**Notes Chains in Langchain.pdf**](https://github.com/Harsh-Jindal-web/Langchain-Chains/blob/main/Notes%20Chains%20in%20LangChain.pdf).

Video walkthrough available here:  
- [📺 LangChain Chains (YouTube)](https://www.youtube.com/watch?v=5hjrPILA3-8&list=PLKnIA16_RmvaTbihpo4MtzVm4XOQa0ER0&index=9)

## 📂 Repository Structure

- `simple_chain.py` – Basic example of a single prompt-to-model pipeline.
- `sequential_chain.py` – Demonstrates step-by-step execution with intermediate data passing.
- `parallel_chain.py` – Shows how to run multiple chains concurrently.
- `conditional_chain.py` – Implements logic-based branching in chain execution.
- `Notes Chains in Langchain.pdf` – Summarized notes explaining chain types and usage.

## 📄 Resources

- **LangChain Documentation – Chains**  
  [https://python.langchain.com/v0.1/docs/modules/chains/](https://python.langchain.com/v0.1/docs/modules/chains/)
  
---

Feel free to explore, contribute, or open issues to improve or expand this guide.

---
