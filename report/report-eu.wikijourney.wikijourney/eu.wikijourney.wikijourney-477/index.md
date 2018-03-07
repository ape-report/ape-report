title: eu.wikijourney.wikijourney

# eu.wikijourney.wikijourney

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.Object android.app.Activity.getSystemService(java.lang.String)' on a null object reference
// 	at eu.wikijourney.wikijourney.views.MapFragment.drawMap(MapFragment.java:259)
// 	at eu.wikijourney.wikijourney.views.MapFragment.access$300(MapFragment.java:48)
// 	at eu.wikijourney.wikijourney.views.MapFragment$1.onLocationChanged(MapFragment.java:179)
// 	at android.location.LocationManager$ListenerTransport._handleMessage(LocationManager.java:285)
// 	at android.location.LocationManager$ListenerTransport.-wrap0(LocationManager.java)
// 	at android.location.LocationManager$ListenerTransport$1.handleMessage(LocationManager.java:230)
// 	at android.os.Handler.dispatchMessage(Handler.java:102)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)

```



