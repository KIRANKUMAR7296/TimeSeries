# Time Series 🕐

`Time Series` forecasting is an application of `Data Science`

Every business operates under `risk` (based on market condition) and `uncertainity` (due to some natural calamity)

`Forecasting` helps us to assess these risks, and based on that the budgets can be managed.

In simple time we can understand with a following equation :

```
y = f(x)

y : Dependent Variable (Future)
x : Independent Variable (Past)
```

### Properties of Time Series data.

- The data points should be at `regular` interval (The time interval should be regular)
- `Intervals` of Time Series : Yearly, Quarterly (4), Monthly(12), Weekly(52), Daily(365), Hourly
- `Order` matters in time series analysis.
- No data should be missing in the given time intervals.

<table>
  <tr><th colspan=3>Time Series</th></tr>
  <tr><th colspan=2>Systematic Component</th><th colspan=1>Irregular Component</th></tr>
  <tr><td>Trend</td><td>Seasonality</td><td>Unpredicted calamity (Error)</td></tr>
  <tr><td>Long term (Ups and downs)</td><td>Regular pattern</td><td>COVID pandemic or any uncertain natural calamity</td></tr>
</table>  

### Decomposition of Time Series 

Breaking of Time Series data into `trend`, `seasonality` and `irregular` components.

We have to find this three components in a given Time Series data.
 
### Decomposition Model

There are two types of decomposition models.

`Additive` Model ( If Seasonality is `constant` ) : `Observation` = `Trend` + `Seasonality` + `Error`

```
Forecasting Sales with Trend, Seasonality and Error :

Sales = Trend (Business Growth) + Seasonality (Weather) + Error (Theft / Calamity)
```

`Multiplicative` Model ( If Seasonality is `changing` ) : `Observation` = `Trend` * `Seasonality` * `Error`

### Statsmodels 

Python library that provides `classes` and `functions` to perform statistical tests on time series data.
