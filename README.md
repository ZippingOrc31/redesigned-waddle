📌 Overview
The Macro Recorder Suite captures keyboard and mouse actions, stores them in an obfuscated .x macro format, and replays them with accurate timing.
It includes a unified tools panel with optional clicker modules and a clean, semi‑transparent UI.

This project is built for:

Automation scripting

Repetitive task execution

Game macro experimentation

Workflow prototyping

Learning how input hooks & event loops work in Python

✨ Features
Macro Recording
Records keyboard + mouse events

High‑accuracy timing

Relative movement mode with optional screenshot anchors

Obfuscated command storage for safer macro sharing

Macro Playback
Smooth replay with consistent timing

Supports long-duration macros

Visual offset engine adapts to UI movement

Tools Panel
Includes optional modules:

ControllerClicker — virtual controller macro clicker

MouseClicker — rapid-fire mouse clicker
Both tools integrate directly into the main UI.

UI / UX
Semi‑transparent light grey theme

Custom window chrome

Clean layout with collapsible panels

Brightened interface for visibility in dark environments

📁 File Structure
Code
/MacroRecorder
    rapdi.pyw
    controller clicker.pyw
    mouse clicker.pyw
    assets/
    macros/
rapdi.pyw — main macro recorder

controller clicker.pyw — controller clicker module

mouse clicker.pyw — mouse clicker module

macros/ — saved .x macro files

assets/ — UI resources

🚀 Getting Started
Requirements
Python 3.10+

Windows OS (recommended)

pynput, PIL, tkinter (included by default on Windows)

Run the Recorder
bash
python rapdi.pyw
Record a Macro
Open the Macro Recorder

Press Start Recording

Perform your actions

Press Stop Recording

Save your macro (.x format)

Play a Macro
Load a macro file

Press Play

Watch the automation run

🛠️ Building an EXE (Optional)
Compatible with PyInstaller:

bash
pyinstaller --noconsole --onefile rapdi.pyw
If you include the clicker modules, bundle them in the same directory.

🐞 Known Issues
Visual offset anchors may drift in games with dynamic FOV changes

Controller virtualization layer is experimental

Some UI elements may behave differently on non‑Windows systems

📜 License
MIT License — feel free to fork, modify, and contribute.

🤝 Contributing
Pull requests are welcome.
If you want to add modules (auto‑hotkey style tools, new clickers, UI themes), open an issue first so we can discuss the design.

💬 Credits
Created by Dustin — built for learning, experimenting, and pushing Python automation further.
