# Milestone 1 — Data cleaning & preprocessing

Summary of work:
- Cleaned Start_Time & End_Time: removed fractional seconds and converted to datetime.
- Dropped high-missing-value columns: End_Lat, End_Lng, Wind_Chill(F), Weather_Timestamp.
- Removed duplicates.
- Filled missing categorical values (Street, City, Zipcode, Timezone, Airport_Code) with 'Unknown'.
- Filled numeric weather missing values (Temperature(F), Humidity(%), Pressure(in)) with median.
- Added features: Hour, Weekday, Month.
- Note: Dataset is large and excluded from repo; see README for Kaggle link.

Notebook: `analysis.ipynb`
