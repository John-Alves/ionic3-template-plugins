# ionic3-template-plugins
Ionic 3 template with some usefull plugins already installed.


## Background Mode considerations
The cordova-plugin-background-mode has some problems in windows-sdk that brokes all plugin. To solve just run:

`ionic cordova plugin add https://github.com/sercatven/cordova-plugin-background-mode.git`

`npm install --save @ionic-native/background-mode@4`

_References:_

1. https://github.com/katzer/cordova-plugin-background-mode/issues/441
2. https://github.com/sercatven/cordova-plugin-background-mode
3. https://ionicframework.com/docs/v3/native/background-mode/
