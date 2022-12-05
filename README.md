# TO350_Linux

Included is a TacticalOps.sh file to start ut-bin using TacticalOps.ini as configuration file.

Modify section [Engine.Engine] in TacticalOps.ini and set the correct ViewportManager:

```
[Engine.Engine]
...
ViewportManager=SDLDrv.SDLClient
```

Some will also edit section [SDLDrv.SDLClient] to manually set the screen resolution:
```
[SDLDrv.SDLClient]
...
FullscreenViewportX=1024
FullscreenViewportY=768
```
