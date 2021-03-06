---
published: true
layout: post
date: '2020-10-14 15:00:00 +0530'
issue: 27
title: How do the self driving cars work ?
description: >-
  Look ma, no hands! are not going to be someone's last words if the cars
  started driving themselves. But how does that work?
img: tesla_autopilot.jpg
fig-caption: Tesla
tags:
  - Computer Vision
  - Sensors
  - Cars
  - Self driving
  - Autonomous
---
We all know humans are susceptible to the Covid-19 virus and that includes Trump, even if [he believes otherwise](https://twitter.com/realDonaldTrump/status/1315316071243476997)🤦.  But do you know who can go out and bring Burger from McD and not catch Corona Virus? Your Car!  

Tech Giants like Waymo(Alphabet), Uber, Tesla, and more have been investing heavily for years to enable the machines with wheels to run free of human control and not be a victim of human brutality - read "Road accidents".    

Being able to let AI decide our pathway and transport is a thing of the future. But today, we look into how are they aiming to achieve it.  

# Ranking - Self-driving cars
Autonomous driving is not a single definition of self-controlling cars. There are levels about how much can a vehicle be self-sufficient. Ranging from Nothing self-controlled to everything. I'll pick them up individually real quick.  

## Level 0
0 Self drivability. But technically no. You can still make a car drive by itself, just put it in a gear and slam a brick on the acceleration pedal. ;)  

## Level 1
Some automation: Self Cruise control and auto braking. No handling, no gearing.

## Level 2
At this level, the car can do some steering by itself but still requires human hands at all times for safe operation. Like a little 2 years old child.

## Level 3
Little more grown-up child. Can steer and control but still requires parental support when it gets confusing.  
*Look ma, no hands!*

## Level 4
Teenager zone. Thinks it's fully autonomous, but actually not in all conditions. It has not yet seen the world. But can do it perfectly fine in your hometown.

## Level 5
Fully mature, can self drive in **every situation**. You can sleep, watch a movie or do something else you've always wanted to do in a car 😏. The car won't have a problem and will drive perfectly fine.
Doesn't mean it can't have accident, it just won't be the reason for the accident <sub><sup>ideally</sup></sub>.

# How does it work - Self-driving cars
In a nutshell, they work by understanding the environment and try to get to a destination without touching anything in between.  

In a little more (yet still an overview) detail, it's a five-part process.

![Self Driving Cars parts]({{site.baseurl}}/assets/img/self_driving_steps.png)
*Image From Youtube - [TEDxWilmingtonSalon](https://www.youtube.com/watch?v=Ly92UcnoEMY)*

Let's quickly look at them one by one:  

## 1. Computer Vision and Sensor Fusion
These two perform common functionality - They get a sense of the environment around the car.  
**Computer Vision** here refers to using a camera to see the surroundings (or say eyes of the car) and **sensor fusion** refers to using sensors to understand the surroundings (lasers, radar, and stuff).  
These two work together to **learn the surroundings**. This also means this step can be performed offline if the car's system is capable enough. (Generally not, they let the data centers and remote servers do all that part. So they can offload the calculations to bespoke systems <sub><sup>(and track you everywhere)</sup></sub>)

## 2. Localization
Correctly guessed! It's the GPS based localization to know the car's position on the globe. But that's not all because that tiny job even a smartphone can do.   
This localization has to be synced with the surroundings data from step #1 to accurately define the car's position. Few feet off and you BatMobil would be running on the footpath.  

## 3. Path Planning
*Stairway to heaven*  
**Path planning** here refers to the literal path that the car would be running on.  
The current lane, and then when to switch lane because there's a crack in the road ahead. All that has to be planned by the system.  

## 4. Control
All the steps above relate to knowing and designing the path to the destination or say to the next exit.  
But what comes after knowledge? <sub><sup>(🗣️ day!.)</sup></sub>  
No. The **DO** comes after it.  
The car actually has to *do* something to go that path it just planned. That requires controlling the acceleration, steering, gearinga and sometimes even braking.

That's it! That's all it takes to get these guys to drive themselves. <sub><sup>(I maybe hiding some details)</sup></sub>