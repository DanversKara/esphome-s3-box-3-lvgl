Overview

This project is based on the work by

https://github.com/chrisdunnname/esphome-s3-box-3-lvgl.  

It has been modified to better integrate with my devices and Home
Assistant setup.

---
Non Secure vs Secure Setup

1. Secure = Front Door Button has 2 Options, Option A will require a Pin Code to press unlock front door, while Option B you can uncheck needing a pin under settings that wont ask for a pin encase you wanna leave this device near the front door or at desk to unlock/lock fast while Option A is encase you wanna mount this touch screen outside and secure screen with pass code i mean a pin code.

2. Secure Settings can only be accssed thru typing in a 2nd pass code that isnt the same as the front door code, inside secure settings is the same settings from Non Secure just behind a hidden settings menu.

3. If the device is away from wifi the screen switches to NO CONNECTION making the device a brick and it cant be used for any period not even a clock making the a brick and them throw it away unless they know how to re-program it.

---

Changes

Removed the bottom navigation bar (Left / Home / Settings / Right) (the red circle on unit, is the home button)

Navigation is now handled entirely by swipe gestures\

Provides increased usable screen space

Redesigned UI buttons for improved clarity and consistency

Added support for box sensors

Integrated CCTV functionality using IP Webcam (Android)

Added a screensaver shortcut

Redesigned the screensaver for a cleaner, more modern appearance

Added a dedicated timer icon to reduce reliance on voice/AI commands

Replaced the battery icon with a percentage display in the top bar

(Home and Screensaver)

Removed the analog clock

Reduces memory usage and code size\

Aligns with a preference for digital display

Removed external GitHub-hosted images

Reduces resource usage\

Improves performance and load consistency\

i replaced HAL, Default and all other wake words with OKAY Computer

also turn off notificaiton sound, turn off wake sound, i find it delays ai from waking up to wake names. make sure you tunr on enable speaker.

Replaced with lightweight icons and cleaner text

*Swipe was already there and alarm clock was there by tapping the time top left.
