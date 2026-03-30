# Sea-Tac-Flight-Delay-Predictions
**An end-to-end study of airline reliability and predictive modeling for SEA-Tac departures.**

## Project Overview
This project analyzes flight disruptions (delays, cancellations, and diversions) for flights departing from **Seattle-Tacoma International Airport (SEA)**. Using data dating back to 2003, our team narrowed a broad dataset of 26 carriers down to the 9 most impactful airlines to provide actionable business insights into carrier efficiency and reliability.

## Interactive Demo & Assets
* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1ojj-2Eh-NRLNMm64szHyHDGamdCBYCPF?usp=sharing)
* [View Presentation Slides](https://github.com/Swt16/Sea-Tac-Flight-Delay-Predictions/blob/main/Flight%20Delay%20Predictions.pdf) — *Highlights: Business Impact & Executive Summary*

---

## Key Business Insights
* **Strategic Data Curation:** Cleaned and standardized inconsistent carrier naming conventions (e.g., "American Airlines Network" vs. "Inc.") to ensure data integrity across 20+ years of records.
* **Volume vs. Performance:** Identified that while some carriers (like Alaska Airlines) show high raw delay counts, their **delay percentage** is lower than competitors when normalized against their high flight volume at SEA.
* **Diversion Analysis:** Performed a specialized study on "Diverted" flights—identifying carriers with the highest rates of emergency or mechanical rerouting.
* **Predictive Modeling:** Built a Multiple Linear Regression model to forecast performance metrics, achieving a **Test RMSE of 9.9**.

## Technical Stack
* **Tools:** Python (Pandas, Scikit-Learn, Seaborn, Matplotlib)
* **Concepts:** Data Scrubbing, Feature Engineering, Multivariate Regression, Business Intelligence.
* **Data Source:** [U.S. Bureau of Transportation Statistics (BTS)](https://www.transtats.bts.gov/ot_delay/OT_DelayCause1.asp?20=E)

---
## License
MIT License
## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
