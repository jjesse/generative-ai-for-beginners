# Exploring and comparing different LLMs

## Understand different types of LLMs

LLMs can have multiple categorizations based on their architecture, training data, and use cases and here are some examples:

- Audio and speech recognition
  - Whisper type models are a great choice
  - Trained on diverse audio and can perform multilingual speech recognition
- Image generation
  - DALL-E and Midjourney are two very known choices
- Text generation
  - Most models are trained on text generation and there is a wide variety of choices

### Foundation models versus LLMs

Standford researchers coined the term and defined it as an AI Model that:

- Trained using unsupervised learning or self-supervised learning
  - They were trained on unlabled multi-model data
  - Do not require human annotation or labeling of data for their training process
- They are very large models
  - Baed on very deep neural networks trained on billions of parameters
- They are intended to serve as a foundation for other models
  - Can be used a starting point for other models to be built on

### Open Source versus Proprietary Models

Open-source models are modesl that are available to the public and be used by anyone.

Examples:

- Alpaca
- Bloom
- LLaMA

Proprietary models are owned by the company or person who creates them.

### Embedding versus Image gneration versus Text and Code Generation

LLMs can be categorized by the output they generate

- Embeddings are models that convert text into numerical form
  - Embeddings make it easier to understand relationships between words or sentences
  - Often used for transfer learning - A model is built for a task with a bunch of data and then model weights (embeddings) are re-used

- Image generation models generate images
  - Often used for image editing, synthesis, and image translation
  - Trained on a large set of images
  - Can be used to generate new images or edit existing images with inpainting, super-resolution, and colorization techniques

- Text Generation models generate text or code
  - Trained on large datasets of text like BookCorpus
  - Trained to answer code questions like CodeParrot

### Service vs. Model

- A service is a product offered by a Cloud Service Provider (CSP)
  - Often a combination of model(s), data, and components
  - Optimized for production use and easier to use than a model
  - Often have some form of GUI (Graphical User Interface)
- A model is the core component of a service
  - It is the foundation of a LLM
  - Models are the Neural Network, with the parameters, weights, and others
  -

### Open Source versus Proprietary Models

### Prompt Engineering with Context

Pre-trained LLMs work on generalized natural language tasks. THe better someone can frame their query with a detailed request.

### Retrieval Augmented Generation (RAG)

LLMs can only use the data that has been used during training to generate an answer. This can be augmented with prompts from external data in the form of chunks of documents.

This can be used to fine tune an LLM when a business doesn't have enought time, data or resources to improve things.

### Fine Tuned Model

Process that leverages transfer learning to adapt the model to a specific task or problem. This is different than a RAG as it results in a new model being generated.

- Using fine-tuned models
  - Like to use fine-tuned less capable models rather than high performance models
  - Results in a more cost effective and fast solution
- Considering latency
  - Latency is important for a specific use-case
  - Not possible to use very long prompts
  - The number of examples that should be learned from doesn't fit the prompt length limit
- Staying up to date
  - A business has a lot of high-quality data and ground truth labels
  - A business has the rsources required to maintain this data up to date

### Trained Model

Training a model from scratch is the most difficult and most complex approach to adapt. It requires a bunch of data, skilled users and lots of computational power.
