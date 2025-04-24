
> [!OBJECTIVES]
> - Collect 6 ducks, 1 of which is on top of Antenna #3. Deliver them to the Echo Base.
> - Press a button 3 times to activate. (To activate antenna 1)
> - Rotate a crank 540° (clockwise or counterclockwise). (To activate antenna 2)
> - Remove a duck from a pressure plate inside a crater. (To activate antenna 3)
> - Enter the keypad code "73738#" (spells RESET). (To activate antenna 4)
> - Enter the crater (>25% robot inside), do a lap along the crater wall below a 4” line. (Points)
> - The robot must deploy the UAV by moving it 15” vertically and horizontally. (Launching Drone)
> - Ensure the UAV lands back and stays on the robot after the mission. (Lands back in spot)
> - The robot should start autonomously using an LED trigger. (Start without button)

## General Vehicle Requirements
---

> **Robot** must fit in a 1x1x1 ft (but can extend once the game starts)
> **Robot** must be completely autonomous
> **Robot** must not exceed more than 25 pounds
> **UAV** must not exceed more than 0.55 pounds or 250 grams

```
Robot Subsystems
├── 1. Core (Essential Movement)
│   ├── Drivetrain
│   └── Path Planning
├── 2. Antenna Tasks (High Scoring)
│   ├── Button Arm (Antenna 1)
│   ├── Crank Arm (Antenna 2)
│   ├── Pressure Grabber (Antenna 3)
│   └── Keypad Tapper (Antenna 4)
├── 3. Duck Rescue (Moderate Scoring)
│   ├── Duck Detection
│   ├── Duck Collection
│   └── Duck Drop-off
├── 4. UAV Tasks (LED Read & Transmit)
│   ├── UAV Deployment
│   ├── LED Color Detection
│   ├── IR Communication
│   └── UAV Recovery
​└── 5. Utility Systems (Support)
    ├── Autonomous Start
    ├── Power Management
    ├── Task Coordinator
    └── Telemetry / Debugging
```
