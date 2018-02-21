# electron-telestrator

Creates a window that allows drawing over your screen content.

Hold left mouse to draw.

Right click to clear screen.

## Use with streaming applications

Open a preview window of your streaming output, then run Telestrator and position the screen over the preview window.

In your streaming app, add a 'Window Source' to your scene and select the Telestrator window.

Draw something on the telestrator and reposition the window until the lines match up.

## To Develop

To clone and run this repository you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer. From your command line:

```bash
# Clone this repository
git clone https://github.com/JPTeasdale/electron-telestrator
# Go into the repository
cd electron-telestrator
# Install dependencies
npm install
# Run the app
npm start
```

## To Package

Follow the Electron Packaging instructions: https://electronjs.org/docs/tutorial/application-distribution

Check package.json for the electron version this app is using.

