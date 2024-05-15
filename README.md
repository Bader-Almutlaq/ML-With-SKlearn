# Machine Learning Experiments with Medical Datasets

This project involves experimenting with three publicly available medical datasets to explore classification, regression, and clustering tasks using various machine learning algorithms implemented in scikit-learn. The datasets used are the Heart Disease dataset, Diabetes dataset, and Breast Cancer Wisconsin dataset.

## Setup

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/project.git
    cd project
    ```

2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the Flask application:
    ```bash
    python app.py
    ```

4. Open your web browser and go to `http://127.0.0.1:5000/` to use the application.

## Datasets

- **Heart Disease Dataset**: Contains 14 attributes related to heart disease.
- **Diabetes Dataset**: Contains 10 attributes related to diabetes progression.
- **Breast Cancer Wisconsin Dataset**: Contains 30 attributes computed from a digitized image of a fine needle aspirate of a breast mass.

## Tasks

- **Classification**: Predict the presence or absence of heart disease and diagnose breast cancer.
- **Regression**: Predict diabetes progression.
- **Clustering**: Cluster breast cancer data to find natural groupings.

## Models

### Classification Algorithms
1. Logistic Regression
2. k-Nearest Neighbors (k-NN)
3. Decision Tree
4. Support Vector Machine (SVM)
5. Random Forest (Ensemble)
6. Gradient Boosting (Ensemble)
7. Naive Bayes
8. Extra Trees Classifier (Ensemble)
9. AdaBoost (Ensemble)
10. XGBoost (Ensemble)

### Regression Algorithms
1. Linear Regression
2. Decision Tree Regressor
3. Random Forest Regressor

### Clustering Algorithms
1. K-Means
2. Agglomerative Clustering
3. DBSCAN

## Results

The results are displayed on the web interface after running the experiments. The performance metrics used are:

- **Classification**: Accuracy, Precision, Recall, F1-score, ROC-AUC.
- **Regression**: Mean Absolute Error (MAE), Mean Squared Error (MSE), R-squared score.
- **Clustering**: Silhouette score, Davies-Bouldin index.
