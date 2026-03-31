# GPT-2 Attention Explorer & Text Generation Analysis

## 📌 Overview
This project explores the deployment and internal mechanics of Large Language Models (LLMs) using the Hugging Face `transformers` library. Built in a GPU-accelerated Google Colab environment, this repository demonstrates the end-to-end implementation of GPT-2, from basic tokenization to the advanced visualization of mathematical attention weights.

The project goes beyond basic text generation by stress-testing model parameters and proposing theoretical bridges between text-based transformers and automated image processing workflows.

## 🚀 Key Features
* **Custom Text Generation:** Implementation of GPT-2 with tuned parameters (`temperature`, `top_k`, `repetition_penalty`) to mitigate probabilistic loops and control creative variance.
* **Attention Visualization:** Integration with `BertViz` to expose the "black box" of the transformer architecture, mapping how specific attention heads link subjects to objects across hidden layers.
* **Contextual Probing:** Analysis of how the model maintains grammatical structure and context over sequential generation.

## 🛠️ Tech Stack & Dependencies
* **Environment:** Google Colab (T4 GPU recommended)
* **Core Libraries:** `torch`, `transformers` (Hugging Face)
* **Visualization:** `bertviz`, `matplotlib`

## ⚙️ How to Run
1. Clone this repository or download the `GPT2_Analysis.ipynb` notebook.
2. Upload the notebook to [Google Colab](https://colab.research.google.com/).
3. Change the runtime to **GPU** (`Runtime > Change runtime type > T4 GPU`).
4. Run the first cell to install the required dependencies:
   ```bash
   pip install transformers torch matplotlib bertviz
