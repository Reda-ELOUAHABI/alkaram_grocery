# flutter_grocery

A new Flutter application.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.


https://docs.6amtech.com/docs-grofresh/mobile-apps/mandatory-setup/
https://codecanyon.net/item/grofresh-grocery-pharmacy-ecommerce-store-app-and-web-with-laravel-admin-panel-delivery-app/32791631


steps:

change color, app_icon add icon language, add .json language, add it to the language list, .. se git for others ,,
https://docs.flutter.dev/deployment/android
then use https://www.appicon.co/ for the mimmap , replace it and add to drawable the same icon size with the same name, the size is already included to the mimap.
now the time for the keystore:
using powershell admin mode run: ( and you will find it in the C: directory)
keytool -genkey -v -keystore \upload-keystore.jks -storetype JKS -keyalg RSA -keysize 2048 -validity 10000   -alias upload

password alkaram
don't forget to put your upload-keystore into android/app even you put storeFile=upload-keystore.jks in the key-property
flutter clean (to apply gradle updates)
flutter build appbundle

build apk:
flutter build apk
flutter build apk --no-shrink
publish new version code:
https://stackoverflow.com/questions/53570575/flutter-upgrade-the-version-code-for-play-store
update packages : flutter upgrade
install packages: flutter pub get
Update Android Target SDK: Check and update the targetSdkVersion in your android/app/build.gradle file to the latest SDK version recommended by Google. This ensures compatibility with the latest Android versions.


IOS:
https://www.linkedin.com/pulse/publishing-flutter-app-apple-store-yogesh-aswar/
https://docs.flutter.dev/deployment/ios



hay feta7
mohim rah ma3titekx dak nhar le prix final, kanat une estimation de la tache puisque bghiti une idee,
mais apres fach cheft la demande exact, w zidt la langue francais, et srtt kano 2 projet et machi une seul (2Apps),
w fixit les bugs li kano fhad lprojet avec la config et tt, donc c'etait pas simple.

anyway daba rah generite the first bundle, w rah ready to get upload on play store.

rah ghadi nehsseb likom 1200dh 3la les modifs et l'upload des deux app sur les play store.
(app store nchofo apres si tout marche bien andirolo chi taman mezyan pour les deux app).

###########ANDROID################
Name of Given App: Alkaram Viandes yak ?
Short Description (Few Lines)
Long Description (It will be a detailed description)
Screenshots (2-8 li bghiti ybano)
Icon (size 512 W x 512 H) : hadi 3andi
Banner (size 1024 W x 500 H)
Privacy Policy (wila 3andek)
Category Name
App tags/keywords
Contains ADD (YES OR NO) : No yak ?
Targeting Audience 0-18+: ndiro men +13 wla meme +0 ?
btw, since you account hasn't any previous apps, darouri tdouz men test, but anchouf if I can publish it to production also in the same time
******************
Name of Given App
Short Description (Few Lines)
Long Description (It will be a detailed description)
App Screenshots(if you have, else I will create by myself on the simulator or emulator)
Banner (size 1024 W x 500 H)
Release Apk (signed APK)
Privacy Policy (If it is there)
App tags/keywords
Bug-free iOS app source code.
Login Credentials (If login exist)

#########IOS#############
 Requirements (iOS):
Name of Given App
Description
Promotional Text
Keywords
Support URL
Copyright
Screenshot
age group
Does it contain Ads?
Privacy URL
Primary Language
Category
Login Credentials (If login exist)
*************
Apple Developer Account Credentials
App Name
App Icon (1024x1024)
App Screenshots(if you have, else I will create by myself on the simulator)
App Description
App tags/keywords
Support URL
Privacy URL
Bug-free iOS app source code.
*******ANOTHER ONE
App name
App description
Support URL
Privacy Policy URL
Your phone number with country code to put in app store
Your paid apple developer account credentials
iPhone app screenshots (1242 × 2208) (minimum 3 screen shots)
iPhone X app screenshots (1242 ×2688) (minimum 3 screen shots)
iPad app screenshots (2048 × 2732) (minimum 3 screen shots
***********************
Name of Given App
Description
Keywords
CopyRight
Screenshot
short description
Long Description (It will be a detailed description)
age group
Does it contain Ads
Privacy URL
Primary Language
Category
Login Credentials (If login exist)

https://github.com/Reda-ELOUAHABI/Cplusplus-cpp-multidimentional_array/blob/master/privacy_policy.md
