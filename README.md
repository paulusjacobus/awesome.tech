# awesome.tech
awesome.tech download page

To relieve our web site from the heavy download traffic, we have posted our source files here.

Please let us know if you are missing any files and we will add them asap.

The firmware can be downloaded from this page and flashed with a ST Link V2 dongle (Mini/Super Gerbils only) or with an Arduino dongle (legacy Gerbil only)

Newest production firmware 32 bits MiniGerbil firmware name = stm32grblVER1_1f_20210106.hex
Includes now:
Ability to invert logic for PWM and Laser enabling, to cater for non K40 lasers. $98,$99 settings
Bugfix for random "Msg door" messages.
Bugfix for motion speed. Increased the stepper motor speeds to 400mm/sec.
Bugfix for motor step driver duration. Previously the step duration was fixed to 10mSec. Now the user can define the step duration in $0. Default setting is 10 milliseconds.
J2 connector Fault Output pin now used as air assist (M8) port

Last production firmware 32 bits MiniGerbil firmware name = MGfirmwareV8_grbl20719.hex

8 bits AVR 328PB Legacy Gerbil firmware = grblUploadgoldnoalarmboot(1).zip

32 bits Super Gerbil firmware = SGRelease030719.hex

Thank you,

Awesome.Tech
