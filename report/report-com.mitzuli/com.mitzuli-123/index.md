title: com.mitzuli

# com.mitzuli

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.RuntimeException: getParameters failed (empty parameters)
// 	at android.hardware.Camera.native_getParameters(Native Method)
// 	at android.hardware.Camera.getParameters(Camera.java:1890)
// 	at com.mitzuli.CameraCropperView.onMeasure(CameraCropperView.java:326)
// 	at android.view.View.measure(View.java:18794)
// 	at android.view.ViewGroup.measureChildWithMargins(ViewGroup.java:5951)
// 	at android.widget.LinearLayout.measureChildBeforeLayout(LinearLayout.java:1465)
// 	at android.widget.LinearLayout.measureVertical(LinearLayout.java:748)
// 	at android.widget.LinearLayout.onMeasure(LinearLayout.java:630)
// 	at android.view.View.measure(View.java:18794)
// 	at android.widget.LinearLayout.measureVertical(LinearLayout.java:901)
// 	at android.widget.LinearLayout.onMeasure(LinearLayout.java:630)
// 	at android.view.View.measure(View.java:18794)
// 	at android.view.ViewGroup.measureChildWithMargins(ViewGroup.java:5951)
// 	at android.widget.FrameLayout.onMeasure(FrameLayout.java:194)
// 	at android.support.v7.widget.CardView.onMeasure(CardView.java:198)
// 	at android.view.View.measure(View.java:18794)
// 	at android.widget.LinearLayout.measureVertical(LinearLayout.java:901)
// 	at android.widget.LinearLayout.onMeasure(LinearLayout.java:630)
// 	at android.view.View.measure(View.java:18794)
// 	at android.view.ViewGroup.measureChildWithMargins(ViewGroup.java:5951)
// 	at android.widget.LinearLayout.measureChildBeforeLayout(LinearLayout.java:1465)
// 	at android.widget.LinearLayout.measureVertical(LinearLayout.java:748)
// 	at android.widget.LinearLayout.onMeasure(LinearLayout.java:630)
// 	at android.view.View.measure(View.java:18794)
// 	at android.view.ViewGroup.measureChildWithMargins(ViewGroup.java:5951)
// 	at android.widget.FrameLayout.onMeasure(FrameLayout.java:194)
// 	at android.support.v7.internal.widget.ContentFrameLayout.onMeasure(ContentFrameLayout.java:124)
// 	at android.view.View.measure(View.java:18794)
// 	at android.view.ViewGroup.measureChildWithMargins(ViewGroup.java:5951)
// 	at android.widget.FrameLayout.onMeasure(FrameLayout.java:194)
// 	at android.view.View.measure(View.java:18794)
// 	at android.view.ViewGroup.measureChildWithMargins(ViewGroup.java:5951)
// 	at android.widget.FrameLayout.onMeasure(FrameLayout.java:194)
// 	at android.view.View.measure(View.java:18794)
// 	at android.view.ViewGroup.measureChildWithMargins(ViewGroup.java:5951)
// 	at android.widget.LinearLayout.measureChildBeforeLayout(LinearLayout.java:1465)
// 	at android.widget.LinearLayout.measureVertical(LinearLayout.java:748)
// 	at android.widget.LinearLayout.onMeasure(LinearLayout.java:630)
// 	at android.view.View.measure(View.java:18794)
// 	at android.view.ViewGroup.measureChildWithMargins(ViewGroup.java:5951)
// 	at android.widget.FrameLayout.onMeasure(FrameLayout.java:194)
// 	at com.android.internal.policy.PhoneWindow$DecorView.onMeasure(PhoneWindow.java:2643)
// 	at android.view.View.measure(View.java:18794)
// 	at android.view.ViewRootImpl.performMeasure(ViewRootImpl.java:2100)
// 	at android.view.ViewRootImpl.measureHierarchy(ViewRootImpl.java:1216)
// 	at android.view.ViewRootImpl.performTraversals(ViewRootImpl.java:1452)
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


