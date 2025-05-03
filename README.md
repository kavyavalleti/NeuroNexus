# NeuroNexus
Data Science Internship Project for NeuroNexus Innovations
# 🚢 Titanic Survival Predictor

This project uses machine learning to predict whether a passenger would survive the Titanic disaster based on input features like age, sex, class, and more. The model is trained on the classic Titanic dataset and provides a risk-based survival prediction through an interactive Gradio web app.

![Titanic](https://upload.wikimedia.org/wikipedia/commons/f/fd/RMS_Titanic_3.jpg)

## 🔍 Features

- Predict survival based on:
  - Passenger class (Pclass)
  - Sex
  - Age
  - Fare
  - Embarkation port
  - Family size (SibSp + Parch)
- Logistic Regression model
- Interactive web UI via Gradio
- Confidence-based output with survival likelihood (visual indicators)

## 🚀 Try it out

To run the app locally:

```bash
pip install -r requirements.txt
python app.py
Or open it in Google Colab to train the model interactively and launch the app from the notebook.

📁 Project Structure
bash
Copy
Edit
titanic-survival-predictor/
├── app.py              # Gradio application
├── titanic_model.pkl   # (Optional) Pretrained model
├── titanic_notebook.ipynb # Colab notebook with training + app
├── requirements.txt    # Python dependencies
└── README.md           # Project description
📊 Dataset
Titanic Dataset on Kaggle

Contains passenger info like:

Age, Sex, Fare, Class, Embarkation port

Number of siblings/spouses and parents/children aboard

🧠 Model
Algorithm: Logistic Regression

Libraries: Scikit-learn, Pandas, Gradio

Evaluation: Accuracy, Probability Score

💻 Technologies Used
Python 3.x

Pandas

Scikit-learn

Gradio

Google Colab (for training)

✨ Screenshots
<img src="screenshot.png" width="600" alt="App Screenshot">
📜 License
This project is licensed under the MIT License.

👤 Author: Kavya sree Valleti
