title: com.danielkim.soundrecorder

# com.danielkim.soundrecorder

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.NullPointerException: Attempt to invoke virtual method 'void android.media.MediaPlayer.pause()' on a null object reference
// 	at com.danielkim.soundrecorder.fragments.PlaybackFragment.pausePlaying(PlaybackFragment.java:270)
// 	at com.danielkim.soundrecorder.fragments.PlaybackFragment.onPlay(PlaybackFragment.java:205)
// 	at com.danielkim.soundrecorder.fragments.PlaybackFragment.access$700(PlaybackFragment.java:29)
// 	at com.danielkim.soundrecorder.fragments.PlaybackFragment$2.onClick(PlaybackFragment.java:144)
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



