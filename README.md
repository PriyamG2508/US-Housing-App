# US-Housing-App 

A comprehensive and interactive dashboard developed using Shiny for Python, designed to provide in-depth visual insights into the U.S. housing market. The platform dynamically explores key market indicators such as median listing prices, residential inventory levels, and the volume of new property listings across all 50 states, enabling a detailed analysis of nationwide housing trends through rich, interactive visualizations.

## Overview 

This interactive Shiny for Python dashboard delivers real-time insights into the U.S. housing market spanning the period from **March 2018** to **April 2025**. Designed with flexibility and usability in mind, the dashboard allows users to filter data by U.S. state and custom date ranges, enabling a granular analysis of market dynamics over time.

By combining historical data with interactive visual elements, the app provides a powerful tool for identifying and understanding trends such as shifts in median listing prices, fluctuations in housing inventory, and patterns in new property listings. Whether users are tracking price surges in coastal markets or evaluating inventory dips in rural states, the dashboard provides a cohesive and visually intuitive platform for exploring regional and national housing market behavior.

This tool is particularly valuable for anyone seeking to uncover temporal and geographic patterns in U.S. real estate — from **market researchers** and **policy analysts** to **investors** and **housing advocates**.

## Features

- **Interactive State Filtering**: Filter data for individual US states or view nationwide trends
- **Date Range Selection**: Analyze trends across custom time periods (2018-2025)
- **Real-time Metrics**: View current median listing prices and inventory percentage changes
- **Multiple Visualizations**: 
  - Median listing price trends over time
  - Home inventory levels and changes
  - New listings volume by period
- **Dual View Options**: Switch between interactive plots and detailed data tables
- **Responsive Design**: Clean, modern interface with dark/light mode toggle

## Installation

### Prerequisites
- Python 3.8 or higher
- pip package manager

### Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/PriyamG2508/US-Housing-App.git
   cd US-Housing_App
2. **Create a virtual enviroment**
   ```bash
   python -m venv housing_dashboard_env
   source housing_dashboard_env/bin/activate  # On Windows: housing_dashboard_env\Scripts\activate
3. **Install the required packages**
   ```bash
   pip install -r Requirements.txt
4. **Run the app**
   ```bash
   shiny run app.py

## Usage

### Dashboard Navigation

1. **Sidebar Controls**
   - **State Filter**: Select a specific US state or choose "United States" for nationwide data
   - **Date Range Slider**: Adjust the time period for analysis (March 2018 - April 2025)
   - **Dark Mode Toggle**: Switch between light and dark themes

2. **Main Dashboard**
   - **Value Boxes**: View current median listing price and inventory percentage change
   - **Three Main Sections**:
     - **Median List Price**: Track pricing trends over time
     - **Home Inventory**: Monitor available housing stock
     - **New Listings**: Analyze new properties entering the market

3. **Visualization Options**
   - **Plot Tab**: Interactive line charts with zoom and hover capabilities
   - **Table Tab**: Raw data in searchable, sortable tables

### Key Metrics Explained

- **Median List Price**: The middle value of all home listing prices in the selected area
- **Home Inventory**: Total number of homes available for sale
- **New Listings**: Number of properties newly listed for sale in each time period
- **Inventory % Change**: Month-over-month percentage change in available inventory

## Technologies Used

- **[Shiny for Python](https://shiny.posit.co/py/)** - Web application framework
- **[Pandas](https://pandas.pydata.org/)** - Data manipulation and analysis
- **[Plotly Express](https://plotly.com/python/plotly-express/)** - Interactive visualizations
- **[Shinywidgets](https://github.com/posit-dev/py-shinywidgets)** - Enhanced Shiny widgets
- **[Faicons](https://github.com/posit-dev/py-faicons)** - Font Awesome icons for Python
- **Python 3.8+** - Programming language

### Key Libraries
```python
import pandas as pd
import plotly.express as px
from shiny import reactive
from shiny.express import input, render, ui
```
## Contributing

Contributions are welcome! If you'd like to contribute to this project:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Ideas for Contributions
- Add more housing metrics (price per sq ft, days on market, etc.)
- Implement additional visualization types (maps, bar charts, etc.)
- Add data export functionality
- Improve mobile responsiveness
- Add unit tests

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

**Your Name** - priyamgupta2508@gmail.com

Live dashboard link: [Click here](https://priyamguptashinyapp.shinyapps.io/us_housing_app/)
---
