title: com.alaskalinuxuser.justnotes

# com.alaskalinuxuser.justnotes

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
Caused by: java.lang.RuntimeException
	at android.app.ActivityThread.deliverResults(ActivityThread.java:3699)
	at android.app.ActivityThread.performResumeActivity(ActivityThread.java:3089)
	... 11 more
Caused by: java.lang.NullPointerException
	at com.alaskalinuxuser.justnotes.MainActivity.makeNote(MainActivity.java:395)
	at com.alaskalinuxuser.justnotes.MainActivity.onActivityResult(MainActivity.java:334)
	at android.app.Activity.dispatchActivityResult(Activity.java:6456)
	at android.app.ActivityThread.deliverResults(ActivityThread.java:3695)
	... 12 more

```



