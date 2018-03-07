title: com.simplemobiletools.camera

# com.simplemobiletools.camera

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.RuntimeException: setParameters failed
// 	at android.hardware.Camera.native_setParameters(Native Method)
// 	at android.hardware.Camera.setParameters(Camera.java:1878)
// 	at com.simplemobiletools.camera.d.b.h(SourceFile:582)
// 	at com.simplemobiletools.camera.activities.MainActivity.D(SourceFile:270)
// 	at com.simplemobiletools.camera.activities.MainActivity.K(SourceFile:354)
// 	at com.simplemobiletools.camera.activities.MainActivity.j(SourceFile:34)
// 	at com.simplemobiletools.camera.activities.MainActivity$a.a(SourceFile:336)
// 	at com.simplemobiletools.camera.activities.MainActivity$a.a(SourceFile:34)
// 	at com.simplemobiletools.commons.activities.a.a(SourceFile:231)
// 	at com.simplemobiletools.camera.activities.MainActivity.J(SourceFile:334)
// 	at com.simplemobiletools.camera.activities.MainActivity.h(SourceFile:34)
// 	at com.simplemobiletools.camera.activities.MainActivity$g.onClick(SourceFile:216)
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



