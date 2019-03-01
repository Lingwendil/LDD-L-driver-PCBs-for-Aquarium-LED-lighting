# LDD-L-driver-PCBs-for-Aquarium-LED-lighting
PCBs for the LDD-L series of LED drivers


A set of PCBs for the LDD300L-LDD700L drivers, multiple versions are available, with four ("nano") and eight ("8up")channels being the main focus of the project. Both an "EZ" and "PRO" version are currently finished, with the main differences being the type of power and PWM inputs used. 

"EZ" boards feature onboard TRS/audio stereo jacks for PWM input, and a DC barrel jack for power. A set of headers is provided to allow parallel connection of each channel, allowing two channel control on the four channel board, and four channel control on the eight channel board. The DC jack is Kobiconn 163-179PH-EX, the TRS jack is Switchcraft 35RAPC2BV4, both available at Mouser.

"PRO" boards feature a pin header for PWM input, and a screw terminal for power. The input header has two identical rows of pins to facilitate easy jumpering of channels, or daisy chaining of boards.

"Nano" boards feature 2.54mm pin spacing for outputs, "8up" feature standard 5.08mm pin spacing for outputs, so that popular and affordable screw terminals can be used, from the usual place like Amazon or Ebay. This project can use the higher-end types, but the cheap stuff from china will work fine for all but the most prolific of power users, that feel the need to constantly swap wiring and parts. Buy nice parts from Phoenix or similar if they will get a lot of hard use.

All boards can be used for up to 32 volts, 700mA output per channel, and up to 36 volts input. Jumpers are featured to allow the pulldown resistors to be enabled/disabled for troubleshooting. M3 or 4-40 screw holes are provided in the corners of each board.

Currently "finished" (more or less, assuming boards test correctly)

LDD-L 4up "pro"
LDD-L 8up "pro"
LDD-L 4up "EZ"
LDD-L8up "EZ"

Currently in-progress designs-

LDD-H 8up pro (with SCW DC-DC converter)
LDD-H 4up pro (basically just a cut-in-half 8up board, but you know, correctly. Natural evolution)
LDD-H 6up "Blue Six" board (bluefish-specific board, hopefully for direct plug-in of the Bluefish Mini controller)

Maybe in the future-

LDD-L 6up "Blue Six Mini" (with onboard PWM level conversion, and Bluefish mini plug-in support)
LDD-H 4up "EZ" (onboard DC jack and TRS jacks for input, as in the LDD-L "EZ" versions)
LDD1000-1200L/LDB-L combo board (if you aren't familiar with the LDB, it's a buck-boost driver, same style as the H-series, just with the capability of supplying higher output voltage than input voltage- handy little driver)
Back-burner designs-
LDD-L 16up board (I think stacking 8ups makes a bit more sense, I may revisit later)

Suggestions on improvement or features are encouraged!
