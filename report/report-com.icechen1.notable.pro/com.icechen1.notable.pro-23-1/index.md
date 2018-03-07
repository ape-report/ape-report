title: com.icechen1.notable.pro

# com.icechen1.notable.pro

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
Caused by: java.lang.IllegalArgumentException
	at android.database.AbstractCursor.getColumnIndexOrThrow(AbstractCursor.java:333)
	at com.icechen1.notable.library.utils.a.b(Unknown Source)
	at com.icechen1.notable.library.utils.a.a(Unknown Source)
	at com.icechen1.notable.library.utils.b.c(Unknown Source)
	at com.icechen1.notable.library.HistoryActivity$1.onReceive(Unknown Source)
	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:881)
	... 7 more

```



