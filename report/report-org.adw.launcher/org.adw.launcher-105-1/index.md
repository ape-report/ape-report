title: org.adw.launcher

# org.adw.launcher

```
java.lang.RuntimeException
	at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:2416)
	at android.app.ActivityThread.handleLaunchActivity(ActivityThread.java:2476)
	at android.app.ActivityThread.-wrap11(ActivityThread.java)
	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
	at android.os.Handler.dispatchMessage(Handler.java:102)
	at android.os.Looper.loop(Looper.java:148)
	at android.app.ActivityThread.main(ActivityThread.java:5417)
	at java.lang.reflect.Method.invoke(Native Method)
	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
Caused by: java.lang.NullPointerException
	at org.adw.launcher.Launcher.showAllApps(Launcher.java:3653)
	at org.adw.launcher.Launcher.fireHomeBinding(Launcher.java:3893)
	at org.adw.launcher.LauncherActions$DefaultLauncherAction.runIntent(LauncherActions.java:192)
	at org.adw.launcher.LauncherActions.launch(LauncherActions.java:81)
	at org.adw.launcher.CustomShirtcutActivity.onCreate(CustomShirtcutActivity.java:103)
	at android.app.Activity.performCreate(Activity.java:6251)
	at android.app.Instrumentation.callActivityOnCreate(Instrumentation.java:1107)
	at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:2369)
	... 9 more

```



