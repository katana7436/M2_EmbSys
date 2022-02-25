# INTRODUCTION
The  project  is  aimed  at  designing  a  density based dynamic traffic signal system where the  timing of signal  will  change  automatically  on  sensing  the  traffic density  atany  junction.  Traffic  congestion  is  a  severe problem in most cities across the world and thereforeit is time to shift more manual mode or fixed timer mode to an automated  system  with  decision  making capabilities. Present  day traffic  signaling system  is fixed  time based which  may  renderinefficient  if one  lane  is operational than the others. To optimize this problem we have madea framework  for  an  intelligent  traffic  control  system.

## FEATURES OF TRAFFIC SIGNAL SYSTEM
* In this system, we will use IR sensors to measure the traffic density.
* We have to arrange one IR sensor for each road; these sensors always sense
* the traffic on that particular road. All these sensors are interfaced to the microcontroller.
* Based on these sensors, controller detects the traffic and controls the traffic system.

## SOFTWARE COMPONENTS:

* Atmega328p 
* SimulIDE
* Virtual studio code
* avr-gcc
* Make

## SWOT ANALYSIS
### STRENGTH:

* This project helps in reducing the time delay.
### WEAKNESS:

* IR sensors sometimes may absorb normal light also. As a result, traffic system works in improper way.
* IR sensors work only for fewer distances.
* We have to arrange IR sensors in accurate manner otherwise they may not detect the traffic density.

### OPPORTUNITIES:

* Avoids wastage of time due to the traffic
* Fully automatic
* Low power consumption
* It provides the easy access in the traffic light
* Low cost to design the circuit, maintenance of the circuit is good
* Easy convenience to handle.

### THREADS:

* IR sensors sometimes may absorb normal light also. As a result, traffic system works in improper way.


## 4W's AND 1H
### WHAT:

      This Project explains you how to control the traffic based on density.
### WHERE:

      In High traffic density areas to control traffic automatically and efficiently.
### WHEN:

     During dense traffic areas.
     High populated areas.
### WHY:

    If there will be no traffic on the other signal, one shouldn’t wait for that signal. 
    The system will skip that signal and will move on the next one.
### HOW:

    It controls traffic signals automatically using sensors and microcontroller.


## HIGH LEVEL REQUIREMENTS


|ID|	DESCRIPTION|
|:------:|:-------:|
|HLR_1|	Fully Automated	|
|HLR_2|	Sensors And Atmega328|
|HLR_3|	Alarm Interfaced with atmega328|

## LOW LEVEL REQUIREMENTS

|ID |	DESCRIPTION	|
|:------:|:-------:|
|LLR_1|	LEDs Interfaced with atmega|
|LLR_2|	Resistors|
|LLR_3|	Cameras|

# BLOCK DIAGRAM
![BLOCK DIAGRAM](https://user-images.githubusercontent.com/94118694/143685072-c55e7d77-4f03-4208-bfa2-55423d5cf443.jpeg)

# BEHAVIOURAL DIAGRAM
![BLOCK DIAGRAM](https://user-images.githubusercontent.com/94118694/143685121-d200e68a-30c3-4f9f-8fac-34a8a54bb497.jpeg)
![BLOCK DIAGRAM](https://user-images.githubusercontent.com/94118694/143846175-2d7f3bcf-6bdd-4fbe-b5a9-e7d4ac018b11.jpeg)

# STRUCTURAL DIAGRAM
![BLOCK DIAGRAM](https://user-images.githubusercontent.com/94118694/143685126-90f3439a-a8f1-44bd-8930-aba82f8a0e36.jpeg)
![BLOCK DIAGRAM](https://user-images.githubusercontent.com/94118694/143846676-b0c88be6-aba4-42de-a2c3-ab84c827f065.jpeg)