title: wiseguys.radar

# wiseguys.radar

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
java.lang.NullPointerException
	at wiseguys.radar.ui.AboutFragment.onResume(AboutFragment.java:64)
	at android.app.Fragment.performResume(Fragment.java:2263)
	at android.app.FragmentManagerImpl.moveToState(FragmentManager.java:1008)
	at android.app.FragmentManagerImpl.moveToState(FragmentManager.java:1148)
	at android.app.BackStackRecord.run(BackStackRecord.java:793)
	at android.app.FragmentManagerImpl.execPendingActions(FragmentManager.java:1535)
	at android.app.FragmentManagerImpl$1.run(FragmentManager.java:482)
	at android.os.Handler.handleCallback(Handler.java:739)
	at android.os.Handler.dispatchMessage(Handler.java:95)
	at android.os.Looper.loop(Looper.java:148)
	at android.app.ActivityThread.main(ActivityThread.java:5417)
	at java.lang.reflect.Method.invoke(Native Method)
	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)

```



