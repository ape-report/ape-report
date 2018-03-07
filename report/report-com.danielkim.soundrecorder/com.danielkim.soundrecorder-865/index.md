title: com.danielkim.soundrecorder

# com.danielkim.soundrecorder

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.RuntimeException: Unable to start service com.danielkim.soundrecorder.RecordingService@4a9b62c with Intent { cmp=com.danielkim.soundrecorder/.RecordingService }: java.lang.IllegalStateException
// 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
// 	at android.app.ActivityThread.-wrap17(ActivityThread.java)
// 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
// 	at android.os.Handler.dispatchMessage(Handler.java:102)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
// Caused by: java.lang.IllegalStateException
// 	at android.media.MediaRecorder.start(Native Method)
// 	at com.danielkim.soundrecorder.RecordingService.startRecording(RecordingService.java:96)
// 	at com.danielkim.soundrecorder.RecordingService.onStartCommand(RecordingService.java:67)
// 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3010)
// 	... 8 more

```



