# NLP_XAI
A deep learning and machine learning-based text classification project to detect suicidal tendencies in tweets. Combines RNNs, SVM, Random Forest, and Logistic Regression with Explainable AI (XAI) tools like Anchor, Eli5, Integrated Gradients, and Tree Interpreter to enhance model transparency and interpretability.


🧠 Suicidal Tweet Detection using NLP, ML & XAI
This project explores the application of Natural Language Processing (NLP) and Explainable Artificial Intelligence (XAI) techniques to detect suicidal tendencies in tweets. We combine deep learning (RNN) and machine learning models (SVM, Logistic Regression, Random Forest) with a suite of XAI tools to make model predictions more transparent and trustworthy.

📌 Problem Statement
Social media platforms like Twitter host millions of user-generated posts that can contain valuable cues about users’ mental health. Detecting suicidal ideation early through automated analysis of such content can aid in prevention efforts. However, black-box models often lack transparency, making it hard to trust decisions. This project addresses both: prediction and interpretability.

📂 Dataset
Source: Kaggle - Suicidal Tweet Detection Dataset

Size: ~10,743 tweets

Labels:

0: Non-suicidal

1: Potentially suicidal

⚙️ Tools & Technologies
Languages & Frameworks:

Python, Jupyter, Pandas, NumPy, Scikit-learn, TensorFlow

NLP & Modeling:

TF-IDF vectorization

Recurrent Neural Networks (RNN)

Machine Learning: SVM, Logistic Regression, Random Forest

Explainable AI (XAI) Tools:

🧠 ELI5

📊 Integrated Gradients (via Captum)

🌲 Tree Interpreter

🎯 Anchor

⚡ Gradient Attribution

🚀 Methodology
Data Preprocessing:

Cleaning, tokenization, and TF-IDF vectorization of tweets

Modeling:

RNN to capture sequential dependencies

SVM, Random Forest, Logistic Regression for comparative baselines

Explainability Layer:

Apply XAI tools to visualize model reasoning

Analyze word-level contributions for both suicidal and non-suicidal classifications

Evaluation:

Accuracy, Loss, Precision, and Model Interpretability

📈 Results
RNN Accuracy: ~89%

Integrated Gradients & Gradient Attribution: Showed clear identification of trigger words like “die”, “want”

Anchor Precision: 95% for word subsets significantly influencing predictions

Tree Interpreter & ELI5: Highlighted most impactful words per classification

📊 Visualizations
Feature importance graphs

Gradient spikes for RNNs

Anchor coverage insights

Word weight heatmaps

(You can embed image links or .pngs here from your outputs folder)

🎯 Conclusion
This project demonstrates how combining NLP with interpretable ML can effectively detect suicidal content in social media while providing transparency in decision-making. It opens the door for ethically safe and trustworthy AI applications in mental health tech.


