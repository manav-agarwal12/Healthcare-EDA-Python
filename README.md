# 📊 Medical Appointments Data Analysis (EDA)

## 📝 Project Overview
This project focuses on understanding **why patients miss medical appointments** by performing an in-depth **Exploratory Data Analysis (EDA)** on a real-world dataset of medical appointments in Brazil.  
The analysis uncovers **patterns, correlations, and insights** that could help healthcare providers improve appointment attendance and optimize patient communication.

---

## 📖 Project Story
Hospitals often struggle with patients **not showing up** for their scheduled medical appointments. This leads to wasted resources, longer waiting times, and inefficiencies in healthcare delivery.  

The key question we aimed to answer was:  
**“What factors influence whether a patient shows up for their medical appointment?”**

By analyzing over **110,000 patient records**, including demographics, health conditions, appointment details, and reminder messages, we identified important trends that explain patient behavior and attendance patterns.

---

## 📊 Dataset Details
The dataset contains **110k+ rows** and **14 columns**, with features such as:
- **Patient demographics**: Gender, Age  
- **Appointment details**: Scheduled Day, Appointment Day, Neighbourhood  
- **Medical history**: Hypertension, Diabetes, Alcoholism, Handicap  
- **Communication**: SMS_received (reminder sent)  
- **Target variable**: No-show (Yes/No)  

---

## ⚙️ Tools & Technologies
- **Programming Language**: Python  
- **Data Analysis & Wrangling**: Pandas, NumPy  
- **Data Visualization**: Matplotlib, Seaborn  
- **Notebook Environment**: Jupyter Notebook  

---

## 📈 Key Results & Insights
**General Findings**

- 32% of patients did not show up for their appointment.

- Younger patients (age < 30) had a no-show rate of ~38%, compared to 17% in older patients (age > 60).

- Certain neighborhoods showed no-show rates above 40%, highlighting geographic disparities.

- There are no appointments on Sundays, and Saturday appointments are very few compared to weekdays.

**Demographics**

- Female patients booked more appointments than male patients.

- Ratio of Show vs. No-show is almost equal across age groups, except for Age 0 and Age 1, which had an 80% show rate.

- Each Neighbourhood had an overall ~80% show rate.

**Social & Medical Factors**

- Out of 99,666 patients without Scholarships, ~80% showed up.

- Out of 21,801 patients with Scholarships, ~75% showed up.

- Out of 88,726 patients without Hypertension, ~78% showed up.

- Out of 21,801 patients with Hypertension, ~85% showed up.

- Out of 102,584 patients without Diabetes, ~80% showed up.

- Out of 7,943 patients with Diabetes, ~83% showed up.

**Communication (SMS Reminders)**

- Out of 75,045 patients without SMS reminders, ~84% showed up.

- Out of 35,482 patients with SMS reminders, only ~72% showed up.

  ---

## 🎯 Conclusion

- The analysis demonstrates that age, chronic conditions, SMS reminders, gender, and neighborhood strongly influence no-show behavior.
Key takeaways:

- Hypertension/Diabetes patients are more likely to attend appointments.

- SMS reminders alone are not enough; they may even correlate with lower attendance, suggesting that patients with higher risk of no-show were targeted.

- By focusing on high-risk groups (younger patients, scholarship recipients, SMS recipients), hospitals can potentially reduce no-show rates by 20–25%.

  ---

## 🔹 Author & Contact  
**Author**: Manav Agarwal  
📧 **Email**: *agarwalmanav1202@gmail.com*  
🔗 **LinkedIn**: [linkedin.com/in/agarwalmanav120105](#)  
💻 **GitHub**: [github.com/manav-agarwal12](https://github.com/manav-agarwal12)

---
