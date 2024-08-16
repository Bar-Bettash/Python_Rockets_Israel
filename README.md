
<h1 align="center">Data Science & Machine Learning : Israel's Rockets Attacks and CPI<p align="center"></h1>

<h1 align="center">Bar Bettash<p align="center">
<a href="https://www.linkedin.com/in/barbettash/" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="LinkedIn" height="30" width="40" /></a>
</h1>


<!-- ABOUT THE PROJECT -->
## About The Project

This data science project analyzes the relationship between rocket attacks and the National Consumer Price Index (CPI) in Israel from October 7th, 2023, to July 30th, 2024. The project utilizes various data science techniques, including data preprocessing, exploratory data analysis, statistical analysis, geospatial visualization, and machine learning modeling.

## Dataset

The project uses two main datasets:

1. Rocket attack data:
   Data Credit : RocketAlert.live
   Contains information about rocket attacks, including date, location, and timing.
   
2. Consumer Price Index (CPI) data:
  Data Credit: https://fred.stlouisfed.org/
  Monthly National CPI values for Israel.

### Built With

Python <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a>

![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) <a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/pandas/pandas-original.svg" alt="pandas" width="40" height="40"/> </a>

![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black) <a href="https://matplotlib.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/matplotlib/matplotlib-original.svg" alt="matplotlib" width="40" height="40"/> </a>

![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white) </p>

![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white) 


<!-- GETTING STARTED -->
## Getting Started


### Prerequisites

To run the project, you need the following libraries installed:

* pandas: A powerful library for data manipulation, analysis, and loading data from various sources (CSV in this case).
  ```sh
  pip install pandas

* json: Built-in Python library for working with JSON data (no installation required)

* geopandas: For working with geospatial data
  ```sh
  pip install geopandas

* matplotlib: Used for creating static visualizations like histograms and scatterplots to explore data.
  ```sh
  pip install matplotlib

* seaborn: A high-level library built on top of matplotlib for creating more sophisticated and visually appealing data visualizations.
  ```sh
  pip install seaborn

* scikit-learn: For machine learning algorithms. Offers functions for splitting datasets into training and testing sets, a crucial step in machine learning.
  ```sh
  pip install scikit-learn
  

* shapely: For creating and manipulating geometric objects
  ```sh
  pip install shapely
  
* contextily: For adding basemaps to plots
  ```sh
  pip install contextily
  
* statsmodels: For statistical modeling and econometrics
  ```sh
  pip install statsmodels
  
* torch: For deep learning with PyTorch
  ```sh
  pip install torch
  

## Technologies Used

- Python 3.x
- Pandas for data manipulation
- Matplotlib and Seaborn for data visualization
- GeoPandas and Contextily for geospatial analysis
- Scikit-learn for data preprocessing and evaluation
- PyTorch for deep learning modeling

## Project Structure

1. Data Loading and Preprocessing
2. Exploratory Data Analysis (EDA)
3. Geospatial Visualization
4. Statistical Analysis
5. Machine Learning Modeling

## Key Findings

- Temporal patterns in rocket attacks
- Geographical distribution of attacks
- Correlation between rocket attacks and CPI across different areas
- Predictive modeling of CPI based on rocket attack data

## Machine Learning Model

The project implements a neural network using PyTorch to predict the National CPI based on rocket attack data and other relevant features. The model architecture includes:

- Input layer
- Two hidden layers with ReLU activation
- Output layer

The model is trained using Adam optimizer and Mean Squared Error loss function.

## How to Run

1. Clone this repository
2. Install required packages: `pip install -r requirements.txt`
3. Run the Jupyter notebook or Python script

## Future Work

- Incorporate additional economic indicators
- Experiment with more advanced machine learning models
- Conduct time series analysis for better trend prediction

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.


<!-- CONTACT -->
## Contact

<p align="left">
<a href="https://www.linkedin.com/in/barbettash/" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="https://www.linkedin.com/in/barbettash/" height="30" width="40" /></a>
</p>


**bar.bettash.jobs@gmail.com** 


<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

This code is provided "as is" and may not function as intended in the future due to potential updates to external libraries, frameworks, websites, or APIs it interacts with. The code is no longer actively maintained and may require modifications to adapt to future changes.

**Recommendations:**

* Keep an eye on updates to libraries and dependencies to ensure compatibility.
* Be prepared to adapt the code based on future changes in the target website or API.



