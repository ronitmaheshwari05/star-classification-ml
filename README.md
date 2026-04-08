# AstroML: Machine Learning Framework for Stellar Classification


![Python](https://img.shields.io/badge/Python-3.x-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![License](https://img.shields.io/badge/License-MIT-green)

---

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

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/numpy-013243?style=for-the-badge&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" />
  <img src="https://img.shields.io/badge/matplotlib-11557C?style=for-the-badge&logo=matplotlib&logoColor=white" />
  <img src="https://img.shields.io/badge/seaborn-4C72B0?style=for-the-badge&logo=seaborn&logoColor=white" />
</p>

---

## How to Run

1. Clone the repository  
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook and run all cells  

---

## Contributing

Contributions are welcome and appreciated.

If you would like to improve this project:
- Fork the repository  
- Create a new branch  
- Make your changes  
- Submit a Pull Request

Please ensure your code is clean and well-documented.

---

## Support

If you find this project useful, consider giving it a star.

Your support helps improve visibility and encourages further development.

---

## Issues

If you encounter any bugs or have suggestions, feel free to open an issue in the repository.

---

## Author
Ronit Maheshwari
