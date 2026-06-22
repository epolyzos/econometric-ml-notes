# Econometric Modeling and Machine Learning – Raw Data Repository

This repository contains **raw datasets** for the project *Econometric Modeling and Machine Learning with R for Applied Forecasting* by **Efstathios Polyzos**.  
The data is made openly available for research and teaching purposes.

---

## Contents

- `data/` – Raw datasets in CSV or other formats.  
- `README.md` – Description of repository and datasets.  
- `LICENSE` – GNU General Public License v3 (GPLv3).  

---

## License

This repository is licensed under the **GNU General Public License v3 (GPLv3)**.  
You are free to use, share, and adapt the data, provided any derivative works are distributed under the same license.  
See the [LICENSE](LICENSE) file for details.

---

## Citation

If you use this repository in your research or teaching, please cite as:
Polyzos, Efstathios (2025). Raw Data for Econometric Modeling and Machine Learning Lecture Notes. GitHub. https://github.com/epolyzos/econometric-ml-notes


---

## Data Dictionary

| File name            | Description                             | Variables included               | Notes |
|----------------------|-----------------------------------------|----------------------------------|-------|
| `global_economy.csv` | Panel data on GDP, CPI, trade, etc.     | Country, Year, GDP, CPI, Trade…  | Extracted from World Bank WDI |
| `financial_timeseries.csv` | Daily financial time series for selected cryptocurrencies and stocks with calendar variables and returns. | symbol, asset_class, date, year, month, weekday, open, high, low, close, volume, adjusted, log_price, log_volume, return, abs_return | Downloaded from Yahoo Finance using `tidyquant`; used for examples of seasonality in financial time series. |
| `…`                  |                                         |                                  |       |


---

## Contact

**Efstathios Polyzos**  
Associate Professor of Finance  
Zayed University, UAE  
Email: Efstathios.Polyzos@zu.ac.ae  
