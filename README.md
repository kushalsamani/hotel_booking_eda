# Hotel Booking EDA – AtliQ Hotels

This project analyzes booking and revenue data for **AtliQ Hotels**, a hotel chain with properties across India.  
The goal was to answer key business questions about **occupancy, revenue, cancellations, and guest behavior** so that the management team can make smarter, data-driven decisions.

---

## Project Objective
Hotels deal with thousands of bookings every month, spread across different cities, room types, and platforms.  
The management team wanted to know:
- Which rooms and cities are performing best?  
- How do weekends compare with weekdays?  
- Which booking platforms bring the most revenue?  
- What do guest ratings say about service quality?  

To answer these, we explored multiple datasets, cleaned them, and ran **exploratory data analysis (EDA)**.

---

## Data Sources
The analysis used six interrelated datasets:
- Hotel details (city, category, property type)  
- Room details and capacity  
- Booking transactions  
- Aggregated booking stats  
- Calendar dimension (dates, months, weekdays)  
- New incremental bookings for August  

Data was cleaned by:
- Handling invalid values (e.g., negative number of guests)  
- Removing outliers using the **±3 standard deviation** method  
- Standardizing data types for consistency  

---

## Key Business Questions & Insights

### 1. Average occupancy by room type  
- **Presidential suites** lead with ~59.3% occupancy.  
- Other room types (Elite, Premium, Standard) are ~58%.  

### 2. Average occupancy by city  
- **Delhi hotels** have the highest occupancy (~61.6%).  
- **Bangalore hotels** are the lowest (~56.6%).  

### 3. Weekday vs Weekend occupancy  
- **Weekends consistently outperform weekdays**, making them critical for revenue planning.  

### 4. June occupancy by city  
- **Delhi** again leads (~62.5%), followed by Hyderabad and Mumbai (~58%).  

### 5. Revenue by city  
- **Mumbai is the top performer** with ₹784M realized revenue.  
- Delhi contributes the least at ₹346M.  

### 6. Month-by-month revenue  
- May: ₹582M → Highest  
- June: ₹554M → Lowest  
- July: ₹573M  

### 7. Revenue by hotel type  
- **Luxury hotels** dominate with over ₹1.05B in revenue.  
- Business hotels contribute ~₹656M.  

### 8. Guest ratings by city  
- Guests in **Delhi rated hotels highest (3.78/5)**.  
- Guests in **Bangalore gave the lowest ratings (3.41/5)**.  

### 9. Revenue by booking platform  
- Majority of revenue comes from **online booking platforms**, highlighting the importance of digital channels.  
- **Others:** ~40.9% (largest single bucket)  
- **MakeYourTrip:** ~19.9%  
- **LogTrip:** ~11.0%  
- **Tripster:** ~7.2%  
- **Journey:** ~6.0%  
- **Direct Online:** ~9.9%  
- **Direct Offline:** ~5.1%  

**Takeaway:** Revenue is fragmented. Named OTAs (MakeYourTrip, LogTrip, Journey, Tripster) **collectively ~44%**, which is much higher than direct channels (~15%). 
However, the single biggest share sits in **“Others” (~40.9%)**, indicating a long tail/unclassified sources that’s worth breaking down further.

---

## Data Visualizations
A few visuals created to support insights:

- **Monthly revenue trend** (up and down across May–July)  
- **Booking status distribution** (Checked-out vs Cancelled vs No-show)  
- **Weekend vs weekday revenue** (weekends perform better in occupancy, weekdays contribute more revenue overall)  
- **Revenue heatmap by city × month** (Mumbai dominates across months)  
- **Revenue vs ratings distribution** (ratings don’t strongly correlate with revenue)  
- **Correlation matrix** (revenue realized strongly linked with revenue generated, weak with ratings)  

---

## Tools Used
- Python (Pandas, NumPy)  
- Visualization: Matplotlib, Seaborn  
- Jupyter Notebook  

---

## Value of the Analysis
This analysis gave the hotel management a **clear picture of where revenue is coming from, what drives occupancy, and how customers perceive the brand**.  

In simple words:
- **Delhi hotels are busy, Mumbai hotels are rich.**  
- **Weekends keep rooms full, luxury hotels keep the money flowing.**  
- **Guest happiness is mixed — especially in Bangalore.**  

With these insights, the team can now:
- Optimize room pricing by city and season.  
- Double down on online booking platforms.  
- Improve service quality in lower-rated cities.  

---

## How to Run
1. Clone the repo  
2. Place all datasets in the `datasets/` folder  
3. Open and run `hotel_analysis.ipynb` in Jupyter Notebook  

---
