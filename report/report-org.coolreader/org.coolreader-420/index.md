title: org.coolreader

# org.coolreader

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.RuntimeException: Unable to pause activity {org.coolreader/org.coolreader.CoolReader}: java.lang.NullPointerException: Attempt to invoke virtual method 'void org.coolreader.crengine.CoverpageManager.removeCoverpageReadyListener(org.coolreader.crengine.CoverpageManager$CoverpageReadyListener)' on a null object reference
// 	at android.app.ActivityThread.performPauseActivity(ActivityThread.java:3381)
// 	at android.app.ActivityThread.performPauseActivity(ActivityThread.java:3340)
// 	at android.app.ActivityThread.handlePauseActivity(ActivityThread.java:3315)
// 	at android.app.ActivityThread.-wrap13(ActivityThread.java)
// 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1355)
// 	at android.os.Handler.dispatchMessage(Handler.java:102)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
// Caused by: java.lang.NullPointerException: Attempt to invoke virtual method 'void org.coolreader.crengine.CoverpageManager.removeCoverpageReadyListener(org.coolreader.crengine.CoverpageManager$CoverpageReadyListener)' on a null object reference
// 	at org.coolreader.CoolReader.onPause(CoolReader.java:332)
// 	at android.app.Activity.performPause(Activity.java:6363)
// 	at android.app.Instrumentation.callActivityOnPause(Instrumentation.java:1311)
// 	at android.app.ActivityThread.performPauseActivity(ActivityThread.java:3367)
// 	... 10 more

```



