title: github.daneren2005.dsub

# github.daneren2005.dsub

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
Caused by: java.lang.NullPointerException
	at github.daneren2005.dsub.fragments.SubsonicFragment.setProgressVisible(SubsonicFragment.java:499)
	at github.daneren2005.dsub.util.TabBackgroundTask.execute(TabBackgroundTask.java:20)
	at github.daneren2005.dsub.fragments.SearchFragment.search(SearchFragment.java:200)
	at github.daneren2005.dsub.activity.SubsonicFragmentActivity.onNewIntent(SubsonicFragmentActivity.java:338)
	at android.app.Instrumentation.callActivityOnNewIntent(Instrumentation.java:1212)
	at android.app.Instrumentation.callActivityOnNewIntent(Instrumentation.java:1224)
	at android.app.ActivityThread.deliverNewIntents(ActivityThread.java:2545)
	at android.app.ActivityThread.performResumeActivity(ActivityThread.java:3085)
	... 11 more

```



