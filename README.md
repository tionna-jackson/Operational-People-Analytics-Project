# 📊 Gartner Operational & People Insights Analytics Project  
A full end-to-end analytics project designed to reflect the analytical rigor, business storytelling, and decision-making frameworks used at **Gartner**. This project blends operational performance data with people analytics to uncover insights that improve SLA performance, forecast capacity, and identify burnout risk. 


# 🧩 Project Overview  
This project analyzes operational performance, workforce capacity utilization, training effectiveness, and burnout risk to identify service delivery risks and strategic intervention opportunities. Using simulated enterprise support data, the analysis demonstrates how demand–capacity imbalance, insufficient training investment, and sustained overtime can negatively impact SLA performance and workforce sustainability

This project simulates the work of a **Gartner Data Analyst** by analyzing:

- Analyst workload  
- Operational efficiency  
- SLA performance  
- Burnout risk  
- Training effectiveness  
- Forecasted ticket demand  
- CSAT & quality metrics  

I created a 500-row synthetic dataset that mirrors real workforce and operational dynamics.  
Programming: **R**  
Dashboarding: **Power BI**  
Techniques: Regression, Classification, Forecasting, Correlation, DAX KPI Modeling.

## Business Questions Addressed
- Are teams operating within sustainable capacity utilization levels?
- Where is ticket demand exceeding current workforce capacity?
- How does training investment impact SLA performance?
- What operational conditions are driving burnout risk?
- Which teams face the highest near-term service delivery risk?
- How can leadership proactively rebalance capacity to protect SLA outcomes?

---

# ⭐ Why This Project Matters 

Gartner hires analysts who can think beyond dashboards — they want professionals who can:
✔ Turn data into decisions  
✔ Identify the “why” behind performance patterns  
✔ Connect workforce metrics to operational outcomes  
✔ Communicate clearly with stakeholders  
✔ Influence strategy with evidence  

This project was intentionally designed to match those expectations.

Gartner analysts frequently work with:
- operational efficiency data  
- people/talent analytics  
- forecasting models  
- executive-ready insights  

This project mirrors that by analyzing:
- SLA performance  
- Team efficiency  
- Burnout risk  
- Ticket forecasts  
- Training impacts  
- Tenure performance  
---

## 🧠Tools & Skills Used
- **Power BI** – Data modeling, DAX measures, interactive dashboards
- **DAX** – KPI calculations (SLA %, closure rate, capacity utilization, demand gaps)
- **Operational Analytics** – Demand forecasting, capacity analysis
- **People Analytics** – Training effectiveness, burnout risk assessment
- **Data Storytelling** – Executive-ready insights and recommendations
- **Business Framing** – Translating data into strategic action
    
---

# 📁 Dataset: `gartner_analytics_operations.csv`

A 500-row synthetic dataset representing real-world analyst workforce metrics.

| Column | Description |
|-------|-------------|
| analyst_id | Unique ID |
| analyst_name | Random name |
| team | Team A, B, or C |
| tickets_assigned | Monthly tickets |
| tickets_closed | Tickets closed |
| avg_resolution_time | 
| sla_met_pct | % meeting SLA |
| csat_score | 1–5 score |
| overtime_hours | Monthly overtime |
| burnout_risk | Low/Moderate/High |
| tenure_months | Employment tenure |
| training_hours | Monthly training |
| sick_days 
| predicted_ticket_volume | Forecasted demand |

---
## Dashboard Breakdown & Key Insights

### Page 1: Operational Performance Analytics
**Purpose:** Assess current service performance and capacity alignment.

**Key Insights:**
- Capacity utilization exceeds optimal thresholds for some teams, increasing SLA risk.
- Ticket demand is unevenly distributed across teams, creating workload imbalance.
- SLA performance is below target, driven by capacity constraints rather than productivity issues.

**Leadership Takeaway:** Capacity rebalancing is required to stabilize service levels.

---

### Page 2: Training Effectiveness & SLA Impact
**Purpose:** Evaluate training as a driver of service performance and burnout reduction.

**Key Insights:**
- SLA performance improves as average training hours increase.
- Optimal SLA outcomes occur around 5–6 training hours per agent.
- Burnout risk decreases as training investment rises, particularly for lower-performing teams.

**Leadership Takeaway:** Targeted training investment delivers measurable SLA and workforce sustainability benefits.

---

### Page 3: Operational Risk, Burnout & Workforce Sustainability
**Purpose:** Identify high-risk teams and forecast future service gaps.

**Key Insights:**
- Sustained overtime is strongly associated with elevated burnout risk.
- Forecasted ticket demand exceeds current capacity for multiple teams.
- The largest demand–capacity gaps align with higher burnout risk and lower closure rates.

**Leadership Takeaway:** Proactive capacity planning and workload redistribution are required to prevent service degradation and workforce attrition.

---

https://www.loom.com/share/4c672812e54e41aab47a9342ea977a9d

## Final Recommendations
- Rebalance ticket demand across teams to reduce overload risk.
- Maintain capacity utilization within a sustainable 70–80% range.
- Prioritize training investments for underperforming teams.
- Monitor burnout risk as an operational KPI.
- Use demand forecasting to guide workforce planning decisions.

---

## Conclusion
This project demonstrates how integrated operational and people analytics can support sustainable service delivery, protect SLA performance, and inform leadership decisions. The approach reflects real-world advisory and analytics practices used to drive measurable organizational outcomes.
