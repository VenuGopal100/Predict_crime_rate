📊 Chicago Crime Data Analysis and Forecasting

This project performs data cleaning, visualization, and forecasting on Chicago crime data from 2005 to 2017. Using Python’s data analysis and visualization libraries along with Facebook Prophet, the project analyzes crime trends and predicts future crime occurrences.

🧩 Project Overview

The goal of this project is to:

Clean and preprocess large-scale crime datasets from multiple years.

Explore and visualize crime patterns by type, location, and time.

Build a time-series forecasting model to predict future crime trends using Prophet.

🗂️ Dataset

Three datasets were combined for analysis:

Chicago_Crimes_2005_to_2007.csv

Chicago_Crimes_2008_to_2011.csv

Chicago_Crimes_2012_to_2017.csv

Each dataset contains crime records including date, type, location, and more.

⚙️ Requirements

Install the required dependencies before running the script:

pip install numpy pandas matplotlib seaborn prophet

📘 Code Workflow

Data Loading

Reads three separate CSV files and concatenates them into one dataframe.

Data Cleaning

Removes unnecessary columns like coordinates, case numbers, and FBI codes.

Handles missing values and converts date columns to datetime format.

Exploratory Data Analysis (EDA)

Visualizes missing values using a heatmap.

Displays the most common crime types and their frequency.

Plots the top crime locations.

Generates yearly, monthly, and quarterly crime trend plots.

Forecasting with Prophet

Aggregates monthly crime counts.

Fits a Prophet model to predict future crime occurrences.

Plots forecast trends and seasonal components.

📈 Example Outputs

Crime frequency by type and location (bar charts)

Yearly, monthly, and quarterly crime trends (line plots)

Prophet model forecast and components (trend, seasonality)

🚀 How to Run

Place the CSV files in the same directory as crime.py.

Run the script:

python crime.py


The script will display visualizations and generate Prophet model forecasts interactively.

🧠 Key Learnings

Handling and merging large real-world datasets.

Applying time-series analysis to real-world crime data.

Using Facebook Prophet for forecasting with seasonality and trend detection.

Visualizing data insights effectively with Seaborn and Matplotlib.

📅 Future Improvements

Integrate geospatial analysis for crime hotspots using Folium or GeoPandas.

Automate data preprocessing for new datasets.

Deploy the forecasting model with an interactive dashboard (e.g., Streamlit or Dash).

👨‍💻 Author

Venu Gopal
Project: Chicago Crime Forecasting
Tools: Python, Pandas, Matplotlib, Seaborn, Prophet
