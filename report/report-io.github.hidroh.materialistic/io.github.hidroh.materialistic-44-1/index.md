title: io.github.hidroh.materialistic

# io.github.hidroh.materialistic

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
java.lang.IllegalArgumentException
	at android.app.LoadedApk.forgetReceiverDispatcher(LoadedApk.java:780)
	at android.app.ContextImpl.unregisterReceiver(ContextImpl.java:1195)
	at android.content.ContextWrapper.unregisterReceiver(ContextWrapper.java:576)
	at android.content.ContextWrapper.unregisterReceiver(ContextWrapper.java:576)
	at org.chromium.content.browser.accessibility.LollipopWebContentsAccessibility.onDetachedFromWindow(LollipopWebContentsAccessibility.java:42)
	at org.chromium.content.browser.ContentViewCoreImpl.onDetachedFromWindow(ContentViewCoreImpl.java:321)
	at org.chromium.android_webview.AwContents$AwViewMethodsImpl.onDetachedFromWindow(AwContents.java:361)
	at org.chromium.android_webview.AwContents.onDetachedFromWindow(AwContents.java:608)
	at com.android.webview.chromium.WebViewChromium.onDetachedFromWindow(WebViewChromium.java:802)
	at android.webkit.WebView.onDetachedFromWindowInternal(WebView.java:2317)
	at android.view.View.dispatchDetachedFromWindow(View.java:14562)
	at android.view.ViewGroup.dispatchDetachedFromWindow(ViewGroup.java:3071)
	at android.view.ViewGroup.dispatchDetachedFromWindow(ViewGroup.java:3063)
	at android.view.ViewGroup.dispatchDetachedFromWindow(ViewGroup.java:3063)
	at android.view.ViewGroup.removeViewInternal(ViewGroup.java:4603)
	at android.view.ViewGroup.removeViewInternal(ViewGroup.java:4576)
	at android.view.ViewGroup.removeView(ViewGroup.java:4507)
	at io.github.hidroh.materialistic.WebFragment.setFullscreen(WebFragment.java:520)
	at io.github.hidroh.materialistic.WebFragment$1.onReceive(WebFragment.java:94)
	at android.support.v4.content.LocalBroadcastManager.executePendingBroadcasts(LocalBroadcastManager.java:311)
	at android.support.v4.content.LocalBroadcastManager.access$000(LocalBroadcastManager.java:47)
	at android.support.v4.content.LocalBroadcastManager$1.handleMessage(LocalBroadcastManager.java:120)
	at android.os.Handler.dispatchMessage(Handler.java:102)
	at android.os.Looper.loop(Looper.java:148)
	at android.app.ActivityThread.main(ActivityThread.java:5417)
	at java.lang.reflect.Method.invoke(Native Method)
	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)

```



