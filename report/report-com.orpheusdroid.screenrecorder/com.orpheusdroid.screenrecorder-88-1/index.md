title: com.orpheusdroid.screenrecorder

# com.orpheusdroid.screenrecorder

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
java.lang.RuntimeException
	at android.app.ActivityThread.performDestroyActivity(ActivityThread.java:3795)
	at android.app.ActivityThread.handleDestroyActivity(ActivityThread.java:3849)
	at android.app.ActivityThread.handleRelaunchActivity(ActivityThread.java:4053)
	at android.app.ActivityThread.-wrap15(ActivityThread.java)
	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1350)
	at android.os.Handler.dispatchMessage(Handler.java:102)
	at android.os.Looper.loop(Looper.java:148)
	at android.app.ActivityThread.main(ActivityThread.java:5417)
	at java.lang.reflect.Method.invoke(Native Method)
	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
Caused by: java.lang.IllegalStateException
	at ly.count.android.sdk.Countly.onStop(Countly.java:469)
	at com.orpheusdroid.screenrecorder.MainActivity.onStop(MainActivity.java:420)
	at android.app.Instrumentation.callActivityOnStop(Instrumentation.java:1278)
	at android.app.Activity.performStop(Activity.java:6395)
	at android.app.ActivityThread.performDestroyActivity(ActivityThread.java:3790)
	... 10 more

```



