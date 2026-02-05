# Constraint-Based Scheduling Tool
Python | OR-Tools

## Problem
Many jobs around the world rely on people to manually schedule their employees; mine is the same. Two of the interns at my job as a tour guide are responsible for scheduling 100+ staff members based on their availability. This process generally takes a day a week to create the schedule manually. The scheduling software being used does a similar thing, but some people would get zero hours, and others would get too many.

## Solution
I am currently in the process of creating a program in Python using OR-Tools to create an optimal schedule in minutes. OR-Tools is an open-source, high-end linear programming tool built to solve large optimization problems

Design goals:
- Retrieve the availability from the scheduling software
- Script that assigned parameters to everyone, like major, school year, etc...
- Solve the problem to find the optimal schedule.
- Send it back to the scheduling software to assign shifts.

## Parameter list
- Availability
- College
- Major
- School year
- Returner / new-hire
- Senior staff / not senior staff

## Demo of current status
This is an image of a schedule that adheres to availability, tries to make the number of shifts equal, and does not allow someone to work the last shift ofone day and the first shift of the next day.

[Staff Availibility Table](docs/assets/images/StaffAvailibilityTable.png)
[Staff Schedule](

