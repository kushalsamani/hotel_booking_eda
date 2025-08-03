# Hotel Booking EDA Project



This project explores hotel booking patterns using six interrelated datasets. The goal is to uncover trends, seasonal behaviors, revenue insights, and booking patterns to help hotel operators make data-driven decisions.



---



## Dataset Overview



| File                     | Description                             |

|--------------------------|-----------------------------------------|

| `dim_date.csv`           | Calendar dimension (dates, months, weeks) |

| `dim_hotels.csv`         | Hotel-level details                     |

| `dim_rooms.csv`          | Room-level details                      |

| `fact_aggregated_bookings.csv` | Daily aggregate bookings              |

| `fact_bookings.csv`      | Raw transactional bookings              |

| `new_data_august.csv`    | New bookings data for August            |



---



## EDA Performed



- Missing value treatment (e.g., capacity filled using mean)

- Data type standardization (e.g., date parsing)

- Handling mismatches (e.g., bookings > capacity)

- Exploratory visualizations:

- Revenue trends by month

- City-wise and platform-wise revenue

- Booking status distribution

- Ratings vs revenue

- Room category popularity

- Weekend vs weekday comparison

- Heatmaps (City × Month revenue)



---



## Tools Used



- Python

- Pandas

- Matplotlib

- Seaborn

- Jupyter Notebook



---



## How to Use



1. Clone the repo

2. Place all CSV files in the `datasets` folder

3. Open `hotel_analysis.ipynb` and run the notebook



---



## Future Improvements



- Add predictive modeling (e.g., cancellation prediction)

- Merge August data and rerun time-series analyses

- Deploy key metrics using a dashboard (e.g., Streamlit or PowerBI)





