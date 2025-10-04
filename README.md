Code Execution Guide

This directory contains the resources necessary for visualizing global energy consumption data using HTML, CSS, JavaScript, D3.js, and data files (CSV/JSON). The guide explains the purpose of each file and how to run them effectively.
________________________________________
Home Page (index.html)

The project begins with a homepage (index.html) that provides an overview of the energy visualization project.

  •	The page features a modern, responsive design with a gradient background and a centered glass-style container.
  
  •	It introduces the project with a brief description of its goals: exploring energy data through interactive charts.
  
  •	A button labeled “Energy Charts Project” is provided. When clicked, it redirects the user to charts.html, where the data visualizations are hosted.
  
This homepage serves as the entry point for the project and ensures a user-friendly start for exploring energy insights.
________________________________________
HTML Files

Each HTML file is designed to display a specific energy consumption visualization. Open them directly in a modern web browser (Chrome, Firefox, or Edge recommended).
1.	Fossil_fuel_stack_area.html
      o	Displays a stacked area chart of global fossil fuel consumption.
2.	Map_visual_percapita_Engy_Index_2.html
      o	Provides a per capita energy consumption index using an interactive map.
3.	Map_visual_primary_Engy_Index.html
      o	Maps global primary energy consumption indices.
4.	Per_capita_energy_Linechart.html
      o	Shows per capita energy consumption trends as a line chart.
5.	Primary_Energy_Linechart.html
      o	Visualizes annual consumption trends for primary energy sources.
6.	Renewable_Energy.html
      o	Displays data related to renewable energy adoption and usage.
7.	Renew_linechart.html
      o	Shows renewable energy consumption trends over time using a line chart.
________________________________________
Running the HTML Visualizations

•	All visualizations fetch their data directly from GitHub (CSV/JSON sources). No manual adjustments to file paths are required.

•	Simply open the desired .html file in a supported browser.

•	After launching one visualization, you can seamlessly switch between others using the dropdown menu integrated into each page.
________________________________________
Data Files

1.	CSV Files
   
    o	global-fossil-fuel-consumption.csv – Global fossil fuel usage data.
    o	per-capita-energy-use.csv – Energy consumption per person across countries.
    o	primary-energy-cons.csv – Primary energy consumption trends.
    o	renewable-share-energy.csv – Share of renewable energy in total energy consumption.
  	
3.	JSON File

    o	world_map.json – Geographic boundary data required for map-based visualizations.
________________________________________
Working with Data Files

•	Since all files are hosted online, they are automatically fetched when opening the HTML visualizations.

•	Ensure you have an active internet connection to load charts properly.
________________________________________
Troubleshooting

•	Missing Data: If visualizations appear blank, confirm your internet connection so data can be retrieved from GitHub.

•	Browser Compatibility: Use the latest version of Chrome, Firefox, or Edge. Some visualizations may not render correctly on outdated browsers.


