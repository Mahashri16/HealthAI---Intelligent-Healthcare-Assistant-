


---

🏥 HealthAI – Intelligent Healthcare Assistant

HealthAI is an AI-powered healthcare assistant that predicts diseases based on user symptoms and provides treatment recommendations. It uses IBM Granite models from Hugging Face for natural language understanding and is deployed using Gradio for an interactive user interface.


---

📌 Project Overview

Goal: Make healthcare guidance accessible, fast, and easy-to-understand

Model Used: ibm-granite/granite-3.2-2b-instruct

Platform: Google Colab (T4 GPU)

Frontend: Gradio Web App



---

✨ Features

✅ Symptom-Based Disease Prediction – ML-driven predictions for possible conditions
✅ AI Treatment Recommendations – Suggests next steps (self-care/consult a doctor)
✅ Conversational Interface – Users can chat naturally with the AI
✅ Fast & Accessible – Runs in Google Colab with shareable Gradio link
✅ Scalable – Can be enhanced with additional datasets & models


---

🏗️ Project Architecture

flowchart TD
    A[User Inputs Symptoms] --> B[Gradio Frontend]
    B --> C[Python Backend in Colab]
    C --> D[IBM Granite Model on Hugging Face]
    D --> E[Prediction + Treatment Plan]
    E --> F[Gradio Output Display]


---

🛠️ Tech Stack

Programming Language: Python 3.8+

Libraries: transformers, torch, gradio

Platform: Google Colab

AI Model: IBM Granite (Hugging Face)



---

⚙️ Setup Instructions

Prerequisites

Google Colab account

Hugging Face account (optional, for API key if needed)


Installation

1. Open the provided Colab Notebook


2. Set runtime to GPU (T4)


3. Install dependencies:

!pip install transformers torch gradio -q


4. Run all cells to launch the app




---

▶️ How to Run

1. Open the notebook in Google Colab


2. Execute all cells in order


3. Launch the Gradio interface


4. Enter symptoms (e.g., "fever, cough, fatigue")


5. Get predicted disease and treatment recommendations




---

📸 Screenshots

(Add screenshots here once you run your app – input + output examples)


---

🚀 Future Enhancements

Add statistical probability calculation (logistic regression, chi-square)

Include explainability using SHAP or LIME

Visualize top predicted diseases in Tableau dashboard

Deploy permanently on Hugging Face Spaces or Streamlit Cloud



--

