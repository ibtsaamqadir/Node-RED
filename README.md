# Node-RED
Dashboarding and Flows for IoT Systems

Node RED version 3.0.2
Node.js version 16.17.0

**Install node RED and type node -red in command prompt to initialize. 
Copy the local address and paste it in your browser to access the UI.**

## Repo consists of:
- Basic Flow Designs to understand the working and basics of node red.
  - HelloWorld_flow:
    Inject node is the input node and the debug node is the output node.
    Functions nodes are the processing nodes. In this example, there is no function node.
    We have a direct input and output.
  - WeatherAlert-flow:
    Using and API and then displaying the message if the weather is clear.
    API: openweathermap.org
  - BasicCal_flow:
    Coding the functions and making a hardcoded calculator that will perform operations on 5&6.
  - EarthquakeAPI_flow: Printing data from earthquake.usgs website. Data: Magnitude and Place of Origin.
  - IfElse_flow: A basuc switching flow
  - CSVParser_flow: Parsing a random CSV data saved in template. 
    

- UI Design Examples to visualize the flow of data betwene the nodes.
  - DummyTemp_flow_ui: Created a random variable and plotted its linearly interpolated chart and guage display. The values are updates every 2 seconds. The UI nodes are downloaded by going to the Menu > Manage Pallete > Install > Node-Red-Dashboards. 
  
- Interfacing Arduino with Node-Red
  - Ultrasonic Sensor to find out 
