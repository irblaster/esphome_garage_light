# esphome_garage_light

Manage the garage light via ESPHome and Home Assistant.  All control is local.  Home Assistant can monitor and control, but the device still functions without a home asssitant server running.

Light is connected to the ESP8266 via a relay board.  Light goes on and stays on for 2 min when:
- The garage is opened or closed
- Motion is detected

Any of the above actions also restart the 2 min timer.

All parts from https://ezmation.com

