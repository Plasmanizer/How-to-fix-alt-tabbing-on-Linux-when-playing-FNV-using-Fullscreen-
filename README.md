I made this guide for myself, so i assume how already know to install MO2 and are using VNV, TBOT or WSG guide. Also i assume you know some linux gaming stuff.

1. First enable wine virtual desktop through Protontricks
protontricks 22380 winecfg
tick virtual desktop
set to your monitor resolution

2. Limit your fps through env variables
DXVK_FRAME_RATE=[Insert_Monitor_HZ_or_FPS_you_want_to_use_here] %command%

3. Make sure to enable fullscreen and disable vsync through falloutcustom.ini
[Display]
bFull Screen=1
iPresentInterval=0

4. Done

Or you can just use OneTweak and use borderless fullscreen if you want to use vsync and no Wine Virtual Desktop Emulation (at the cost of unstable fps somehow)

Or use gamescope?

Note: disabling vsync is necessary because Wine Virtual Desktop locks the game to 60 fps for some reason and limiting fps are also necessary because you don't want FNV to have too high fps as it can cause instability issues.

Pros and Cons of using Exclusive Fullscreen in FNV (as far as i know)
Pros:
1. You can tune brightness with ingame settings
2. You have the best performance

Cons:
1. You're stuck with blue virtual screen, so you need to have a seperate workspaces.
2. The game is not really unfocused when alt-tabbing, so your mouse (or maybe even keyboard) can send input into the game. (this one needed verification)
