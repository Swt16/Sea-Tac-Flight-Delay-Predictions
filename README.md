# Sea-Tac-Flight-Delay-Predictions
Analysis of BTS flight data using Multiple Linear Regression.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1ojj-2Eh-NRLNMm64szHyHDGamdCBYCPF?usp=sharing)

## Project Overview
This project predicts flight delays based on arrivals at Sea-Tac International Airport from 2003 through 2025. The analysis was done using linear regression.

## Key Insights
* **Carrier Comparison:** While initial data suggested Alaska Airlines had a high count of delays, further analysis revealed they perform competitively when normalized by flight volume.
* **Predictive Power:** Developed a Multiple Linear Regression model to forecast delay percentages based on carrier, weather, and security factors.
* **Model Performance:** The model achieved a Root Mean Square Error (RMSE) of **9.9**, providing a solid baseline for predicting flight disruptions.

## Technical Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-Learn
* **Visualization:** Matplotlib, Seaborn
* **Environment:** Google Colab / Jupyter Notebooks

## Project Structure
* `Flight_Delay_Prediction.ipynb`: The core data pipeline and modeling code.
* `Project_Report.pdf`: A detailed technical deep-dive into the findings.
* `Presentation_Slides.pdf`: A high-level summary for non-technical stakeholders.

## Data Source
Data was pulled from the [Bureau of Transportation Statistics (BTS)](https://www.transtats.bts.gov/ot_delay/OT_DelayCause1.asp?20=E), focusing on domestic flight delay causes and carrier performance.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
