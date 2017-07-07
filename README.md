## ClipSaverV v1.0.0

ClipSaverV is a small script which let your players to save clips for the Rockstar Editor (Pause -> Rockstar Editor)

## Installation
* Copy the clipsaverv folder and put it in your resources folder from the [git](https://github.com/Kyominii/ClipSaverV/)
* Add clipsaverv in the autostart section (server.cfg or citmp-server.yml)
* Modify bindings as you want in the [config.lua](https://github.com/Kyominii/ClipSaverV/blob/master/clipsaverv/config.lua) file (https://wiki.fivem.net/wiki/Controls)
* Stop your server, clear the cache then start your server
* Enjoy :)

## /!\ You have to be in the session you recorded the clip to edit it in the rockstar editor, and you have to press the Open Editor button to open the Rockstar Editor (not the menu pause one) otherwise it will bug out /!\

## Default bindings

|                     Action                     |               Default Binding               | Default Key |
|:----------------------------------------------:|:-------------------------------------------:|:-----------:|
| Start record action replay (not seems to work) |      INPUT_REPLAY_START_STOP_RECORDING      |      F1     |
|                Start record clip               |            INPUT_SAVE_REPLAY_CLIP           |      F3     |
|                   Save record                  |            INPUT_SAVE_REPLAY_CLIP           |      F3     |
|                 Discard record                 | INPUT_REPLAY_START_STOP_RECORDING_SECONDARY |      F2     |
|               Open Editor button               |               INPUT_DROP_AMMO               |     F10     |
