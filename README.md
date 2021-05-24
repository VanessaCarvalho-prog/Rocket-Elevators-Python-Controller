
# Rocket-Elevators-Python-Controllers

This project aims to simulate the operation of elevators in a residential building using object orientation.
To test the function of the project, it is necessary to make some simulations.
For example:
Scenario 2:
In a building with 10 floors and two elevators.
If one elevator is on the 10th floor and the other is on the 3th floor.
A user is on the 1rd floor and needs to climb to the 6th floor.


## Scenario02
```
column = Column(1,10,2)
column.elevatorsList[0].currentFloor = 10
column.elevatorsList[1].currentFloor = 3
column.requestElevator(1, 'up')
column.elevatorsList[1].requestFloor(6)
```
## Result:
```
Elevator 2 is at floor 2
Elevator 2 is at floor 1
Door 2 opened.
Door 2 closed.
Elevator 2 is at floor 2
Elevator 2 is at floor 3
Elevator 2 is at floor 4
Elevator 2 is at floor 5
Elevator 2 is at floor 6
Door 2 opened.
```