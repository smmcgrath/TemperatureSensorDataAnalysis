# TemperatureSensorDataAnalysis
Using Node.js, Plotly and an Arduino to get real-time data from a temperature sensor and generate visualisation. 

With a TMP36 Temperature Sensor and an Arduino board set up as shown it is possible to achieve this.

The StandardFirmata firmware is verified and uploaded to the board.

From the terminal:

  $ mkdir your-project-name
  
  $ cd your-project-name
  
From the node package manager the following modules are required:

  $ npm install plotly
  
  $ npm install johnny-five
  
Using the following command to set up the connection and start real-time measurements:

  $ node tmp36.js
  
Or node followed by the name of your script file.
