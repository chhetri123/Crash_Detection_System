# Vehicle Crash Detection and Alert System


## Abstract: 
This research endeavors to enhance driver safety by implementing a facial image classifier through a camera module for continuous attentiveness monitoring. In the event of an accident, the system activates a 10-second alert on the driver's mobile app, and in the absence of a response, an automatic alert is transmitted to the rescue center. This alert comprises accident details and interior vehicle images, facilitated by the integration of a GPS module . The approach utilizes computer vision techniques, leveraging a pre-trained facial image classifier for detecting signs of drowsiness or distraction. Swift accident detection employs algorithms incorporating impact sensitivity calculations or accelerometer data. Additionally, the system incorporates a SIM module for automatic alert transmission. Through the SIM module, an SMS is sent to the rescue center, which includes the current location and images. The combination of GPS -derived accident location data and interior vehicle images allows for a comprehensive analysis of accident severity, facilitating an efficient emergency response.

## System components
* Arduino UNO 
* MPU 6050
* SIM 800L 
* NEO 6M 
* LM2596 DC-DC Buck Converter Step-Down Power 
* Jumper Wire 
* Bread Board


## Software Components:
*  Driver’s Drowsiness detection algorithm
*  Mobile Application

## Circuit Diagram
  <figure>
  <img src="https://github.com/chhetri123/Minor-Project/assets/65161301/5bb3c547-da8f-4ad0-a683-b6d2c84bae03" style="width: 50%;" />
</figure>

## Mobile Application
 <figure>
  <img src="https://github.com/chhetri123/Minor-Project/assets/65161301/40d41f46-b2d2-43bf-b435-eee4aa46d52b" style="height: 300px;" />
</figure>


## System operation

The SIM600L GPS module will be used to determine the vehicle's location. The accelerometer will be used to detect sudden changes in acceleration. The microcontroller will be used to process data from the GPS module and accelerometer. The cellular modem will be used to send alerts to designated contacts.

The microcontroller will continuously monitor the accelerometer for sudden changes in acceleration. If the microcontroller detects a change in acceleration that is consistent with a crash, it will record the vehicle's location and time of the crash.Also the algorithm continuously reads the facial image of driver's, if drowiness detect then alert the drives to prevent from accident. The microcontroller will then send an alert to a designated contact. The alert will include the vehicle's location, time of the crash, and a link to a map showing the crash location and latest image of driver.

## Conclusion

The crash detection system has the potential to improve driver safety by providing a quick and easy way to notify emergency services in the event of a crash. The system can also be used to track vehicle movements and provide insights into driver behavior.

## Team members

* Manish Chhetri (PAS076BEI015)
* Nirajan Paudel (PAS076BEI017)
* Nabaraj Subedi (PAS076BEI018)
* Sudharshan Acharya  (PAS076BEI042)


## Some Images 

<figure>
  <img src="https://github.com/chhetri123/Minor-Project/assets/65161301/9e2f41a6-9d0c-4a2d-911f-14baab9acaae" style="width: 48%;" />
  &nbsp;&nbsp;&nbsp;&nbsp;
  <img src="https://github.com/chhetri123/Minor-Project/assets/65161301/d03cf517-0904-4acb-acda-1cc3ff223952" alt="Image 2" style="width:48%;"/>
</figure>
<hr>
&nbsp;&nbsp;&nbsp;&nbsp;
<figure style="margin: auto;">
  <img src="https://github.com/chhetri123/Minor-Project/assets/65161301/96ee21c5-884c-465a-8421-2ac71c168ffe" style="width: 50%;" />
</figure>

