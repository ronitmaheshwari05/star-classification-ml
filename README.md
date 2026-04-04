# Star Classification using Machine Learning

## Project Overview
This project focuses on predicting the type of stars using machine learning models based on their physical characteristics, including Temperature, Luminosity, Radius, Absolute Magnitude, Color, and Spectral Class.

The objective is to evaluate and compare multiple classification algorithms to determine the most reliable model for star classification.

---

## Dataset
The dataset contains astrophysical properties of stars with the target variable **Type**, representing different categories of stars.

### Target Classes
- 0 – Red Dwarf  
- 1 – Brown Dwarf  
- 2 – White Dwarf  
- 3 – Main Sequence  
- 4 – Super Giants  
- 5 – Hyper Giants  

---

## Machine Learning Models Used
- Logistic Regression  
- Decision Tree  
- Random Forest  
- Support Vector Machine (SVM)  
- K-Nearest Neighbors (KNN)  

---

## Model Performance

| Model | Accuracy |
|------|--------|
| Logistic Regression | 0.9167 |
| Decision Tree | 1.0000 |
| Random Forest | 0.9792 |
| SVM | 0.9375 |
| KNN | 0.9167 |

---

## Analysis and Insights

- Random Forest achieved the best performance with high accuracy and strong generalization capability.  
- Decision Tree achieved perfect accuracy on the test data, but this indicates overfitting and reduced reliability on unseen data.  
- Support Vector Machine performed well after feature scaling and handled non-linear decision boundaries effectively.  
- Logistic Regression and K-Nearest Neighbors provided baseline performance for comparison.  

---

## Feature Importance

The most influential features identified were:
- Absolute Magnitude (A_M)  
- Radius (R)  
- Luminosity (L)  

Other features such as Temperature, Spectral Class, and Color showed lower contribution but still supported the model’s predictions.

---

## Conclusion

Random Forest is the most suitable model for this problem as it provides a strong balance between accuracy and generalization.

Although Decision Tree achieved perfect accuracy, it is prone to overfitting and may not generalize well to unseen data. Therefore, it is not considered a reliable model in this context.

---

## Future Work

- Hyperparameter tuning for improved performance  
- Cross-validation for more robust evaluation  
- Deployment using a web-based interface  
- Advanced model explainability techniques  

---

## Technologies Used

- Python  
- pandas  
- numpy  
- scikit-learn  
- matplotlib  
- seaborn  

---

## How to Run

1. Clone the repository  
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook and run all cells  

---

## Author
Ronit Maheshwari
