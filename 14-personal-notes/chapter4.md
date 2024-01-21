# Prompt Engineering Fundamentals

How you write your prompt to the LLM matters, a carefully crafted prompt can achieve a better result than one that isn't.

Generative AI is capable of creating new content in response to user request. It does this using Large Language Models.

Users can now interact with these models using chat without the need for technical expertise or training. These modesl are prompt-based, users send a prompt, and get back the AI response (completion).

"Prompts" become the primary programming interface for AI apps. "Prompt Engineering" focuses on the design and optimization of prompts.

## What is Prompt Engineering?

Defined this earlier as "the process of designing and optimizing text inputs (prompts) to deliver consistent and quality responses (completions). This is a two step process

- designing the initial prompt for a given model and objective
- refining the prompt iteratively to improve the quality of the response.

This is basically a trail-and-error process. We need to understand three things:

- Tokenization = how the model sees the prompt
- Base LLMs = how the foundation model processes a prompt
- Instruction-Tuned LLMs = how the model can now see "tasks"

### Tokenization

An LLM sees prompts as a sequence of tokens and different models can tokenize the same prompt in different ways. Remember an LLM is trained on tokens and not raw data

### Concept: Foundation Models

Once a prompt is tokenized, the primary function of the "Base LLM" or Foundation Model is to predict the token in that sequence. The LLM doesn't understand the meaning of the word in the prompt or token, they just see a pattern.

### Concept: Instruction Tuned LLMs