# Climate Kids Nigeria

A simple child-friendly climate change education Progressive Web App (PWA).

## Features
- Six climate lessons with Nigeria-focused examples
- English, Hausa, Yoruba and Igbo interface/content
- 5-question quiz with saved score
- Climate action checklist
- Read-aloud using the browser speech API when available
- Local progress using browser localStorage
- Service worker for offline use after the app is loaded online
- Installable as a PWA on supported browsers

## Run locally
Use a local web server (not file://), for example:

Python:
python -m http.server 8000

Then open:
http://localhost:8000

## Put online
Upload the whole folder to a site that serves HTTPS. Then open it in a supported browser and use the browser's install/add-to-home-screen option.

## Android APK
This starter is deliberately dependency-free. Once the web version is working, it can be packaged as an Android app using a web-to-native wrapper such as Capacitor, or rebuilt in Flutter/React Native.
