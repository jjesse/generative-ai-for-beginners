# Chapter 1 - Introduction to Generative AI and LLMs

## How did we gte Generative AI

Focused on a statisical approach to AI, able to learn patterns from data

A Nueral network and specifically a Recurrent Neural Network (RNN) signficantly enhanced natural lanague processing, enabling the represenation of the meaning of text in a better way

This RNN is what powers the modern virtual assitants (Siri, Alexa, etc.)

## Present Day

- Artificial Intelligence (1956)
  - The field of computer science that seeks to create intelligent machines that replicate or exceed human intelligence

- Machine Learning (1997)
  - Subset of AI that enables machines to learn from existing data and improve upon that data to make decisions or predictions

- Deep Learning (2017)
  - A machine learning technique in which layers of neural networks are used to process data and make decisions

- Generative AI (2021)
  - Create new written, visual, and auditory content given prompts or existing data

After a ton of reearch a new model architecture called Transform overcame the limits of RNNs (Recurrent Neural Networks)

- Based on the attention mechanism
- Different weights to the inputs it receives 
- "paying more attention" to the most relevant information

Most of the recent models (Also known as Large Language Models (LLMs)) are based on this architecture

## How do large language models work?

Will focus on OpenAI GPT (Generative Pre-trained Transformer) models

- Tokenizer, text to numbers
  - LLMs receive text as input and generate a text as output
  - However, since they are statisical models they work better with numbers than sequences
  - Every input is given a token (a chunk of text consisting of a number of characters)
- Predicting output tokens
  - Given n tokens as input the model is able to predict one token as an output
  - Token then becomes a part of the next prediction
  - Sometimes cause ChatGPT to pause
- Selection process,probability distribution
  - Output token is chosen by the model of it occuring after the current text sequence
  - A degree of randomness is added to this choice so we don't get the exact same output for the same input
  - Used to simulate creative thinking and can be tuned by changing a parameter called "temperature"

## How can I leverage Large Language Models?

The main capabiity of an LLM is generating a text from scratch, starting from an input, and written in a natural language

The input of an LLM is called a prompt and the output is called a completion

A prompt may include:

- An insturction specifying the type of output we expect from the model
- A question, asked in the form of a conversation w/ an agent
- A chunk of text to complete, which implicity is an ask for assistance
- A chunk of code together with the ask of explaining and documenting it, or a comment asking to generate a piece of code performing a specific task


## Knowledge Check

- What's true about a large language model?
  - The response may bary despite using the same prompt. It is also great at giving you a first draft of something, be it text or code
  - An LLM is non-deterministic, the response may vary based on the temperature setting