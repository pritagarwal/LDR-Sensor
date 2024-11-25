<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Project README</title>
</head>
<body>
  <h1 style="text-align: center;">📖 Project: Light Intensity Monitoring and Control System</h1>
  
  <h2>🚀 Project Overview</h2>
  <p>
    This project is a comprehensive system for monitoring and controlling light intensity using an LDR sensor. 
    It includes real-time data acquisition, threshold-based alarms, and relay control functionalities. 
    The system communicates with firmware using UART and provides an intuitive user interface for managing configurations, setting thresholds, and viewing reports.
  </p>

  <h2>🛠️ Tech Stack</h2>
  <ul>
    <li><b>Frontend:</b> Angular for building the user interface</li>
    <li><b>Backend:</b> C# with .NET Core for handling business logic and system communication</li>
    <li><b>Database:</b> MS SQL Server for storing acquired data and configurations</li>
    <li><b>Firmware Communication:</b> UART protocol for interfacing with hardware</li>
    <li><b>Graphing Library:</b> Dynamic real-time graphs for data visualization</li>
    <li><b>Logging:</b> Serilog for structured logging and diagnostics</li>
    <li><b>Testing:</b> MS Test for unit testing</li>
    <li><b>Version Control:</b> Git for source code management</li>
    <li><b>Documentation:</b> Doxygen for generating technical documentation</li>
  </ul>

  <h2>📑 Features</h2>
  <ul>
    <li>Real-time light intensity monitoring with periodic updates</li>
    <li>Threshold-based alarms and relay control</li>
    <li>4-20mA current control based on sensor readings</li>
    <li>Graphical representation of real-time data</li>
    <li>Manual mode for direct relay and threshold configuration</li>
    <li>EEPROM-based storage for configuration persistence</li>
    <li>User-friendly interface with intuitive navigation</li>
  </ul>

  <h2>📂 Project Structure</h2>
  <ul>
    <li><b>/frontend</b> - Contains the Angular-based UI code</li>
    <li><b>/backend</b> - C# .NET Core service code</li>
    <li><b>/database</b> - SQL scripts for database schema</li>
    <li><b>/docs</b> - Documentation generated by Doxygen</li>
    <li><b>/tests</b> - Unit testing scripts</li>
  </ul>

  <h2>💻 Getting Started</h2>
  <ol>
    <li>Clone the repository: <code>git clone https://github.com/your-repo-name</code></li>
    <li>Install dependencies for frontend and backend.</li>
    <li>Set up the database using the provided SQL scripts.</li>
    <li>Run the backend service and the frontend UI.</li>
    <li>Connect the hardware via UART and start monitoring.</li>
  </ol>
</body>
</html>
