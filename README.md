# Forecasting PJM power demand using regression algorithms on open-source weather data!

*Current status:* Major WIP!

Updates:
- Gathered demand-side bid price + quantity data from PJM
- Gathered locational weather data (however, will need to think of Nodal analysis)
- Cleaned data to fit future models for testing
- Started on EDA, working on shortlisting ML models / ensemble methods

Things to think about:
- Can we get nodal data to more accurately predit weather?
- How many lag-based variables to add for time-series analysis?
- One hot encode columns!
- ANNs are known to work best, reading recent research articles. Which make most sense to use here?
