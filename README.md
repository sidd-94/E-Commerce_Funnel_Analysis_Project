# E-Commerce_Funnel_Analysis_Project
SQL-driven funnel analysis processing 10K+ event logs to map user journeys, isolate a major 20% friction point at the "Add to Cart" stage, and deliver actionable UX recommendations.

# E-commerce Funnel Optimisation Analysis

## 📌 Project Overview
An analytics project focused on mapping the end-to-end consumer conversion journey. By processing over 10,000 clickstream event logs, this analysis isolates specific digital friction points where users drop off, distinguishing between highly optimised funnel stages and areas requiring user experience intervention.

## 🛠️ Tools & Technologies Used
* **SQL Flavor:** Google BigQuery
* **Funnel Analysis:** Conversion mapping and milestone tracking.
* **Data Metrics:** Stage-to-stage dropout rate calculation and event-sequence mapping.

## 📊 Key Findings & Actionable UX Recommendations
* **The High Performer ("Don't Touch"):** Analysis revealed an exceptional 80%+ conversion rate from the checkout stage to final purchase. The data-driven recommendation delivered to the UX and website optimisation team was to **leave the checkout flow completely untouched**, as it is already performing at an elite tier.
* **The True Friction Point:** Identified a major dropout earlier in the funnel—the **"View to Cart" conversion rate was stagnant at only around 30%**. 
* **The Recommendation:** Advised the UX team to deep-dive into the top-of-funnel browsing experience, specifically investigating if products are being displayed optimally and ensuring users can immediately find the items they are looking for.

## 📂 Repository Structure
* `/queries`: BigQuery SQL scripts mapping out the user stages (Sessions -> Product View -> Add to Cart -> Purchase).
* `/insights`: Formal write-up of the funnel performance and UX recommendations.
