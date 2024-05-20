## Extracting the Assets from Sappharad's Website

How I did it:
- Go to his Sonic 3 A.I.R page (https://projects.sappharad.com/s3air_ios/20240202_beta/sonic3air_web.html)
- Right Click the page and press Inspect
- in the Inspect Menu, click the Sources Tab
- Open the worker.js directory, and then open the two other subdirectories within, and lastly, open the worker.js file
- Look at lines 3-12, and note the files listed:

```
_cacheFiles = [
	'sonic3air_web.html',
	'sonic3air_web.js',
	'sonic3air_web.wasm',
	'loader.js',
	'manifest.json',
	'icon.png',
	'browserfs.min.js',
	'filemanager.js',
	'fileManagerRuntime.js',
	'react.js'
```

- Copy the file names into the url of Sapphard's website and replace the .html file with these other files

  (For Example: https://projects.sappharad.com/s3air_ios/20240202_beta/sonic3air_web.html -> https://projects.sappharad.com/s3air_ios/20240202_beta/loader.js)
> [!NOTE]
> You will have to do this step many times until you download all the files
- To download any file that doesn't immediately download it automatically, like the html file, just Right Click -> Save as, then save it
- Once you have downloaded all the files, you're done, and you can host it yourself using the instructions in [readme.md](https://github.com/burnedpopcorn/sonic3air-webport)

> [!NOTE]
> If you didn't understand any of this, just remember this is not necessary to run it for yourself, as I have extracted the assets for you already, and the files are in the repo

You know what, here:
- https://projects.sappharad.com/s3air_ios/20240202_beta/sonic3air_web.html
- https://projects.sappharad.com/s3air_ios/20240202_beta/sonic3air_web.js
- https://projects.sappharad.com/s3air_ios/20240202_beta/sonic3air_web.wasm
- https://projects.sappharad.com/s3air_ios/20240202_beta/loader.js
- https://projects.sappharad.com/s3air_ios/20240202_beta/manifest.json
- https://projects.sappharad.com/s3air_ios/20240202_beta/icon.png
- https://projects.sappharad.com/s3air_ios/20240202_beta/browserfs.min.js
- https://projects.sappharad.com/s3air_ios/20240202_beta/filemanager.js
- https://projects.sappharad.com/s3air_ios/20240202_beta/fileManagerRuntime.js
- https://projects.sappharad.com/s3air_ios/20240202_beta/react.js

For your cOnVeNiEnCe, so you don't have to manually ctrl+c, ctrl+v the filenames into the url
