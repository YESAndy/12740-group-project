# Automatic indoor light adjustment
- Weijia Cai, Yuming Chang

Video link: [link](https://github.com/YESAndy/12740-group-project/edit/gh-pages/index.md)

## Introduction
### Motivation
Life is not easy for CMU student. Reports said that the average sleeping time of CMU student in at 1:36am. So, working in the night with comfortable light is very essential for every one of us. Also, an energy-saving light system will benefit a lot because it saves money. Based on these reasons, we want to design an automatic indoor light adjustment system to make our lives a little bit easier

### Goals
We want to measure the comfortable level range of light based on personal preference, environmental lightness, existence of human indoor to control the number of LEDs opening automatically. 

## Progress report

### Progress step by step
Currently, we have basically two main tasks to solve:
1. To distinguish different scenarios: natural light, mixed(natrual and artificial lights), artificial light
2. To measure the comfortable light zone for the group members.
We have read several websites about how to implement and how to write the code to detect the lightness using photoresistor sensors and control the LEDs.

In order to accomplish these goals, we designed the experiments in the following.


- Step one: set up the hardware system. The following is the light measurement system:
![Image](https://github.com/YESAndy/12740-group-project/blob/gh-pages/lightmeasuresystem.jpg?raw=true)
- Step two: determine the light intensity ranges of natural light and artificial light separately
- Step three: determine the comfortable light ranges when doing step two

### coding progress
The following is part of the light measurement code:

![Image](https://github.com/YESAndy/12740-group-project/blob/gh-pages/lightmeasurecode.png?raw=true)


### Problems Encountered
1.When we are going to implement the whole system using the code we wrote, we found there are some bugs in our code. And now we can't find where the bugs are.
![Image](https://github.com/YESAndy/12740-group-project/blob/main/lightmeasurebug.png?raw=true)

2.Since we intended to do a lot of work off campus and remotely, we tried to connect the raspberry pi to share internet with our pcs and at-home wifi (no one has a monitor, keyboard, or required HDMI cable off-campus). Also the Cooperation between teammates is limited due to the remote study.

### Future Plan
Describe what you plan to do in the next two weeks
1. we are going to schedule serval meeting to talk more about the progress each one achived and how to do things better.
2. We are going to continue to debug our code to make the code and system can run successfully.
3. We are going to design a room, where we can test our detect system and code in serval situations.

## Methodology
### Phenomena of Interest
We want to measure the light intensity and corresponding temperature at the same time to see the pattern of light intensity and temperature.
__Visible Light__


__Temperature__


### Sensor(s) Used
Describe the sensor(s) you used, e.g. physical principles, static and dynamic behavior, and signal characteristics

**MCP3008**

This is an Analog to Digital Converter

![image](https://www.microchip.com/_images/ics/medium-MCP3008-PDIP-16.png=40x)

**Photosensitive Light Sensor Module**
![image](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.faranux.com%2Fproduct%2Fphotosensitive-sensor-module-detection-photoresistor-ldr-light-sensor-module-com43%2F&psig=AOvVaw0uuK_j6SdIQmW5fv4subOy&ust=1602693169464000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCLjo47r_sewCFQAAAAAdAAAAABAG)

**DS18B20 Temperature Sensor Module**
![image](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.fasttech.com%2Fproduct%2F1000900-arduino-compatible-ds18b20-digital-temperature&psig=AOvVaw0bSu2cxUilkWhCFv1f2poV&ust=1602693221893000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCNCI39P_sewCFQAAAAAdAAAAABAM)

**LED light bulb**


### Signal Conditioning and Processing
Describe the signal conditioning and processing procedures

## Experiments and Results
Describe the experiments you did and present the results; Use tables and plots if possible

## Discussion
Discuss the insights from the project
