# Mimic Persona using Prompt-Tuning through HF Models

This repository contains code leveraging the `langchain` library and specific dependencies to enable persona-based responses to queries.

## Overview

The primary functionality is encapsulated in the `wizard-lm.ipynb` notebook, implementing the `langchain` library. This notebook serves as a tool to generate personalized responses based on a given persona and query.

### Files

- `wizard-lm.ipynb`: Primary notebook containing the implementation using `langchain`.
  
## Usage

To utilize the code within `wizard-lm.ipynb`, ensure you have the necessary dependencies installed.

```bash
!pip -q install langchain tiktoken chromadb pypdf transformers sentence_transformers InstructorEmbedding
!pip -q install accelerate bitsandbytes sentencepiece Xformers
```

#### Important Notes

- **Dataset and Prompt Privacy:** The notebook requires access to a private dataset and prompt for accurate functionality. These private files are not included in this public repository.

- **No Model Training:** This repository does not focus on training a model. Instead, it utilizes the `langchain` library to generate responses based on a pre-trained model, a prompt, and a persona.

## Disclaimer

This repository does not provide the private data required for generating personalized responses. It solely offers a framework using the `langchain` library for generating responses based on a trained model, a prompt, and a persona.

Please reach out for inquiries or further details.
