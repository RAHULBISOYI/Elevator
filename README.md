ELEVATOR CHALLANGE:

DESCRIPTION:

The Elevator Challenge is a Java application that simulates an elevator system. It allows users to either manually control the elevator by specifying start and destination floors or automatically run a simulation with random floor requests. The elevator system handles boarding and un-boarding, moves between floors, and adjusts its direction based on requests.


FEATURES:

> Manual Mode: Input starting and destination floors to control the elevator.
> 
> Automatic Mode: Simulate random elevator requests to test the system's response.
> 
> Floor Request Management: Handles multiple requests and updates the elevator's destination accordingly.
> 
> Basic Error Handling: Validates floor input and ensures the elevator doesn’t malfunction.
> 

INSTALLATION:
>clone the reprository:https://github.com/assistantgimini/Elevator.git

 USAGE:
 > Manual Mode: Run the manualElevator() method. You will be prompted to enter a starting and destination floor.

> Example:
To test the manual mode:

> public static void main(String[] args) throws InterruptedException {
    manualElevator();
}


CODE OVERVIEW:

MAIN CLASSES:
> ElevatorChallenge: Contains the main method and methods to run the manual and automatic elevator modes.
> 
> Elevator: Manages the elevator's current state, handles requests, and moves between floors.
> 
> Direction: Enum to represent the elevator's direction (UP, DOWN, IDLE).
>
> 
KEY METHOD:

> manualElevator(): Prompts the user for floor input and starts the elevator.
> 
> automaticElevator(): Simulates elevator activity with random requests.
> 
> callElevator(int start, int destination): Adds a request to the elevator's queue.
> 
> start(): Begins the elevator operation and processes each floor.
> 
> moveUp(), moveDown(): Moves the elevator up or down by one floor.
>
> 

CONTRIBUTING:

> Fork the repository.
> 
> Create a feature branch (git checkout -b feature/YourFeature).
> 
> Commit your changes (git commit -am 'Add new feature').
> 
> Push to the branch (git push origin feature/YourFeature).
> 
> Create a new Pull Request.
> 
