# Smart Walking Stick Using Arduino

An academic assistive-technology prototype designed to support safer navigation for visually impaired users and elderly individuals through real-time obstacle detection and direction-based audio feedback.

## Academic Context

- **Project type:** Diploma Project · Five-student academic team
- **Completion:** June 2024
- **Institution:** Middle East College, Oman
- **Supervisor:** Ms. Vimala Elumalai

## Problem

People with visual impairments and elderly users may face safety risks when navigating around nearby obstacles. This project explored an affordable embedded prototype that detects obstacles and gives immediate visual and audio feedback.

## Objective

To enhance mobility, safety, confidence, and independence by providing real-time obstacle detection and user feedback.

## My Contribution

I personally built, programmed, and tested the working prototype as part of the five-student academic team.

## System Overview

The prototype uses three ultrasonic sensors to monitor the user’s surroundings. When an obstacle enters the configured safety range, the Arduino Uno processes the sensor input, activates an LED indicator, and triggers direction-based audio feedback through a DFPlayer Mini and speaker.

## System Workflow

```text
Obstacle
→ Ultrasonic Sensor
→ Arduino Uno
→ LED Indicator
→ DFPlayer Mini
→ Audio Warning
