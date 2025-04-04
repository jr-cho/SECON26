
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

## Vehicles
---
### Main Bot
-  [[00 - MAIN BOT PARTS]]
### Helper Bot
- [[01 - HELPER BOT PARTS]]
### Micro UAV
- [[02 - UAV PARTS]]

## Subsystems
---
### Core Movement and Navigation

1. Drivetrain system
2. Path planning system

### Astro-Duck Rescue

1. Duck Detection System (Path planning system)
2. Duck collection system
3. Duck drop off system

### Antenna Interaction

1. Antenna #1
	- Press Button
2. Antenna #2
	- Crank Arm
3. Antenna #3
	- Precision Grabber
4. Antenna #4
	- Keypad Entry Mechanism

### UAV Task

1. Must Launch 15" x 15" away from the main bot
2. UAV LED Detection
3. UAV Communication Subsystem
4. UAV Recovery Mechanism

## Starting & Timing

1. Detect white start light
2. Automatically begin without start button

### Utility Subsystem

1. Power Management
2. State Machine
3. Telemetry

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
