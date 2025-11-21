# Travel Procurement Analytics Dashboard

This project delivers a full travel procurement analytics solution based on real-world responsibilities of an **Assistant Category Manager (Travel)**. It analyzes global travel spend, agency performance, trip efficiency, and sustainability impact using Python and Power BI.

The goal is to simulate the type of analysis Maersk would expect when managing categories such as Flights, Hotels, Agencies, Meetings & Events, and Travel Management Companies.

---

# Project Overview

A complete end-to-end analytics workflow was built:

1. **Data Preparation (Python)**
   - Cleaned and merged 270k+ rows of travel data  
   - Joined users, flights, and hotels  
   - Built trip-level metrics with custom logic  

2. **Feature Engineering**
   - Total trip cost  
   - Cost per km, cost per night, cost per flight  
   - Trip duration estimation  
   - High-cost trip flags using z-score  
   - CO₂ calculations for flights and hotels  
   - Supplier (agency) performance indicators  

3. **Interactive Power BI Dashboard**
   - 3 fully designed pages:
     - **Travel Cost & Efficiency**
     - **Supplier / Agency Performance**
     - **Trips & CO₂ Footprint Analytics**

---

# Key Insights Found

## **1. Supplier (Agency) Spend Distribution**
- Travel spend is **highly concentrated** in a small number of agencies.
- Top agencies handle the majority of bookings, making them the **primary negotiation targets**.
- Smaller agencies contribute minimal volume and could be consolidated.

**Business impact:**  
→ Opportunity for **supplier rationalization** and **volume-based rate negotiations**.

---

## **2. Cost Efficiency Differences Between Agencies**
- Cost per km varies **significantly** across agencies.
- Some agencies consistently produce **higher cost per km** for similar distances.
- Variability indicates **inconsistent fare sourcing** or **non-optimal booking behavior**.

**Business impact:**  
→ Clear potential for enforcing **preferred agency usage**  
→ Evaluate agencies causing inflated cost_per_km

---

## **3. High-Cost Trips (Outliers)**
- Using z-score > 2.5, we flagged high-cost trips.
- Outliers are driven mainly by:
  - Long-haul flights  
  - Last-minute bookings  
  - Agencies with poor cost efficiency  

**Business impact:**  
→ Opportunity to implement **booking optimization**, **advance booking policies**, and **fare monitoring**.

---

## **4. Hotel Spend & Nights**
- Hotel spend is concentrated in a few destinations.
- Cost per night varies greatly by trip and user profile.
- Many trips have hotels booked through different agencies.

**Business impact:**  
→ Potential for **hotel rate renegotiation**  
→ Introduce a **preferred hotel program**.

---

## **5. CO₂ Emissions**
- CO₂ footprint correlates strongly with:
  - Flight distance  
  - Number of nights  
- Agency mix impacts overall carbon footprint.

**Business impact:**  
→ Helps support Maersk’s mission to **decarbonize logistics**  
→ Opportunity to build **sustainable travel policies**.

---

## 📊 Dashboard Pages

---

## **1. Travel Cost & Efficiency Overview**

This page provides:
- Total travel spend  
- Total trips
- Average trip cost
- Total CO₂ emissions
- Total trip cost trend by flight time  
- Hotel nights distribution  
- High-cost trip identification (donut chart)

![Travel Cost & Efficiency](Dashboard_Images/Page1.PNG)
*(This corresponds to the image shown on page 8 of the uploaded file)*

---

## **2. Supplier / Agency Performance**

This page shows:
- Total spend by agency  
- Average cost per km by agency  
- Supplier efficiency  
- High-cost trip contribution  
- Agency-level KPIs  
- Strategic sourcing insights  

![Supplier Performance](Dashboard_Images/Page3PNG.PNG)
*(This corresponds to the first large agency table + bar charts shown on page 5)*
:contentReference[oaicite:2]{index=2}

---

## **3. Trip Efficiency & Cost Drivers**

This page contains:
- Average cost per km  
- Average cost per hotel night  
- Scatter plot (total trip cost vs flight distance)  
- Hotel insights (hotel total & cost per night)  
- Cost per night by # of flights  

![Cost Efficiency](Dashboard_Images/Page2PNG.PNG)
*(This corresponds to the scatter + hotel visual section shown on page 6)* 
:contentReference[oaicite:3]{index=3}

---

# Technology Stack

### **Python**
- Pandas  
- NumPy  
- Data cleaning  
- Trip-level feature engineering  
- Z-score anomaly detection  
- CO₂ calculations  
- Data export for BI  

### **Power BI**
- Data modeling  
- Measures & calculated fields  
- Interactive visuals  
- Slicers  
- KPI cards  
- Conditional formatting  
- Executive-level dashboard design  

### **GitHub Pages**
- Portfolio website  
- Project documentation  
- Public access for employers  

---

# Why This Project Matters 

This dashboard demonstrates skills aligned directly with the job posting:

### Procurement insight generation  
### Supplier performance analysis  
### Travel spend optimization  
### Policy & compliance indicators  
### Sustainability (CO₂) tracking  
### Advanced BI reporting  
### Collaboration across global data sources  

It proves the ability to work with:

- Indirect procurement categories  
- Travel suppliers  
- Data-driven decision frameworks  
- Multi-stakeholder environments  
- Large datasets (270k+ rows)

---

# 📁 Full Project Repository
Browse the full code, data, and files:

👉 **https://github.com/Amin-Azad/travel-procurement-dashboard**

---

# Live Portfolio Website
This website is powered by **GitHub Pages**.

👉 **https://Amin-Azad.github.io/travel-procurement-dashboard**

---

# 📬 Contact
For collaboration or interview opportunities:

📧 YOUR_EMAIL  
🔗 LinkedIn: YOUR_LINKEDIN


