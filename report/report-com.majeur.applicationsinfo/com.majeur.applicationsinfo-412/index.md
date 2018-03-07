title: com.majeur.applicationsinfo

# com.majeur.applicationsinfo

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{d4eb0d1 V.E...... R......D 0,0-1154,348} not attached to window manager
// 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
// 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
// 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
// 	at android.app.Dialog.dismissDialog(Dialog.java:362)
// 	at android.app.Dialog.dismiss(Dialog.java:345)
// 	at com.majeur.applicationsinfo.ViewManifestActivity.showProgressBar(ViewManifestActivity.java:126)
// 	at com.majeur.applicationsinfo.ViewManifestActivity.access$100(ViewManifestActivity.java:47)
// 	at com.majeur.applicationsinfo.ViewManifestActivity$MyWebChromeClient.onProgressChanged(ViewManifestActivity.java:118)
// 	at com.android.webview.chromium.WebViewContentsClientAdapter.onProgressChanged(WebViewContentsClientAdapter.java:45)
// 	at org.chromium.android_webview.AwContentsClientCallbackHelper$MyHandler.handleMessage(AwContentsClientCallbackHelper.java:81)
// 	at android.os.Handler.dispatchMessage(Handler.java:102)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)

```



