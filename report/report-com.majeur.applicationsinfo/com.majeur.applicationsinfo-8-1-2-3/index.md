title: com.majeur.applicationsinfo

# com.majeur.applicationsinfo

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.RuntimeException: Unable to start activity ComponentInfo{com.majeur.applicationsinfo/com.majeur.applicationsinfo.MainActivity}: android.view.InflateException: Binary XML file line #1: Binary XML file line #1: Error inflating class fragment
// 	at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:2416)
// 	at android.app.ActivityThread.handleLaunchActivity(ActivityThread.java:2476)
// 	at android.app.ActivityThread.-wrap11(ActivityThread.java)
// 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
// 	at android.os.Handler.dispatchMessage(Handler.java:102)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
// Caused by: android.view.InflateException: Binary XML file line #1: Binary XML file line #1: Error inflating class fragment
// 	at android.view.LayoutInflater.inflate(LayoutInflater.java:539)
// 	at android.view.LayoutInflater.inflate(LayoutInflater.java:423)
// 	at android.view.LayoutInflater.inflate(LayoutInflater.java:374)
// 	at com.android.internal.policy.PhoneWindow.setContentView(PhoneWindow.java:393)
// 	at android.app.Activity.setContentView(Activity.java:2172)
// 	at com.majeur.applicationsinfo.MainActivity.onCreate(MainActivity.java:20)
// 	at android.app.Activity.performCreate(Activity.java:6251)
// 	at android.app.Instrumentation.callActivityOnCreate(Instrumentation.java:1107)
// 	at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:2369)
// 	... 9 more
// Caused by: android.view.InflateException: Binary XML file line #1: Error inflating class fragment
// 	at android.view.LayoutInflater.createViewFromTag(LayoutInflater.java:782)
// 	at android.view.LayoutInflater.createViewFromTag(LayoutInflater.java:704)
// 	at android.view.LayoutInflater.inflate(LayoutInflater.java:492)
// 	... 17 more
// Caused by: java.lang.IllegalStateException: Content view not yet created
// 	at android.app.ListFragment.ensureList(ListFragment.java:386)
// 	at android.app.ListFragment.getListView(ListFragment.java:280)
// 	at com.majeur.applicationsinfo.MainListFragment.setSortBy(MainListFragment.java:217)
// 	at com.majeur.applicationsinfo.MainListFragment.onCreate(MainListFragment.java:96)
// 	at android.app.Fragment.performCreate(Fragment.java:2198)
// 	at android.app.FragmentManagerImpl.moveToState(FragmentManager.java:942)
// 	at android.app.FragmentManagerImpl.moveToState(FragmentManager.java:1126)
// 	at android.app.FragmentManagerImpl.onCreateView(FragmentManager.java:2227)
// 	at android.app.FragmentController.onCreateView(FragmentController.java:98)
// 	at android.app.Activity.onCreateView(Activity.java:5559)
// 	at android.view.LayoutInflater.createViewFromTag(LayoutInflater.java:754)
// 	... 19 more

```



