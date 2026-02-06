# VeriFact-Fake-News-Detector
Developing an NLP system using BERT to classify misinformation with 92% accuracy. Built REST APIs using FastAPI and deployed the model as a web application.

Day 1:
- Environment setup
- Dataset loaded
- Project structure created
## 📊 Dataset Information

The model is trained on the **ISOT Fake News Dataset**. Due to file size constraints, large CSV files are managed via **Git LFS**.

* **Source:** [Kaggle - ISOT Fake News Dataset](https://www.kaggle.com/datasets/rahulogoel/isot-fake-news-dataset)
* **Files Managed via LFS:** * `data/Fake.csv` (~60 MB)
    * `data/True.csv` (~51 MB)
* **Format:** CSV files containing `title`, `text`, `subject`, and `date`.
