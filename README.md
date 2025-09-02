# Yggdrasil Essence for Electron-builder

Copyright © 2025 [Yggdrasil Leaves, LLC.](https://yggdrasil-leaves.com)

## What's it?

These are useful extra features on Electron.  
You can select source files under your wish from this solution and copy freely.  

## Need a Help?

But we'll not help you:-P

## Documentation

see [web version](https://github.com/ylllc/yges_js_web)  

## Required Packages

see package.json  
and update them.
```
$ npm update
```

### for Windows

Can one touch installing with setup.bat

## Build to an Application

```
$ npm run make
```

see dist/win-unpacked/  
and run YggdrasilEssenseExamples

### for Windows

Can one touch building with build.bat  
** (Administrator privilage requred) **  

not Administrator, will happen an error  
```
errorOut=ERROR: Cannot create symbolic link  
```
can ignore, build operation is done  
see dist/win-unpacked/  
and can run YggdrasilEssenseExamples

otherwise, put winCodeSign package to workingDir in manually   
```
workingDir=%USERPROFILE%\AppData\Local\electron-builder\Cache\winCodeSign
```
and see downloading log  
```
downloading     url=https://github.com/electron-userland/electron-builder-binaries/releases/download/winCodeSign-2.6.0/winCodeSign-2.6.0.7z
```
extract it, and put winCodeSign-2.6.0 to workingDir  


## Tips

### Show Packaged Files

package.json

```
  "build": {
    "asar": false,
  },
```

build and see dist/win-unpacked/resources/app/  
(for debug, and not recommended for release)  
