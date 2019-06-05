# IoT-Based Water Quality Monitoring System(WQMS) for Aquaculture.



### The purpose of this project is to design and implement a portable and low-cost water monitoring system to consistently monitor the status of water to be quality and conducive for fish farming in aquaponic tanks at the aquaculture sector.

- Since the composition of pond water is continuously affected by environmental changes making it difficult for the farmers to consistently monitor the status of water therefore our WQMS was developed to monitor the variations.
- Water quality test can be done at source other than shipping water samples to laboratory reducing traditional laboratory testing.
Why our system is different from other systems:
    1. Measures the temperature, turbidity, pH and water level, of the pond to maintain and control the water quality.
    2. Quickly identifies specific parameter change in water
    3. Generates visual information(line chart)
    4. Sends notification alert

## System operation
- Measures water physical(temperature, depth, turbidity) and chemical(pH) characteristics of water
- Processes data on microcontroller using Espduino#2 
- Sends data to cloud sever 
- And publishes the data on webpage 

## Hardware Implementation
- Espduino-32
- Waterproofed temperature sensor DS18B20
- pH sensor- E-201-C
- Turbidity Sensor- SKU SEN0189
- Ultrasonic Sensor- HC-SR04

## Software Implementation
- Front-end
    - HTML/CSS/ 
    - Bootstrap
    - Jinja
    - Chartjs
- Backend
    - Python: logic
    - Flask: server
    - SMTP: messaging 
    - SQLite: DB
    - C program: sensor program on Esp32
    - HTTP
    - Heroku
    - VsCode



This project is intended to ...
    ...to continuously monitor the chemical properties( pH, temperature) of water for fish farming.
    ...to consistently monitor the physical properties(turbidity, water level) of water for aquaculture
    ...to remotely keep track of the status of water in real time and send email notification when wrong data is recorded.
    ...to generate a live visual chart of the properties of water pond for analysis and interpretation
    ...to collect data of the status of water for research by scientists 


  The normal parameter ranges for tilapia(fish) production
            Temperature  23-34
            Turbidity(Nephelometric Turbidity Units or Jackson Turbidity Unit) 0-5
            pH  4-10
            Water level 5-27 (based on site)



Technologies Used
    HTML/CSS
    Python
    Chart.js
    Sqlite DB
    SMTP
    Heroku
    Espduino 32
    Temperature sensor - DS18B20
    pH sensor - E-201-C
    Turbidity sensor - SEN0189
    Ultrasonic sensor
    9V battery


How it operates:
    The system is connected to the internet and transfers the data collected to a cloud server and send the data to the user(farmer,scientist) via web client in real time for analysis and to take certain measures to ensure that the water is conducive and for research purposes.


Usage:
    Set up hardwares/sensors to read data
    Connect micro-controller to the internet
    Run <python app.py>
    Visit url provided. Enjoy :)



Project Team Members
    John PK Erbynn  - john.erbynn@gmail.com
    Josiah Nii Kortey - josiahkotey13@gmail.com
    Isaac Duffour Agyen - izagyen96@gmail.com


Open Source Project Repo.
    Server codes: Github.com/erbynn/IoT-WQMS
    Sensor codes: 










```general info````

Turbidity is the cloudiness or haziness of a fluid caused by large numbers of individual particles that are generally invisible to the naked eye, similar to smoke in air. The measurement of turbidity is a key test of water quality.

 
 WQMS controls sensors placed in water
 ...collects anolgue data into digital format
 ...organise and store in sqlite database
 ...retrieved and processed for description
 ...to be rendered in a simple web interface on the front
 ...for interpretation


`````analysis`````
analysis of data is deriving, extracting useful, relevant and meaning full info from observations....that lead to better decisions in turn adding value to individuals, companies and institution
...descriptive analysis summarizes and describes data and makes it understand how things are going
why analyz....for parameter estimation(inferring unknown), prediction(forcasting), fault detection(process monitoring)

analyzing and interpreting data
for analyzing...organization, graphing and design to see the changes occure over time
for interpreting...evaluate, mathematics statistics for understanding significant of the data readings

independable variables: datetime
dependable variables: ph,temp,turbidity,water_level



