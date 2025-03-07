﻿# TRAFFIC-SYSTEM-USING-AI
# Traffic-Control-using-AI
We have created a Project on Traffic System using AI. Our lives have been made easier by the swift advancement of scientific advances across all domains, yet the road traffic accidents have increased over time and claimed countless lives. The average commute time in India's main cites has increased dramatically during rush hour. The typical traffic signal runs on a constant stream of instructions that are kept in memory. For over ten years, traffic control has been a challenge, and it will likely remain so for some time to come. In this system vehicle density at an intersection is measured and a signal switching algorithm is used to measure the proper time for the duration of the green and red lights, as well as the length of the vehicles waiting in each route at the intersection and also the next intersection to ensure a smooth flow of traffic.
![image](https://github.com/user-attachments/assets/7ef3f0fc-8d58-43ba-8f24-8751bb757b02) Our Proposed System is A . Calculating Vehicle Density
The function set_Time() adjusts signal timings based on vehicle quantity and type at the subsequent signal.
It initializes variables to count different vehicle types (cars, buses, trucks, rickshaws, bikes).
Counts for each vehicle type are incremented as vehicles are cycled through.
Total time for green signal is computed considering counts of vehicle categories.
Average time for each vehicle type to pass intersection is factored into the computation.
Debugging feature prints the computed green time for each signal change cycle.
![image](https://github.com/user-attachments/assets/ceb6c5fd-52fa-4fdc-a822-9f15abd07af6)
B.Signal Switching Algorithm

Intersection features multiple signals cycling through green, yellow, and red phases.
Green allows movement in its direction; others remain red for safety.
Yellow signals upcoming changes, preparing for the next green phase.
Signal timing regulated by predefined parameters like default_Red, default_Yellow.
Algorithm considers processing time, lane count, vehicle volume, and traffic density.
Preset sequence maintains order, minimizing confusion for drivers.
![image](https://github.com/user-attachments/assets/89e9f36f-f3cb-40fd-b5d6-9b11a0131526)

C. Simulation
Pygame used to create real-world traffic simulation for enhanced visualization.
Four-way stop simulation includes timers at each signal for signal changes.
Variety of vehicles such as cars, motorbikes, buses, trucks, and rickshaws included.
Some far-right lane vehicles turn at intersection to mimic real-life scenarios.
Random numbers used in vehicle construction for increased variability.
Timers on vehicles display elapsed simulation time for monitoring.
![image](https://github.com/user-attachments/assets/aaf6f9b5-6163-4cd3-8609-e0fa54224bca) The advantages of our proposed system is Autonomous: There are no need of the Manpower
Dynamic System, Manages Traffic light switching according to current traffic density.
Less expensive than other solutions.
There are no need to new hardware to be installed.
![image](https://github.com/user-attachments/assets/aeb018f9-ebd5-429e-9ad0-672711d7dc82)
Our implemented system could pass 3193 vehicles in an hour compared to 2356 vehicles in the static system, which is an increase of 837 vehicles.
This translates to an increase in performance by 35% of the AI enabled traffic light system. 
On an average 70 more vehicles can pass in every simulation
![image](https://github.com/user-attachments/assets/8a01ef05-2105-4082-b1b5-edf5289b54d5) Finally our conclusion is 
Our proposed Traffic management system with AI improves the performance by over 35% comparing to Current System.
Using the AI model adds an additional functionality to reduce the waiting time of vehicles at their next crossing.
Both of these can be implemented using edge computing at the traffic signal itself.
It can be implemented with effectively with very little cost.
![image](https://github.com/user-attachments/assets/89115b68-3727-42d1-a1fe-e0b35bb98b7d)





