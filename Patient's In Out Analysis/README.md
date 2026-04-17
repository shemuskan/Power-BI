*Patient's In-Out Analysis Dashboard*

Business Problem  
Clinics and hospitals often face challenges in:
- Tracking patient inflow and outflow  
- Monitoring doctor performance  
- Managing department workload efficiently  


Key Insights  
- Neurology and General Physician departments handle the highest patient load  
- Over 55% of patients are male, indicating a gender imbalance  
- Patient visits peak around the mid-month period  
- Some doctors have high referral %, indicating specialization or overload  

Sample DAX Measures  
Avg Age = AVERAGE(Patients[Age])

IP % = DIVIDE([In Patients], [Total Patients])

Referral % = DIVIDE([Referrals], [Total Patients])



Dashboard Preview  
<img width="1908" height="932" alt="Animation" src="https://github.com/user-attachments/assets/864a0740-20b1-4d7e-ab3a-825876e80f74" />


