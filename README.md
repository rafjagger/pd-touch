# pd-touch
puredata and touch-osc interface was made to automate audio-spatialization with panoramix (ircam).

In Touch-OSC you'll see 4 Banks each with 4 Units. Every 
unit remotes azimuth and distance for a channel in panoramix.

Unit-description:

	xy-pad:
	- shows current position of soundsource
	- manual control (manual-mode / rec-mode)
	- red dot in the upper right corner shows audioactivity 
	  (enabled by panoramix-projectfile)
	- centertext: actual mode
	- frametext: direction
	- startup-text: is hidden but appears on changing 
	  direction and mode

Polar-Mode
```
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
|     |     | send |
|-----|-----|------|

- dir = direction
- send = send to panoramix toggle
```
Cartesian-Mode
```
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
| -y  | -y  | send |
|-----|-----|------|

- dir = direction
- send = send to panoramix toggle
```

Record-Mode
```
Not Ready yet.
```

How to:
```
- buy and install touch-osc on your smartphone
- download touch-osc editor to your computer
- upload iosx.touchosc via touch-osc editor to your smartphone (build on iPhone-Xr)
- put the pd-touch folder in puredata path
- open master.pd 
- install required externals
- follow project-instructions
```
