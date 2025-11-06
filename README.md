# OYO-Hotel-Booking-Analysis

<img width="900" height="300" alt="Image" src="https://github.com/user-attachments/assets/e1b0694c-61a8-4971-a8e4-d0c090f651e7" />

## Objective and Analysis
I carried out an Exploratory Data Analysis (EDA) on a hotel booking dataset comprising two categories: Resort Hotel and City Hotel. To improve the dataset’s usability and enhance user interaction, I performed feature engineering by modifying and transforming specific variables. For example, the 'Is Canceled' field was restructured into a categorical format (Yes/No) to make it more intuitive. I also separated the date into distinct components- day, month, and year- enabling time-based filtering and analysis.
To maintain data quality, I addressed missing values, eliminated duplicates, and cleaned the dataset for greater consistency and reliability. Once the data was preprocessed, I utilized Power BI to create a dynamic dashboard. The visuals, built using data imported from a Python-based analysis, were aligned with targeted objectives to deliver actionable insights. This approach supports a comprehensive understanding of booking patterns, customer preferences, and operational performance, ultimately aiding strategic, data-informed decision-making for optimizing future revenue. 

## DataSet
The dataset consists of 119,390 records with 32 columns, covering bookings made for two hotel types:
1) 🏨 City Hotel
2) 🏖️ Resort Hotel


<img width="2880" height="1398" alt="Image" src="https://github.com/user-attachments/assets/e85d39b2-ad31-449e-b34b-b2248226eb13" />
   
Key Features:
Booking behavior (is_canceled, lead_time, arrival_date)
Guest demographics (adults, children, babies, country)
Room and stay details (reserved_room_type, assigned_room_type, adr, special_requests)
Financial and channel information (adr, deposit_type, distribution_channel)

## Conclusion
This project provides valuable insights into hotel customer behavior, preferences, and operational factors. It helps stakeholders make informed decisions to improve service quality, increase revenue, and optimize bookings.

## Insights

• Analyzed 100k+ records using Python to uncover booking patterns, revenue trends, and customer behaviors. Employed pandas, matplotlib, and seaborn for data aggregation and visualization, boosting data visibility for targeted marketing campaigns.

• Discovered a surge in bookings in 2016 and peak revenue in 2017; identified transient customers as yielding the highest daily earnings and contract customers as generating maximum revenue; tackled high booking cancellation ratios with proposed mitigation strategies.

• Designed metrics to pinpoint key factors influencing booking cancellations, delivering actionable insights to enhance customer retention and reduce cancellations.
