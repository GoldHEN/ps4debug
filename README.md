# ps4debug
```
                   _____     .___    ___.
   ______  ______ /  |  |  __| _/____\_ |__  __ __  ____
   \____ \/  ___//   |  |_/ __ |/ __ \| __ \|  |  \/ ___\
   |  |_> >___ \/    ^   / /_/ \  ___/| \_\ \  |  / /_/  >
   |   __/____  >____   |\____ |\___  >___  /____/\___  /
   |__|       \/     |__|     \/    \/    \/     /_____/

                   Coded by golden.
                   Updated by Ctn & SiSTRo.
```

This is a debugger for the PlayStation 4. Yes thats right! Look around and you will find some very useful tools online or on the PS4 Source Discord channel. Anything is possible, except kernel mode debugging, which I decided to leave out.

Latest version: `v1.1.17`

Please report any issues to the [GoldHEN Discord](https://discord.gg/pR5NTEVBGt).

### Quickstart Guide
I am going to try to give you a little rundown on how to use ps4debug....
1. Download Debug Watch or another debugging tool, checkout the discord for downloads
2. Load the latest version of `ps4debug.bin` on the console (on the release page)
3. I recommend just loading ps4debug and your choice of HEN
4. Start your favorite game!
5. Attach to the game (or userland process)
6. Start messing around with your debugging tool, try to find a bug for me!
7. Make l33t hacks.

## Features

- Everything you know and love about ps4debug including:
  - Firmware supported: (*) means untested
    - `5.05`, `5.07`,
    - `6.71`, `6.72`,
    - `7.02`, `7.50`, `7.51`, `7.55`,
    - `9.00`, `9.60`,
    - `10.00`, `10.01`, `10.50`, `10.51`, `10.70`(*), `10.71`(*),
    - `11.00`.
  - Rest mode support.
  - Console scanner.

## Current status with tools

### Reaper Studio - Debugger, Trainer creator.
- Working.

### MultiTrainer II - Cheat/Trainer Loader
- Working

### Original Reaper - Debugger, Trainer creater.
- Working

### PS4 Cheater - Memory scanner/viewer.
- Working

### Credits

Coded by [golden](https://github.com/jogolden), updated by [ctn123](https://github.com/ctn123) & [SiSTRo](https://github.com/SiSTR0).

Special thanks to:
- [Kameleon](https://github.com/kmeps4)

Greeting to other devs: (alphabetical order)
- [2much4u](https://github.com/2much4u)
- [Al-Azif](https://github.com/Al-Azif)
- [berkayylmao](https://github.com/berkayylmao)
- [ChendoChap](https://github.com/ChendoChap)
- [flat_z](https://github.com/flatz)
- [idc](https://github.com/idc)
- [kiwidoggie](https://github.com/kiwidoggie)
- [qwertyoruiop](https://twitter.com/qwertyoruiopz)
- [sleirsgoevy](https://github.com/sleirsgoevy)
- [Specter](https://github.com/Cryptogenic)
- [SocraticBliss](https://github.com/SocraticBliss)
- [theflow0](https://github.com/TheOfficialFloW)
- [Vortex](https://github.com/xvortex)
- [zecoxao](https://twitter.com/notzecoxao)
- [Znullptr](https://github.com/dmiller423)

Greeting to QA/Testers: (alphabetical order)
- [Big_Wadger](https://twitter.com/big_wadger)
- [Echo Stretch](https://twitter.com/StretchEcho)
- [Hejran7](https://www.youtube.com/@BabaAlloush)
- [Pharaoh2k](https://github.com/Pharaoh2k)

### Changelog:
- v1.1.16
  - Added support for `9.00`, `9.60`, `10.00`, `10.01` and `11.00`
  - Fixed attach/detach issue when game exits during a debug session.
- v1.1.17
  - Improved support for debugging multi-threaded processes.
  - Improved allocations for cheats.
  - General stability improvements.
  - General performance improvements.
  - Added support for 10.50, 10.51, 10.70 and 10.71
  - Fixed loading with latest GoldHEN.
  - Implemented hardware breakpoints.

