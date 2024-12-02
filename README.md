# Traffic Simulation Project

This repository contains a traffic simulation system that models vehicular behavior and traffic signals on a road network. The project uses Python for simulation logic, along with visual assets to represent roads, vehicles, and traffic lights.

---

## Features
- **Road Network Simulation:** Models a multi-lane road with moving vehicles.
- **Traffic Light System:** Dynamically updates traffic signals (Green, Yellow, Red) based on predefined rules.
- **Vehicle Behavior:** Simulates vehicles entering and exiting the road, changing speeds, and reacting to signals.
- **Counter Tracking:** Tracks and logs vehicle counts across intersections.

---

## File Structure
### Python Code
- `simulation.py`: Core simulation logic for managing vehicles, traffic signals, and interactions.
- `vehicle.py`: Defines the `Vehicle` class and its behavior.

### Visual Assets
- **Road and Intersection Models:**
![Road Simulation](images/mod_int.png)

- **Vehicle Images:**
![Road Simulation](images/car2.jpg)
![Road Simulation](images/car1.png)

- **Traffic Signal Images:**
 - `green.png`: Green traffic light.
 - `red.png`: Red traffic light.
 - `yellow.png`: Yellow traffic light.

### Data Files
- `counter.txt`: Tracks vehicle counts in each road, formatted as lines of numeric entries:
 - Example:
 ```
    4
    2
    2
    2
```
---

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Antony1247/Traffic-light-optimization.git

1.  Ensure you have Python 3.7 or above installed.

* * * * *

Usage
-----

1.  Run the simulation:

    bash

    Copy code

    `python simulation.py`

2.  View the output, including vehicle movements and traffic light status.

* * * * *

Example Visuals
---------------

### Road and Vehicles

![Road Simulation](images/1.png)

### Traffic Lights

#### Green Light
![Road Simulation](images/signals/green.png)

#### Red Light
![Road Simulation](images/signals/red.png)

#### Yellow Light
![Road Simulation](images/signals/yellow.png)
