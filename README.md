# Uber-Journey-Intelligence-Optimizing-Demand-Supply-Dynamics-Reducing-Revenue-Leakage
Uber Analysis  Optimizing Demand-Supply Dynamics &amp; Reducing Revenue Leakage


# 🚖 Uber Journey Intelligence: Analyzing Demand & Supply Gaps

## 📌 Project Overview
As a Data Analyst transitioning into the **Transportation Domain**, I undertook this project to dissect the operational challenges of a ride-hailing giant like Uber. The goal was not just to visualize data, but to understand the **"Two-Sided Marketplace"** dynamics—balancing rider demand with driver supply.

This analysis focuses on a dataset of **150,000 trip requests**, aiming to identify why rides fail, when demand peaks, and which vehicle types drive the most revenue.

## 💼 The Business Problem
Upon initial exploration, a critical issue emerged: **High Failure Rate**.
The data revealed that a significant portion of booking requests do not result in a completed trip. This represents a massive **"Revenue Leakage"** and a poor customer experience. My mission was to diagnose the *root causes* of these failures and propose data-driven solutions.

## 🔍 Key Insights & Findings

### 1. The "Lost Demand" Crisis (Booking Status Analysis)
My analysis uncovered a startling statistic: **~38% of all booking requests fail.**
* **Completed:** 62%
* **Cancelled by Driver:** 18% (The biggest pain point)
* **No Driver Found:** 7%
* **Cancelled by Customer:** 7%

> **Observation:** Drivers are cancelling trips 2.5x more often than customers. This suggests a misalignment in incentives or operational issues (e.g., traffic, low fare visibility).

*("status.png")*

### 2. Temporal Patterns: The 6 PM Struggle
By mapping demand against time, I identified clear patterns:
* **Peak Demand:** Occurs at **6:00 PM (18:00)** followed by 10:00 AM.
* **Supply Gap:** The highest frequency of "No Driver Found" errors also happens exactly at **6:00 PM**.
* **Insight:** We are losing the most potential revenue exactly when customers need us the most.

*("hour3.png")*

### 3. Revenue & Fleet Efficiency
I analyzed the financial performance of different vehicle types:
* **Volume Leader:** The **"Auto"** (Rickshaw) is the absolute volume leader, generating the highest total revenue due to sheer demand.
* **Margin Leader:** **"Go Sedan"** generates the highest Revenue Per KM (~34.6/km), making it the most efficient per unit of distance.
* **Underperformer:** **"Uber XL"** shows very low utilization, suggesting a need to revisit its pricing or availability strategy.

*("km3.png")*

## 💡 Strategic Recommendations
Based on the data, I propose the following actions:

1.  **Dynamic Incentives for Peak Hours:** Introduce a "Surge Bonus" for drivers specifically between **5 PM - 7 PM** to combat the high "No Driver Found" rate.
2.  **Investigate Driver Cancellations:** With 27,000+ driver cancellations, we need to revise the "Acceptance Screen" to show drivers more details (destination/fare) upfront to reduce post-acceptance churn.
3.  **Strengthen the "Auto" Fleet:** Since "Auto" is the cash cow, ensure maximum availability and lower wait times for this category to maintain market dominance.

## 🛠️ Tools & Technologies Used
* **Python:** The core engine for analysis.
* **Pandas:** For data manipulation and cleaning.
* **Seaborn & Matplotlib:** For data visualization and storytelling.
* **Geospatial Concepts:** Understanding O-D (Origin-Destination) and time-series trends.

---
*Author: [Mohamed Shauky]*
*Data Source: Kaggle (Uber Journey Intelligence)*
