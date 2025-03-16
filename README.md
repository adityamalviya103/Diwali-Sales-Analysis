Diwali Sales Analysis

Overview
This project analyzes Diwali sales data to gain insights into customer purchasing behavior, demographic trends, and product performance. The analysis was performed using Python, Pandas, Seaborn, and Matplotlib.

Data Cleaning & Preprocessing
- Removed unnecessary columns (`Status`, `unnamed1`).
- Filled missing values in the `Amount` column with 0.
- Converted `Marital_Status` from 0/1 to `Unmarried`/`Married`.

Key Analyses & Findings
1. Demographics Analysis:
   - Gender-wise and Age-wise sales trends visualized.
   - State-wise and Occupation-wise purchasing behavior identified.
2. Sales Performance:
   - Total sales (`Amount`) and `Orders` analyzed across different attributes.
   - Identified top-selling Product Categories and Product_IDs.
3. Filtering for Specific Customer Segments:
   - Analyzed purchasing behavior of Married Women (26-35) in IT, Healthcare, Aviation sectors from selected states.
   - Issue found: `Marital_Status` needed conversion from numerical to categorical labels.
   
Visualizations & Improvements
- All plots resized for better readability (`plt.figure(figsize=(15,5))`).
- Applied number formatting to display sales values without scientific notation.
- Used `hue` in Seaborn `barplot` instead of `palette` for better future compatibility.
