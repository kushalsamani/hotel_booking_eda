\# 📊 Hotel Booking EDA Project



This project explores hotel booking patterns using six interrelated datasets. The goal is to uncover trends, seasonal behaviors, revenue insights, and booking patterns to help hotel operators make data-driven decisions.



---



\## 📁 Dataset Overview



| File                     | Description                             |

|--------------------------|-----------------------------------------|

| `dim\_date.csv`           | Calendar dimension (dates, months, weeks) |

| `dim\_hotels.csv`         | Hotel-level details                     |

| `dim\_rooms.csv`          | Room-level details                      |

| `fact\_aggregated\_bookings.csv` | Daily aggregate bookings              |

| `fact\_bookings.csv`      | Raw transactional bookings              |

| `new\_data\_august.csv`    | New bookings data for August            |



---



\## 🧪 EDA Performed



\- Missing value treatment (e.g., capacity filled using mean)

\- Data type standardization (e.g., date parsing)

\- Handling mismatches (e.g., bookings > capacity)

\- Exploratory visualizations:

&nbsp; - Revenue trends by month

&nbsp; - City-wise and platform-wise revenue

&nbsp; - Booking status distribution

&nbsp; - Ratings vs revenue

&nbsp; - Room category popularity

&nbsp; - Weekend vs weekday comparison

&nbsp; - Heatmaps (City × Month revenue)



---



\## 📓 Tools Used



\- Python

\- Pandas

\- Matplotlib

\- Seaborn

\- Jupyter Notebook



---



\## 🚀 How to Use



1\. Clone the repo

2\. Place all CSV files in the `data/` folder

3\. Open `hotel\_analysis.ipynb` and run the notebook



---



\## 🔍 Future Improvements



\- Add predictive modeling (e.g., cancellation prediction)

\- Merge August data and rerun time-series analyses

\- Deploy key metrics using a dashboard (e.g., Streamlit or PowerBI)





