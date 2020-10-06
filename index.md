# Automatic indoor light adjustment
- Weijia Cai, Yuming Chang

Video link: [link](https://github.com/YESAndy/12740-group-project/edit/gh-pages/index.md)

## Introduction
### Motivation
Life is not easy for CMU student. Reports said that the average sleeping time of CMU student in at 1:36am. So, working in the night with comfortable light is very essential for every one of us. Also, an energy-saving light system will benefit a lot because it saves money. Based on these reasons, we want to design an automatic indoor light adjustment system to make our lives a little bit easier

### Goals
We want to measure the comfortable level range of light based on personal preference, environmental lightness, existence of human indoor to control the number of LEDs opening automatically. 

## Progress report

### Current Progress
Currently, we have basically two main tasks to solve:
- To distinguish different scenarios: natural light, mixed(natrual and artificial lights), artificial light
- To measure the comfortable light zone for the group members.
We have read several websites about how to implement and how to write the code to detect the lightness using photoresistor sensors and control the LEDs.
In order to accomplish these goals, we designed the experiments in the following.


- Step one: set up the hardware system. The following is the light measurement system:
![Image](https://github.com/YESAndy/12740-group-project/blob/gh-pages/lightmeasuresystem.jpg)
- Step two: determine the light intensity ranges of natural light and artificial light separately
- Step three: determine the comfortable light ranges when doing step two


### Problems Encountered
1.When we are going to implement the whole system using the code we wrote, we found there are some bugs in our code. And now we can't find where the bugs are.

2.Since we intended to do a lot of work off campus and remotely, we tried to connect the raspberry pi to share internet with our pcs and at-home wifi (no one has a monitor, keyboard, or required HDMI cable off-campus). Also the Cooperation between teammates is limited due to the remote study.

### Future Plan
Describe what you plan to do in the next two weeks
1. we are going to schedule serval meeting to talk more about the progress each one achived and how to do things better.
2. We are going to continue to debug our code to make the code and system can run successfully.
3. We are going to design a room, where we can test our detect system and code in serval situations.

