*Patient's In Out Analysis*

Business Problem- 
Clinics often struggle to track patient trends, doctor performance, and department workload efficiently.  This dashboard solves that by providing a centralized view of patient data to improve operational decisions.

Key Insights-
- Neurology and General Physician departments handle the highest patient load  
- 55%+ patients are male, indicating a gender imbalance  
- Peak patient visits observed around mid-month  
- Some doctors have high referral % indicating specialization or overload  

Sample DAX Measures-
Avg Age = AVERAGE(Patients[Age])
IP % = DIVIDE([In Patients], [Total Patients])
Referral % = DIVIDE([Referrals], [Total Patients])


