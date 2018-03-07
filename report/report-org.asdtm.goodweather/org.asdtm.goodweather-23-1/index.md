title: org.asdtm.goodweather

# org.asdtm.goodweather

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
java.lang.IllegalArgumentException
	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
	at android.app.Dialog.dismissDialog(Dialog.java:362)
	at android.app.Dialog.dismiss(Dialog.java:345)
	at android.app.Dialog.cancel(Dialog.java:1199)
	at org.asdtm.goodweather.MainActivity$1.onLocationChanged(Unknown Source)
	at android.location.LocationManager$ListenerTransport._handleMessage(LocationManager.java:285)
	at android.location.LocationManager$ListenerTransport.-wrap0(LocationManager.java)
	at android.location.LocationManager$ListenerTransport$2.handleMessage(LocationManager.java:237)
	at android.os.Handler.dispatchMessage(Handler.java:102)
	at android.os.Looper.loop(Looper.java:148)
	at android.app.ActivityThread.main(ActivityThread.java:5417)
	at java.lang.reflect.Method.invoke(Native Method)
	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)

```



