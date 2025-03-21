# Heatmap_event

## Problem:

Occlusion by other road agents like vehicles can negatively affect road safety. Consider the situation in the following figure: another car is blocking the car at the back from viewing a pedestrian. To cope with this problem, communication between vehicles (V2V) and communication between vehicles and infrastructure (V2I), like a Roadside Unit (RUD), can be utilized to provide information on the whole scene. Even with such technology, parts of the road will be invisible to both cars. Thus, we can define a confidence zone that covers the visible area for each vehicle. By combining the confidence zones for all intelligent cars, a heatmap can be generated in which each location will have a value ranging between 0 (for total invisible areas) to 1 (for areas visible by two vehicles at least).

![problem](image/problem.png)

## Scenario:

Consider a scenario of two intelligent vehicles, A and B, as shown in the following image. Vehicle A is blocking a pedestrian from vehicle B. Both cars use lidar to sense the surroundings.

![scenario](image/scenario.png)

## challenge

1. The programming challenge: generate the confidence zone for each vehicle and combine them into a heatmap.
2. The Design Challenge: Design a vehicle dashboard to increase road safety, incorporating the concept of a confidence zone and the visibility heatmap.

