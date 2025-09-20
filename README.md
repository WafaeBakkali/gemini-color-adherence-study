\# Color Code Adherence in AI Image Generation: A Case Study on Gemini



This repository contains a two-part case study on achieving precise color adherence with Google's \*\*Gemini 2.5 Flash Image\*\* ("Nano Banana") model. The project includes:



\- \*\*The Generation Notebook\*\* (`interactive\_generator.ipynb`): A practical, interactive tool that demonstrates how to use the superior Image-Reference method.

\- \*\*The Evaluation Notebook\*\* (`evaluation\_notebook.ipynb`): A 50-sample quantitative analysis that evaluates the accuracy of the Image-Reference method compared to traditional text prompts.



---



\## How to Use 



\### 1. Requirements



You must have Python 3 and Jupyter installed. First, install the dependencies:

```bash

pip install -r requirements.txt

```

You will also need to enable the `ipywidgets` extension for Jupyter:

```bash

jupyter nbextension enable --py widgetsnbextension

```



\### 2. Get a Gemini API Key



Get your API key from \[Google AI Studio](https://aistudio.google.com/app/apikey).



\### 3. Run the Notebooks



\* \*\*For the generation notebook (`generation.ipynb`):\*\*

&nbsp;  Open and run this notebook. The interactive widgets will allow you to generate images, test the "Use color as a reference" feature, and download your results.



\* \*\*For the evaluation (`evaluation.ipynb`):\*\*

&nbsp;  Open and run all cells from top to bottom. The 50-sample loop (Cell 8) will take several minutes.



