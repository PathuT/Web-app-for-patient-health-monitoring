# Web-app-for-patient-health-monitoring

With tons of new healthcare technology start-ups, IoT is rapidly revolutionizing the healthcare industry. 
In this project, we are trying to do an IoT Based Patient Health Monitoring System using ESP8266 & Thigsspeak

**Intoduction**

The IoT platform used in this project is ThingSpeak. ThingSpeak is an open-source Internet of Things (IoT) application and API to store and retrieve data from things using the HTTP protocol over the Internet or via a Local Area Network. 
We monitor the Room temperature in addition with the heart beat and Blood Pressure of the patient in the Mobile Application it self

**Working Principle**


This is a simple block diagram that explains the IoT Based Patient Health Monitoring System using ESP8266 & Arduino. Pulse Sensor and LM35 Temperature Sensors measure BPM & Environmental Temperature respectively.
The Arduino processes the code and displays it to 16*2 LCD Display. ESP8266 Wi-Fi module connects to Wi-Fi and sends the data to IoT device server. The IoT server used here is Thingspeak. Finally, the data can be monitored from any part of the world by logging into the Thingspeak channel.
