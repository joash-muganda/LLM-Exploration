# LLama-Factory

This directory contains Google Colab notebooks demonstrating various training techniques and optimizations for LLaMa models using the Hugging Face Transformers library and Low-Rank Adaptation (LoRA) or Quantized LoRA (QLoRA) methods. 

## Overview

The goal of the notebooks in this directory is to explore different methods to fine-tune and optimize LLaMa models, including:
- **Supervised Fine-Tuning:** Training the model using supervised learning with LoRA or QLoRA to enhance its performance on specific datasets.
- **Direct Preference Optimization (DPO) Training:** Applying reinforcement learning techniques to optimize model preferences directly.
- **Proximal Policy Optimization (PPO) Training:** Using advanced reinforcement learning methods to train the model for specific tasks.

## Notebooks

- **`a1_supervised_finetuning.ipynb`**: Demonstrates supervised fine-tuning of a small LLaMa model (e.g., LLaMa 2 7B quantized) using LoRA or QLoRA. The notebook is adapted for execution in a Google Colab environment with TPU support.
  
- **`a2_dpo_training.ipynb`**: Shows the process of Direct Preference Optimization (DPO) training using a small LLaMa model. This notebook is designed for quick experimentation and execution on Google Colab.

- **`a3_ppo_training.ipynb`**: Covers Proximal Policy Optimization (PPO) training for a small LLaMa model, utilizing a reinforcement learning approach to optimize the model's performance on specific tasks.

## Usage

To use these notebooks:

1. **Open each notebook in Google Colab.**
2. **Connect to a T4 TPU** for efficient model training (Go to `Runtime` > `Change runtime type` > Set `Hardware accelerator` to `TPU`).
3. **Install the necessary libraries** as instructed in the notebooks.
4. **Run the notebooks** step-by-step, ensuring all cells execute successfully.

## Prerequisites

- **Hugging Face Account**: Make sure you have a Hugging Face account and a valid token to access the model and datasets.
- **Google Colab**: Use Google Colab with TPU support to execute the notebooks.

## Additional Notes

- These notebooks are designed to use the smallest models available (e.g., Gemma 2B quantized) to minimize resource usage and ensure compatibility with Google Colab's free tier.
- Please refer to the main [README](../README.md) file for additional details on the overall project structure and goals.

## License

This project is licensed under the MIT License - see the [LICENSE](../LICENSE) file for more details.
