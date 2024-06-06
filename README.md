# Intelligent-Alcohol-Detector-For-Road-Safety

This project tackles the critical issue of drunk driving by presenting an innovative Alcohol Detector with Engine Locking System. This system leverages the power of the Internet of Things (IoT) to promote responsible driving and potentially save lives.

**Key Features:**

* **Alcohol Detection:** The system employs an MQ-3 Alcohol Sensor to detect the presence of alcohol in the driver's breath.
* **Arduino-Powered Processing:** An Arduino Uno microcontroller acts as the heart of the system, processing sensor data and making critical decisions.
* **Legal Limit Comparison:** The Arduino compares the detected alcohol level against a pre-programmed legal limit.
* **Engine Locking Mechanism:** If the alcohol level exceeds the threshold, the system activates a relay module, effectively disabling the vehicle's engine to prevent drunk driving.
* **Location Tracking:** For enhanced safety and potential recovery, a GPS module is integrated to record the vehicle's latitude and longitude.
* **Alert Notifications:** A GSM module is used to send SMS alerts to designated contacts when the alcohol level exceeds the limit or the engine is locked.


**Benefits:**

* **Promotes Safe Driving:** The system discourages drunk driving, potentially preventing accidents and saving lives.
* **Easy to Implement:** The use of readily available components makes the system accessible for hobbyists and potentially educational purposes (with appropriate safety precautions).
* **Customization Potential:** The project offers a platform for further development, such as incorporating breathalyzer-like calibration, voice alerts, or integration with advanced driver-assistance systems (ADAS).


**Components:**

* **Arduino Uno:** Microcontroller for processing sensor data and controlling the system.
* **MQ-3 Alcohol Sensor:** Detects the presence of alcohol in the driver's breath.
* **Relay Module:** Enables or disables the engine based on the Arduino's instructions.
* **GPS Module:** Tracks vehicle location for enhanced safety and potential recovery efforts.
* **GSM Module:** Sends SMS alerts when the alcohol level exceeds the limit or the engine is locked.
