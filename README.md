# Sonic 3 A.I.R. Web Port

WebAssembly Port of  "Sonic 3 - Angel Island Revisited", a fan-made remaster of Sonic 3 & Knuckles.

Demo Site of This Project: http://sonic3airwebport.x10.mx/sonic3air_web.html

Main Project homepage: https://sonic3air.org/

### About Repository
I did not compile this myself, all I did was extract all the files from Sappharad's Web Port (and technecally an IOS Port) straight from [his website](https://projects.sappharad.com/s3air_ios/20240202_beta/)

Special thanks to him for doing it for me

Honestly, he should've just released the files from the start, but at least I have a reason to stall my other web ports (yes I have more)

Also as a bonus, touch controls work as well, so I guess its a IOS port as well (And please read the entire readme, it holds lots of info)

![image](https://github.com/burnedpopcorn/sonic3air-webport/blob/main/images/s3airtitle.png)
![image](https://github.com/burnedpopcorn/sonic3air-webport/blob/main/images/s3airmenu.png)
![image](https://github.com/burnedpopcorn/sonic3air-webport/blob/main/images/s3airgame.png)

### To Run this yourself
- Get the files from this repo (Code -> Download ZIP)
- Put the files in a web server (Because I'm 99.99% sure this was made by Emscripten, it CANNOT be run locally with the file:// protocol, as that results in CORS issues because of Emscripten Limitations)
- Open sonic3air_web.html from within your website (https:// (your domain) /sonic3air_web.html)

### To run this Locally
If you want to run this locally, use something like python to run a temporary web server on your machine

To do this using Python, you do by
- Again, Get the files from this repo (Code -> Download ZIP)
- Entering the directory containing sonic3air_web.html and other files and typing the command python3 -m http.server in the linux terminal or py -m http.server for windows powershell given you installed python
- At which point you can enter http://localhost:8000/sonic3air_web.html to play the game locally

Also, you still need to have Sonic_Knuckles_wSonic3.bin as of now, but this repo will have it for you, and I will try and see if I can change it to just include it within the same server it is hosted on

### To Extract the Assets for Yourself
Read [EXTRACTING.md](https://github.com/burnedpopcorn/sonic3air-webport/blob/main/EXTRACTING.md) for that (if you really want to)

### MODS!
Not sure if mods work, but you can access the mods folder and then restart the game if you exit within the main menu

![image](https://github.com/burnedpopcorn/sonic3air-webport/blob/main/images/s3airfiles.png)

## Disclaimer

Sonic 3 A.I.R. is a non-profit fan game project. It is not affiliated in any way with SEGA or Sonic Team, the original creators of Sonic 3 and Sonic & Knuckles.

Sonic the Hedgehog is a trademark of SEGA. All copyrights regarding Sonic the Hedgehog, including characters, names, terms, art, and music belong to SEGA. All registered trademarks belong to SEGA and Sonic Team.

The developers of Sonic 3 A.I.R. have no intent to infringe said copyrights and registered trademarks.
No financial gain is made from this project.

Any commercial use of this project without SEGA's explicit consent is strictly prohibited.

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
