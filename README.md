MACRO RECORDER SUITE — PROJECT OVERVIEW

Macro Recorder Suite is a lightweight Python-based automation toolkit designed for capturing, saving, and replaying keyboard and mouse actions. The suite includes optional clicker modules, a soundboard application, voice-controlled macro playback, and a custom borderless UI with dynamic resizing, theme customization, and layout persistence. It is built for automation, repetitive workflows, experimentation, prototyping, and controller-based automation.

------------------------------------------------------------
FEATURES
------------------------------------------------------------
Known issues:: Macro recorder doesnt record 3 key combos (patch in development), Macro recorder conflicts and causes mouse lag and general sluggishness if two hotkeys are bound to the same action or 2 voice commands are bound to the same action (patch in development)

MACRO RECORDING
- Captures keyboard and mouse events
- Records accurate timing between actions
- Supports long-duration recordings
- Saves macros in a simple .x format
- Records relative and absolute mouse movement
- Records scroll wheel and click states
- Filters unsupported keys for stability

MACRO PLAYBACK
- Replays macros with consistent timing
- Supports infinite loops or fixed loop counts
- Adjustable playback speed
- Cleans up stuck keys after playback
- Works reliably across long recordings

VOICE CONTROL PLAYBACK
- Dynamic voice-triggered macro playback
- Keyword-based activation
- Optional authentication phrase (coming soon)
- Integrated with the suite’s audio routing
- Works alongside all other modules

TOOLS PANEL
- ControllerClicker: Virtual controller clicker (XInput devices only for now)
- MouseClicker: Rapid mouse clicker with adjustable rate
- SoundboardApp: Custom soundboard module with Voicemeeter routing
- Voicemeeter Extension: Complimentary audio routing layer for voice control, soundboard playback, and macro audio triggers
- All modules can be toggled dynamically inside the launcher

LAUNCHER AND UI
- Borderless, draggable, semi-transparent window
- Scrollable macro panel with invisible scrollbars
- Dynamic window resizing (Window + and Window -)
- Custom resize handle in bottom-right corner
- Scale controls for zooming macro content (Scale + and Scale -)
- Right sidebar occupies approximately ten percent of the window
- Compact grid layout for tool buttons
- Theme customization window with color pickers
- Theme presets loaded from theme.json
- Save and load theme files (.theme or .json)
- Layout persistence (geometry, sash position, scale)
- Smooth resizing and snapping behavior
- Stable toggle system for embedded modules

------------------------------------------------------------
KNOWN ISSUES
------------------------------------------------------------
- Controller virtualization layer is experimental
- Some UI elements may behave differently on non-Windows systems
- Macro timing may vary slightly depending on system load
- Scrollbars are intentionally hidden; mouse wheel is required for scrolling
- Soundboard latency may vary depending on audio backend
- Voice control accuracy depends on microphone quality and environment
- Window resizing and management is under development

------------------------------------------------------------
LICENSE — MOZILLA PUBLIC LICENSE 2.0
------------------------------------------------------------
This project is licensed under the MPL 2.0, allowing:
- Open core files
- Proprietary or obfuscated extensions
- Mixed open and closed modules
- Full copyright retention

------------------------------------------------------------
CONTRIBUTING
------------------------------------------------------------
Pull requests are welcome. If you want to add new modules or expand the macro format, open an issue first. Contributions to the launcher, detection engine, controller subsystem, or UI improvements are encouraged.

------------------------------------------------------------
UPCOMING FEATURES
------------------------------------------------------------

IMAGE-BASED DETECTION ENGINE
- Screenshot-based object detection
- Pixel-pattern matching for UI elements
- Trigger-based macros (run when an image appears)
- Optional low-memory color-compressed screenshot format
- High reliability for IT workflows and game automation
- Intelligent macros that adapt to screen conditions

ADVANCED CONTROLLER RECORDING AND REPLAY
- Full controller input capture (sticks, triggers, buttons)
- High-precision analog movement timing
- Replay engine simulating real controller behavior
- Improved virtual controller layer
- Mapping profiles for different games or applications
- Complete controller automation toolkit

C++ REWRITE (LONG-TERM GOAL)
- Lower latency
- Higher performance
- Better threading
- Native Windows integration
- More reliable controller virtualization
- Python remains the prototyping layer; final engine becomes C++ powered

------------------------------------------------------------
END OF DOCUMENT
------------------------------------------------------------
