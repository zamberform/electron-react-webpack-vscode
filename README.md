# electron-react-webpack-vscode
Try this Electron/React/Webpack2 template for a quick development and prototyping with vscode.

## Install
``` bash
# Clone the repository
$ git clone https://github.com/zamberform/electron-react-webpack-vscode

# Go into the repository
$ cd electron-react-webpack-vscode

# Install dependencies
$ npm install
```

## Usage
Run in VSCode to start Launch&Attach Electron process
``` bash
# Webpack task in task.json

# Launch with launch.json by Debug mode

```

## What's included
- JSX support for React using Babel.
- ES6 native support for React via Node (this is Electron, no need for Babel to transpile ES6).
- CSS modules support.
- JS, CSS and assets bundling with hot reloading via Webpack 2.


## Folder structure
```
├── electron-react-webpack-vscode/             # Your project's name

    ├── .vscode/

        ├── launch.json                    # VSCode launch Control

        ├── tasks.json                    # Webpack 2 control build

    ├── app/

        ├── build/                      # Webpack 2 will create and update this folder
            ├── bundle.css              # Bundled CSS
            ├── bundle.js               # Bundled JS
            ├── ...                     # Your images will be copied here

        ├── src/

            ├── assets/                 # Images
                ├── electron.png
                ├── react.png
                ├── webpack.png

            ├── components/             # React Components
                ├── Link.jsx
                ├── Logo.jsx

            ├── styles/                 
                ├── Local.css           # Local CSS
                ├── Global.css          # Global CSS and constants

            ├── App.jsx                 # React main component
            ├── entry.js                # App entry. Your global JS can go here

        ├── index.html                  # Single Page Application HTML, it only uses build's files

    ├── main.js                         # Electron app
    ├── package.json
    ├── webpack.config.js               # Webpack 2 setup
```

## Related
- [electron-react-webpack](https://github.com/pastahito/electron-react-webpack) -
Minimal Electron template using Webpack 2.
- [electron-vue-webpack](https://github.com/pastahito/electron-vue-webpack) -
Minimal Electron template using Vue 2 instead of React.
