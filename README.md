# Sales Funnel Analysis & A/A/B Testing in a Food Products App
## Context
Understanding user behavior is crucial for improving conversion rates and user experience in an e-commerce app. This project aims to analyze the sales funnel of a food products application and evaluate the results of an A/A/B test assessing the impact of font changes.

## Tools Used
- **Python:** For data processing and analysis.
- **Pandas & NumPy:** For cleaning and structuring the dataset.
- **Matplotlib & Seaborn:** For visualizing trends and patterns.
- **Scipy & Statsmodels:** For statistical testing in the A/A/B experiment.
- **Dataset:** User interaction logs, including sales funnel events and test group assignments.
## Analysis Performed
**1. Sales Funnel Analysis**
The sales funnel helps evaluate how users progress through different stages of the purchasing process, addressing key questions such as:

- How many users complete a purchase?
- Where do most users drop off?
- Which stages create the biggest bottlenecks?
Conversion rates were calculated for each funnel step to pinpoint friction points in the process.

**2. A/A/B Test Evaluation**
The A/A/B test was designed to assess the impact of changing the app’s font. Users were divided into three groups:

- Group A1 & Group A2 (Control): Continued using the old font.
- Group B (Test): Received the new font.
The purpose of having two control groups (A1 & A2) was to validate the reliability of the experiment. If significant differences appeared between them, it could indicate hidden factors affecting the results.

Key metrics analyzed included:

- Conversion rates across groups.
- Drop-off rate differences.
- Statistical tests to determine if font changes significantly affected user interaction.
## Results & Findings
**Sales Funnel:** Critical stages with high user drop-off were identified, guiding efforts to improve retention.
**A/A/B Test:**
- No significant differences were found between the A1 and A2 groups, confirming test reliability.
- Comparing Group B to the control groups determined whether the font change positively or negatively affected conversion and user engagement.
## Conclusions
This analysis provides valuable insights for optimizing the app’s conversion process. The sales funnel findings highlight key areas for improvement, while the A/A/B test results support data-driven decisions regarding the app’s visual design.

Future iterations could test additional design changes, such as colors or button placements, to further enhance the user experience and sales performance.
