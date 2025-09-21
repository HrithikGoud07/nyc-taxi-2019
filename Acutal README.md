# NYC Taxi Fare Prediction (2019)

## 📌 Project Overview
This project predicts taxi fares using NYC Yellow Taxi trip data (August 2019).  
We engineered additional features such as distance, time of day, weather, and holidays to improve model accuracy.

## 📂 Repository Contents
- `notebooks/` → Jupyter notebooks with preprocessing, EDA, and modeling.  
- `presentation.pptx` → Final project presentation.  
- `README.md` → Project documentation.  

## 📊 Dataset
The dataset is too large to upload here. You can download it from the official NYC Taxi & Limousine Commission (TLC):  
- [NYC TLC Trip Record Data](https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf)  
- [Yellow Taxi Trip Data (August 2019)](https://www.nyc.gov/assets/tlc/downloads/pdf/trip_data/2019/2019-08_yellow_tripdata.parquet)  

Additional features used:  
- Weather data: [NOAA](https://www.ncei.noaa.gov/)  
- Holiday data: [US Federal Holidays](https://www.opm.gov/policy-data-oversight/pay-leave/federal-holidays/)  

## ⚙️ How to Run
1. Clone this repository:  
   ```bash
   git clone https://github.com/HrithikGoud07/nyc-taxi-2019.git
Download the datasets from the links above.

Place them in a data/ folder inside the repo.

Run notebooks in order for preprocessing, training, and evaluation.

📈 Results
RMSE: ~3.96

MAE: ~1.60
