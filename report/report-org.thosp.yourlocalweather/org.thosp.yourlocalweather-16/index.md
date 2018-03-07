title: org.thosp.yourlocalweather

# org.thosp.yourlocalweather

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.RuntimeException: Unable to start service org.thosp.yourlocalweather.service.LocationUpdateService@ed410c1 with Intent { act=android.intent.action.LOCATION_UPDATE pkg=org.thosp.yourlocalweather (has extras) }: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{fbfeb36 V.E...... R......D 0,0-1026,348} not attached to window manager
// 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
// 	at android.app.ActivityThread.-wrap17(ActivityThread.java)
// 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
// 	at android.os.Handler.dispatchMessage(Handler.java:102)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
// Caused by: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{fbfeb36 V.E...... R......D 0,0-1026,348} not attached to window manager
// 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
// 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
// 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
// 	at android.app.Dialog.dismissDialog(Dialog.java:362)
// 	at android.app.Dialog.dismiss(Dialog.java:345)
// 	at android.app.Dialog.cancel(Dialog.java:1199)
// 	at org.thosp.yourlocalweather.service.LocationUpdateService.requestWeatherCheck(LocationUpdateService.java:685)
// 	at org.thosp.yourlocalweather.service.LocationUpdateService.onLocationChanged(LocationUpdateService.java:357)
// 	at org.thosp.yourlocalweather.service.LocationUpdateService.onStartCommand(LocationUpdateService.java:239)
// 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3010)
// 	... 8 more

```



