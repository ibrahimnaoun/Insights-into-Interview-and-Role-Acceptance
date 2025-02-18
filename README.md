# 📌 Interview Selection Analysis

## 📖 About the Project
This project analyzes interview selection factors based on real evaluation data. We explore what influences selection and rejection decisions, providing insights to help candidates prepare effectively.

## 📂 Dataset
The dataset used in this analysis can be found here: [Interview Selection Dataset](https://www.kaggle.com/datasets/suryasanju/interview-selection-dataset)

## 📊 Key Findings
- **Structured Thinking in Call Pitch** is the most influential factor.
- **Confidence on a given topic** strongly impacts selection chances.
- **Fluency in English** plays a significant role.
- **Work experience and current employment status have minimal impact** on selection.

## 🔬 Logistic Regression Results
**Accuracy:** 83%  
**Precision & Recall:**
          precision    recall  f1-score   support

       Reject       0.72      0.46      0.56       881
       Select       0.85      0.94      0.90      2860
       accuracy                         0.83      3741
       macro avg    0.79      0.70      0.73      3741
       weighted avg 0.82      0.83      0.82      3741

**Feature Importance (Coefficients):**
| Feature | Coefficient |
|---------|------------|
| Structured Thinking (Call Pitch) | 1.31 |
| Structured Thinking (Regional) | 0.72 |
| Confidence on Given Topic | 0.49 |
| Fluency in English | 0.30 |
| Confidence in Introduction | 0.26 |
| Currently Employed | 0.06 |
| Experience (Months) | 0.004 |

## 📌 Key Takeaways for Candidates
✅ Structure your responses logically.  
✅ Speak with confidence—practice mock interviews.  
✅ Improve English fluency for better communication.  
✅ Work experience matters less than presentation skills.  

## 📁 Files
- `Insights into Interview and Role Acceptance.ipynb` → Jupyter Notebook with full analysis and visualizations.
- `README.md` → This file.

## 🚀 Future Improvements
- Try different ML models for better predictions.
- Expand dataset with more interview cases.
- Perform deeper NLP analysis on responses.

📢 **Want to ace your interview? Work on structure, confidence, and fluency!** 🚀
