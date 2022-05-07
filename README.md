# CUER-Cheetah


This project aims to model Helia with telemetry provided during a race.

```
               telemetry
  ┌─────────┐             ┌────────────────┐
  │         ├────────────►│                │
  │  Helia  │             │  Base Station  │
  │         │◄────────────┤                │
  └─────────┘             └────────────────┘
               strategy
```

Data processed ahead of time:

- Race track:
  - Path location and elevation
  - Location of stops
  - Race rules and regulations
  - Average wind direction and speed

- Vehicle characteristics:
  - Power characteristics

Data we seek to process during the race:
- Current trajectory and position 
- Battery capacity and power usage

What we want to find out:
- Optimal power usage taking racce rules into account
