# 📊 Funnel Analysis Dashboard — Portfolio Case Study (Power BI)(Demo Included)

---

## 🧠 Project Summary

This project is a **comprehensive funnel analysis dashboard** built in Power BI to evaluate user behavior across key stages of a digital journey. The goal is to identify **conversion bottlenecks**, quantify **drop-offs**, and provide **actionable business insights**.

This case study demonstrates:

* Strong **analytical thinking**
* Practical use of **DAX & data modeling**
* Ability to translate data into **business decisions**

---

## 🎯 Business Problem

Businesses often struggle to understand:

* Where users abandon the journey
* Which stage impacts revenue the most
* How different segments behave

Without this clarity, optimizing conversion becomes guesswork.

👉 This dashboard solves that by providing **stage-level visibility and interactive exploration**.

---

## 📊 Dataset Overview

The dataset tracks user progression through a 4-stage funnel:

| Stage   | Description                     |
| ------- | ------------------------------- |
| Home    | User lands on platform          |
| Search  | User explores products/services |
| Payment | User initiates transaction      |
| Confirm | Transaction completed           |

---

## 🧱 Data Modeling Approach

* Binary flags used for each stage (`visited_home`, `visited_search`, etc.)
* Funnel progression calculated using **conditional filtering**
* Measures created for:

  * Conversion Rate (CVR)
  * Drop-off %
  * Relative performance

---

## 📄 Dashboard Structure


# 🖥️ Page 1: Funnel Overview                                                                                           

