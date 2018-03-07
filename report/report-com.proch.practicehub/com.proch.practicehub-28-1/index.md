title: com.proch.practicehub

# com.proch.practicehub

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
java.lang.IllegalStateException
	at android.media.AudioTrack.play(AudioTrack.java:1574)
	at com.proch.practicehub.Drone$PitchGenerator.<init>(Drone.java:51)
	at com.proch.practicehub.Drone.playPitch(Drone.java:22)
	at com.proch.practicehub.Drone.playPitch(Drone.java:29)
	at com.proch.practicehub.DroneScreen.toggleDrone(DroneScreen.java:110)
	at com.proch.practicehub.DroneScreen$1.onClick(DroneScreen.java:86)
	at android.view.View.performClick(View.java:5204)
	at android.view.View$PerformClick.run(View.java:21153)
	at android.os.Handler.handleCallback(Handler.java:739)
	at android.os.Handler.dispatchMessage(Handler.java:95)
	at android.os.Looper.loop(Looper.java:148)
	at android.app.ActivityThread.main(ActivityThread.java:5417)
	at java.lang.reflect.Method.invoke(Native Method)
	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)

```



