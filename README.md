# How to Set Up Heart Rate Monitor for Streaming without a smartphone?

HypeRate Web Bluetooth Connection
HypeRate Web Bluetooth is the world’s first web application that enables you to stream your heart rate on any live streaming platform without the need for a smartphone.

Pair your heart rate monitor with our Web Bluetooth application right in your browser, and start streaming in less than 20 seconds!

Works with all heart rate monitors with BLE support!

How does it work?
1. Put on your heart rate monitor
2. Open Chrome Browser
3. Activate Bluetooth
4. Connect
5. Copy Link to Streaming Software like OBS

All heart rate monitors that support BLE can connect. This includes most Chest Steps, Armbands, and Wrist Bands mostly used for fitness training. This includes Polar H10, COOSPO H808s, and many, many more!

Note: You still need the HypeRate app (regardless if you are using the iOS / Android / WearOS / WatchOS version) since the Unity plugin uses our Websocket API and DOES NOT use bluetooth for that.
And you need an API token before you can access the Websocket API via the Unity plugin. You can request your own here at https://www.hyperate.io/api-free-request
What version of Unity are you using: Unity Hub 3.4.1

**Important Note**: 
With this approach, you can only get BPM for the heart rate, you cannot get Heart Rate Variability (HRV) or Inter-beat Interval (IBI) data for Research Development


Links:
* WEbBLE: https://www.hyperate.io/webbluetooth
* https://www.hyperate.io
* https://app.hyperate.io/anCHqpX
* https://www.hyperate.io/supported-devices
* https://github.com/braincomputingsantosh/VRCOSC
* https://github.com/TheLostLion/OSC-Pulse
* https://github.com/200Tigersbloxed/HRtoVRChat_OSC
* https://github.com/Sonic853/HypeRate-to-VRChat-OSC
* https://github.com/VolcanicArts/VRCHypeRate

Unity Asset: https://assetstore.unity.com/packages/tools/input-management/heart-rate-plugin-for-hyperate-212796

Sample Video:

https://github.com/braincomputingsantosh/hrv-unity-plugin/assets/19161376/3764f20e-864b-42bc-9ea4-927f6e03afbc

