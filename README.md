# Churn Analysis Dashboard

*Power BI Report | Customer Retention Insights | Executive Summary*

This project analyzes customer churn in a telecom dataset, revealing a **27.0% overall churn rate** among 6,418 customers. Built with demographic, behavioral, and service-based breakdowns to uncover retention opportunities. Includes a detailed **PDF report** with recommendations.

## Dashboard Previews

### Summary Overview
![Churn Analysis Dashboard](https://raw.githubusercontent.com/Jerry-Nelson/churn-analysis-report/main/Screenshot%20(13).png)

Use the slicers above to explore breakdowns by gender, state, tenure, contract, and more.

## 📊 Key Insights

### Overall Metrics
| Metric          | Value    |
|-----------------|----------|
| Total Customers | 6,418   |
| New Joiners     | 411     |
| Total Churn     | 1,732   |
| Churn Rate      | 27.0%   |

### Demographic Breakdowns
- **Gender**: Females lead churn (**64.1%** or 1,111 customers) vs. males (**35.9%** or 621)—potential pricing/engagement gaps for women.
- **Age Group**: Churn rises with age—**23.5%** (<20 years), **24.0%** (20–35), peaking at **31.0%** (>50). Older customers need tailored plans for relevance.

### Geographic Hotspots (Top 5 Churn Rates)
| Region             | Churn Rate |
|--------------------|------------|
| Jammu & Kashmir   | 57.2%     |
| Assam             | 38.1%     |
| Jharkhand         | 34.5%     |
| Chhattisgarh      | 30.5%     |
| Delhi             | 29.9%     |

Service issues or competition may fuel these—regardless of gender.

### Account Information
- **Payment Method**: Highest for Mailed Check (**37.8%**) and Bank Withdrawal (**34.4%**); lowest for Credit Card (**14.8%**). Push digital payments for loyalty.
- **Contract Type**: Month-to-month (**46.5%**) >> One-year (**11%**) > Two-year (**2.7%**). Incentivize longer commitments.
- **Tenure**: Steady **26–28%** across groups—target early onboarding to curb initial drop-off.

### Service Usage
- **Internet Type**: Fiber Optic (**41.1%**) > Cable (**25.7%**) > DSL (**19.4%**)—tech upgrades may not satisfy on cost/experience.
- **Subscribed Services**: Alarming churn in high-adoption areas: Internet (**93.7%**), Paperless Billing (**74.6%**), Phone (**90.6%**), Unlimited Data (**85.5%**). Review for improvements.
- **Non-Subscribed**: High churn without Online Backup (**70%**), Online Security (**83.6%**), Premium Support (**82.4%**)—market these for upsell.

### Churn Reasons (Top Drivers)
| Reason            | Customers | Key Factors |
|-------------------|-----------|-------------|
| Competitor       | 761      | Better devices/pricing, higher speeds/data |
| Dissatisfaction  | 304      | Poor support/expertise, network issues, limited services |
| Attitude         | 301      | Service rep interactions |
| Price            | 196      | High costs, extra charges |

Competitive pressure and service quality dominate—focus on value and delivery.

## 🚀 How to Use
1. **Download Files**:
   - [Churn analysis.pbix](Churn analysis.pbix) – Open in [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free).
   - [Churn rate report.pdf](Churn rate report.pdf) – View in any PDF reader.

2. **Interact with Dashboard**:
   - Refresh data (if connected to external sources).
   - Use slicers for demographics, regions, services, etc.
   - Export visuals as PDF/PNG for reports.

3. **Tech Stack**:
   - **Power BI** for visualization and DAX measures.
   - Dataset: Anonymized telecom customer data.

## 📈 Recommendations
1. **Gender-Targeted Campaigns**: Engage females via feedback and retention perks.
2. **Loyalty for At-Risk Groups**: Incentives for older/month-to-month customers to extend contracts.
3. **Regional Interventions**: Boost quality/engagement in Jammu & Kashmir/Assam.
4. **Digital Payment Push**: Promote electronic methods for convenience.
5. **Support Overhaul**: Train reps to fix attitude/dissatisfaction issues.
6. **Service Bundling**: Pair Online Security/Premium Support for added value.
7. **Early Engagement**: Programs for first 6 months to cut tenure churn.
8. **Pricing Flexibility**: Enhance propositions to counter competitors.

## 🔚 Conclusion
At **27% churn**, attrition is moderate but actionable. Prioritize short-tenure users, flexible contracts, and high-risk regions through experience upgrades, competitive edges, and targeted programs to drive retention and profitability.

## 🤝 Contributing
Fork, clone, and submit PRs for enhancements (e.g., add ML predictions). Issues welcome!

## 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

*Built with ❤️ for data-driven decisions. Questions? Open an issue!*
