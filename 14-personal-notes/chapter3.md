# Using Generative AI Responsibly

## Responsible AI Principles

The core principles are:

- Fairness
- Inclusiveness
- Reliability/Safety
- Security & Privacy
- Transparency
- Accountability

## Why you should prioritize responsible AI?

The uniqueness of Generative AI is its power to create helpful answers, information, guidance, and content for users. There are also some harmful results for your users, product, and society. Here are some potential harmful results:

### Hallucinations

A term used to describe when an LLM products content that is either

- Nonsensical
- Something we know is factually wrong based on other sources

The answer could be very confident and thorough but it is incorrect.

### Harmful Content

Harmful content can be defined as:

- Providing instructions or encouraging self-harm or harm to certain groups
- Hateful or demeaning content
- Guiding planning any type of attack or violent acts
- Providing instructions on how to find illegal content or commit illegal acts
- Displaying sexually explicit content
  - Sexually explicit content by nature isn't harmful.

### Lack of Fairness

Fairness is defined as "ensuring that an AI system is free from bias and discrimination." Want to make sure that worldviews of marginalized groups are not reinforced by the output.

## How to Use Generative AI Responsibly

The four steps to build AI Solutions responsibly:

- Measure
- Mitigate
- Operate
- Identify

### Measure Potential Harms

In software testing we test the expected actions of a user on application. We need to test a diverse set of prompts users are most likely going to use to measure potential harm

### Mitigate Potential Harms

Four different potential harms caused by the model and it's responses:

- Model
  - Choosing the right model for the right use cause
  - Using only your training data to fine-tune and reduce the risk of harmful content
- Safety System
  - A safety system is a set of tools and configurations on the platform serving the model
  - Systems should also detect jailbreak attacks and unwanted activity like requests from bots
- Metaprompt
  - Metaprompts and grounding are ways we can direct or limit the models based on behaviors and information
  - This could used to define certain limits of the model
- User Experience
  - The final layer is where the user interacts directly with the model
  - We can design the UI/UX to limit the user on the type of inputs
  - We must be transparent about what our Generative AI application can do
- Evaluate model
  - We don't always have control over the data the model is built on
  - We should always evaluate the model's performance and outputs
  - Measure the model's accuracy, similarity, groundedness, and relevance of the output

### Operate a Responsible Generative AI solution

 The final stage of things