📹[Click here for demo](https://drive.google.com/file/d/1irTu4hUweSle4BlmQ8rk5cOR-OTgH535/view?usp=sharing)

## 📌 Objective

Provide a high-level view of user movement across the funnel.

## 📊 Visuals Used

* Funnel Chart
* KPI Cards (Total Users, Conversion Rate)
* Stage-wise Drop-off Bars

## 🔢 Key Metrics (Example)

* Total Users: **90,000**
* Home → Search CVR: **59%**
* Search → Payment CVR: **17%**
* Payment → Confirm CVR: **7%**
* Overall Conversion: **0.70%**

## 💡 Insights

* Largest drop occurs at **Home → Search CVR: 59%**
* Strong conversion at final stage (Payment → Confirm), indicating:

  * Payment UX is effective
  * Users with high intent convert successfully

👉 **Business Insight:**
Focus optimization efforts on **Search → Payment transition** (pricing clarity, CTA placement, trust signals).



---

# 📉 Page 2: Segment Analysis(e.g., Device)


📹[Click here for demo](https://drive.google.com/file/d/1h7ZsPsJvkYzYxR_sJSCc8cZCsf06Oq8M/view?usp=sharing)

## 📌 Objective
Understand how different user segments behave.


## 📊 Visuals Used
* Stacked Bar Chart
* Slicers (Device Type)


## 🔢 Key Metrics 

| Device  | Conversion Rate |
| ------- | --------------- |
| Desktop | 1%             |
| Mobile  | 0%             |

## 💡 Insights

* Mobile users have **0.8% lead conversion** than desktop
* Likely performance issue on desktop


👉 **Business Action:**

* Optimize desktop UI
* Improve loading speed
* Simplify checkout flow


---

# 📊 Page 3: Time Trend Analysis

📹[Click here for demo](https://drive.google.com/file/d/1pA2tYrhkKBD-XsCNVobDatSNw-0eFtjh/view?usp=sharing)

## 📌 Objective

Monitor how CVR and drop-off evolve monthly across funnel stages, devices, and gender to separate structural issues from time-bound anomalies.

## 📊 Visuals Used

*  Two line charts — monthly drop-off trend by stage (Search, Payment, Confirm)
*  Monthly CVR trend split by Desktop, Mobile, and Daily overall — filtered by Device and Gender slicers.


## 🔢 Key Metrics (Example)

* Monthly CVR by device,
* drop-off rate per stage over time
* daily CVR as a rolling baseline.


## 💡 Insights

* Drop-off at Payment and Confirm converges upward from March onward indicating a worsening late-stage problem.
* Desktop and Mobile CVR lines are nearly flat at the bottom while Daily CVR trends slightly upward — suggesting overall volume is growing but device-level conversion is not improving proportionally.

👉 **Business Insight:**

* The widening gap between Daily CVR growth and stagnant Desktop/Mobile CVR signals


---

# 🔍 Drill-through Functionality (Key Feature)

📹[Click here for demo](https://drive.google.com/file/d/1y_MpoZyo3i_v02MDVGF2ejyMa-nBX6l9/view?usp=sharing)

## 📌 What It Does

Allows users to **click on any stage** and navigate to a **detailed breakdown page**.

## ⚙️ How It Works

* Drill-through filter applied on **Stage field**
* User clicks on a stage (e.g., Search)
* Dashboard opens a **focused analysis page**

---

## 🖥️ Drill-through Page: Stage Deep Dive

## 📊 Visuals Used

* Detailed breakdown charts
* Segment-wise performance
* KPI comparisons

## 🔢 Example Insight (Search Stage)

* Total Users Entered: **45,000**
* Users Dropped: **39,000**
* Drop-off Rate: **87%**

Further breakdown:

* Mobile conversion rate: **20%**
* Desktop conversion rate: **10%**

## 💡 Insights

* Majority of drop-off driven by **Desktop users**
* Confirms earlier hypothesis from segment analysis

👉 **Business Insight:**
Search experience on desktop is a **critical failure point**

---

## 🎯 Key Business Takeaways

1. **Primary Bottleneck:** Search → Payment transition
2. **High-performing Stage:** Payment → Confirmation
3. **Critical Segment Issue:** Mobile users
4. **Opportunity Area:** UX improvements in search & product discovery

---

## 🚀 Recommendations

* Improve search relevance & UX
* Optimize mobile experience
* Add trust signals before payment
* Simplify navigation between stages

---
## Screenshots

* Funnel Overview:
<img width="698" height="386" alt="image" src="https://github.com/user-attachments/assets/4633863c-d704-48d4-98f3-d281a718dcfc" />

* Segment Analysis:
<img width="694" height="392" alt="image" src="https://github.com/user-attachments/assets/e5d68ef9-3334-499a-a730-c1bc471ba9d1" />

* Time Trends:
<img width="698" height="392" alt="image" src="https://github.com/user-attachments/assets/4fb425c6-3aea-485e-9587-248c68d2ab4d" />

* Stage Drill-Throughs:
<img width="695" height="390" alt="image" src="https://github.com/user-attachments/assets/9eaa15d1-beec-402b-8e38-03a496ee576f" />
<img width="698" height="395" alt="image" src="https://github.com/user-attachments/assets/5a362420-6302-4aa7-b1b7-fa49607733aa" />
<img width="695" height="391" alt="image" src="https://github.com/user-attachments/assets/787e12e2-3735-48b5-9804-ec8c66700b35" />
<img width="695" height="388" alt="image" src="https://github.com/user-attachments/assets/9f41971b-4a12-4469-b89d-e613c8c279e0" />
---
<!--
## 🛠️ Technical Highlights

* Advanced DAX:

  * Conversion Rate calculations
  * Relative CVR comparison
  * Dynamic KPI visuals

* UX Enhancements:

  * Tooltip insights
  * Conditional formatting
  * Interactive drill-through

---


## 📁 Repository Contents

```
📦 funnel-analysis-powerbi
 ┣ 📄 Funnel_Analysis.pbix
 ┣ 📄 README.md
 ┗ 📂 archive
```
-->

## ⭐ Final Note

This project showcases the ability to:

* Translate business problems into data solutions
* Build interactive dashboards
* Generate actionable insights from raw data

---

