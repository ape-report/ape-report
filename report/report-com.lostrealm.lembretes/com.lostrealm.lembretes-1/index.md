title: com.lostrealm.lembretes

# com.lostrealm.lembretes

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String com.lostrealm.lembretes.Meal.getText()' on a null object reference
// 	at com.lostrealm.lembretes.MainActivity.updateViews(MainActivity.java:98)
// 	at com.lostrealm.lembretes.MainActivity.access$100(MainActivity.java:37)
// 	at com.lostrealm.lembretes.MainActivity$1.onReceive(MainActivity.java:92)
// 	at android.support.v4.content.LocalBroadcastManager.executePendingBroadcasts(LocalBroadcastManager.java:297)
// 	at android.support.v4.content.LocalBroadcastManager.access$000(LocalBroadcastManager.java:46)
// 	at android.support.v4.content.LocalBroadcastManager$1.handleMessage(LocalBroadcastManager.java:116)
// 	at android.os.Handler.dispatchMessage(Handler.java:102)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)

```



