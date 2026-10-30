# 🏥 Apollo Hospital Appointment Analysis

### Business Insights | Patient Attendance | Revenue | Doctor Utilisation

## 📌 1. Project Overview

This project analyzes hospital appointment data to understand patient attendance patterns, appointment trends, no-show behaviour, revenue-related patterns, and doctor utilisation.

The objective is to use Python and data analysis techniques to identify meaningful business insights that can help improve hospital operations and support better decision-making.

## 🎯 2. Business Problem

Missed appointments, cancellations, patient waiting time, and inefficient appointment management can affect hospital operations and revenue.

This analysis explores appointment data to understand these challenges and identify patterns that may help hospital management improve operational efficiency.

## 🎯 3. Project Objectives

- Analyze appointment trends over time.
- Understand completed, cancelled, and no-show appointments.
- Identify patient groups and booking patterns associated with no-shows.
- Explore the relationship between reminders and patient attendance.
- Analyze revenue patterns and patient payment behaviour.
- Understand doctor utilisation and patient waiting time.
- Explore consultation duration and patient satisfaction.

## 📂 4. Dataset Information

The project uses two datasets:

| Dataset | Records | Description |
|---|---:|---|
| Appointments | 75,000 | Hospital appointment details |
| Doctors | 320 | Doctor-related information |

## 🛠️ 5. Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 🔍 6. Analysis Performed

### A. Appointment Analysis

- Appointment volume by month and quarter.
- Appointment status distribution.
- Year-wise appointment trends.

### B. Patient Attendance & No-Show Analysis

- No-show rate analysis.
- Booking lead-time analysis.
- Weekday and weekend comparison.
- Time-of-day analysis.
- Reminder and previous attendance patterns.

### C. Revenue & Payment Analysis

- Revenue-related patterns.
- Payment mode distribution.
- Insurance coverage and out-of-pocket expenses.
- Estimated revenue impact of missed appointments.

### D. Doctor & Operational Analysis

- Appointment volume by specialty.
- Doctor utilisation analysis.
- Average patient waiting time.
- Consultation duration and patient satisfaction.

## 📊 7. Key Business Insights

### Appointment Performance

| KPI | Result |
|---|---:|
| Total Appointments | 75,000 |
| Unique Patients | 32,705 |
| Completed Appointments | 55,275 |
| No-Show Appointments | 11,584 |
| Cancelled Appointments | 5,793 |
| Completion Rate | 73.70% |
| No-Show Rate | 15.45% |

### Appointment Trends

- December 2023 recorded the highest monthly appointment volume with 2,342 appointments.
- June 2022 recorded the lowest monthly volume with 1,863 appointments.
- Q4 recorded the highest appointment volume in each of the three years analyzed.

### Booking Lead-Time Insight

- Appointments booked 0–1 days in advance had a 13.22% no-show rate.
- Appointments booked 15–30 days in advance had a 20.03% no-show rate.

### Insurance Insight

- Patients without insurance had an average out-of-pocket expense of approximately 1,138.
- Patients with insurance had an average out-of-pocket expense of approximately 649.

## 📁 8. Project Structure

```text
Apollo-Appointment-Analysis/
│
├── Apollo_Appointment_Analysis.ipynb
├── apollo_appointments_fact.csv
├── apollo_doctors_dim.csv
└── README.md
```

- **Apollo_Appointment_Analysis.ipynb** – Complete Python analysis, data cleaning, exploration, and visualizations.
- **apollo_appointments_fact.csv** – Hospital appointment dataset.
- **apollo_doctors_dim.csv** – Doctor information dataset.
- **README.md** – Project documentation.

## 📂 9. Project Files

- `Apollo_Appointment_Analysis.ipynb` — Complete data analysis notebook.
- `apollo_appointments_fact.csv` — Hospital appointment dataset.
- `apollo_doctors_dim.csv` — Doctor details dataset.

## ▶️ 10. How to Run the Project

1. Clone or download this repository.
2. Keep the notebook and both CSV files in the same folder.
3. Install the required Python libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

4. Open Jupyter Notebook.
5. Open `Apollo_Appointment_Analysis.ipynb`.
6. Run all cells in sequence.

## 💡 11. Conclusion

This project demonstrates how Python-based data analysis can be used to explore hospital appointment trends, patient attendance, booking behaviour, payment patterns, and operational performance.

The analysis provides useful insights that can support better appointment planning and data-driven decision-making.

---

## 👤 Author
**Ankit Kumawat**

Aspiring Data Analyst

**Skills:** Advanced Excel | SQL | Power BI | Python

**LinkedIn:** https://www.linkedin.com/in/ankit-kumawat-da/
