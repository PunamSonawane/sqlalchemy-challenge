# SQLAlchemy - Climate Analysis 

Used Python and SQLAlchemy to do basic climate analysis and data exploration of your climate database. All of the following analysis should be completed using SQLAlchemy ORM queries, Pandas, and Matplotlib.

* [Background](#background)
* [Obsevable trends](#trends)
* [Jupyter Notebook](#nb)
* [Technologies Used](#technologies)

##  <a name="background"></a>Background

For this project analysis, Used the provided starter notebook and hawaii.sqlite files to complete your climate analysis and data exploration.Used SQLAlchemy create_engine to connect to your sqlite database.Design a query to retrieve the last 12 months of precipitation data.
Ploted the results using the DataFrame plot method.Designed a Flask API based on the queries that just developed.
The csv file being analyzed is located [here](./EmployeeSQL/data).
The schema file is located [here](./EmployeeSQL/tables.sql).
The query file is located [here](./EmployeeSQL/queries.sql).


## <a name="trends"></a>Observable Trends 

* For Climate Analysis and Exploration:
 	* Used the provided starter notebook and hawaii.sqlite files to complete your climate analysis and data exploration.

	* Choose a start date and end date for your trip. Make sure that your vacation range is approximately 3-15 days total.

	* Used SQLAlchemy create_engine to connect to your sqlite database.

	* Used SQLAlchemy automap_base() to reflect your tables into classes and save a reference to those classes called Station and Measurement. 
* For Precipitation Analysis:
	* Design a query to retrieve the last 12 months of precipitation data.

	* Selected only the date and prcp values.

	* Loaded the query results into a Pandas DataFrame and set the index to the date column.

	* Sorted the DataFrame values by date.

	* Ploted the results using the DataFrame plot method.

	* Used Pandas to print the summary statistics for the precipitation data.
 * For Station Analysis:
	* Designed a query to calculate the total number of stations.

	* Designed a query to find the most active stations.

	* Designed a query to retrieve the last 12 months of temperature observation data (tobs).

	* Filter by the station with the highest number of observations.
	  * Plot the results as a histogram with bins=12.
	  * Station-histogram.
 * Designed a Flask API based on the queries that just developed.
	* Used FLASK to create routes.

 ##  <a name="nb"></a>Jupyter Notebook

For this project, I used jupyter notebook to render and display the results of this analysis. You can view the notebook here:

<https://github.com/PunamSonawane/sqlalchemy-challenge/blob/master/climate_starter.ipynb>
The notebook is also available inside this repository [here](./climate_starter.ipynb).
The Flask app.py is also available [here](./app.py)

##  <a name="technologies"></a>Technologies Used

* Python
* PostgreSQL 
* HTML/CSS
* Pandas library
* Matplotlib library
* Jupyter Notebook