It is a fork from [https://github.com/jeromeetienne/threejs-inspector]

# Three.js Inspector
three.js inspector is an extension for chrome devtool. It allows you to inspect the three.js scene in a web page. 
You can install from only locally.

## How to be sure the extension find your scene
- export your THREE.Scene as a `scene` global variable
  - typically `window.scene = scene;` 
- export THREE as a ```THREE``` global variable when using module bundler
  - typically `window.THREE = THREE`
- press 'refresh' button to refresh the scene

YES we are looking for a better way to do it :)

## How to install three.js inspector locally

copy the repo files to your computer and launch the extension as a developer.
Follow those steps:

- download the lastest version - [Download](https://github.com/gyuha/threejs-inspector/releases)
- unpack the file.
- Goto the Chrome's Extensions page : Settings -> More tools -> Extensions
- Enable Developer Mode
- Click on "Load unpacked extension"...
- Select the unpacked folder.
