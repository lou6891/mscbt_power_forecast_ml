# Power Forecast Ml Model
## Group Assigment Data Analytics Class MCSBT at IE

### Important:
> Data not present .For this project we do not have authorization to disclose full the data

### Team:
- Luca Conti
- Diego Marroquin ([GitHub](https://github.com/dmarroq))

### The Assigment:
Power Retail companies need an accurate power consumption prediction to buy electricity in the-wholesale market. 
They have available the consumption data of each customer per hour. 

The datastructure is depicted in the following table:

| Field   | Meaning                   |
|---------|---------------------------|
| CUPS    | Customer Code             |
| ZipCode | Postal Code               |
| Rate    | Customer Type             |
| Date    | Date of Consumption       |
| Hour    | Hour of Consumption       |
| Value   | Consumption in watts-hour |

You will be given a file with the described structure that contains detailed consumption data form 
2016-01-01 to 2017-06-30. Your task is to predict the total energy consumption of your customer for dates between 
2017-08-01 to 2017-11-01.

You must consider things like:
- Seasonality
- External factors
- Customer base variations


### Deliverables: 
1. A presentation describing Global approach 
   - The data analysis process
   - Data Transformations
   - External data 
   - Feature engineering
   - Modelling
2. The program implementing these steps and getting the results