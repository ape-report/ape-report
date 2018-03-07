title: net.alegen.android.netclip

# net.alegen.android.netclip

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
java.lang.IllegalStateException
	at android.app.FragmentManagerImpl.saveAllState(FragmentManager.java:1790)
	at android.app.FragmentController.saveAllState(FragmentController.java:112)
	at android.app.Activity.onSaveInstanceState(Activity.java:1373)
	at android.support.v4.app.FragmentActivity.onSaveInstanceState(FragmentActivity.java:522)
	at android.app.Activity.performSaveInstanceState(Activity.java:1302)
	at android.app.Instrumentation.callActivityOnSaveInstanceState(Instrumentation.java:1289)
	at android.app.ActivityThread.callCallActivityOnSaveInstanceState(ActivityThread.java:4088)
	at android.app.ActivityThread.handleRelaunchActivity(ActivityThread.java:4050)
	at android.app.ActivityThread.-wrap15(ActivityThread.java)
	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1350)
	at android.os.Handler.dispatchMessage(Handler.java:102)
	at android.os.Looper.loop(Looper.java:148)
	at android.app.ActivityThread.main(ActivityThread.java:5417)
	at java.lang.reflect.Method.invoke(Native Method)
	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)

```



