# Drone Flight Training Simulator
Python + Ursina (Panda3D). Full quadcopter flight model, 30 buildings, 8 scoring rings, 2 landing pads, 3 cameras, live HUD.

## Controls
| Key | Action |
|---|---|
| SPACE / LEFT SHIFT | Throttle up / down (hover ~50%) |
| W / S | Pitch forward / backward |
| A / D | Roll left / right |
| Q / E | Yaw left / right |
| R | Reset drone (keeps score) |
| T | Full reset (score + rings) |
| C | Cycle camera: chase / FPV / orbit |
| H | Toggle help |
| ESC | Quit |

## Run from source
    pip install -r requirements.txt
    python main.py

## Build the .exe (Windows)
Install Python 3.10+ (tick "Add to PATH"), double-click `build.bat`, get `dist\DroneFlightSimulator.exe`.

## Flight model
- Thrust = throttle x 2g along the drone's tilted up-axis -> hover at 50%; tilting drifts you sideways.
- Motor lag, self-levelling attitude, linear + quadratic air drag, light wind gusts, battery drain.
- Crash: vertical speed > 4.5 m/s, tilt > 15 deg on touchdown, > 8 m/s sideways, or hitting a building wall. Roofs are landable.

## Scoring
Ring +100 (all 8: +300 bonus) | Pad landing 50-150 by precision (once per visit) | Crash -50.
Landing on a pad with motors idle recharges the battery.
