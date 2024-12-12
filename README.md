# Comparison-of-FDA-and-ReliefF-for-Feature-Reduction-in-Cancer-Classification-Using-Machine-Learning

The program was made in Google Colab using Python 3
Project Link: [https://drive.google.com/file/d/1hjshpWTrIDtshX5W7hMb3RXnFKneIYsI/view?usp=sharing](https://colab.research.google.com/drive/1WCAE94yAz-Lhq8AUuH2lo2ucTyz_1lEB?usp=sharing) (Open with Google Colaboratory)

The code file is also located in this GitHub project with the name: "Comparison-of-FDA-and-ReliefF-for-Feature-Reduction-in-Cancer-Classification-Using-Machine-Learning"

This project focuses on classifying cancer subtypes using gene expression data from the Gene Expression Cancer RNA-Seq dataset. The dataset contains high-dimensional features, making it challenging for machine learning models to perform effectively. To address this, two feature reduction techniques are applied:
1. Fisher Discriminant Analysis (FDA) – A feature extraction method that maximizes class separability.
2. ReliefF – A feature selection method that identifies the most relevant features for classification.

The project evaluates the performance of six machine learning classifiers:
- Mahalanobis Distance
- K-Nearest Neighbors (KNN)
- K-Means
- Support Vector Machine (SVM)
- Random Forest
- Neural Network

## Key Features of the Project

- Feature Reduction: Comparison of FDA and ReliefF to reduce the high-dimensional gene expression data.
- Model Evaluation: Performance assessed using 5-fold cross-validation.
- Visualization: Confusion matrices to analyze classification errors.
- Results: Detailed analysis and comparison of classifier performance with both feature reduction methods.

## Technologies Used
- Python
- Scikit-Learn
- Pandas
- NumPy
- Matplotlib

## Dataset
- Source: UCI Machine Learning Repository – Gene Expression Cancer RNA-Seq dataset.
- Classes: 5 cancer subtypes (BRCA, KIRC, COAD, LUAD, PRAD).

## How to Run the Project
1. Clone the repository:

   #--- git clone https://github.com/yourusername/cancer-classification.git
                #-- Visualizamos la imagen hibrida r
       ###-- cd cancer-classification
   
3. Install dependencies:
    #-- pip install -r requirements.txt
4. Run the notebook or script to perform feature reduction and model training.

