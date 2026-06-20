# Car Parking Simulation

A terminal-based Python program that simulates a car parking lot. Cars are parked into randomly chosen open slots and tracked by license plate, and the lot's occupancy can be inspected at any time. Originally built as a small group project.

## What it does

The program asks for the lot's capacity, then loops on a menu:

1. **Park a new car** – prompts for a plate number and places the car in a randomly selected empty slot (rejecting duplicates and a full lot).
2. **Make a car drive out** – prompts for a plate number and frees that slot.
3. **Display status** – shows total, filled, and empty slot counts plus the current slot layout.
4. **Exit** – ends the program.

It demonstrates list-based state tracking, random slot assignment, and input-driven control flow.

## Tech stack

- Python 3 (standard library only — uses `random`)

## Project structure

```
car-parking-simulation/
└── ParkingLot.py   # the full simulation
```

## Run

```bash
python ParkingLot.py
```

Then follow the on-screen menu. State is kept in memory for the duration of the session.
