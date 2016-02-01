# pgdus16

These is a summary of the [PhoneGap Day US 2016](http://pgday.phonegap.com/us2016/) by SAP employee's Marc-Lester Tan, Xiaojun Feng and Marco Eidinger.

The summary can be viewed as static webpage via or you can create your own PhoneGap app.

## Summary in web
[http://marcoeidinger.github.io/pgdus16/](http://marcoeidinger.github.io/pgdus16/)

## How-To: create PhoneGap app for this summary

### Prerequisities

* PhoneGap Desktop App -> (Get Started)[http://docs.phonegap.com/getting-started/1-install-phonegap/desktop/]
  * [Mac Link](https://github.com/phonegap/phonegap-app-desktop/releases/download/0.2.1/PhoneGapDesktop.dmg)
  * [Win Link](https://github.com/phonegap/phonegap-app-desktop/releases/download/0.2.1/PhoneGapSetup-win32.exe)

* PhoneGap CLI

```bash
$ npm install -g phonegap@latest
```

* PhoneGap Developer App installed to your mobile device(s) -> [http://app.phonegap.com/](http://app.phonegap.com/)
  * [Apple AppStore](https://itunes.apple.com/us/app/phonegap-developer/)
  * [Google Play](https://play.google.com/store/apps/details?id=com.adobe.phonegap.app)
  * [Windows Store](https://www.microsoft.com/en-us/store/apps/phonegap-developer/9wzdncrdfsj0)

* Optional but helpful: PhoneGap CLI configured for at least one platform by following the platform guides
  * [Android](http://cordova.apache.org/docs/en/latest/guide/platforms/android/index.html)
  * [iOS](http://cordova.apache.org/docs/en/latest/guide/platforms/ios/index.html)
  * [Windows](http://cordova.apache.org/docs/en/latest/guide/platforms/win8/index.html)

### a) use Phonegap desktop & mobile app or

1. Open Phonega desktop app on your laptop/PC
2. Click + to create a new phonegap project
3. Specify directory where to stor the new phonegap project, give it a name and click 'Create project'
4. Open File Explorer / Finder and navigate to directory of your phonegap project. Replace content of www folder with content of this github repository
5. Open Phonegap mobile app on your phone and enter URL which is shown in Phonegap desktop app
6. Voila, you run this summary as a mobile app :)

### b) use Phonegap CLI & emulator/simulator

```bash
$ phonegap create
```

```bash
$ phonegap create
```

```bash
$ cd www
```

Replace content of www folder with content of this github repository

```bash
$ cd ..
```

Example for iOS:

```bash
$ phonegap run ios
```

### Remarks
The cotent of this github repository was created with the intention to be embedded into a cordova/phonegap application. Even it does not use any plugins the cordova.js file is referenced in index.html
