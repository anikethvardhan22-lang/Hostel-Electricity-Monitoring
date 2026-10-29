# Hostel Electricity Monitoring System

## Project Overview
The Hostel Electricity Monitoring System is a Python-based project designed to analyze electricity consumption across different hostel areas and identify unusual usage patterns.

## Features
- Generate and analyze hourly electricity consumption data.
- Calculate average, minimum, and maximum electricity usage.
- Visualize electricity consumption using graphs.
- Detect unusual readings using statistical anomaly detection.
- Evaluate anomaly detection performance using precision, recall, and F1-score.
- Visualize the hostel meter network using NetworkX.
- Store electricity readings and anomaly results in a SQL database.
- Execute SQL queries, aggregations, and joins.
- Demonstrate client-server communication using socket programming.
- Support optional MySQL database integration.
- Export analyzed data and detected anomalies to CSV files.

## Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- NetworkX
- SQLite
- MySQL
- Socket Programming

## Installation
Install the required Python libraries using the following command in a Jupyter Notebook cell:

```python
%pip install pandas numpy matplotlib networkx mysql-connector-python
```

## How to Run
1. Download or clone this repository.
2. Open `Hostel_Electricity_Monitoring_Project.ipynb` in Jupyter Notebook.
3. Execute the notebook cells in order.
4. View the generated tables, graphs, and anomaly detection results.
5. Check the `data` folder for exported files and the SQL database.

## Database Integration
The project uses SQLite for storing electricity readings and anomaly detection results. SQL queries are used to summarize consumption and retrieve unusual readings.

Optional MySQL integration is also provided for connecting to a MySQL Server database.

## Network Visualization
NetworkX is used to represent the relationship between the main electricity meter and the different hostel areas.

## Socket Programming
Python socket programming demonstrates communication between a client and server by transmitting electricity reading data in JSON format.

## Output Files
- `hostel_readings.csv`
- `hostel_readings_with_flags.csv`
- `flagged_readings.csv`
- `hostel_electricity.db`

## Conclusion
The project combines data analytics, statistical anomaly detection, SQL database operations, network visualization, and socket programming to build a hostel electricity monitoring system.
