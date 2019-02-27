# elm-seed

_yaes_ - yet another elm seed...

compile, run and build your elm spa without any bundler only using the elm compiler, uglify-js and the packages rimraf and copyfiles... thats it.

For development the packages watch and live-server allow for watching file changes and automatically reload everything in your browser.

## Usage

While developing run `npm start` to start a server and watch for changes.

To build for production run `npm run build` - that's it.

## FAQ:

Q: Why don't you use elm-live?
A: live-server allows multiple proxy configurations while elm-live only allows a single one... that's all.
