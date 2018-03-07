title: com.simplemobiletools.camera

# com.simplemobiletools.camera

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
java.lang.RuntimeException
	at android.hardware.Camera.native_setParameters(Native Method)
	at android.hardware.Camera.setParameters(Camera.java:1878)
	at com.simplemobiletools.camera.d.b.q(SourceFile:295)
	at com.simplemobiletools.camera.d.b.h(SourceFile:28)
	at com.simplemobiletools.camera.d.b$c.onAutoFocus(SourceFile:408)
	at android.hardware.Camera$EventHandler.handleMessage(Camera.java:1127)
	at android.os.Handler.dispatchMessage(Handler.java:102)
	at android.os.Looper.loop(Looper.java:148)
	at android.app.ActivityThread.main(ActivityThread.java:5417)
	at java.lang.reflect.Method.invoke(Native Method)
	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)

```



