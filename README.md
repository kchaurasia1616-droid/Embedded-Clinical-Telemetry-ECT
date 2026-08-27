# Embedded-Clinical-Telemetry-ECT

##Overview:

An embedded health-monitoring system designed for real-time acquisition and monitoring of physiological parameters. The system uses an ESP32 to integrate the MAX30102 for heart rate and SpO₂ measurement, AD8232 for ECG acquisition, and MPU6050 for motion and fall detection. Sensor data is processed in real time and presented through a telemetry interface, demonstrating a low-cost approach to remote patient monitoring and wearable healthcare applications.

##Key Features:
* Real-time Heart Rate and SpO₂ monitoring
* ECG signal acquisition
* Motion and fall detection
* Multi-sensor data acquisition using I²C and analog interfacing
* Real-time telemetry and data visualization
  
##Hardware & Tools:
* ESP32
* MAX30102
* AD8232
* MPU6050
* Arduino IDE

##Future Development Scope:
Future development could include AI/ML-based analysis of physiological data to identify patterns and predict potential health deterioration at an early stage. The system can also be enhanced with cloud connectivity, long-term data logging, additional sensors, improved signal processing, and automated alerts, enabling more accurate and proactive remote health monitoring.
