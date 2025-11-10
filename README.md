#  MNIST Handwritten Digit Recognition

This project demonstrates handwritten digit recognition using the MNIST dataset.
Two classic machine learning models — **K-Nearest Neighbors (KNN)** and **Gaussian Naive Bayes (GNB)** — were implemented and compared.

##  Dataset
- Source: MNIST (60,000 train, 10,000 test)
- Features: 28x28 grayscale pixel values
- Labels: digits (0–9)

##  Methods
- Data cleaning and normalization ([0, 255] → [0, 1])
- Dimensionality reduction via PCA (for KNN)
- Model training using scikit-learn

##  Results
| Model | Accuracy | Notes |
|:------|:----------|:------|
| Gaussian Naive Bayes | ~60% | Fast, simple baseline |
| KNN (k=3) | ~80% | Higher accuracy, slower prediction |

## Tools Used
- Python, Pandas, NumPy
- Scikit-learn
- Google Colab
- Matplotlib
- ReportLab, python-pptx

## 👤 Author
**Muddasar Razzaq**  
Employee of *Information Tech Consultants*  
MSc Data Science — *Ulster University*
