# J&D Report With CI/CD in Power BI

## 🚀 Power BI CI/CD Architecture 

- **Validation Pipeline**  
  Automatically runs on each commit to the dev branch. Checks that datasets and reports follow best practices, verifies measure accuracy, and applies a wide range of validation rules (such as reviewing data model relationships or flagging report pages with too many visuals). Ensures all requirements are met before allowing pull requests to the main branch.

- **Release Pipeline**  
  Automatically deploys changes that pass validation to different deployment stages. Each stage has its own workspace, reducing the risk of unintended changes and supporting robust testing before production rollout.

- **Approval Process**  
  Release managers review and approve deployments to production, providing human oversight and compliance before changes go live.
---
<p align="center">
  <img src="https://github.com/Einsuomi/J-D-Power-BI-CI-CD/blob/main/Images/J%26D%20CI_CD%20Architecture.drawio%20(1).png" alt="Power BI CI/CD Architecture" width="600">
</p>
---

## Overview Page

- **Hidden Slicers**  
  Keep slicers out of view for a cleaner, less cluttered report page.

- **KPI Tracking**  
  Effortlessly monitor key performance indicators over different time periods.

- **Drill-Through Enabled**  
  Quickly access detailed data by drilling through visualizations for in-depth analysis.

---

<p align="center">
  <img src="https://github.com/Einsuomi/J-D-Power-BI-CI-CD/blob/main/Images/Screenshot%202025-07-27%20201111.jpg" alt="Power BI Dashboard" width="600">
</p>

---

## Customer Details

- **KPIs Selection**  
  Easily select KPIs to follow—view by customer or revenue per customer.

- **Top Customer Analysis**  
  Analyze top customers by segment with ease.

- **No Purchase Customer Analysis**  
  Identify and analyze customers who have not made a purchase to uncover potential opportunities and improve engagement strategies.
<p align="center">
  <img src="https://github.com/Einsuomi/J-D-Power-BI-CI-CD/blob/main/Images/Screenshot%202025-07-27%20202244.jpg" alt="Power BI Dashboard" width="600">
</p>
---

### 👉 [**View the full interactive report in Power BI Service here**](https://app.powerbi.com/view?r=eyJrIjoiZjQwOGI3MjctNjY1Yy00Zjg1LTg3YWUtZDcyNDcyMWQ0NTQ2IiwidCI6IjA2ZDllZTNkLTQxN2EtNGMyYi04NzdmLTgxNWMyMjdiYjk0NSIsImMiOjEwfQ%3D%3D)

---

*For more information, visit the [J&D Report Data Analytics Portfolio](https://ethannie2020.wixsite.com/data-analytics/copy-of-heureka-science-center-report).*
