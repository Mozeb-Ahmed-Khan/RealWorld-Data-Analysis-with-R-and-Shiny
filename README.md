# Real World Data Analysis with R and Shiny

## Project Overview
This project is designed to perform statistical analysis on a real-world dataset and present the results through a web interface using R and Shiny. The project is developed as part of a team effort, following guidelines for implementing various statistical tools, graphical representations, and regression modeling.

## Key Features:
1. **Web Interface**: The application is built using `Shiny` and allows users to view, analyze, and update the data dynamically.
2. **Real-Time Statistical Analysis**: 
   - **Descriptive statistics** such as mean, median, and interquartile range (IQR).
   - **Graphical Representations**: Data visualization through histograms, scatter plots, and more.
   - **Probability Distributions**: Apply appropriate probability distributions to the dataset.
   - **Regression Modeling**: Build and visualize predictive models based on the data.
3. **Interactive Data Update**: Users can add or delete data through the web interface, and the statistical analysis is updated accordingly.
   
## Dataset:
The dataset chosen for this project is "Meteorite Landings", which contains data about meteorite masses, locations, and classifications. The data is loaded, cleaned, and analyzed in real-time using R.

## Technologies Used:
- **R** for backend statistical analysis.
- **Shiny** for web interface and dynamic interaction with data.
- **Shiny Themes** for customizing the UI appearance.
- **ggplot2**, **plotrix** for data visualization.
- **leaflet** for map visualizations.
- **dplyr**, **plyr** for data manipulation.

## Statistical Analysis Methods:
1. **Central Tendency & Dispersion**: Calculation of the median, interquartile range (IQR), and other measures of data spread.
2. **Graphical Representation**: Interactive plots displaying key insights from the data.
3. **Probability Distribution**: Application of probability models to understand the distribution of the dataset.
4. **Regression Modeling**: Building and evaluating regression models for predictions based on the dataset.

## How to Run the Project:
1. **Clone the repository**: 
   ```bash
   git clone https://github.com/Mozeb-Ahmed-Khan/RealWorld-Data-Analysis-with-R-and-Shiny.git
2. **Install the required R packages**: Open your R console or RStudio and run the following command:
   ```bash
   install.packages(c('shiny', 'shinythemes', 'Hmisc', 'dplyr', 'plyr', 'magrittr', 'plotrix', 'ggplot2', 'leaflet', 'leaflet.extras', 'DT', 'htmltools'))
3. **Run the Shiny app**: After cloning the repository and installing the necessary packages, navigate to the project folder and run the app using:
   ```bash
   shiny::runApp('C:\Users\Aisha\Desktop\Semester 8\Regular Courses\Probability & Statistics')

## Team Details:
**Team Leader**: 
Mozeb Khan

**Team Members**:
1. Usman Bashir
2. Rabia Arif
3. Ahmed Saleem
