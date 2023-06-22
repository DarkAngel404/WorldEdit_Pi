WorldEdit\_MCPi
===============

Normally to re-create WorldEdit mod in MCPi (Reborn or ++)

Installation
============

In a terminal : `git clone https://github.com/DarkAngel404/WorldEdit_MCPi.git`

#### Don't forget to modify [MCPI_PSEUDO] by your MCPi pseudonyme (from line 94 to line 99 of `main.py`) and [YOUR_OS_USERNAME] by your OS username (by default `pi`)

Launch
======

Just launch `main.py`

[How to launch](https://github-production-user-asset-6210df.s3.amazonaws.com/126427514/247960958-a9480259-0a6a-4f4a-85c6-51ddaeff2c6b.mp4)

Customization
=============

#### Line 83
Edit `for line in capture("[YOUR CLIENT]"):`
#### Clients :
- MCPi Reborn : `client["reborn"]`
- MCPi++ : `client["++"]`

# DON'T MOVE WORLDEDIT FOLDER FROM DEFAULT FOLDER OR IT WILL CRASH (for the moment)
