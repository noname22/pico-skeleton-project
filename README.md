# Raspberry Pi Pico Project Skeleton

This is a project skeleton (blink example) that can be used to base a project on without all the other crap in the pico examples repository.

## Using as a base for a new project
Remeber to
 * Change the target name from `pico_project_skeleton` in root CMakeLists.txt, eg. `my_project`
 * If adding additional source files in src src/ remember to also add them to the executable in src/CMakeLists.txt

## Building & running
 * Download and install Raspberry Pi Pico C SDK
   - Windows users can download it here: https://github.com/raspberrypi/pico-setup-windows
   - SDK source available here: https://github.com/raspberrypi/pico-sdk
 * If using Pico Visual Studio Code
   - Select Pico ARM GCC kit on the status bar at the bottom of the screen
   - To debug using the debug probe, click Debug and select Pico Debug