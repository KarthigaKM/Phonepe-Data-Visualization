# [PROJECT 2: PhonePe Data Visualization](https://github.com/KarthigaKM/Phonepe-Data-Visualization) 
## Overview:
 * The "PhonePe Data Visualization using Streamlit, Plotly, Python" project aims to create an interactive and visually appealing data visualization dashboard to analyze and 
  explore PhonePe transaction data. It utilizes various technologies, including Python, Streamlit, Plotly, and MySQL, to present insights from the data.
## Technologies Used:
  * Python
  * Streamlit: For building the interactive web application.
  * Plotly: For creating visually appealing and interactive plots and charts.
  * Pandas: For data manipulation and preprocessing.
  * MySQL: For storing and managing the transaction data.
##  Project Structure:
  * The project consists of the following main components:
## Main Script (phonepe_main.py):
  * The main script is responsible for running the Streamlit web application.
  * It imports the necessary libraries and establishes a connection to the MySQL database.
  * The Streamlit interface allows users to navigate between different visualizations using the sidebar.
  * The dashboard is divided into two tabs: "Chart_Visualizations" and "Map_Visualizations".
## Chart Visualizations:
 ![](https://github.com/KarthigaKM/Phonepe-Data-Visualization/blob/main/pie%20chart%20visual.PNG?raw=true)
  * The "Chart_Visualizations" tab contains six sub-tabs, each presenting specific transaction data visualizations for different states.
  * Users can select a state from the dropdown menu to view insights related to transaction types, user demographics, top transactions, and top users based on districts 
    and pincodes.
  * Plotly and Streamlit are used to create interactive pie charts and bar charts, allowing users to explore the data and understand transaction patterns.
## Map Visualizations:
![](https://github.com/KarthigaKM/Phonepe-Data-Visualization/blob/main/Map%20visual.PNG?raw=true)
  * The "Map_Visualizations" tab consists of two sub-tabs, each displaying choropleth maps based on statewise transactions and user data.
  * The "Map of Statewise Transactions" presents a choropleth map showcasing transaction data by state.
  * The "Map of Statewise Users" displays a choropleth map indicating the number of users by state.
## Data Source:
  * The project uses a MySQL database to store and manage PhonePe transaction data.
  * GeoJSON data (states_india.geojson) is utilized to create the choropleth maps.
## Deployment:
  * The interactive dashboard is deployed using Streamlit Sharing, allowing users to access and explore PhonePe data visualizations with ease.
## Future Enhancements:
  * Integration of real-time data updates to ensure up-to-date insights.
  * Incorporating machine learning models for predictive analytics.
  * Enhancing the user interface with more customization options and filters.
