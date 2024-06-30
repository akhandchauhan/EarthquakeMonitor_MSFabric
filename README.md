# EarthquakeMonitor_MSFabric
This project demonstrates the implementation of an automated data pipeline for retrieving, processing, and visualizing earthquake data using Microsoft fabric tools.

## Key Features
Automated Data Pipeline: A data pipeline built in Microsoft Fabric's Data Factory that schedules daily data retrieval at 6 AM.
Data Processing: Utilization of Microsoft Fabric to process and transform earthquake data from the USGS API.
Real-time Monitoring: Implementation of a data activator to set alerts for earthquakes exceeding a magnitude of 5.
Data Visualization: Creation of a Power BI report to visualize worldwide earthquake events on a map.

## Technologies Used
Microsoft Fabric's Data Pipeline
Fabric Lakehouse
Notebook
USGS API
Data Activator
Power BI
![image](https://github.com/akhandchauhan/earthquake_fabric/assets/112802105/5a687cfe-f823-4235-bd45-4e580a1c730a)

## Project Details

1. Data Processing
Using Microsoft Fabric, the raw data retrieved from the USGS API is processed and cleaned for further analysis. This step includes transforming the data into a suitable format, handling missing values, and ensuring data quality.
![image](https://github.com/akhandchauhan/earthquake_fabric/assets/112802105/def8be6d-71cf-45d5-b185-f7399819f2e6)
2. Automated Data Pipeline
The data pipeline is scheduled to run daily at 6 AM, ensuring timely and consistent retrieval of earthquake data. This process is automated using Microsoft Fabric's Data Factory, demonstrating the capability to handle regular data ingestion tasks without manual intervention.
![image](https://github.com/akhandchauhan/earthquake_fabric/assets/112802105/1197b9d2-25c7-4a84-b355-464f92010f7f)

3. Real-time Monitoring
A data activator is implemented to monitor incoming data for earthquakes exceeding a magnitude of 5. When such an event is detected, an alert is triggered, showcasing the ability to use data to drive real-time actions.
![image](https://github.com/akhandchauhan/earthquake_fabric/assets/112802105/d0f8b0e4-0d3f-41cd-9021-a6d7e13f136c)

4. Data Visualization
A comprehensive Power BI report is created to visualize the processed earthquake data. The report includes an interactive map that displays earthquake events worldwide, allowing for easy analysis and insights into seismic activities.
![image](https://github.com/akhandchauhan/earthquake_fabric/assets/112802105/b76ff8ea-3d0a-4fc0-8761-6fe09cef01ad)

## How to Run
Setup Data Pipeline: Configure Microsoft Fabric's Data Factory with the provided pipeline configuration to schedule daily data retrieval.
Process Data: Use the provided scripts to process and clean the data retrieved from the USGS API.
Monitor Real-time Data: Set up the data activator to monitor earthquake events and trigger alerts for significant seismic activities.
Visualize Data: Import the processed data into Power BI and use the provided templates to create the interactive report.

## Use Cases
1. High-Magnitude Earthquake Alerts
Alerts are set for earthquakes exceeding a magnitude of 6 or 7. When such an earthquake is detected, an email notification is sent to relevant stakeholders, allowing for timely responses and preparations.

2. Tsunami Warning System
If an earthquake occurs near coastal areas or beaches, it could potentially trigger a tsunami. The system monitors the location of earthquakes and can send alerts to warn about possible tsunami threats, enabling prompt evacuation and safety measures.

3. Seismic Activity Pattern Detection
The system is capable of detecting patterns in seismic activity. For instance, a small earthquake may be a precursor to a series of larger earthquakes. By monitoring and analyzing these patterns, the system can provide early warnings and help in disaster preparedness.

4. Continuous Monitoring and Historical Analysis
The pipeline continuously monitors earthquake activity and maintains a historical database of seismic events. This allows for ongoing analysis and understanding of earthquake patterns over time, contributing to better risk assessment and mitigation strategies.

# Conclusion
This project showcases the integration of automated data pipelines, real-time monitoring, and effective data visualization. It demonstrates how to leverage Microsoft Fabric, USGS API, and Power BI to manage and analyze earthquake data efficiently.

