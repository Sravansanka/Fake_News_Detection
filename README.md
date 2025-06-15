📘 Fake News Detection - README
🎯 Objective
This assignment aims to develop a Semantic Classification model to distinguish between true and fake news articles. Using the Word2Vec method, we capture semantic relations and apply supervised learning models to classify news based on meaning rather than syntax.
🏢 Business Objective
The rampant spread of fake news has made it crucial to deploy intelligent systems that can automate the detection of misinformation. This project demonstrates how semantic classification can help news platforms and users verify content effectively.
🗂️ Dataset Description
🔹 True.csv – 21,417 records of true news articles.
🔹 Fake.csv – 23,502 records of fake news articles.
Each dataset contains:
🔹 📌 title: Title of the news article
🔹 📌 text: Main content of the news article
🔹 📌 date: Date of publication
📊 Observed Patterns
🔹 ✅ True News: Formal language, factual nouns, domain-specific terminology, structured writing.
🔹 ⚠️ Fake News: Emotionally charged language, repetitive phrases, informal structure, frequent misleading n-grams.
🔹 📈 Word clouds and frequency analysis showed distinct linguistic styles across classes.
🔧 Methodology
🧹 Preprocessing
🔹 Text cleaning
🔹 Lemmatization
🔹 POS filtering (focused on nouns)
🧠 Feature Engineering
🔹 Used pre-trained Word2Vec embeddings to convert text into semantic vectors.
🧪 Models Used
🔹 Logistic Regression
🔹 Decision Tree
🔹 Random Forest
📐 Model Evaluation
🔹 Validation Accuracy: 0.8600
🔹 Precision: 0.8590
🔹 Recall: 0.8701
🔹 F1 Score: 0.8645
Classification Report:
Label	Precision	Recall	F1-Score	Support
0 (Fake)	0.86	0.85	0.86	73
1 (True)	0.86	0.87	0.86	77
Overall	0.86	0.86	0.86	150
🔍 Conclusion
🔹 Semantic modeling improves classification robustness.
🔹 Word2Vec embeddings enrich feature quality without needing deep learning.
🔹 Random Forest performs best for this type of text classification.
🔹 The model supports scalable and practical deployment for misinformation detection.
🔮 Future Work
🔹 Fine-tune Word2Vec on domain-specific news data.
🔹 Integrate transformer-based embeddings (e.g., BERT) for context-aware classification.

🖋️ **Author**: Sravana Sanka & Shriyan
