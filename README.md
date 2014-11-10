CordovaSocketDemo
=================

A socket client demo for Cordova


##Dependence##

1. [cdv-socket-plugin](https://github.com/Tlantic/cdv-socket-plugin)

2. [cordova](http://cordova.apache.org/) (3.5 or above)


##How To##
1. install cordova:
```
npm install -g cordova
```
2. add platform:
```
cordova platform add ios
```
3. re-install plugin:
```
cordova plugin rm com.tlantic.plugins.socket
cordova plugin add com.tlantic.plugins.socket
```
4. build platform:
```
cordova build ios
```
(replace `ios` with `android` if your target platform is Android)
