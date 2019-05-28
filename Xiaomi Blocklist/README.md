#Xiaomi or more specifically Redmi devices

All Redmi devices are maufactured by Chinese vendors. And it also has been known that they collect data about you even if you dont give their default system aplications any permissions.
There have been cases reported [[1]](https://forum.xda-developers.com/android/general/xiaomi-sending-users-private-data-t2832695), [[2]].
And many services are specifically run for this purpose, for example - (data.mistat.xiaomi.com), (tracking.miui.com), (data.mistat.india.xiaomi.com), etc.

In order to capture and log data, I used Wireshark and deployed a Man-In-The-Middle Attack through my own WiFI router and then captured it on my PC. Or else you can also use an easier way through an
android application on your device like [Packet Capture](https://play.google.com/store/apps/details?id=app.greyshirts.sslcapture) or root the device and then using ADB (much easier and more reliable).

And then start filtering the captured data and further analyze it.
