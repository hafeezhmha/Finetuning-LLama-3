# Llama-3.2-3B-Instruct Fine-Tuning with LoRA Adapters

This repository demonstrates fine-tuning the **Llama-3.2-3B-Instruct** model using LoRA (Low-Rank Adaptation) adapters with the **FastLanguageModel** from the `unsloth` library. The training script utilizes the **FineTome-100k** dataset to refine the model's conversational capabilities.

## 📚 Overview
- **Model Used**: `unsloth/Llama-3.2-3B-Instruct`
- **Dataset**: [FineTome-100k](https://huggingface.co/datasets/mlabonne/FineTome-100k)
- **Libraries**: PyTorch, transformers, unsloth, trl, datasets
- **Training Framework**: Weights & Biases (W&B)

## 🚀 Setup & Execution

### 1. Install Dependencies
Ensure you have the necessary dependencies installed. Run the following command:
```bash
pip install torch unsloth datasets trl transformers wandb
```

### 2. Clone the Repository
```bash
git clone https://github.com/hafeezhmha/Finetuning-LLama-3.git
cd Finetuning-LLama-3
```

### 3. Run the Fine-Tuning Script
Run the provided script or open the Jupyter Notebook to fine-tune the model.

### 4. W&B Integration
To log in to Weights & Biases, run:
```bash
wandb login
```

## 💡 Key Features
- **Fine-tuning with LoRA Adapters**: Efficient training with reduced computational requirements using LoRA adapters.
- **Chat Template Customization**: Standardizes conversations using templates for consistent model training.
- **Dataset Preparation**: Automated dataset processing and tokenization.
- **Weights & Biases Integration**: Track experiment details, visualize metrics, and store model artifacts.

## 📦 Dependencies
- `torch`
- `unsloth`
- `datasets`
- `trl`
- `transformers`
- `wandb`

### Installation
Dependencies can be installed using the following command:
```bash
pip install -r requirements.txt
```

## 📂 Outputs & Checkpoints
Checkpoints and logs will be saved in the `outputs/` folder. Make sure to add it to `.gitignore` to avoid pushing large files to GitHub.
