title: im.r_c.android.jigsaw

# im.r_c.android.jigsaw

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
java.lang.RuntimeException
	at android.app.ActivityThread.performDestroyActivity(ActivityThread.java:3831)
	at android.app.ActivityThread.handleDestroyActivity(ActivityThread.java:3849)
	at android.app.ActivityThread.-wrap5(ActivityThread.java)
	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1398)
	at android.os.Handler.dispatchMessage(Handler.java:102)
	at android.os.Looper.loop(Looper.java:148)
	at android.app.ActivityThread.main(ActivityThread.java:5417)
	at java.lang.reflect.Method.invoke(Native Method)
	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
Caused by: java.lang.IllegalArgumentException
	at me.drakeet.mailotto.Mailbox.leave(Mailbox.java:126)
	at im.r_c.android.jigsaw.activity.GameActivity.onDestroy(GameActivity.java:85)
	at android.app.Activity.performDestroy(Activity.java:6422)
	at android.app.Instrumentation.callActivityOnDestroy(Instrumentation.java:1142)
	at android.app.ActivityThread.performDestroyActivity(ActivityThread.java:3818)
	... 9 more

```



