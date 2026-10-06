# Safe TeleOp Demo

This project contains a safe TeleOp implementation for the FTC Robot Controller.

## Features
- **Speed Limit Safety:** Motor power is capped at 50% (`0.5`) for controlled and safe robot operations.
- **Drive Controls:**
    - Left Stick Y: Forward / Backward movement.
    - Right Stick X: Turning left / right.
- **Telemetry:** Real-time feedback on motor powers displayed on the Driver Station.

## Setup Instructions
1. Clone this repository into Android Studio.
2. Allow Gradle sync to complete.
3. Deploy the `SafeTeleOp` OpMode to the FTC Robot Controller / Driver Station.