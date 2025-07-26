# Telecom User Data Analysis

This repository contains a Jupyter Notebook (`Telecom_Plan_Scaled_final.ipynb`) and a synthetic dataset (`synthetic_telecom_user_data.csv`) for analyzing telecom user behavior and plan distributions.

Files

* Telecom_Plan_Scaled_final.ipynb`
    * Description: This Jupyter Notebook contains Python code for analyzing telecom user data. It reads the `synthetic_telecom_user_data.csv` file, performs data analysis, and likely includes visualizations to understand user behavior and current plan distributions. The notebook appears to use the pandas library for data manipulation.
    * Key Operations (based on initial code):
        * Loading data from `synthetic_telecom_user_data.csv` into a pandas DataFrame.
        * Displaying the head of the DataFrame to show initial data structure.
    * Potential Analysis (inferred from file names and data):
        * Analysis of average monthly data usage (GB).
        * Analysis of average voice minutes.
        * Analysis of average SMS count.
        * Understanding current telecom plans and their costs in INR.
        * Visualizations of the data.

* `synthetic_telecom_user_data.csv`
    * Description: This CSV file contains synthetic user data for a telecom company. It includes various metrics related to user consumption and their current plans.
    * Columns:
        * user_id: Unique identifier for each user.
        * avg_monthly_data_gb: Average monthly data consumption in gigabytes.
        * avg_voice_minutes: Average monthly voice call minutes.
        * avg_sms_count: Average monthly SMS count.
        * current_plan: The current telecom plan subscribed by the user (e.g., DataPlus, TalkMax, UltraMax, Basic).
        * plan_cost_inr: The cost of the current plan in Indian Rupees (INR).

How to Use:
1.  Ensure both `Telecom_Plan_Scaled_final.ipynb` and `synthetic_telecom_user_data.csv` are in the same directory.
2.  Open the `Telecom_Plan_Scaled_final.ipynb` notebook using a Jupyter environment (e.g., JupyterLab, Jupyter Notebook, Google Colab).
3.  Run the cells in the notebook to execute the data analysis and generate outputs.
