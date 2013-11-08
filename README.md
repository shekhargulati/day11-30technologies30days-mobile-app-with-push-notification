## Reader30 -- 30Technologies30Days Reader Mobile Application##

To create mobile follow the steps mentioned below.

1. Create a phonegap app
```
$ phonegap create reader --id io.reader --name Reader30
```

2. Add plugins
```
$ cd reader
$ cordova plugin add org.apache.cordova.geolocation
$ cordova plugin add org.apache.cordova.dialogs
$ cordova plugin add https://github.com/edewit/aerogear-pushplugin-cordova.git
``` 

3. Copy the www folder from https://github.com/shekhargulati/day11-30technologies30days-mobile-app-with-push-notification

4. Run on android app
```
$ phonegap run android
```

 
 
 