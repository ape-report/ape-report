title: com.vrem.wifianalyzer

# com.vrem.wifianalyzer

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.IllegalStateException: Fragment has not been attached yet.
// 	at android.support.v4.a.h.C(Unknown Source)
// 	at android.support.v4.a.h.h(Unknown Source)
// 	at android.support.v4.a.i.a(Unknown Source)
// 	at android.support.v4.a.i.onSaveInstanceState(Unknown Source)
// 	at android.support.v7.app.e.onSaveInstanceState(Unknown Source)
// 	at android.app.Activity.performSaveInstanceState(Activity.java:1302)
// 	at android.app.Instrumentation.callActivityOnSaveInstanceState(Instrumentation.java:1289)
// 	at android.app.ActivityThread.callCallActivityOnSaveInstanceState(ActivityThread.java:4088)
// 	at android.app.ActivityThread.performStopActivityInner(ActivityThread.java:3490)
// 	at android.app.ActivityThread.handleStopActivity(ActivityThread.java:3550)
// 	at android.app.ActivityThread.-wrap20(ActivityThread.java)
// 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1373)
// 	at android.os.Handler.dispatchMessage(Handler.java:102)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)

```



