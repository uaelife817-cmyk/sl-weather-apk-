# SL WEATHER — Android starter project

A bilingual (Sinhala / English) Android WebView app with:
- Interactive Sri Lanka map (Leaflet + OpenStreetMap)
- City search and live weather via Open-Meteo
- Rain layer via Open-Meteo precipitation data (map markers; not a radar product)
- Sri Lanka Department of Meteorology official website link for warnings

## Build an APK
1. Install Android Studio (current stable) and Android SDK.
2. Open this folder in Android Studio.
3. Let Gradle sync.
4. Build > Build Bundle(s) / APK(s) > Build APK(s).
5. APK is typically at `app/build/outputs/apk/debug/app-debug.apk`.

This is a starter project; I cannot compile/sign an APK in this environment. The project source is provided so you can build the installable APK in Android Studio.

## Notes
- Weather is fetched live from Open-Meteo over the internet.
- Rain display is precipitation intensity at sampled locations, not a live weather-radar mosaic.
- Official warnings are opened from Sri Lanka's Department of Meteorology website; this starter does not claim an unofficial feed is an official API.
- Leaflet and OpenStreetMap tiles require internet access.
