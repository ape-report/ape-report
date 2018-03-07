title: com.greenaddress.greenbits_android_wallet

# com.greenaddress.greenbits_android_wallet

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.RuntimeException: Camera is being used after Camera.release() was called
// 	at android.hardware.Camera.setHasPreviewCallback(Native Method)
// 	at android.hardware.Camera.setOneShotPreviewCallback(Camera.java:801)
// 	at de.schildbach.wallet.camera.CameraManager.requestPreviewFrame(CameraManager.java:239)
// 	at de.schildbach.wallet.ui.ScanActivity$5.run(ScanActivity.java:299)
// 	at android.os.Handler.handleCallback(Handler.java:739)
// 	at android.os.Handler.dispatchMessage(Handler.java:95)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.os.HandlerThread.run(HandlerThread.java:61)

```



