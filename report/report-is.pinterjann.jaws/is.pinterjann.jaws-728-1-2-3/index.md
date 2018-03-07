title: is.pinterjann.jaws

# is.pinterjann.jaws

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
java.lang.RuntimeException
	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:891)
	at android.os.Handler.handleCallback(Handler.java:739)
	at android.os.Handler.dispatchMessage(Handler.java:95)
	at android.os.Looper.loop(Looper.java:148)
	at android.app.ActivityThread.main(ActivityThread.java:5417)
	at java.lang.reflect.Method.invoke(Native Method)
	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
Caused by: java.lang.ArrayIndexOutOfBoundsException
	at is.pinterjann.jaws.model.WirelessNetwork.<init>(WirelessNetwork.java:31)
	at is.pinterjann.jaws.activities.JAWSActivity$WifiScanReceiver.onReceive(JAWSActivity.java:218)
	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:881)
	... 7 more

```



