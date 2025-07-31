# Flight Delay and Cancellation Analysis (U.S. Domestic Flights - 2015)

This project explores the causes and patterns of flight delays and cancellations in the U.S. aviation industry using 2015 historical flight data. The analysis was conducted using SQL for data preparation and Power BI for interactive dashboard visualization. The goal is to provide actionable insights for stakeholders such as airlines, airport authorities, and policy makers.

## Project Objectives

- Analyze the primary reasons for flight delays and cancellations.
- Evaluate performance across airlines and airports.
- Examine how time-based factors (hour, weekday, month) affect operations.
- Build interactive dashboards for data exploration and reporting.
- Deliver strategic recommendations to improve on-time performance.

## Tools & Technologies Used

- **SQL (PostgreSQL)** – Data ingestion, cleaning, enrichment, KPI definition
- **Power BI** – Dashboard creation, interactivity, insights generation
- **Microsoft Excel** – Preliminary data validation
- **Python (optional)** – Used to automate report generation and dashboard creation
- **GitHub** – Version control and project sharing

## 🧾 Datasets

- `flights.csv`: Contains detailed flight-level records (date, airline, delay times, etc.)
- `airlines.csv`: Airline code to full name mapping
- `airports.csv`: Airport codes with city, state, and geolocation

Source: [U.S. DOT / Kaggle](https://www.kaggle.com/datasets/giovamata/airline-delay-and-cancellation-data-2009-2018)

## Dashboard Highlights

- **Overview Page**: Key KPIs including On-Time Performance, Average Delay, Cancellation Rate.
- **Airline Analysis**: Comparison of OTP%, delay types, and cancellations across airlines.
- **Temporal Trends**: Delays by hour of day, day of week, and month.
- *(Planned)*: Route-level and airport-level performance dashboards.

Power BI Dashboard: `Flight_Delay_Cancellation_Analysis_Presentation.pbix`  

## Key Insights

- Airline and Late Aircraft delays are major contributors to total delays.
- Peak delays occur between **5–8 PM**, especially during **summer months**.
- **Alaska Airlines** has the best OTP, while **Frontier** shows high cancellations.
- ORD and ATL are among the top delay-prone airports.



1. Improve early morning operational efficiency to prevent cumulative delays.
2. Enhance weather preparedness through predictive systems and resource planning.
3. Optimize aircraft turnaround schedules to reduce Late Aircraft delays.

---

## 📂 Repository Structure

