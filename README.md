"monkeyPatch.folderMap": {
    "my-custom-modules" : "~/custom-modules",
},
"monkeyPatch.browserModules": [
    // Will load "~/custom-modules/browser1.js" in browser process
    "my-custom-modules/browser1"
],
"monkeyPatch.mainProcessModules" : [
    // Will load "~/custom-modules/mainProcess.js" in main process
    "my-custom-modules/mainProcess1"
]
