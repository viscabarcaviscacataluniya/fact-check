📰 Fact Check: Fake News Detection with Machine Learning & BERT
Fact Check is an end-to-end machine learning and deep learning project designed to combat online misinformation. It classifies news articles as real or fake using both traditional ML algorithms and modern NLP transformers like BERT. The goal is to raise public awareness and promote critical thinking about the authenticity of digital content.

📌 Overview
Fake news has become a global challenge, impacting social trust and decision-making. This project combines the speed of traditional machine learning with the accuracy of transformer-based deep learning to detect misinformation more effectively.

🚀 Features
🔍 Traditional ML Models

Logistic Regression

Decision Tree

Random Forest

Gradient Boosting

🤖 Deep Learning with BERT

Uses bert-base-uncased from Hugging Face

Fine-tuned using PyTorch and Transformers

Tokenization, attention masks, and classification

🧪 Validation & Evaluation

Stratified Train/Validation/Test split

Per-epoch validation during training

Final evaluation on held-out test set

A/B testing: ML vs. DL performance

📊 Metrics Used

Accuracy

F1-Score

Confusion Matrix

Classification Report

🛠️ Technologies Used
Category	Tools & Libraries
Language	Python
ML Algorithms	Scikit-learn
DL/NLP Models	Hugging Face Transformers, PyTorch
Data Handling	Pandas, NumPy
Visualization	Matplotlib, Seaborn
Development	Jupyter Notebook

📁 Project Structure
bash
Copy
Edit
fact-check/
│
├── data/                   # True.csv, Fake.csv
├── Fact Check.ipynb        # Main notebook
├── requirements.txt        # Python dependencies
├── README.md               # This file
└── models/                 # (Optional) Saved model checkpoints
🧑‍💻 Getting Started
1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/viscabarcaviscacataluniya/fact-check.git
cd fact-check
2. Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
3. Launch the Notebook
bash
Copy
Edit
jupyter notebook
Open Fact Check.ipynb and follow the instructions to:

Load data

Train ML and DL models

Compare performances

Visualize results

📈 A/B Testing Results (Sample)
Model	Accuracy	F1 Score
Logistic Regression	0.93	0.93
Random Forest	0.95	0.95
BERT (DL)	0.9989	0.91

✅ In our case, BERT-based deep learning significantly outperformed traditional machine learning in accuracy, while F1-score was competitive.

📬 Future Improvements
🔁 Add early stopping & best model checkpointing

🌐 Build API using FastAPI or Flask

🧩 Add SHAP/LIME for interpretability

🧠 Extend with multilingual fake news datasets

💻 Deploy a web UI using Streamlit

🤝 Contributing
Contributions are welcome! Feel free to:

Fork this repo

Raise issues

Submit pull requests with improvements or fixes

📄 License
This project is licensed under the MIT License.


