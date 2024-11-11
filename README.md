# Animatrix's Zen Config

1. Install "Satoshi" font. https://font.download/font/satoshi
2. Modify userChrome.css with the one in this repo
3. Install sidebery add on
4. Sidebery > import addon data > sidebery.json (in this repo)
5. Install the zen sidebery mod (allow transparency in mod settings)

Gradient config:
#112536
#000
#000
#000
#112536

Rotation: 141 degrees
Texture: ~50%

### For sidebery transparency issues:
1. Remove your existing sidebery addon
2. Drag and drop the provided sidebery.xpi in your add-on page

### If you don't trust it / want to rebuild your own updated version down the line:

1. download sidebery source [https://github.com/mbnuqw/sidebery](https://github.com/mbnuqw/sidebery)
2. change sidebery/src/sidebar/sidebar.html with sidebar.html provided in this repo
3. build it, rename dist/sidebery.zip to dist/sidebery.xpi
