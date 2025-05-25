## Sentiment Analysis of Amazon Fine Food Reviews 🛒📊

This project performs sentiment analysis on the [Amazon Fine Food Reviews dataset](https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews), aiming to classify customer reviews as either **Positive** or **Negative** using machine learning models.

---

## 📌 Project Objectives

- Analyze real-world product reviews using NLP and ML.
- Build models to classify sentiment while handling challenges like negation and noisy text.
- Compare baseline models (Logistic Regression) with more robust models (SVM).
- Evaluate and visualize results to understand performance.
- Document the system clearly for reproducibility and future use.

---

## 📁 Folder Structure

sentiment-analysis-reviews/
├── data/                    # (Optional) sample or link to dataset
├── models/                  # Saved model files (.pkl)
├── visuals/                 # Plots, charts, UML diagram
├── sentiment_analysis.py    # Main script or use .ipynb
├── requirements.txt         # Dependencies
├── README.md                # This file
├── presentation.pdf         # Phase 2 slide deck
└── final_report.pdf         # Final project report

---

## 🧠 Dataset

- **Source:** Kaggle – [Amazon Fine Food Reviews](https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews)
- **Size:** 568,000+ reviews
- **Fields Used:** `Text` and `Score`
- **Labeling:**  
  - `Score >= 4` → Positive  
  - `Score <= 2` → Negative  
  - Neutral (Score = 3) removed

---

## ⚙️ How to Run

1. **Clone the repo**
```bash
git clone (https://github.com/SaarthakSolomon/sentiment-analysis-reviews)
cd sentiment-analysis-reviews
```

2. **Create and activate virtual environment (optional but recommended)**
```bash
python -m venv venv
source venv/bin/activate   # or venv\Scripts\activate on Windows
```

3. **Install dependencies**
```bash
pip install -r requirements.txt
```

4. **Run the script**
```bash
python sentiment_analysis.py
```

---

## 🔍 Model Overview

| Model                | Accuracy | F1 Score |
|---------------------|----------|----------|
| Logistic Regression | 87%      | 0.86     |
| SVM                 | 89%      | 0.88     |

- **TF-IDF** used for feature extraction
- **SVM** chosen as final model due to stronger class generalization
- Models evaluated with confusion matrix, accuracy, and F1-score

---

## 📊 Visual Outputs

- Confusion matrix heatmap
- Model comparison bar chart
- UML diagram for system architecture

Available under the `/visuals` folder.

---

## 💡 Future Work

- Add neutral sentiment classification
- Deploy as a web app using Flask or Streamlit
- Extend to multilingual datasets
- Integrate with customer support tools for real-time sentiment tracking

---

## 📌 References

- [Kaggle: Amazon Fine Food Reviews](https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews)
- [Scikit-learn Documentation](https://scikit-learn.org/)
- [NLTK](https://www.nltk.org/)
- [Seaborn & Matplotlib](https://matplotlib.org/)

---

## 🧠 Author
**Saarthak Solomon**  
---

```
