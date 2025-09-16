# customer-churn-eda

This project performs an exploratory data analysis (EDA) on a telecommunications dataset to identify the key factors driving customer churn. The goal is to provide data-driven insights and actionable recommendations to help a company reduce customer turnover.

The analysis is conducted using Python and popular data science libraries, with a focus on data cleaning, visualization, and summarization.

### **Dataset**
The dataset used in this project is the **Telco Customer Churn** dataset, available on Kaggle. It contains information on a fictional telecommunications company's customers, including services, account information, and whether they churned.

* **Source:** [https://www.kaggle.com/datasets/blastchar/telco-customer-churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

### **Key Findings**
Based on the analysis, several key factors were identified as having a significant impact on customer churn:

* **Contract Type:** Customers on a month-to-month contract have a significantly higher churn rate compared to those with one- or two-year contracts.
* **Internet Service:** Customers using **Fiber Optic** internet service show the highest churn rate.
* **Payment Method:** The churn rate is highest among customers who use **Electronic Check** as their payment method.
* **Tenure & Monthly Charges:** Churned customers, on average, have a shorter tenure and higher monthly charges than retained customers.


### **Technology Stack**
* **Python:** The core programming language.
* **Pandas:** For data manipulation and analysis.
* **NumPy:** For numerical operations.
* **Matplotlib & Seaborn:** For creating professional data visualizations.

### **How to Run the Code**
1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/your-username/telco-customer-churn-analysis.git](https://github.com/your-username/telco-customer-churn-analysis.git)
    cd telco-customer-churn-analysis
    ```
2.  **Download the Dataset:**
    Download the `Telco-Customer-Churn.csv` file from the [Kaggle link](https://www.kaggle.com/datasets/blastchar/telco-customer-churn) and place it in the project directory.
3.  **Install Dependencies:**
    ```bash
    pip install pandas numpy matplotlib seaborn
    ```
4.  **Run the Script:**
    ```bash
    python your_script_name.py
    ```
