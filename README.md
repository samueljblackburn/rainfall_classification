# **Rainfall Classification Model (XGBoost) 🌧️**  

## **Overview**  
This project is a machine learning model that predicts rainfall occurrence using **XGBoost**. The dataset comes from **Kaggle**, and the model is optimized for **AUC (Area Under the Curve)**.  

## **Dataset**  
- Source: https://www.kaggle.com/competitions/playground-series-s5e3/data
- Contains meteorological features to classify rainfall occurrence.  

## **Model & Approach**  
- **Algorithm**: XGBoost  
- **Metric**: AUC (Area Under the Curve)  
- **Optimization**: Hyperparameter tuning using GridSearchCV  
- **Notebook**: Implemented in **JupyterLab**  

## **Installation & Setup**  
To run this notebook, ensure you have the necessary dependencies installed:  

```bash
pip install pandas numpy scikit-learn xgboost matplotlib seaborn jupyterlab
```

## **Usage**  
1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/rainfall-classification.git
   cd rainfall-classification
   ```
2. Open the Jupyter Notebook:  
   ```bash
   jupyter lab
   ```
3. Run **rainfall_classification.ipynb** step by step.  

## **Results**  
- **AUC Score**: 0.852  
- **Feature Importance**: Temperature, Humidity, Wind Speed, etc.  
- **Visualizations**: ROC Curve, Feature Importance Plot  

## **Future Improvements**  
- Experiment with deep learning models (e.g., LSTMs).  
- Improve feature engineering techniques.  
- Optimize model inference speed for deployment.  

## **Contributing**  
Feel free to fork this repo and submit pull requests if you have improvements!  

## **License**  
This project is under the **MIT License**.  
