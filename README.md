# GridTest
## Input: User location coordinates; Output: 5 closest events + cheapest ticket price for each event

### 1. Scenario

The program developed in C# using Visual Studio as IDE will do the following:
- Randomly generate seed data;
- Operate in a world that ranges from -10 to +10 (Y axis), and -10 to +10 (X axis);
- Assume that each co-ordinate can hold a maximum of one event;
- Each event has a unique numeric identifier (e.g. 1, 2, 3);
- Each event has zero or more tickets;
- Each ticket has a non-zero price, expressed in US Dollars;
- The distance between two points should be computed as the Manhattan distance.

### 2. Instructions
 
 The requirements for the program are as follow:
- Program will accept a user location as a pair of co-ordinates and returns a list of the five closest events, along with the cheapest ticket price for each event;

### 3. Example

Please Input Coordinates:
 
> 6,5
 
Closest Events to (6,5):
 
Event 003 - $27.65, Distance 3
Event 001 - $34.10, Distance 5
Event 006 - $09.60, Distance 12

