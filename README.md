# Color Code Adherence in AI Image Generation: A Case Study on Gemini

This repository contains a two-part case study on achieving precise color adherence with Google's **Gemini 2.5 Flash Image** (Nano Banana) model. The project includes:

- **The Generation Notebook** (`generation.ipynb`): A practical, interactive tool that demonstrates how to use the color Image-reference method.
- **The Evaluation Notebook** (`evaluation.ipynb`): A 50-sample quantitative analysis that evaluates the accuracy of the olor Image-reference method compared to color text-only instructions.

---

## 📋 Prerequisites

- Python 3.7 or higher
- Jupyter Notebook or JupyterLab
- Google Gemini API key

## 🚀 How to Use

### 1. Requirements

You must have Python 3 and Jupyter installed. First, install the dependencies:

```bash
pip install -r requirements.txt
```

### 2. Enable the `ipywidgets` Extension for Jupyter

You will also need to enable the `ipywidgets` extension for Jupyter:

```bash
jupyter nbextension enable --py widgetsnbextension
```

### 3. Get a Gemini API Key

Get your API key from [Google AI Studio](https://aistudio.google.com/app/apikey).

### 4. Run the Notebooks

- **For the generation notebook (`interactive_generator.ipynb`):**  
  Open and run this notebook. The interactive widgets will allow you to generate images, test the "Use color as a reference" feature, and download your results.

- **For the evaluation notebook (`evaluation_notebook.ipynb`):**  
  Open and run all cells from top to bottom. The 50-sample loop (Cell 8) will take several minutes.

## 📁 Project Structure

```
.
├── generation.ipynb              # Interactive image generation tool
├── evaluation.ipynb              # Quantitative evaluation notebook
├── requirements.txt              # Python dependencies
└── README.md                     # This file
```

## 🔍 What's Inside

### Generation Notebook
- Interactive widgets for real-time image generation
- Color reference image upload functionality
- Side-by-side comparison of text-only vs. image-reference methods
- Download capabilities for generated images

### Evaluation Notebook
- Automated testing across 50 sample cases
- Quantitative color accuracy metrics
- Statistical analysis of color adherence
- Visualization of results

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
