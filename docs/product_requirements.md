# Product Requirements – RoomLight

## Overview

RoomLight is a system for controlling hotel room lights. The idea is that lighting can be set once and then applied to all rooms automatically.
One important goal of the system is to reduce energy consumption through automation and efficient lighting settings.
For example, lights can automatically switch to lower brightness during the night or when the room is not in use.

## Main Features

### Central control
The system should have one main lighting setup that can be changed when needed. This setup can then be used for all rooms.

### Room synchronization
All rooms should be able to update their lighting based on the main setup. When something is changed, it should update to every room.

### Room handling
The system should be able to store multiple rooms. Each room should have its own light settings.

### Custom settings
Even though there is a main setup, individual rooms can have their own settings if needed.

### Light settings
Each room should have:
- on/off state
- brightness level
- simple modes (night mode, reading mode, relax mode, cleaning mode, energy saving mode)
- for example night mode uses low brightness and cleaning mode uses maximum brightness

Different modes can change brightness automatically depending on the situation and help reduce energy usage.
Energy saving can be supported by lowering brightness when the room is empty or by using predefined low-power modes.

### Energy efficiency

The system should support energy saving by:
- using lower brightness levels when possible
- applying energy saving mode automatically at certain times
- reducing unnecessary light usage in empty rooms

### Status view
It should be possible to see what the current light status is in each room.

## Other requirements

- The system should be simple to use
- It should work with many rooms
- Changes should happen quickly
