# no_show_appointment_eng_version

In this project, we analyze data on patient appointments at hospital centers in Brazil.  

Each observation (or row) provides details about a specific appointment. For each appointment, specific attributes are recorded.  

The project was carried out in Jupyter Notebook. The libraries used are:  
- `pandas`  
- `numpy`  
- `matplotlib`  
- `seaborn`  

The goal is to understand the factors contributing to patients missing their hospital appointments.  

After exploring and visualizing the data, the following observations were made.  

### **Regarding patients' age:**  
The age groups 10-20 years and 20-30 years have the highest proportions of missed appointments, with:  

- **10-20 years:** 25.3% missed appointments  
- **20-30 years:** 24.6% missed appointments  

### **Regarding hospital locations:**  
The five locations with the highest percentage of missed appointments are:  

- **SANTOS DUMONT:** 28.9% missed appointments  
- **SANTA CECÍLIA:** 27.5%  
- **SANTA CLARA:** 26.5%  
- **ITARARÉ:** 26.3%  
- **JESUS DE NAZARETH:** 24.4%  

### **Regarding the days of the week:**  
Saturday has the highest percentage of missed appointments (23%). However, the other days have percentages that are not significantly different, such as Friday (21%) and Monday (20%).  

### **Regarding appointment hours:**  
There is a peak in the percentage of missed appointments at **8 PM and 9 PM** (30% and 33%, respectively).  
The lowest percentages of missed appointments occur during early morning hours (between 6 AM and 9 AM).  

### **Regarding messages received by patients:**  
It is possible that reminder messages impact whether a patient attends their appointment. Indeed, the percentage of those who attend **without receiving messages** is higher than those who attend **after receiving messages** (83% vs. 72%). This is an observation that requires further investigation.  

To draw conclusions, statistical tests will be conducted, which will likely be the subject of a future report.  
