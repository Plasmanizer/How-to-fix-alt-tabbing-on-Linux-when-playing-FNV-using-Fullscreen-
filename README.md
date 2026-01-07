I made this guide for myself, so i assume how already know to install MO2 and using WSG guide. Also i assume you know some linux gaming stuff.

1. First enable wine virtual desktop through Protontricks
protontricks 22380 winecfg
tick virtual desktop
set to your monitor resolution

2. Limit your fps through env variables
DXVK_FRAME_RATE=[Insert_Monitor_HZ_or_FPS_you_want_to_use_here]

3. Make sure to enable fullscreen and disable vsync through falloutcustom.ini
[Display]
bFull Screen=1
iPresentInterval=0

4. Done
