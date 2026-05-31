# DKDemos

DK is a prototype of a 2D space simulation game.

This repo contains several minimal feature demos.

### Engine demo

Supposed DK engine model includes calculationg momentum. So that ship with all engines on one side destroyed can't move forward because it have lost stability. If a shitp has 2 engines on one side and 1 engine on other side, and those engine trust vectors have similar momentums relative to center of mass, the side with 2 engines can run on approximately half power to move the ship forwar and not cause spinning (destabilize). Destabilizing is supposed to play important roli in DK space battle mechanics.
EngineDemo folder contains a scrrenshot and very minimalist prototype demo program.
