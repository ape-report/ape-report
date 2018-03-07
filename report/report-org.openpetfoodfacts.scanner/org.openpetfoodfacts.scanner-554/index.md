title: org.openpetfoodfacts.scanner

# org.openpetfoodfacts.scanner

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// android.content.res.Resources$NotFoundException: File res/drawable-hdpi-v4/error_image.png from xml type xml resource ID #0x7f020064
// 	at android.content.res.Resources.loadXmlResourceParser(Resources.java:2821)
// 	at android.content.res.Resources.loadXmlResourceParser(Resources.java:2776)
// 	at android.content.res.Resources.getXml(Resources.java:1214)
// 	at android.support.graphics.drawable.VectorDrawableCompat.create(Unknown Source)
// 	at openfoodfacts.github.scrachx.openfood.views.adapters.NutrientLevelListAdapter.getView(Unknown Source)
// 	at android.widget.AbsListView.obtainView(AbsListView.java:2346)
// 	at android.widget.ListView.onMeasure(ListView.java:1158)
// 	at android.view.View.measure(View.java:18794)
// 	at android.view.ViewGroup.measureChildWithMargins(ViewGroup.java:5951)
// 	at android.widget.LinearLayout.measureChildBeforeLayout(LinearLayout.java:1465)
// 	at android.widget.LinearLayout.measureVertical(LinearLayout.java:748)
// 	at android.widget.LinearLayout.onMeasure(LinearLayout.java:630)
// 	at android.view.View.measure(View.java:18794)
// 	at android.support.v4.widget.NestedScrollView.measureChildWithMargins(Unknown Source)
// 	at android.widget.FrameLayout.onMeasure(FrameLayout.java:194)
// 	at android.support.v4.widget.NestedScrollView.onMeasure(Unknown Source)
// 	at android.view.View.measure(View.java:18794)
// 	at android.support.v4.view.ViewPager.onMeasure(Unknown Source)
// 	at android.view.View.measure(View.java:18794)
// 	at android.view.ViewGroup.measureChildWithMargins(ViewGroup.java:5951)
// 	at android.support.design.widget.CoordinatorLayout.onMeasureChild(Unknown Source)
// 	at android.support.design.widget.HeaderScrollingViewBehavior.onMeasureChild(Unknown Source)
// 	at android.support.design.widget.AppBarLayout$ScrollingViewBehavior.onMeasureChild(Unknown Source)
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
// Caused by: java.io.FileNotFoundException: Corrupt XML binary file
// 	at android.content.res.AssetManager.openXmlAssetNative(Native Method)
// 	at android.content.res.AssetManager.openXmlBlockAsset(AssetManager.java:485)
// 	at android.content.res.Resources.loadXmlResourceParser(Resources.java:2803)
// 	... 61 more

```



