# electRuBus
Smart Plug - IoT device using Raspberry Pi 

**Electricity** + **Rubus** (the genus of flowering plants including *raspberry*) = **electRuBus**

Project from paper *"How many polar bears can you save with a Raspberry Pi?"*

by Nefeli Zikou and Melina Zikou, 4th High School of Alexandroupolis

Presented in [**A**natolia **C**ollege **S**cience and **T**echnology **A**nual **C**onference](http://www.acstac.gr/), Thessaloniki, November 2017
 
___
## Description
A smart Internet-of-Things (IoT) device that monitors and optimizes electrical power for room appliances and lighting, based on user presence or preferences. 
The Smart Plug records the state and operating time of an electric outlet and the presence of a human based on infrared light sensor that can capture photos when triggered. 
   
  
   
The device supports multiple modes of operation:

  * The "WatchMe" mode records electric outlet operation time along with human 
    presence in the room and generates maps of electric consumption.
 
  * The “SaveTheBear” mode, the device optimizes electric consumption by turning off selected appliances 
    when no human is present. 

  * The "AlwaysAround" mode allows the user to remotely control 
     the electric outlet via the internet. 

  * The “ProtectMyTerritory” mode uses the human presence detector and the camera to 
    notify the lawful occupant of any intruder. 

## Implementation 
It was created using a **Raspberry Pi** (an affordable, credit-card size computer), commonplace electronic components, and a novel web application.

**Python v.3** : Main program (reading input from infrared sensor, user input from button, input from web camera, controling output to the relay, storing user activity to the database and coordinating interaction with web application and user actions therein)

**SQLite3** : Local Database (Stores input and processed data)

**HTML v.5**  and **Flask v. 0.12** : Web Application (allows user interaction)

**Chart.js** : Grpahs of data (JavaScript library)

## Usage
The reduction in energy consumption achieved by using the device and its impact on cost and climate preservation is not significant on an individual level, but when scaled up in time and amongst society, it can certainly make a difference. 
 
