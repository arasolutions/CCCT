# CCCT : Cordova/Capacitor Comparaison Table

- Ionic : 5.0.5
- Capacitor : 1.5.1
- Cordova IOS : 5.1.1
- Cordova Android : 8.1.0

## General
|  Purpose | Cordova | Capacitor | Comment |
| -------------------- |:-----------:|:---------:| -------------------------------------------- |
| Starter  | :white_check_mark: | :white_check_mark::small_orange_diamond: | :small_orange_diamond:Compile with Capacitor but some plugins/code are useless (seen on conference app stater)|
| AppFlow Integration | :white_check_mark: | :white_check_mark: ||
| Icon & Splash | :white_check_mark: |  :white_check_mark::small_orange_diamond: |:small_orange_diamond:OK but you have to import icons and splashscreen in the native project|

## Plugins
:blue_heart: : included in capacitor core
|  Purpose | Cordova | Capacitor | Comment |
| -------------------- |:-----------:|:---------:| -------------------------------------------- |
| Splashscreen  | :white_check_mark: | :blue_heart: | |
| Camera  | :white_check_mark::small_orange_diamond: | :white_check_mark: | :small_orange_diamond: Need to import webview plugin in order to user convertFileSrc function to convert file:// |
| AdMob Free | :white_check_mark: | TODO | |

:white_check_mark:
:x:
:small_orange_diamond:
