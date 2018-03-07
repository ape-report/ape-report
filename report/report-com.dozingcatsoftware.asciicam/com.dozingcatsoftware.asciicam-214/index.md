title: com.dozingcatsoftware.asciicam

# com.dozingcatsoftware.asciicam

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.RuntimeException: Unable to resume activity {com.dozingcatsoftware.asciicam/com.dozingcatsoftware.asciicam.LibraryActivity}: java.lang.RuntimeException: Failure delivering result ResultInfo{who=null, request=0, result=1, data=null} to activity {com.dozingcatsoftware.asciicam/com.dozingcatsoftware.asciicam.LibraryActivity}: java.lang.IndexOutOfBoundsException: Invalid index 0, size is 0
// 	at android.app.ActivityThread.performResumeActivity(ActivityThread.java:3103)
// 	at android.app.ActivityThread.handleResumeActivity(ActivityThread.java:3134)
// 	at android.app.ActivityThread.handleLaunchActivity(ActivityThread.java:2481)
// 	at android.app.ActivityThread.handleRelaunchActivity(ActivityThread.java:4077)
// 	at android.app.ActivityThread.-wrap15(ActivityThread.java)
// 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1350)
// 	at android.os.Handler.dispatchMessage(Handler.java:102)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
// Caused by: java.lang.RuntimeException: Failure delivering result ResultInfo{who=null, request=0, result=1, data=null} to activity {com.dozingcatsoftware.asciicam/com.dozingcatsoftware.asciicam.LibraryActivity}: java.lang.IndexOutOfBoundsException: Invalid index 0, size is 0
// 	at android.app.ActivityThread.deliverResults(ActivityThread.java:3699)
// 	at android.app.ActivityThread.performResumeActivity(ActivityThread.java:3089)
// 	... 11 more
// Caused by: java.lang.IndexOutOfBoundsException: Invalid index 0, size is 0
// 	at java.util.ArrayList.throwIndexOutOfBoundsException(ArrayList.java:255)
// 	at java.util.ArrayList.get(ArrayList.java:308)
// 	at com.dozingcatsoftware.asciicam.LibraryActivity.onActivityResult(LibraryActivity.java:124)
// 	at android.app.Activity.dispatchActivityResult(Activity.java:6456)
// 	at android.app.ActivityThread.deliverResults(ActivityThread.java:3695)
// 	... 12 more

```



