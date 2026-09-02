# 🫀 Predicting Heart Disease with Linear Regression

## 👋 Hi there!
This is my submission for **Task 3** of the AI & ML Internship at **Elevate Labs**. 

For this task, I dove into **Multiple Linear Regression** to build a model that predicts the percentage of heart disease based on lifestyle choices—specifically biking and smoking. It was a great way to see how code can find patterns in real-world health data!

## 🧐 What's this project about?
The goal was simple: can we predict heart disease risk just by looking at how much someone bikes and smokes? 

I used a linear regression model to find the relationship between these habits. As you might guess, the model confirmed that healthy habits (biking) tend to lower the risk, while unhealthy ones (smoking) raise it.

## 📂 The Data
I used the `heart.data.csv` file for this analysis. It has three main columns:
* **biking:** The distance a person bikes.
* **smoking:** How much a person smokes.
* **heart.disease:** The percentage chance of having heart disease (this is what we are predicting).

## 🛠️ Tools I Used
* **Python** (obviously!)
* **Pandas** to load and clean up the messy data.
* **Scikit-learn** to actually build and train the machine learning model.
* **Seaborn & Matplotlib** to create the charts and visualize the results.

## 🚀 My Workflow
Here is how I approached the problem:
1.  **Loading the Data:** I started by loading the CSV and checking for any weird formatting (like that extra index column).
2.  **Splitting:** I split the data into a **training set** (to teach the model) and a **test set** (to quiz it later).
3.  **Training:** I fitted the Linear Regression model to the training data.
4.  **Testing:** I let the model predict heart disease rates for the test set to see how close it got to the real numbers.
5.  **Visualizing:** I plotted the predicted values against the actual values to visually check the accuracy.

## 📊 Results & What They Mean
The model actually performed really well!
* **R² Score:** ~0.98 (This basically means the model explains 98% of the patterns in the data, which is awesome).
* **MAE (Mean Absolute Error):** ~0.52 (On average, the prediction is only off by about 0.5%).

**Key Takeaway:** The math confirmed that biking has a negative coefficient (reduces risk) and smoking has a positive one (increases risk).

## 📸 Visuals
Check out the plots in the notebook/code! The "Actual vs. Predicted" scatter plot shows the dots lining up almost perfectly on the red line, which felt pretty satisfying to see.

## 💻 How to Run It
If you want to test this out on your own machine:

1.  Clone this repo.
2.  Make sure you have the libraries installed:
    ```bash
    pip install pandas matplotlib seaborn scikit-learn
    ```
3.  Run the script:
    ```bash
    python task_3.py
    ```

---
*Thanks for checking out my task submission!*
