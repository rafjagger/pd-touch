# pd-touch
puredata and touch-osc interface for Panoramix

It's made to automate audio-spatialization with panoramix. 

In Touch-OSC you will see 4 Banks each with 4 Units. Each 
unit will remotecontrol the azim and dist for a channel in 
panoramix.

Unit-description:

	xy-pad:
	1. shows the actual position of the soundsource
	2. can be used to manual control in manual mode or rec-mode
	3. the red dot in the upper right corner shows audioactivity 
	via panoramix-osc (must be set in panoramix-projectfile)
	4. centered text shows the actual mode
	5. frametext shows the direction
	6. initial startup the text is hidden but appears on changing 
	direction and mode

- dir = direction
- edit = toggle unit-output to panoramix

Polar-Mode
|------------------|
|              led |
|                  |
|      polar       |
|                  |
|                  |
|-----------|------|
| speed     | mode |
|-----------|------|
| radius    | dir  |
|-----|-----|------|
|     |     |      |
|     |     |------|
|     |     | edit |
|-----|-----|------|

Cartesian-Mode
|------------------|
|              led |
|                  |
|      cart        |
|                  |
|                  |
|-----------|------|
| speed-x   | mode |
|-----------|------|
| radius-x  | dir-x|
|-----|-----|------|
| spe | rad | dir-y|
| ed  | ius |------|
| -y  | -y  | edit |
|-----|-----|------|

Record-Mode
Not Ready yet.

How to:
- buy and install touch-osc on your smartphone
- download touch-osc editor to your computer
- upload iosx.touchosc to your smartphone (build on iPhone-Xr)
- put the pd-touch folder in puredata path
- open master.pd (install required externals) and follow the 
project-instructions

enjoy!
