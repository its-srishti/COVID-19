# COVID-19 Time Series Forecasting using ARIMA

*“All models are wrong, but some are useful.”\* — George E. P. Box



This project examines the temporal evolution of COVID-19 confirmed cases and applies classical **time-series forecasting techniques** to model short-term trends. The analysis focuses on understanding data behavior, model assumptions, and practical limitations rather than producing production-grade forecasts. The work was conducted using a Jupyter Notebook and publicly available datasets from Kaggle.
---



## 🎯 Objective

To analyze COVID-19 case trajectories over time and evaluate the applicability and limitations of **ARIMA (AutoRegressive Integrated Moving Average)** models for epidemiological time-series data.



---



## 📂 Project Structure

- `Covid-19.ipynb` → Jupyter notebook containing data preprocessing, analysis, modeling, and forecasts  

- Dataset sourced directly from Kaggle (not stored in the repository)



---



## 📊 Dataset

- Public COVID-19 confirmed case datasets sourced from **Kaggle**

- Time-indexed case counts across countries and regions

- Data used in accordance with Kaggle dataset and competition usage guidelines



---



## ⚙️ Methodology



### 1. Data Preparation

- Cleaning and formatting time-indexed case data  

- Handling missing values and inconsistencies  

- Aggregation and selection of relevant country-level series  



### 2. Exploratory Data Analysis (EDA)

- Visualization of global and country-specific COVID-19 trends  

- Identification of growth phases and structural changes  

- Preliminary assessment of trend and variance behavior  



### 3. Time-Series Modeling

- Stationarity checks and differencing where required  

- ARIMA model selection and fitting  

- Short-horizon forecasting based on historical patterns  



### 4. Interpretation

- Evaluation of forecast behavior  

- Discussion of model assumptions and breakdowns  

- Reflection on real-world applicability and constraints  



---



## 📈 Results & Observations

- ARIMA models capture **broad temporal patterns** in confirmed case counts  

- Forecasts perform reasonably over short horizons but degrade rapidly during structural breaks  

- The model struggles to adapt to sudden regime shifts driven by policy changes, pandemic waves, or behavioral factors  



---



## ⚠️ Caveats & Limitations

- **Single-variable modeling**: Only historical case counts are used; no exogenous variables (e.g., mobility, policy interventions) are incorporated  

- **Structural breaks**: Sudden changes in pandemic dynamics cannot be reliably predicted  

- **Interpretability vs realism**: While ARIMA is interpretable, it lacks the flexibility needed for complex, evolving systems  



This project emphasizes **methodological understanding**, not predictive authority.



---



## 🛠️ Tools & Libraries

- Python  

- Pandas, NumPy  

- Matplotlib, Seaborn  

- statsmodels (ARIMA)



---



## 🧠 Notes

- This project is intended for **exploratory and educational purposes**

- Forecasts are illustrative and should **not** be interpreted as medical, policy, or public-health guidance



---



## 🙏 Acknowledgements

- Data provided by **Kaggle** and original data contributors  

- Open-source Python libraries used for analysis and visualization  



---



### ✍️ Author

**Srishti Tripathy**



