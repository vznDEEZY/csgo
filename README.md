###### vznDEEZY: CONFIG, OPTIONS & SETTINGS for CS:GO - ESEA & FACEIT Optimized
###### Last Updated: 12/20/2020

##### Place the "vznexec.cfg" file to your Steam CSGO Directory
###### Example Path: C:\Program Files(x86)\Games\Steam\steamapps\common\Counter-Strike Global Offensive\csgo\cfg\vznexec.cfg

### Windows Information & Settings
	OS: Windows 10 Pro
	Monitor Resolution: 1920x1080
	Monitor Refresh Rate: 240hz
	Mouse DPI: 600
	Mouse Polling Rate: 1000hz
	Windows Sensitivity: 5/11
### Windows Gaming Settings
##### Windows + R > type "ms-settings:" > Gaming 
	Xbox Game Bar: Disabled
	Game Mode: Enabled
	NAT Type: Moderate
	Background Apps: Disabled		
### NVIDIA 3D Settings (Tweaked Program Settings)
##### Right-click on your desktop & open NVIDIA Control Panel to make these changes.
###### Best visibility & smoother gameplay __particularly for my specs__
	Anisotropic Filtering: 16x
	Antialiasing - Gamma Correction: On
	Antialiasing - Mode: Enhance the application setting
	Antialiasing - Setting: 8x
	Monitor Technology: G-SYNC
	Texture Filtering - Trilinear optimization: On
	Texture Filtering - Quality: High Quality
	Texture Filtering - Negative LOD bias: Clamp
	Threaded Optimization: On
	Vertical Sync: Off
	Power management mode: Prefer maximum performance
	Preferred Refresh rate: Application-controlled
	Max Frame Rate: Off
	Low Latency Mode: Ultra
### In-game Video Settings (In-Game)
###### Improved Visibility with the Smoothest Gameplay - Faster load times, lowest input lag & highest FPS __particularly for my specs__
	Anisotropic Filtering: 16x
    Display Mode: Full-screen Windowed
    Effect Detail: High
    FXAA Anti-Aliasing: Enabled
    Global Shadow Quality: Very Low
    Model/Texture Detail: Low
    Shader Detail: Low
    Texture Filtering Mode: Anisotropic 16x
    Texture Streaming: Enabled
    NVIDIA Multi-Frame Sampled Anti-Aliasing: Off 

## Launch Options
##### Steam > Right-click on Counter-Strike: Global Offensive > Properties > SET LAUNCH OPTIONS
> -refresh 240 -novid -nojoy -tickrate 128 -windowed -w 1920 -h 1080 -noborder +snd_mute_losefocus 0 +exec vznexec.cfg
