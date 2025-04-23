
> [!OBJECTIVE]
> 1. Locate and rescue the Astro-Ducks
> 2. Establish communication with the Earth
> 3. Restore power to the antennas
> 4. Communicate the antennas' LED color to the Earth

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
