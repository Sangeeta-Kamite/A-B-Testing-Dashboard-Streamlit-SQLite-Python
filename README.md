# AB-Testing-Dashboard-Streamlit-SQLite-Python
This project demonstrates how to conduct and visualize A/B testing using real-world style data on conversion rates. It features a complete pipeline from data generation to statistical testing, dashboard visualization, and interactive insights using Python, SQLite, and Streamlit.

**Project Goals**
- Simulate and store A/B testing data in a lightweight relational database (SQLite)
- Compare conversion performance between Group A and Group B
- Apply statistical hypothesis testing (t-test) to assess significance
- Build a visual and interactive Streamlit dashboard for business insight
- Deploy on Google Colab using pyngrok for easy web access

**Dataset Overview**
Simulated Data: Mimics A/B testing outcomes (conversion or no conversion)
Fields:
- user_id: Unique user identifier
- group: A or B (treatment vs. control)
- converted: Binary outcome (1 = converted, 0 = not)

**Technologies Used**
- Python: Core programming logic
- SQLite:	Lightweight database to store A/B data
- Streamlit:	Interactive web dashboard
- Pandas: Data manipulation and preprocessing
- Scipy:	T-test and statistical calculations
- Matplotlib:	Conversion rate visualization
- Pyngrok:	Public URL access via Google Colab

**Project Features**
- Generate synthetic A/B test data and store in SQLite
- Real-time bar chart comparison of conversion rates
- Statistical inference (p-value) with interpretation
- User-friendly interface for students, analysts, or marketers
- Deployed from Google Colab with ngrok tunnel

**A/B Testing & Statistics**

**1. Test Used:** Independent t-test (scipy.stats.ttest_ind)

**2. Hypothesis:**
   - Null: No difference in conversion rates between A and B
   - Alt: Significant difference exists

**3. Output:**
   - Mean conversions
   - p-value
   - Statistical conclusion (Significant / Not Significant)

**Performance Metrics**
- Conversion rate for each group
- Difference in conversion rate
- p-value (threshold 0.05)
- Visualization of group-wise performance

