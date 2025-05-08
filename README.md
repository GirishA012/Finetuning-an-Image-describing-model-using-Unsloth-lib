# Vision LLM Fine-tuning with Custom Character Image Dataset

This repository contains the process and code for creating a custom dataset of images, generating and cleaning image descriptions, and fine-tuning the `unsloth/Llama-3.2-11B-Vision-Instruct` model using the [Unsloth](https://github.com/unslothai/unsloth) library.

## 📂 Dataset

We curated a dataset of **122 images** consisting of:
- **Single character images**
- **Multi-character images**
- **No-character images**

### Description Generation
Image descriptions were generated using **Gemini 1.5 Flash**, and later:
- **Augmented** to improve clarity and context
- **Cleaned** for consistency and quality

## 🛠️ Fine-tuning

We fine-tuned the **LLaMA 3.2 Vision model** (`unsloth/Llama-3.2-11B-Vision-Instruct`) using the [Unsloth library](https://github.com/unslothai/unsloth), which allows efficient fine-tuning of large models.

### Fine-tuning Details
- Framework: `Unsloth`
- Model: `Llama-3.2-11B-Vision-Instruct`


## 🧪 Testing

After fine-tuning, the model was tested on a **new image not included in the training dataset** to evaluate generalization and performance.

## 🔧 Setup


