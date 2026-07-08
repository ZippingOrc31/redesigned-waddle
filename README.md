Macro Recorder Suite  
A lightweight Python macro recorder for capturing and replaying keyboard and mouse actions.
Designed for automation, repetitive tasks, and experimentation with Python input hooks.


EXE in RELEASES SECTION >>>>


📌 Overview
The Macro Recorder Suite records keyboard and mouse events, saves them into a simple .x macro format, and replays them with accurate timing.
It includes optional clicker modules and a minimal, custom‑styled UI.

✨ Features
Macro Recording
Captures keyboard and mouse events

Accurate timing between actions

Saves macros in a simple .x format

Macro Playback
Replays macros with consistent timing

Supports long-duration recordings

Tools Panel
Optional modules included:

ControllerClicker — virtual controller clicker(xinput devices only for now)

MouseClicker — rapid mouse clicker
Both modules integrate with the main UI.

UI / UX
Clean, minimal layout

🐞 Known Issues
Controller virtualization layer is experimental
Some UI elements may behave differently on non‑Windows systems
Macro timing may vary slightly depending on system load

📜 License — Mozilla Public License 2.0
This project is licensed under the MPL 2.0, allowing you to:

Keep your core files open
Release obfuscated or proprietary extensions
Mix open and closed modules safely
You retain full copyright over your work.

🤝 Contributing
Pull requests are welcome.
If you want to add new modules or expand the macro format, open an issue first.

TO BE DONE ***
🚧 Upcoming Features
These are the next major upgrades planned before the project transitions toward a C++ rewrite:

**Scheduling of recorded macros with system clock**

🖼️ Image‑Based Detection Engine
A new detection subsystem that will allow macros to react to what’s on the screen.
Planned capabilities include:

Screenshot‑based object detection

Pixel‑pattern matching for UI elements

Trigger‑based macros (run when an image appears)

Optional low‑memory color‑compressed screenshot format

High reliability for IT workflows and game automation

This system will enable intelligent macros that adapt to changing screen conditions instead of relying only on static coordinates.

🎮 Advanced Controller Recording & Replay
Expanding beyond the current clicker module, this feature will introduce:

Full controller input capture (sticks, triggers, buttons)

High‑precision timing for analog movement

Replay engine capable of simulating real controller behavior

Virtual controller layer improvements

Optional mapping profiles for different games or apps

This will turn the suite into a complete controller automation toolkit, not just a clicker.

🛠️ C++ Rewrite (Long‑Term Goal)
After the above features are complete, the project will begin transitioning toward a C++ implementation for:

Lower latency

Higher performance

Better threading

Native Windows integration

More reliable controller virtualization

Python will remain the prototyping layer, but the final engine will be C++‑powered.
