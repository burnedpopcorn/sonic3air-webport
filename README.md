# Sonic 3 A.I.R. Web Port

WebAssembly Port of  "Sonic 3 - Angel Island Revisited", a fan-made remaster of Sonic 3 & Knuckles.

Main Project homepage: https://sonic3air.org/

### About
I did not compile this myself, all I did was extract all the files from Sappharad's Web Port (and technecally an IOS Port) from [his website](https://projects.sappharad.com/s3air_ios/20240202_beta/)

Special thanks to him for doing it for me

### To Run this yourself
- Get the files from this repo
- Put the files in a web server (Because I'm 99.99% sure this was made by Emscripten, it CANNOT be run locally with the file:// protocol, as that results in CORS issues because of Emscripten Limitations)
- Open sonic3air_web.html from within your website (https:// (your domain) /sonic3air_web.html)

### To run this Locally
If you want to run this locally, use something like python to run a temporary web server on your machine

To do this using Python, you do by
- Entering the directory containing sonic3air_web.html and other files and typing the command python3 -m http.server in the linux terminal or py -m http.server for windows powershell given you installed python
- At which point you can enter http://localhost:8000/sonic3air_web.html to play the game locally

Also, you still need to have Sonic_Knuckles_wSonic3.bin as of now, but this repo will have it for you, and I will try and see if I can change it to just include it within the same server it is hosted on

### Disclaimer

Sonic 3 A.I.R. is a non-profit fan game project. It is not affiliated in any way with SEGA or Sonic Team, the original creators of Sonic 3 and Sonic & Knuckles.

Sonic the Hedgehog is a trademark of SEGA. All copyrights regarding Sonic the Hedgehog, including characters, names, terms, art, and music belong to SEGA. All registered trademarks belong to SEGA and Sonic Team.

The developers of Sonic 3 A.I.R. have no intent to infringe said copyrights and registered trademarks.
No financial gain is made from this project.

Any commercial use of this project without SEGA's explicit consent is strictly prohibited.


## Repository overview

This repository is split into several different projects:
* The larger external dependencies (namely SDL2, Ogg/Vorbis, zlib) inside the "framework" directory. These are copies of the respective open source projects, with a few custom changes applied where needed - see the "how-to-build.txt" files in there for details.
* The librmx libraries that together with the external dependencies build a foundation for my own projects (S3AIR and my private stuff). This primarily consists of rmxbase, a collection of helper and utility classes, and rmxmedia, which is providing a basic game framework built on top of SDL2 & OpenGL.
* Lemonscript language library, with compiler and runtime environment for script execution.
* Oxygen Engine, the backbone game engine powering Sonic 3 A.I.R. This includes input, graphics, audio handling, and all the other game application stuff, as well as a simulation environment built around lemonscript that - as far as needed for the purposes of S3AIR - emulates aspects of Sega Genesis hardware. Note that Oxygen can be built as its own application (OxygenApp) that lacks the S3AIR C++ code.
* S3AIR-specific C++ code, scripts and data in the "Oxygen/sonic3air" directory. Yes, that's what it's named.

## Contributors

Thanks to all contributors!

Source code contributions by:
* Sappharad
* Heyjoeway
* Carjem Generations
* Ultracoolguy
* gl33ntwine
* Rinnegatamante
* MDashK

Remastered soundtrack by:
* G Spindash

Game scripts & other contributions by:
* Vinegar
* Thorn
* Legobouwer
* GFX32
* Dynamic Lemons
* HazelSpooder
* iCloudius
* D.A. Garden
* Alieneer
* 3Pills
* Elsie The Pict
* TheMushrunt
* mrgrassman14
