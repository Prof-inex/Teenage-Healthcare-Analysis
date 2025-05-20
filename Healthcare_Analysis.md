
# Teenage Healthcare Data Analysis

This project analyzes a healthcare dataset obtained from [Kaggle](https://www.kaggle.com/) to uncover patterns specifically related to **teenage patients (ages 13–19)**. The dataset originally includes 55,500 records, from which 1,693 teenage entries were extracted and analyzed.

---

## Project Objectives

- Explore demographic trends among teenage patients (gender, blood type).
- Identify the most common medical conditions and medications.
- Analyze hospital admission patterns, billing, and length of stay.
- Investigate the relationship between blood type and medical condition using statistical analysis.

---

## Tools & Technologies

- Python (Pandas, Matplotlib, Seaborn, SciPy)
- Tableau (for interactive visualizations)
- Jupyter Notebook

---

## Key Insights

1. **Demographics**: Female teens slightly outnumber male teens in the dataset.
2. **Health Trends**: 
   - Arthritis is the most common condition overall.
   - Ibuprofen is the most prescribed drug for females; Lipitor for males.
3. **Cost & Billing**:
   - Hypertension has the highest mean billing amount, despite being less prevalent.
   - Negative billing values indicate copayments, and these were excluded from average cost analysis.
4. **Length of Stay**:
   - The average stay is 15 days; Obesity-related cases had slightly shorter durations.
5. **Admissions**:
   - Emergency admissions are most common across both genders.
   - September 2019 saw the highest number of admissions.
6. **Statistical Analysis**:
   - No statistically significant relationship was found between blood type and medical condition (p-value > 0.05).

---

## 📊 Tableau Dashboard

To complement the data analysis, an interactive dashboard was created using Tableau to visualize key healthcare insights among teenage patients.

👉 [**View Dashboard on Tableau Public**](https://public.tableau.com/views/TeensHospitalDataInsight/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

![Teen Healthcare Dashboard](https://public.tableau.com/thumb/views/TeensHospitalDataInsight/Dashboard1?:language=en-US)

### Dashboard Highlights:
- Distribution of common medical conditions among teens
- Medication patterns segmented by gender
- Average billing by medical condition
- Monthly admission trends

---

## How to Use

1. Clone the repository or download the `.ipynb` file.
2. Open the notebook in JupyterLab, Jupyter Notebook, or Google Colab.
3. Run the cells step by step to follow the data analysis process.

---

## Conclusion
-
This project reveals critical insights into the healthcare utilization patterns among teenagers. While conditions like arthritis and obesity are more prevalent, hypertension cases tend to be more costly—possibly due to more complex care needs or associated comorbidities. The absence of a statistical link between blood type and condition suggests that other factors play a more substantial role in teen health outcomes. These findings can guide further research, policy development, and educational efforts in adolescent healthcare.
---

## Dataset Source

The dataset used in this project is publicly available on [Kaggle](https://www.kaggle.com/).

---

## Author

**[Olusegun Ajala]**  
_Data Analyst | Python | Excel | Tableau_
