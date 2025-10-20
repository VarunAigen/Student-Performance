# Student Performance Prediction

## **Overview**
This project predicts students’ final grades based on various demographic, social, and academic features using Python. The dataset used is `student-mat.csv`, which contains numerical/tabular data about students’ performance in mathematics.

---

## **Dataset**
- **Name:** student-mat.csv  
- **Type:** Tabular / Numerical  
- **Features:** Includes student demographic, social, and academic information (e.g., age, study time, failures, previous grades).  
- **Target:** Final grade (G3).  

---

## **Tools & Technologies**
- **Programming Language:** Python  
- **Libraries:** pandas, numpy, matplotlib, seaborn, scikit-learn, tensorflow / keras  
- **Visualization Tools:** Matplotlib and Seaborn  

---

## **Data Processing & Modeling**
- Handling missing values (if any)  
- Encoding categorical variables  
- Feature scaling (if required)  
- Splitting dataset into training and testing sets  
- **Model Used:** Multilayer Perceptron (MLP)  
- **Evaluation Metrics:** Mean Absolute Error (MAE), Mean Squared Error (MSE), R² Score  

---

## **Project Structure**
Student-Performance-Prediction/
│
├── student-mat.csv # Dataset file
├── Student_Performance.ipynb # Notebook containing EDA, preprocessing, model training, and evaluation
└── README.md # Project description

## **How to Run**
1. Clone the repository:
   ```bash
   git clone <your-repo-link>
2. Install required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn tensorflow
3. Open and run the notebook Student_Performance.ipynb in Jupyter Notebook or Google Colab.

## **Results**

Exploratory Data Analysis (data distribution and correlations)
Model performance metrics (MAE, MSE, R² Score)
Predicted vs Actual final grades visualization
