### GROWAI LLM Engineering - Assignment 4

## Prompt Engineering Showdown

This project demonstrates and compares three prompting techniques — `Zero-Shot, Few-Shot and Chain-of-Thought prompting` — using the `Qwen3 0.6B` model through Ollama. The techniques are evaluated on three real-world tasks: sentiment classification, entity extraction and text summarisation.

The project also demonstrates a prompt failure mode and its improvement using `structured and validated output with Pydantic`.

## Features

- Zero-Shot prompting
- Few-Shot prompting with examples
- Chain-of-Thought prompting
- Sentiment classification
- Named entity extraction
- Text summarisation
- Prompt failure-mode analysis
- Structured JSON output
- Pydantic schema validation
- Side-by-side prompting technique comparison

## Technologies Used

- Python
- Jupyter Notebook
- Ollama
- Qwen3 0.6B
- Requests
- Pydantic
- Pandas

## Requirements

- Python 3.x
- Ollama
- Qwen3 0.6B
- Jupyter Notebook
- requests
- pydantic
- pandas

## Setup / Installation

Install the required dependencies:
``` text
pip install -r requirements.txt
```

Install and run Ollama, then download the required model:
``` text
ollama pull qwen3:0.6b
```

## How to Run

1. Start Ollama.
2. Open the Jupyter Notebook.
3. Ensure the "qwen3:0.6b" model is available locally.
4. Run the notebook cells sequentially.
5. Observe and compare the outputs from Zero-Shot, Few-Shot and Chain-of-Thought prompting.
6. Review the failure-mode and Pydantic structured-output sections.

## Project Files

- "Prompt_Engineering_Showdown.ipynb" – Main implementation and demonstrations
- "requirements.txt" – Python dependencies
- ".gitignore" – Files excluded from version control

## Real-World Relevance

Prompt engineering is an important part of building reliable LLM applications. These techniques can be applied to `customer feedback analysis, information extraction, document summarisation, chatbots, content processing and automated workflows`.

Structured output with Pydantic is particularly useful when LLM responses need to be consumed reliably by other software components.

## Edge Case / Failure Mode

The project demonstrates how `ambiguous or loosely defined prompts can result in inconsistent or incomplete outputs`. The issue is addressed by defining a structured output schema using Pydantic and Ollama's "format" parameter, making the response more predictable and easier to validate programmatically.

## Assignment
GROWAI LLM Engineering & Generative AI - Assignment 4
