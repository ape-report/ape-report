title: click.dummer.funphonepuppet

# click.dummer.funphonepuppet

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.OutOfMemoryError: Failed to allocate a 5760012 byte allocation with 5671272 free bytes and 5MB until OOM
// 	at dalvik.system.VMRuntime.newNonMovableArray(Native Method)
// 	at android.graphics.BitmapFactory.nativeDecodeStream(Native Method)
// 	at android.graphics.BitmapFactory.decodeStreamInternal(BitmapFactory.java:635)
// 	at android.graphics.BitmapFactory.decodeStream(BitmapFactory.java:611)
// 	at android.graphics.BitmapFactory.decodeFile(BitmapFactory.java:391)
// 	at android.graphics.BitmapFactory.decodeFile(BitmapFactory.java:417)
// 	at click.dummer.funphonepuppet.FaceActivity.loadBitmaps(FaceActivity.java:180)
// 	at click.dummer.funphonepuppet.FaceActivity.onCreate(FaceActivity.java:85)
// 	at android.app.Activity.performCreate(Activity.java:6251)
// 	at android.app.Instrumentation.callActivityOnCreate(Instrumentation.java:1107)
// 	at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:2369)
// 	at android.app.ActivityThread.handleLaunchActivity(ActivityThread.java:2476)
// 	at android.app.ActivityThread.handleRelaunchActivity(ActivityThread.java:4077)
// 	at android.app.ActivityThread.-wrap15(ActivityThread.java)
// 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1350)
// 	at android.os.Handler.dispatchMessage(Handler.java:102)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)

```



