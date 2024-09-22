# Hotel Booking Analysis Dashboard

This project is a data visualization dashboard built using Plotly Dash and Bootstrap for analyzing hotel booking trends, guest behavior, and revenue insights. The dashboard allows for interactive exploration of key insights from hotel booking data, offering a range of visualizations like time-series line charts, bar plots, heatmaps, and choropleth maps.

## Features

- **Interactive Dashboard**: Users can navigate through different insights via the sidebar, which offers three key analysis areas:
  1. **Booking Trends and Seasonality**: Visualize booking trends over time and seasonal patterns.
  2. **Guest Behavior and Preferences**: Explore guest preferences, including hotel type, meal type, and room type.
  3. **Revenue and Performance Insights**: Analyze hotel performance through revenue and guest metrics across different countries.
  
- **Time-Series Analysis**: Dynamic line and area charts to observe booking trends over time for different hotel types and room types.

- **Geographical Insights**: Choropleth maps showing the origin of guests.

- **Guest Preference Analysis**: Bar plots and pie charts show how guest preferences vary over different hotel and meal types.

- **Cancellation Insights**: Bar plots to understand cancellation rates over different months.

- **Room Type Insights**: Box plots highlighting the average daily rate (ADR) across various room types and hotel categories.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/DhruvViradiya1515/Hotel-Booking-Analysis-Dashboard.git
    cd hotel-booking-analysis
    ```

2. Install the required Python packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Run the app:
    ```bash
    python app.py
    ```

2. Open your web browser and navigate to `http://127.0.0.1:8050/`. The dashboard will be displayed.

## Project Structure

```bash
hotel-booking-analysis/
│
├── app.py                   # Main application script
├── hotel_bookings.csv        # Dataset
├── README.md                 # This file
```

## Visualizations
1. Booking Trends Over Time: Line and area charts showing booking trends for resort and city hotels.
2. Guest Behavior: Bar plots, heatmaps, and pie charts providing insights into guest preferences by meal type, hotel type, and more.
3. Revenue and Performance: Choropleth maps visualizing the geographic distribution of guests and heatmaps showing booking density by month.


## Dependencies
- Dash
- Dash Bootstrap Components
- Plotly
- Pandas
- Seaborn
- Matplotlib

You can install these dependencies using:
```bash
pip install dash dash-bootstrap-components plotly pandas seaborn matplotlib
```
