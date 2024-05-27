The smart manhole monitoring and detection system utilizes Raspberry Pi as its central microprocessor, integrating various sensors for comprehensive hazard detection. Gas sensors identify toxic gases, while water level sensors prevent flooding risks. Door monitor sensors track manhole cover positions, and temperature sensors detect fluctuations, ensuring holistic hazard monitoring. 

In the event of a hazard, the system promptly alerts authorities via SMS facilitated by a GSM module, providing location data through GPS for swift intervention. A counter mechanism manages alerts effectively, activating a DC fan via relay to mitigate temperature spikes. Additionally, if toxic gases are detected, a solenoid valve releases neutralizing agents. 

Overall, this system offers a robust solution for urban safety, providing real time monitoring and proactive hazard management. It safeguards workers and enhances public safety by addressing potential risks associated with manholes promptly and efficiently.

![WhatsApp Image 2024-05-27 at 13 02 42_d2007629](https://github.com/Mounika-Sangana/Smart-Manhole-Monitoring-and-Detecting-System-/assets/104778898/6f3a4d1b-7024-4ed7-8aea-c42b21baa7ba)

Working

The smart manhole monitoring and detecting system utilizes Raspberry Pi as a central microprocessor to coordinate various sensors and actions. Here's how the system operates: 

1) Sensor Integration: The system incorporates multiple sensors including a gas sensor to detect toxic gases, a water level sensor to monitor water levels, a door monitor sensor to track the position of the manhole cover, and a temperature sensor to detect temperature variations within the manhole. 

2) Data Collection and Processing: Raspberry Pi collects data from these sensors in realtime, continuously monitoring the conditions inside the manhole. 

3) Threshold Monitoring: The system sets predefined thresholds for each sensor parameter. If any parameter exceeds its threshold (e.g., high gas levels, increased water levels, or elevated temperature), it triggers an alert.
   
4) Alert Generation: Upon detecting abnormal conditions, the system generates alerts. These alerts are sent to concerned authorities via SMS using a GSM module. The inclusion of GPS allows the system to provide precise location information along with the alerts. 

5) Counter Mechanism: A counter mechanism is employed to track instances of temperature increase. If the temperature rises beyond the predefined limit, an alert is triggered, prompting authorities to take necessary action. Additionally, a DC fan is activated using a relay to help regulate the temperature within the manhole. 

6) Toxic Gas Neutralization: In case toxic gases are detected, the system activates a solenoid valve containing neutralizing agents. These agents are released into the manhole to neutralize the toxic gases, minimizing their harmful effects.

Operation :
The operation of the smart manhole monitoring and detecting system involves several steps: 
1) Initialization: The system initializes upon power-up, with the Raspberry Pi booting up and initializing all connected sensors and modules. 

2) Sensor Monitoring: The system continuously monitors sensor data in realtime. The gas sensor detects toxic gases, the water level sensor detects water levels, the door monitor sensor tracks the position of the manhole cover, and the temperature sensor detects temperature variations within the manhole. 

3) Threshold Comparison: The system compares the sensor readings with predefined threshold values. If any sensor reading exceeds its threshold, indicating a potential hazard, the system proceeds to the next step. 

4) Alert Generation: 
      -> Gas Detection Alert: If toxic gases are detected, the system generates an alert                 indicating the presence of hazardous gases. This alert includes information about the           gas levels and the location of the manhole. 
      -> Water Level Alert: If the water level rises above the threshold, signaling a risk of            flooding, the system generates an alert specifying the increased water level and the            manhole location. 
      -> Door Status Alert: If the door monitor sensor detects an open manhole cover,                    indicating a potential safety hazard, the system generates an alert indicating the              open position of the manhole cover and its location. 
      -> Temperature Increase Alert: If the temperature sensor detects a significant increase            in temperature, indicating a potential fire or overheating hazard, the system                   generates an alert specifying the temperature rise and the manhole location
5) Alert Transmission: Upon generating an alert, the system sends a notification to concerned authorities via SMS using the GSM module. The message includes relevant details such as the type of alert, sensor readings, and the precise location of the manhole obtained from the GPS module. 

6) Counter Mechanism Activation: If the temperature exceeds the predefined limit and triggers an alert, the system activates a counter mechanism to track the number of occurrences. 

7) Temperature Regulation: In response to a temperature increase alert, the system activates a DC fan using a relay to help regulate the temperature within the manhole, mitigating the risk of overheating. 

8) Toxic Gas Neutralization: 
- If toxic gases are detected, the system activates a solenoid valve containing neutralizing agents. 
- The solenoid valve releases neutralizing agents into the manhole to neutralize the toxic gases, minimizing their harmful effects on the surrounding environment and public health.
9) Continuous Monitoring: The system continues to monitor sensor data and respond to any detected hazards or abnormal conditions, ensuring the safety and integrity of the manhole infrastructure. 

Example Result :
![WhatsApp Image 2024-05-27 at 13 20 47_10d7d608](https://github.com/Mounika-Sangana/Smart-Manhole-Monitoring-and-Detecting-System-/assets/104778898/b4d48121-39b5-49e1-ab41-afc595cec07f)

