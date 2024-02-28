# sqlalchemy-challenge

Overview
This repository contains code for analyzing climate data in Honolulu, Hawaii. It includes a Jupyter notebook for data analysis and exploration, as well as a Flask API to access the analysis results.

Data Analysis
Part 1: Analyze and Explore the Climate Data
Utilizes Python, SQLAlchemy, Pandas, and Matplotlib for analysis.
Performs precipitation and station analysis.
Closes the session at the end of the analysis.
Flask API
Part 2: Design Your Climate App
Provides various routes to access climate data:
/api/v1.0/precipitation: Returns precipitation data for the last 12 months.
/api/v1.0/stations: Returns a list of stations.
/api/v1.0/tobs: Returns temperature observations for the last 12 months.
/api/v1.0/<start> and /api/v1.0/<start>/<end>: Returns temperature statistics for a specified date range.
Requirements
Jupyter Notebook Database Connection
Precipitation Analysis
Station Analysis
API SQLite Connection & Landing Page
API Static Routes
API Dynamic Route
Coding Conventions and Formatting
Deployment and Submission
Comments
