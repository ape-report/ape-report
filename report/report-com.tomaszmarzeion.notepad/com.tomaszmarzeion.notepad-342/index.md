title: com.tomaszmarzeion.notepad

# com.tomaszmarzeion.notepad

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.IndexOutOfBoundsException: Invalid index 0, size is 0
// 	at java.util.ArrayList.throwIndexOutOfBoundsException(ArrayList.java:255)
// 	at java.util.ArrayList.get(ArrayList.java:308)
// 	at com.example.tomek.notepad.d.getView(Unknown Source)
// 	at android.widget.AbsListView.obtainView(AbsListView.java:2346)
// 	at android.widget.ListView.measureHeightOfChildren(ListView.java:1281)
// 	at android.widget.ListView.onMeasure(ListView.java:1188)
// 	at android.view.View.measure(View.java:18794)
// 	at android.view.ViewGroup.measureChildWithMargins(ViewGroup.java:5951)
// 	at android.widget.LinearLayout.measureChildBeforeLayout(LinearLayout.java:1465)
// 	at android.widget.LinearLayout.measureHorizontal(LinearLayout.java:1112)
// 	at android.widget.LinearLayout.onMeasure(LinearLayout.java:632)
// 	at android.view.View.measure(View.java:18794)
// 	at android.view.ViewGroup.measureChildWithMargins(ViewGroup.java:5951)
// 	at android.support.design.widget.CoordinatorLayout.a(Unknown Source)
// 	at android.support.design.widget.j.a(Unknown Source)
// 	at android.support.design.widget.AppBarLayout$ScrollingViewBehavior.a(Unknown Source)
// 	at android.support.design.widget.CoordinatorLayout.onMeasure(Unknown Source)
// 	at android.view.View.measure(View.java:18794)
// 	at android.view.ViewGroup.measureChildWithMargins(ViewGroup.java:5951)
// 	at android.widget.FrameLayout.onMeasure(FrameLayout.java:194)
// 	at android.support.v7.widget.ContentFrameLayout.onMeasure(Unknown Source)
// 	at android.view.View.measure(View.java:18794)
// 	at android.view.ViewGroup.measureChildWithMargins(ViewGroup.java:5951)
// 	at android.widget.LinearLayout.measureChildBeforeLayout(LinearLayout.java:1465)
// 	at android.widget.LinearLayout.measureVertical(LinearLayout.java:748)
// 	at android.widget.LinearLayout.onMeasure(LinearLayout.java:630)
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



