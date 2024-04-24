# Project Name

## Air Quality Visualization Tool

This project aims to visualize air quality indices for various components across different dates using interactive widgets and heatmap representations.

### Prerequisites
- Python 3.x
- Jupyter Notebook environment
- Required Python libraries: pandas, ipywidgets, folium

### Installation
1. Clone this repository to your local machine.
2. Ensure all required libraries are installed by running `pip install -r requirements.txt`.
3. Download the necessary data files (for this project we used the [Daily air quality (Citeair) indices per pollutant on the Île-de-France](https://data.europa.eu/data/datasets/5a4651eb88ee380bb9eff81e?locale=en) :
    - ninsee_lat_long.csv
    - indices_QA_commune_IDF_2014.csv
    - indices_QA_commune_IDF_2015.csv
    - indices_QA_commune_IDF_2016.csv
    - indices_QA_commune_IDF_2017.csv
4. Run the Jupyter Notebook file (`air_quality_visualization.ipynb`) to launch the application.

### Usage
1. Launch the Jupyter Notebook and execute the code cells.
2. Select the desired air quality component (PM10, NO2, or O3) from the dropdown menu.
3. Choose a specific date using the date picker widget.
4. Click the "Afficher" button to display the air quality index for the selected component and date.
5. View the generated heatmap with color-coded air quality index values.

### Features
- Interactive dropdown menu for selecting air quality components.
- Date picker widget for choosing specific dates.
- Heatmap visualization of air quality indices.
- Customizable color gradient based on air quality index values.


### License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
