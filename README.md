# Dialogue Summarization with FLAN-T5

## Overview

- This repository demonstrates how to perform dialogue summarization using the FLAN-T5 model, a large language model from Hugging Face. We explore various techniques, including prompt engineering and one-shot/few-shot inference, to generate concise summaries from dialogues.

## Table of Contents

- [Dialogue Summarization with FLAN-T5](#dialogue-summarization-with-flan-t5)
  - [Overview](#overview)
  - [Table of Contents](#table-of-contents)
  - [Use Cases](#use-cases)
    - [1. Summarize Dialogue without Prompt Engineering](#1-summarize-dialogue-without-prompt-engineering)
    - [2. Summarize Dialogue with an Instruction Prompt](#2-summarize-dialogue-with-an-instruction-prompt)
    - [3. Summarize Dialogue with One Shot and Few Shot Inference](#3-summarize-dialogue-with-one-shot-and-few-shot-inference)
    - [4. Generative Configuration Parameters for Inference](#4-generative-configuration-parameters-for-inference)
  - [Usage](#usage)
  - [Contributing](#contributing)
  - [License](#license)

## Use Cases

### 1. Summarize Dialogue without Prompt Engineering

In this use case, we generate summaries of dialogues using the FLAN-T5 model without any prompt engineering. We explore how well the model can summarize dialogues in its default state.

### 2. Summarize Dialogue with an Instruction Prompt

We instruct the model to summarize dialogues by converting the dialogues into instruction prompts. This technique, known as zero-shot inference, helps the model understand its task better.

### 3. Summarize Dialogue with One Shot and Few Shot Inference

We demonstrate one-shot and few-shot inference techniques to improve dialogue summarization. By providing the model with full examples of prompt-response pairs, we enhance its understanding of the task.

### 4. Generative Configuration Parameters for Inference

We explore how different configuration parameters for text generation affect the model's output. By adjusting parameters like `do_sample`, `temperature`, and `max_new_tokens`, we fine-tune the model's responses.

## Usage

To use this repository, follow these steps:

1. Clone the repository to your local machine:

   ```
   git clone https://github.com/Prureddy/dialogue_summarization.git
   ```

2.Install the required dependencies by running:
```
pip install torch torchvision torchaudio
pip install torchdata
pip install transformers
pip install datasets
```
3.Explore the Jupyter Notebook files provided to understand and experiment with the dialogue summarization techniques.

## Contributing
Contributions to this project are welcome! Feel free to open issues, suggest improvements, or submit pull requests.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
