This is a test app demonstrating a bug in contenteditable divs and autocorrect in ios webviews which results in duplicate words. Tested on iOS 8.3. Safari seems fine, it's just webviews which are affected.

This is provided as a cordova app. To run, check out the app and run from app dir:

    npm install -g cordova
    cordova platform add ios
    cordova run ios --device

Follow instructions on page to replicate bug.
