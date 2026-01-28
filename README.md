%%writefile README.md
# Text Generation with Fine-Tuned GPT-2

## 📌 Project Overview
This project focuses on the **fine-tuning of the GPT-2 transformer model** to perform stylistic text generation. Using a custom dataset of 40,000+ lines of Shakespearean text, the model was adapted from a general-purpose language model into a specialized generator capable of mimicking 16th-century linguistic patterns.

## 🛠️ Technical Stack
* **Base Model:** GPT-2 (117M parameters)
* **Frameworks:** Hugging Face `transformers`, `datasets`
* **Hardware:** NVIDIA T4 GPU (via Google Colab)
* **Language:** Python 3.12
* **Deployment:** Gradio (Web Interface)

## 🚀 Key Features
* **Custom Fine-Tuning:** Leveraged the `Trainer` API to update model weights based on specialized stylistic corpora.
* **Optimization:** Achieved a **17.9% reduction in training loss** (from 4.46 to 3.66).
* **Interactive UI:** Integrated a Gradio frontend for real-time text generation.
* **Contextual Awareness:** The model maintains character-based dialogue structures (e.g., `ROMEO:`).

## 📊 Performance Metrics
* **Initial Loss:** 4.46
* **Final Loss:** 3.66
* **Inference Speed:** ~3.73 iterations per second on T4 GPU

## 💻 How to Run
1. **Install Dependencies:**
   ```bash
   pip install transformers datasets torch gradio
   ```
2. **Run Inference:**
   Execute the notebook `PRODIGY_AI_01.ipynb` to launch the Gradio interface.

## 🎓 Internship Credits
This project was completed as part of the **AI Engineering Internship at Prodigy Infotech (Task-01)**.
