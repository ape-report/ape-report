title: net.sf.andbatdog.batterydog

# net.sf.andbatdog.batterydog

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.ArrayIndexOutOfBoundsException: length=1; index=1
// 	at net.sf.andbatdog.batterydog.BatteryGraph$BatteryRecordCursor.getCharge(BatteryGraph.java:443)
// 	at net.sf.andbatdog.batterydog.BatteryGraph$BatteryRecordCursor.moveToTime(BatteryGraph.java:469)
// 	at net.sf.andbatdog.batterydog.BatteryGraph$GraphView.drawDischargeRateGraph(BatteryGraph.java:322)
// 	at net.sf.andbatdog.batterydog.BatteryGraph$GraphView.onDraw(BatteryGraph.java:255)
// 	at android.view.View.draw(View.java:16184)
// 	at android.view.View.draw(View.java:16096)
// 	at android.view.ViewGroup.drawChild(ViewGroup.java:3609)
// 	at android.view.ViewGroup.dispatchDraw(ViewGroup.java:3399)
// 	at android.view.View.draw(View.java:16094)
// 	at android.view.ViewGroup.drawChild(ViewGroup.java:3609)
// 	at android.view.ViewGroup.dispatchDraw(ViewGroup.java:3399)
// 	at android.view.View.draw(View.java:16094)
// 	at android.view.ViewGroup.drawChild(ViewGroup.java:3609)
// 	at android.view.ViewGroup.dispatchDraw(ViewGroup.java:3399)
// 	at android.view.View.draw(View.java:16187)
// 	at com.android.internal.policy.PhoneWindow$DecorView.draw(PhoneWindow.java:2690)
// 	at android.view.ViewRootImpl.drawSoftware(ViewRootImpl.java:2728)
// 	at android.view.ViewRootImpl.draw(ViewRootImpl.java:2642)
// 	at android.view.ViewRootImpl.performDraw(ViewRootImpl.java:2434)
// 	at android.view.ViewRootImpl.performTraversals(ViewRootImpl.java:2067)
// 	at android.view.ViewRootImpl.doTraversal(ViewRootImpl.java:1107)
// 	at android.view.ViewRootImpl$TraversalRunnable.run(ViewRootImpl.java:6013)
// 	at android.view.Choreographer$CallbackRecord.run(Choreographer.java:858)
// 	at android.view.Choreographer.doCallbacks(Choreographer.java:670)
// 	at android.view.Choreographer.doFrame(Choreographer.java:606)
// 	at android.view.Choreographer$FrameDisplayEventReceiver.run(Choreographer.java:844)
// 	at android.os.Handler.handleCallback(Handler.java:739)
// 	at android.os.Handler.dispatchMessage(Handler.java:95)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)

```



