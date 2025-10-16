# Churn Analysis Dashboard

An interactive **Power BI dashboard** exploring customer churn in a telecom dataset, revealing a **27.0% overall churn rate** among 6,418 customers. Built with demographic, behavioral, and service-based breakdowns to uncover retention opportunities. Includes a detailed **Word report** with recommendations.

![Screenshot (13)](https://raw.githubusercontent.com/Jerry-Nelson/churn-analysis-report/main/Screenshot(13).png)

## 📊 Key Insights
- **Overall Metrics**:
  - Total Customers: **6,418**
  - New Joiners: **411**
  - Total Churn: **1,732**
  - Churn Rate: **27.0%**

- **Demographics**:
  - Males account for **65%** of churn (vs. 35% females).
  - Highest churn in younger age groups: **40%** for <20 years.
  - Regional hotspots: Jamshedpur (**38%**), Jharkhand (**30.5%**).

- **Behaviors & Services**:
  - Month-to-month contracts: **45.6%** churn (vs. 2.7% for two-year).
  - Mailed check payments: **37.8%** churn—switch to digital!
  - Top reasons: Complaints/Attitude (**301 cases each**), followed by dissatisfaction (**300**).

For full breakdowns, explore the dashboard filters (e.g., by state, tenure, or service type).

| Factor | High Churn Example | Low Churn Example |
|--------|--------------------|-------------------|
| Contract | Month-to-Month (45.6%) | Two-Year (2.7%) |
| Payment | Mailed Check (37.8%) | Credit Card (18.9%) |
| Service | Unlimited Data (85% with churn) | Phone Service (16% with churn) |

## 🚀 How to Use
1. **Download Files**:
   - [Churn-Analysis-Summary.pbix](Churn-Analysis-Summary.pbix) – Open in [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free).
   - [Churn-Analysis-Report.docx](Churn-Analysis-Report.docx) – Read in Microsoft Word.

2. **Interact with Dashboard**:
   - Refresh data (if connected to external sources).
   - Use slicers for gender, state, tenure, etc.
   - Export visuals as PDF/PNG for reports.

3. **Tech Stack**:
   - **Power BI** for visualization and DAX measures.
   - **Microsoft Word** for narrative reporting.
   - Dataset: Anonymized telecom customer data (CSV/Excel compatible).

## 📈 Recommendations
- **Target Early Retention**: Focus on <12-month customers (28% churn) with onboarding perks.
- **Upsell Contracts**: Promote one/two-year plans to slash month-to-month losses.
- **Service Tweaks**: Investigate unlimited data complaints—bundle with support.
- **Regional Focus**: Pilot campaigns in high-churn states like Jamshedpur.

## 🤝 Contributing
Fork, clone, and submit PRs for enhancements (e.g., add ML predictions). Issues welcome!

## 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

*Built with ❤️ for data-driven decisions. Questions? Open an issue!*
