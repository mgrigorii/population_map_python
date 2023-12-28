# population_map_python
# World Population Visualization

This project visualizes global population data using GeoPandas and Folium in a Jupyter Notebook environment.

## Introduction

This repository contains code that generates a map displaying country borders along with their respective population data. It uses free geographical data obtained from Natural Earth to draw country borders and population estimates.

## Project Structure

- `world_population.ipynb`: Jupyter Notebook containing the code for data visualization.
- `README.md`: This file providing an overview of the project and instructions for replicating the visualization.

## Dependencies

- `geopandas`: For handling geographical data and visualization.
- `matplotlib`: For plotting country borders and population data.
- `folium`: For creating an interactive map with pop-up information for each country.

## Code Overview

### Data Loading and Visualization

The notebook begins by importing necessary libraries and loading geographical data using GeoPandas. It visualizes country borders on a matplotlib plot, coloring countries based on their population estimates using a 'plasma' colormap.

### Interactive Map Creation

After the visualization, the code proceeds to create an interactive map using Folium. It iterates through the country data, creating pop-ups for each country's centroid location. These pop-ups display the country's name and population estimate.

## How to Run

To replicate this visualization:

1. Install the required dependencies mentioned in the `requirements.txt` file.
2. Ensure you have Jupyter Notebook installed.
3. Download the `world_population.ipynb` file.
4. Open Jupyter Notebook and run each cell in the notebook sequentially.

## Credits

- GeoPandas: [GeoPandas Documentation](https://geopandas.org/)
- Natural Earth Data: [Natural Earth](https://www.naturalearthdata.com/)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
