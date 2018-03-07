title: com.agateau.catgenerator

# com.agateau.catgenerator

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.NullPointerException: Attempt to invoke virtual method 'android.graphics.Bitmap android.graphics.drawable.BitmapDrawable.getBitmap()' on a null object reference
// 	at com.agateau.catgenerator.MainActivity.saveAvatar(MainActivity.java:145)
// 	at com.agateau.catgenerator.MainActivity.shareAvatar(MainActivity.java:127)
// 	at com.agateau.catgenerator.MainActivity.access$200(MainActivity.java:40)
// 	at com.agateau.catgenerator.MainActivity$2.onClick(MainActivity.java:88)
// 	at android.view.View.performClick(View.java:5204)
// 	at android.view.View$PerformClick.run(View.java:21153)
// 	at android.os.Handler.handleCallback(Handler.java:739)
// 	at android.os.Handler.dispatchMessage(Handler.java:95)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)

```



