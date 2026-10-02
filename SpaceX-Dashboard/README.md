SpaceX Launch Dashboard
Project Overview
This project is a web-based dashboard created using Plotly Dash to analyze SpaceX launch data. The dashboard provides interactive visualizations that allow users to explore launch records, launch sites, payloads, and mission outcomes.
Dashboard Features
The dashboard includes the following features:
1. Launch Site Selection  
   - Users can select a specific launch site or view data for all launch sites.
2. Pie Chart  
   - Displays the total number of successful and unsuccessful launches.
   - The chart can be used to compare launch outcomes across different launch sites.
3. Payload Range Selection  
   - A slider allows users to select a payload mass range.
4. Scatter Plot   
   - Shows the relationship between payload mass and the selected launch outcomes/orbits.
   - The visualization changes according to the selected payload range and launch site.
Technologies Used
- Python
- Plotly Dash
- Plotly
- Pandas
- HTML/CSS
- Jupyter Notebook / Python environment
Dataset
The dashboard uses the SpaceX Launch Dataset stored in:
       "spacex_launch_dash.csv"
The dataset contains information about SpaceX launches, including launch sites, payload masses, orbit types, and mission outcomes.
Files in This Repository
- "spacex_dash_app.py" - Python source code for the Dash application.
- "spacex_launch_dash.csv" - SpaceX launch dataset.
- "README.md" - Project documentation.
- "screenshots/" - Screenshots of the completed dashboard.
How to Run the Dashboard
1. Download or clone this repository.
2. Make sure Python and the required libraries are installed.
3. Open the project folder in the terminal.
4. Run the following command:
python spacex_dash_app.py
5. Open the local URL provided by Dash in your web browser.
Dashboard Screenshot
A screenshot of the completed dashboard is included in the "screenshots" folder.
Key Insight
Based on the dashboard visualization for all launch sites, KSC LC-39A has the largest number of successful launches among the launch sites shown in the dashboard.
Project
This dashboard was created as part of the IBM Skills Network exercise Build a Dashboard Application with Plotly Dash.
