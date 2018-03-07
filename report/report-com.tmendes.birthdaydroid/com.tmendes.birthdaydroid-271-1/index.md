title: com.tmendes.birthdaydroid

# com.tmendes.birthdaydroid

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
java.lang.RuntimeException
	at android.app.ActivityThread.performResumeActivity(ActivityThread.java:3103)
	at android.app.ActivityThread.handleResumeActivity(ActivityThread.java:3134)
	at android.app.ActivityThread.handleLaunchActivity(ActivityThread.java:2481)
	at android.app.ActivityThread.handleRelaunchActivity(ActivityThread.java:4077)
	at android.app.ActivityThread.-wrap15(ActivityThread.java)
	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1350)
	at android.os.Handler.dispatchMessage(Handler.java:102)
	at android.os.Looper.loop(Looper.java:148)
	at android.app.ActivityThread.main(ActivityThread.java:5417)
	at java.lang.reflect.Method.invoke(Native Method)
	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
Caused by: java.lang.IllegalArgumentException
	at android.app.FragmentManagerImpl.moveToState(FragmentManager.java:965)
	at android.app.FragmentManagerImpl.moveToState(FragmentManager.java:1148)
	at android.app.BackStackRecord.run(BackStackRecord.java:793)
	at android.app.FragmentManagerImpl.execPendingActions(FragmentManager.java:1535)
	at android.app.FragmentController.execPendingActions(FragmentController.java:325)
	at android.app.Activity.performResume(Activity.java:6321)
	at android.app.ActivityThread.performResumeActivity(ActivityThread.java:3092)
	... 11 more

```



