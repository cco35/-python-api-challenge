# Exploring Weather Patterns: WeatherPy and VacationPy Data Analysis Project

## Project Overview

This project aims to analyze weather data using Python, requests, APIs, and JSON traversals to answer the question: "What is the weather like as we approach the equator?" The analysis is divided into two main parts: WeatherPy and VacationPy.

## Project Structure

### Part 1: WeatherPy
The WeatherPy part of the project involved the following tasks:
- **WeatherPy.ipynb:** Jupyter notebook for visualizing weather data and computing linear regressions.
  - Generated random geographic coordinates.
  - Used citipy to find the nearest city to each latitude and longitude combination.
  - Retrieved weather data using the OpenWeatherMap API for cities generated.
  - Created scatter plots showcasing the relationship between latitude and weather variables (Temperature, Humidity, Cloudiness, Wind Speed).
  - Computed linear regressions for each relationship, separated into Northern and Southern Hemispheres.

### Part 2: VacationPy
The VacationPy part of the project included the following activities:
- **VacationPy.ipynb:** Jupyter notebook for vacation planning based on weather data.
  - Utilized geoViews Python library and Geoapify API to create map visualizations.
  - Displayed a point for every city in the city_data DataFrame, where point size represented humidity.
  - Narrowed down city_data to find ideal weather conditions for vacation (temperature, wind speed, cloudiness).
  - Used Geoapify API to find the first hotel located within 10,000 meters of coordinates for each city.
  - Added hotel name and country as additional information in the hover message for each city on the map.

## Repository Structure

The repository is structured as follows:

- **.gitignore:** File to exclude sensitive files and folders like `api_keys.py` and cache files from version control.

- **README.md:** Overview of the project.

- **output_data/:**
  - Contains the following files and folders:
    - `cities.csv`: Dataset containing city data.
    - `fig1.png`: Image file of City Latitude vs Maximum Temperature plot.
    - `fig2.png`: Image file of City Latitude vs Humidity plot.
    - `fig3.png`: Image file of City Latitude vs Cloudiness plot.
    - `fig4.png`: Image file of City Latitude vs Wind Speed plot.

- **weatherpy/:**
  - Contains the following files and folders:
    - `WeatherPy.ipynb`: Jupyter notebook for weather data analysis.
    - `VacationPy.ipynb`: Jupyter notebook for vacation planning.
    - `__pycache__/`: Folder containing cached Python files.
    - `.ipynb_checkpoints/`: Folder containing Jupyter notebook checkpoints.

## Tools Used

- Python
- Jupyter Notebook
- OpenWeatherMap API
- Geoapify API
- Pandas
- Matplotlib

## Conclusion
This project showcases my proficiency in working with weather data, performing data analysis using Python and Jupyter Notebook, utilizing APIs for data retrieval, generating visualizations, and deriving insights for vacation planning based on weather conditions.
