# Flight Price Exploratory Data Analysis (EDA)

This repository contains an exploratory data analysis (EDA) project on flight price data collected from EaseMyTrip, focusing on flights between India's top 6 metro cities. The analysis explores key factors affecting ticket prices and provides insights into patterns related to airlines, departure times, stops, and other factors.

---

## Project Overview

### Objectives
The primary goals of this project are:

- To analyze the distribution of ticket prices.
- To identify factors that influence ticket prices, such as airline, seat class, and number of stops.
- To derive actionable insights for optimizing flight pricing strategies and improving customer experience.

---

## Dataset Overview

The dataset contains **300,261 datapoints** with the following **11 features**:

1. **Airline**: Name of the airline (categorical, 6 unique values).
2. **Flight**: Flight code (categorical).
3. **Source City**: Origin city of the flight (categorical, 6 unique values).
4. **Departure Time**: Categorized departure times (categorical, 6 unique bins).
5. **Stops**: Number of stops (categorical, 3 unique values).
6. **Arrival Time**: Categorized arrival times (categorical, 6 unique bins).
7. **Destination City**: Destination city of the flight (categorical, 6 unique values).
8. **Class**: Seat class (categorical, 2 unique values: Business and Economy).
9. **Duration**: Total travel time in hours (continuous).
10. **Days Left**: Days between booking and travel date (continuous).
11. **Price**: Ticket price (target variable, continuous).

---

## Key Insights

### Highlights

- **Seat Class**: Business class tickets are significantly more expensive than economy class tickets.
- **Stops**: Flights with more stops tend to be cheaper but take longer durations.
- **Departure Times**: Peak departure times (morning and evening) correlate with higher ticket prices.
- **Airline Trends**: Certain airlines dominate specific routes and pricing categories.
- **Booking Timing**: Tickets booked closer to the travel date are generally more expensive.

---

## Project Structure

```
Flight-Price-EDA/
│
├── data/
│   └── flight_price_data.csv       # Cleaned dataset (if sharing is permitted)
│
├── notebooks/
│   └── flight_price_eda.ipynb     # Jupyter Notebook with EDA
│
├── images/
│   └── price_distribution.png     # Sample visualization outputs
│
├── README.md                      # Project documentation
│
└── LICENSE                        # Licensing information
```

---

## Setup Instructions

### Prerequisites
- Python 3.7 or higher
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`

### Steps to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/Flight-Price-EDA.git
   ```
2. Navigate to the project folder:
   ```bash
   cd Flight-Price-EDA
   ```
3. Install required libraries:
   ```bash
   pip install -r requirements.txt
   ```
4. Open the Jupyter Notebook in the `notebooks/` directory to explore the analysis:
   ```bash
   jupyter notebook notebooks/flight_price_eda.ipynb
   ```


## Future Work

- Implement predictive modeling for price forecasting.
- Integrate real-time data for dynamic analysis.
- Analyze additional features such as seasonal trends or weather impacts on prices.

---

## Contributing

Contributions are welcome! If you find an issue or have suggestions for improvement, feel free to create an issue or submit a pull request.

---


