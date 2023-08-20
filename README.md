Heavily modified version of Spike's Quakespasm fork, focused on improving the way UI elements are scaled and formatted.

## Main Features
- Decoupled main menu and console rendering from the window or fullscreen size to prevent stretching, can be scaled like any other UI elements now
- Clean integer scaling of all UI elements ranging from menu, console, status bar and crosshair using the menu slider
- New FOV cvar that sets the regular FOV and automatically adjusts the viewmodel FOV to match, proportianality factor can be manually adjusted
- Implemented mh's elevator fix, player no longer sinks into rising elevators

## Optional Features
- Reintroduced subtle idle camera sway as initially implemented by John Romero during Quake's development, was cut due to lack of approval from the rest of team
- Dynamic status bar mode, will only show the status bar while a key is pressed for more immersion
- Support for disabling certain monsters on the server side, added for a certain friend that really likes Quake but does not like spiders
