# United States Power Plant Carbon Emissions Dashboard

Power plants are one of the largest sources of non-biogenic carbon dioxide emissions in the United States (U.S.). Understanding emission trends across states and facilities can help policymakers and energy stakeholders identify high-impact areas for emission reduction and cleaner energy transition.

## Dataset
Source: U.S. Environmental Protection Agency (EPA)
Time Period: 2011 - 2020

## Key Metrics
These metrics support facility-level and state-level emissions comparison over time.
- Total carbon dioxide emissions by state and year
- Emission trends over time (2011 - 2020)
- Top emitting states by total carbon dioxide emissions
- Top emitting power plant facilities by state and year

### 2020 Snapshot
- Total carbon dioxide emissions across all U.S. Power Plants
- Top 5 emitting states
- Total number of power plant facilities

## Analysis & Tools
- Cleaned and analyzed EPA emissions data using Python (Pandas, NumPy)  
- Built an interactive dashboard using Plotly and Dash  
- Implemented filters (state, facility, year) for exploratory data analysis  
- Used CSS to enhance dashboard usability and layout  

## Key Insights
- A small number of states account for the majority of total CO₂ emissions, highlighting high-impact regions for targeted emission reduction initiatives.
- Emissions trends vary across states and facilities, indicating that location-specific strategies are necessary to effectively reduce overall emissions.
- Several high-emission power plants have shown minimal reduction over the 2011–2020 period, suggesting the need for focused interventions at the facility level.

## Recommendations
- Prioritize emissions reduction initiatives in top-emitting states  
- Target facility-level improvements rather than broad national averages  
- Use interactive monitoring tools to track progress over time  

## Dashboard Features
- Dropdown menus for state selection  
- Time slider and play button for to visuzalize year-over-year emission trends
- Interactive charts for comparison across regions  

## How to Run Locally
1. Install required libraries:
   pip install numpy pandas plotly dash

2. Clone the repository and run:
   python main.py

3. Open the local server link in your browser to view the dashboard.
