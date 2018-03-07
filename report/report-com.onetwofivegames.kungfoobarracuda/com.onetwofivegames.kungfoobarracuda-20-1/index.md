title: com.onetwofivegames.kungfoobarracuda

# com.onetwofivegames.kungfoobarracuda

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.RuntimeException: Unable to destroy activity {com.nightonke.cocoin/com.nightonke.saver.activity.ShowActivity}: java.lang.NullPointerException: Attempt to invoke virtual method 'void com.nightonke.saver.fragment.PasswordChangeFragment.onDestroy()' on a null object reference
// 	at android.app.ActivityThread.performDestroyActivity(ActivityThread.java:3831)
// 	at android.app.ActivityThread.handleDestroyActivity(ActivityThread.java:3849)
// 	at android.app.ActivityThread.handleRelaunchActivity(ActivityThread.java:4053)
// 	at android.app.ActivityThread.-wrap15(ActivityThread.java)
// 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1350)
// 	at android.os.Handler.dispatchMessage(Handler.java:102)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
// Caused by: java.lang.NullPointerException: Attempt to invoke virtual method 'void com.nightonke.saver.fragment.PasswordChangeFragment.onDestroy()' on a null object reference
// 	at com.nightonke.saver.activity.ShowActivity.onDestroy(ShowActivity.java:558)
// 	at android.app.Activity.performDestroy(Activity.java:6422)
// 	at android.app.Instrumentation.callActivityOnDestroy(Instrumentation.java:1142)
// 	at android.app.ActivityThread.performDestroyActivity(ActivityThread.java:3818)
// 	... 10 more

```



