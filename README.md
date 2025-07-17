# 🚌 Portland Bus Ridership Forecasting (1960–1968)

This project analyzes monthly bus ridership in Portland, Oregon, from January 1960 to December 1968. Using time series analysis techniques in **JMP Pro**, the goal was to forecast ridership for the first half of 1969 and support future planning for public transit operations.

The project was completed as part of a graduate-level course in Advanced Regression and showcases methods for trend analysis, stationarity testing, seasonal adjustment, and SARIMA modeling.

---

## 📌 Project Objectives

- Visualize trends and seasonality in monthly ridership  
- Determine whether the series is stationary using ADF testing  
- Apply differencing to stabilize the series  
- Build and evaluate SARIMA models  
- Forecast future ridership with confidence intervals  

---

## 🧪 Tools & Methods

- **JMP Pro** – Time series modeling, diagnostics, and forecasting 
- **Markdown/PDF** – Report and documentation  

---

## 📈 Forecast Summary

Using the best-fitting SARIMA(0,1,0)x(1,1,1)[12] model, bus ridership was forecasted for January–June 1969. The model accounts for both trend and seasonality, and all key parameters were statistically significant.

| Month    | Forecast | 95% CI Lower | 95% CI Upper |
|----------|----------|--------------|--------------|
| Jan 1969 | 1,407    | 1,345        | 1,469        |
| Feb 1969 | 1,415    | 1,327        | 1,503        |
| Mar 1969 | 1,377    | 1,270        | 1,485        |
| Apr 1969 | 1,391    | 1,267        | 1,515        |
| May 1969 | 1,364    | 1,225        | 1,502        |
| Jun 1969 | 1,314    | 1,162        | 1,466        |

---

## 📚 Documentation

- 📄 [Final Report](./report/portland_bus_ridership_report.pdf) – Full analysis, results, and appendix   
- 📊 [Dataset Info](./data/README.md)  
