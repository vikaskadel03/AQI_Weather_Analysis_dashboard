# AQI_Weather_Analysis_dashboard


This is a git repositry to store source code for my AQI and Weather Analytics Dashboard. The project uses mostly open source tools and docker for easy and scalable deployment 

Data Source :
  open mateo 
  open weather
  open AQ 
  weather stack 

Technical Stack :

  Batch Data:

    Python - For Data Ingestion from  Rest APIs
    Apache Spark - For Batch data Transformations
    Delta Lake - For storing large batch data files 
    Apache Airflow - For orchestrating batch data workflow

  Streaming Data:

    Apache Kafka - Used for streaming weather API data using Kraft
    Apache Spark Structured Streaming - For streaming data aggregations and transformations
    Postgre DB - DWH to store streaming data for further analysis 

  Data Visualizartion:

    Grafana - For data viz. and reporting 


High level architecture diagram:

<img width="1064" alt="Screenshot 2025-03-30 at 1 18 51 AM" src="https://github.com/user-attachments/assets/c1b3e6d0-5904-4f26-85b3-682a659c294d" />





