title: com.mschlauch.comfortreader

# com.mschlauch.comfortreader

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
java.lang.RuntimeException
	at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:2416)
	at android.app.ActivityThread.handleLaunchActivity(ActivityThread.java:2476)
	at android.app.ActivityThread.-wrap11(ActivityThread.java)
	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
	at android.os.Handler.dispatchMessage(Handler.java:102)
	at android.os.Looper.loop(Looper.java:148)
	at android.app.ActivityThread.main(ActivityThread.java:5417)
	at java.lang.reflect.Method.invoke(Native Method)
	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
Caused by: java.lang.StringIndexOutOfBoundsException
	at java.lang.String.startEndAndLength(String.java:298)
	at java.lang.String.substring(String.java:1087)
	at com.mschlauch.comfortreader.SettingsLoader.getCurrentNotesFilePath(SettingsLoader.java:317)
	at com.mschlauch.comfortreader.SettingsLoader.getCurrentNotes(SettingsLoader.java:301)
	at com.mschlauch.comfortreader.NoteActivity.onCreate(NoteActivity.java:76)
	at android.app.Activity.performCreate(Activity.java:6251)
	at android.app.Instrumentation.callActivityOnCreate(Instrumentation.java:1107)
	at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:2369)
	... 9 more

```



