# Sales God Mode — Android build

## Recommended free route
Use Capacitor + Android Studio.

1. Install Node.js LTS and Android Studio.
2. Open this project folder in a terminal.
3. Run:
   `npm install`
4. Add Android:
   `npx cap add android`
5. Sync:
   `npx cap sync android`
6. Open Android Studio:
   `npx cap open android`
7. Build > Generate Signed Bundle / APK > APK.

The app is designed to work offline; its data is stored in local browser/WebView storage.

## Important
This package is APK-ready scaffolding. An APK file is NOT included because Android SDK/Gradle signing tools are not available in the current build environment.

## Release QA
Before publishing, test:
- app launch/relaunch
- PIN lock/unlock
- add brand/category/product
- purchase batch and FIFO costing
- stock in/out
- sale and negative-stock prevention
- return
- expenses
- date-filtered reports
- CSV export
- printable invoice/report
- backup/restore
- airplane-mode operation
- rotation/background-resume on Android
