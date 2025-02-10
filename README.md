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

** (Administrator privilage requred) **  
Can one touch building with build.bat

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
