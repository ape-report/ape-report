title: com.icechen1.notable.pro

# com.icechen1.notable.pro

```
java.lang.RuntimeException
	at android.app.ActivityThread.performStopActivityInner(ActivityThread.java:3500)
	at android.app.ActivityThread.handleWindowVisibility(ActivityThread.java:3592)
	at android.app.ActivityThread.-wrap24(ActivityThread.java)
	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1383)
	at android.os.Handler.dispatchMessage(Handler.java:102)
	at android.os.Looper.loop(Looper.java:148)
	at android.app.ActivityThread.main(ActivityThread.java:5417)
	at java.lang.reflect.Method.invoke(Native Method)
	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
Caused by: java.lang.IllegalArgumentException
	at android.app.LoadedApk.forgetReceiverDispatcher(LoadedApk.java:780)
	at android.app.ContextImpl.unregisterReceiver(ContextImpl.java:1195)
	at android.content.ContextWrapper.unregisterReceiver(ContextWrapper.java:576)
	at com.icechen1.notable.library.HistoryActivity.onStop(Unknown Source)
	at android.app.Instrumentation.callActivityOnStop(Instrumentation.java:1278)
	at android.app.Activity.performStop(Activity.java:6395)
	at android.app.ActivityThread.performStopActivityInner(ActivityThread.java:3497)
	... 9 more

```



