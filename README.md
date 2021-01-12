# Android-screenRTC

## WebRTC Live Streaming

An Android client for [ProjectRTC](https://github.com/pchab/ProjectRTC) supporting screen sharing and is modified from pchab's work [AndroidRTC](https://github.com/pchab/AndroidRTC).

Build with Android Studio 4.1.1. and latest webrtc(org.webrtc:google-webrtc:1.0.32006). The app's minSDKversion is 21.

## How To

You need [ProjectRTC](https://github.com/pchab/ProjectRTC) up and running, and it must be somewhere that your android can access. (You can quickly test this with your android browser). Modify the host string (in res/values/strings.xml) to the server IP.

When you launch the app, you will be given several options to send a message : "Call someone".
Use this menu to send a link of your stream. This link can be opened with a WebRTC-capable browser or by another AndroidRTC.

Your stream should appear as "android_test" in ProjectRTC, so you can also use the call feature there. You may simply click "view" instead of "call" to see the shared screen.

## Libraries

### [libjingle peerconnection](https://code.google.com/p/webrtc/)
### [socket.io-client](https://github.com/nkzawa/socket.io-client.java)
