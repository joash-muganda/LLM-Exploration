# LLM-Exploration

Welcome to the **LLM-Exploration** repository! This repository contains various experiments, demonstrations, and workflows to explore the capabilities of Large Language Models (LLMs) using different frameworks and platforms.

## Overview

This repository is organized into multiple sections, each focusing on different tasks related to the training, fine-tuning, and deployment of LLMs. The primary goal is to demonstrate how to work with LLMs using various techniques and tools, including fine-tuning, preference optimization, and multimodal applications, both in cloud environments and on local machines.

## Repository Structure

The repository is organized into the following directories:

- **LLama-Factory/**: Contains notebooks for fine-tuning and training LLaMa models using various optimization techniques such as LoRA (Low-Rank Adaptation), DPO (Direct Preference Optimization), and PPO (Proximal Policy Optimization) on Google Colab.
  - [Link to LLama-Factory Demo](https://drive.google.com/file/d/1UmlaRofZVub6WOo9pDYnQ3Efk9Cze3hk/view?usp=sharing)
  
- **LM-Studio/**: Demonstrates the use of the LM-Studio platform to load and interact with models like Gemma 2B, including PDF upload functionality and question-answering capabilities.
  - [Link to LM-Studio Demo](https://drive.google.com/file/d/1klxKQHxmnZBYQ71Iyu7iHdxEPxdK6Fzu/view?usp=sharing)

- **Ollama/**: Focuses on running LLMs locally using the Ollama platform, showcasing various capabilities such as multimodal models, REST APIs, and deployment in Google Colab.
  - [Ollama Multimodal Demo](https://drive.google.com/file/d/1VXJwBN-snMDvCBNOZkak3vRfOQMQoKFj/view?usp=sharing)
  - [Ollama REST API Demo](https://drive.google.com/file/d/1QaHw4gpGGfq1YRuusKRNGygWgs7EzQUM/view?usp=sharing)
  - [Ollama on Google Colab Terminal Demo](https://drive.google.com/file/d/1QNmBRH7BJ4LUK2gYF7vha8gRZAk7IFFz/view?usp=sharing)
  - [Ollama on Local Terminal Demo](https://drive.google.com/file/d/13oKSGX_irR15Ojlb30rBk3mkf-jLLElZ/view?usp=sharing)
  - [Ollama WebUI Demo](https://drive.google.com/file/d/1BbJSvFPqE4XAAjXZmqJwv1cCeOl6oaje/view?usp=sharing)

- **Diffy.ai/**: Demonstrates the workflow capabilities of Dify.ai, including RAG (Retrieval-Augmented Generation) engine, agent functionality, workflow management, observability, and local deployment.
  - [Link to Diffy.ai Demo 1](https://drive.google.com/file/d/1yR8ifnPKTl0xkfs0Ti-sDOqPDhuoNurm/view?usp=sharing)
  - [Link to Diffy.ai Demo 2](https://drive.google.com/file/d/1AdX1jEAjxcFagpVkw2ojSlePvFzsGg9a/view?usp=sharing)

## Getting Started

To get started with the experiments in this repository, navigate to the relevant folder based on the task or tool you want to explore. Each folder contains a `README.md` file with detailed instructions on how to set up and run the notebooks.

### Prerequisites

- **Google Colab**: For executing notebooks in the cloud with GPU/TPU support.
- **Hugging Face Account**: Some tasks require access to models hosted on the Hugging Face Model Hub. Make sure to have a valid Hugging Face token.
- **Python Packages**: Install necessary packages listed in each subdirectory's `README.md`.

## Usage

1. **LLama-Factory/**: Start with the Colab notebooks to explore various training methods for LLaMa models.
2. **LM-Studio/**: Use the provided notebooks to test out the features of the LM-Studio.
3. **Ollama/**: Experiment with running LLMs locally and on Google Colab using Ollama.
4. **Diffy.ai/**: Follow the notebooks to learn about the Dify.ai workflow capabilities.

## Contributing

Feel free to contribute to this repository by submitting pull requests or creating issues for any bugs or feature suggestions.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

Special thanks to the open-source community for providing tools and resources that made these explorations possible.
