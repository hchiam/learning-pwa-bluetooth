# Learning PWA Bluetooth

Just one of the things I'm learning. <https://github.com/hchiam/learning>

You can easily connect a web app to an external bluetooth/NFC/USB/etc device. No need for a separate code base for Android/iOS/etc.

<https://youtu.be/ppwagkhrZJs?t=219>

<https://github.com/fireship-io/7-pwa-features-demo>

<https://github.com/fireship-io/7-pwa-features-demo/blob/main/app/bluetooth.js>

BLE Peripheral Simulator: <https://play.google.com/store/apps/details?id=io.github.webbluetoothcg.bletestperipheral&hl=en_CA&gl=US>

```bash
npx serve
```

Then:

1. http://localhost:5000
2. In your browser, click on "Connect Device" and select your mobile device.
3. In the BLE app, click on "Heart Rate Monitor" and then "NOTIFY" to see `console.log`s in the paired browser.
