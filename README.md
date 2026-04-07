
[![image](https://img.shields.io/badge/mozilla%20add--on-UNOFFICIAL-orange?style=for-the-badge)](https://addons.mozilla.org/en-US/firefox/addon/shikiplayer-fixed/)

## How to build

## Ахтунг
Билдиться будет только если установлена локально esbuild в node_modules, из за следующих строчек в build.js
```
    const path = require('path');
    const esbuildPath = path.join(__dirname, 'node_modules', '@esbuild', 'win32-x64', 'esbuild.exe');
```
иначе у меня под виндой не работало, замените на оригинальные или под себя, если у вас иначе

### To build extension:
- With VSCode: Run 'Build Extension' or 'Build Release Extension' task.
- With Node: Run 'node build.js extension' or 'node build.js extension --release'.
### To build userscript:
- With VSCode: Run 'Build Userscript' or 'Build Release Userscript' task.
- With Node: Run 'node build.js userscript' or 'node build.js userscript --release'.

You need Node, NPM and ESBuild to be installed in your environment.

> This repo is using [Build.js](https://github.com/qt-kaneko/Build.js), a smol build system.

### Beautiful design:
![image](./assets/screenshots/1.png?raw=true)

### Quick releases:
![image](./assets/screenshots/2.png?raw=true)

### Many voiceovers:
![image](./assets/screenshots/3.png?raw=true)

### High quality:
![image](./assets/screenshots/4.png?raw=true)

### Useful settings:
![image](./assets/screenshots/5.png?raw=true)
