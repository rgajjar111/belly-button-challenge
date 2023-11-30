# Belly Button Biodiversity Dashboard
This interactive dashboard is designed to explore the Belly Button Biodiversity dataset, which catalogs the microbes colonizing human navels. The dataset reveals key information about operational taxonomic units (OTUs) present in human navels, with some species being common among the majority of individuals.

This site was built using [GitHub Pages]([https://pages.github.com/](https://rgajjar111.github.io/belly-button-challenge/).

A dropdown menu labeled "Test Subject ID No." will appear. Select a specific test subject ID to view corresponding data.

Explore the interactive charts and visualizations that provide insights into the microbial diversity of the selected test subject.

## Code Overview
The dashboard is built using HTML, JavaScript, D3.js, and Plotly.js. The main functionalities include fetching data from an external source, initializing the dashboard with default values, and updating the charts when a new test subject is selected.

Code Structure
Data Fetching: The fetchData function uses D3.js to fetch data from the provided URL.

Initialization: The init function initializes the dropdown menu and charts when the page loads.

Dropdown Menu Change: The optionChanged function is called when a new test subject is selected, updating the charts accordingly.

Chart Building: The buildCharts function coordinates the construction of bar charts, bubble charts, and metadata displays for the selected test subject.

Helper Functions: getPatientData and getPatientValues are helper functions to retrieve specific data for the selected test subject.

Charts
Bar Chart: Displays the top 10 OTUs for the selected test subject.

Bubble Chart: Visualizes the distribution of OTUs based on sample values and OTU IDs.

Metadata Display: Presents demographic information for the selected test subject.

Dependencies
D3.js
Plotly.js

## Usage
This dashboard provides an interactive and user-friendly interface to explore the Belly Button Biodiversity dataset. Feel free to experiment with different test subjects and gain insights into the microbial composition of their navels.

