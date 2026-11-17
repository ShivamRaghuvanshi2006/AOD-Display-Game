# AOD Display Game

A small Android game concept built around the Always-On Display (AOD). The idea is to make short interactions possible without opening a full game or keeping the screen fully active.

## Project status

**Status:** Project placeholder — implementation not yet documented.

This repository is intended to hold experiments for a lightweight, low-distraction game that can work within the constraints of an always-on display. Battery use, limited screen updates, and simple interaction are the main design considerations.

## Planned work

- Define a simple game loop that suits short interactions.
- Explore what Android's AOD and lock-screen APIs actually permit.
- Keep rendering and background work minimal.
- Measure battery and wake-up impact on a real device.
- Document supported Android versions and device limitations.

## Development notes

A normal Android application cannot freely draw over every manufacturer's always-on display. Any implementation will need to respect Android platform restrictions and vendor-specific behaviour.

## Contributing

There is no contribution workflow yet. The repository will be updated as the prototype takes shape.
