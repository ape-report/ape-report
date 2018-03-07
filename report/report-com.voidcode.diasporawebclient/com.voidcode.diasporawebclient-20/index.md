title: com.voidcode.diasporawebclient

# com.voidcode.diasporawebclient

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.NullPointerException: Attempt to invoke virtual method 'boolean android.app.ProgressDialog.isShowing()' on a null object reference
// 	at com.voidcode.diasporawebclient.MainActivity$2.onPageFinished(MainActivity.java:115)
// 	at com.android.webview.chromium.WebViewContentsClientAdapter.onPageFinished(WebViewContentsClientAdapter.java:224)
// 	at org.chromium.android_webview.AwContentsClientCallbackHelper$MyHandler.handleMessage(AwContentsClientCallbackHelper.java:72)
// 	at android.os.Handler.dispatchMessage(Handler.java:102)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)

```



