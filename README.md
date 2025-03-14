# Hyperspectral Imaging Analysis for DON Concentration Prediction

## Project Overview
This project involves analyzing hyperspectral imaging data to predict DON concentration in corn. The workflow includes exploratory data analysis (EDA), data transformation, dimensionality reduction using PCA, and model building.

## Folder Structure
- **`objective.docx`** – Contains key insights about the data.
- **`ImagOAI.ipynb`** – Jupyter Notebook with code implementation, including EDA, data transformation, PCA, and model building.

## Technologies Used
The following Python libraries were utilized:
- **pandas** – For data manipulation and analysis.
- **numpy** – For numerical computations.
- **scikit-learn** – For preprocessing, PCA, and machine learning models.
- **xgboost** – For boosting-based regression modeling.
- **matplotlib** & **seaborn** – For data visualization.
- **tensorflow** – For potential deep learning model experimentation.
- **scipy** – For statistical analysis and transformation techniques.

## Key Learnings
- **EDA was crucial** to understanding the data structure and patterns.
- **Data transformation techniques** like Yeo-Johnson and Huber loss were applied due to skewed data.
- **PCA was used** for dimensionality reduction to improve model efficiency.
- **Model performance evaluation:** Achieved **Good R-squared**
- **MLflow was explored** for experiment tracking but wasn’t fully implemented due to time constraints.
- **Reflectance values were key** in classifying whether corn is toxic or not.

## How to Run the Project
1. Install the required dependencies:
   ```bash
   pip install pandas numpy scikit-learn xgboost matplotlib seaborn tensorflow scipy
   ```
2. Open the `ImagOAI.ipynb` Jupyter Notebook.
3. Follow the structured workflow in the notebook:
   - **EDA** (Data visualization, correlation analysis, skewness check)
   - **Data Transformation** (Handling skewed data, normalization)
   - **Dimensionality Reduction** (PCA implementation)
   - **Model Building & Evaluation** (Training models and analyzing results)

## Future Enhancements
- Implement **MLflow** for tracking experiments.
- Explore deep learning models using **TensorFlow**.
- Fine-tune **XGBoost hyperparameters** to further optimize performance.

---
This README provides a comprehensive overview of the project, detailing the methodology, key learnings, and future improvements. 🚀

