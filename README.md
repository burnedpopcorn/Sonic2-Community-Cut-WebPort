# Sonic 2 Communty's Cut Web Port

Demo Site of This Project: https://sonicwebports.x10.mx/sonic2cc/index.html

### About Repository
I did not compile this myself, instead I stole it from HeyJoeWay's website
> (This was after the site shutdown, so I had to use the Wayback Machine to get it)

Currently, this port has a similar situation to my Sonic 3 A.I.R. re-upload, so you will have to do the same work-around as that project

### Thanks To
- HeyJoeWay, for the original Sonic 2 Community's Cut [Project](https://github.com/heyjoeway/s2cx) and now somewhat defunct [Website](https://jojudge.com/s2cx/)
- bitdruid, for the [Wayback Machine Downloader](https://github.com/bitdruid/python-wayback-machine-downloader)

### To Run this yourself
- Get the files from this repo (Code -> Download ZIP)
- Put the files in a web server (Because this was made with Emscripten, it CANNOT be run locally with the file:// protocol, as that results in CORS issues because of Emscripten Limitations)
- Open RSDKv5.html from within your website (https:// (your domain) /RSDKv5.html)

> Or you could place all the files into the root of your github.io repo and host it through github.io pages

### To run this Locally
If you want to run this locally, use something like python to run a temporary web server on your machine

To do this using Python, you do by
- Again, Get the files from this repo (Code -> Download ZIP)
- Entering the directory containing RSDKv5.html and other files and typing the command python3 -m http.server in the linux terminal or py -m http.server for windows powershell given you installed python
- At which point you can enter http://localhost:8000/RSDKv5.html to play the game locally
