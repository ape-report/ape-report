title: click.dummer.funphonepuppet

# click.dummer.funphonepuppet

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.RuntimeException: Unable to start activity ComponentInfo{click.dummer.funphonepuppet/click.dummer.funphonepuppet.FaceActivity}: android.view.InflateException: Binary XML file line #14: Binary XML file line #14: Error inflating class <unknown>
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
// Caused by: android.view.InflateException: Binary XML file line #14: Binary XML file line #14: Error inflating class <unknown>
// 	at android.view.LayoutInflater.inflate(LayoutInflater.java:539)
// 	at android.view.LayoutInflater.inflate(LayoutInflater.java:423)
// 	at android.view.LayoutInflater.inflate(LayoutInflater.java:374)
// 	at com.android.internal.policy.PhoneWindow.setContentView(PhoneWindow.java:393)
// 	at android.app.Activity.setContentView(Activity.java:2172)
// 	at click.dummer.funphonepuppet.FaceActivity.onCreate(FaceActivity.java:74)
// 	at android.app.Activity.performCreate(Activity.java:6251)
// 	at android.app.Instrumentation.callActivityOnCreate(Instrumentation.java:1107)
// 	at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:2369)
// 	... 9 more
// Caused by: android.view.InflateException: Binary XML file line #14: Error inflating class <unknown>
// 	at android.view.LayoutInflater.createView(LayoutInflater.java:645)
// 	at com.android.internal.policy.PhoneLayoutInflater.onCreateView(PhoneLayoutInflater.java:58)
// 	at android.view.LayoutInflater.onCreateView(LayoutInflater.java:694)
// 	at android.view.LayoutInflater.createViewFromTag(LayoutInflater.java:762)
// 	at android.view.LayoutInflater.createViewFromTag(LayoutInflater.java:704)
// 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:835)
// 	at android.view.LayoutInflater.rInflateChildren(LayoutInflater.java:798)
// 	at android.view.LayoutInflater.inflate(LayoutInflater.java:515)
// 	... 17 more
// Caused by: java.lang.reflect.InvocationTargetException
// 	at java.lang.reflect.Constructor.newInstance(Native Method)
// 	at android.view.LayoutInflater.createView(LayoutInflater.java:619)
// 	... 24 more
// Caused by: java.lang.OutOfMemoryError: Failed to allocate a 331788 byte allocation with 233304 free bytes and 227KB until OOM
// 	at dalvik.system.VMRuntime.newNonMovableArray(Native Method)
// 	at android.graphics.BitmapFactory.nativeDecodeAsset(Native Method)
// 	at android.graphics.BitmapFactory.decodeStream(BitmapFactory.java:609)
// 	at android.graphics.BitmapFactory.decodeResourceStream(BitmapFactory.java:444)
// 	at android.graphics.drawable.Drawable.createFromResourceStream(Drawable.java:1080)
// 	at android.content.res.Resources.loadDrawableForCookie(Resources.java:2635)
// 	at android.content.res.Resources.loadDrawable(Resources.java:2540)
// 	at android.content.res.TypedArray.getDrawable(TypedArray.java:870)
// 	at android.widget.ImageView.<init>(ImageView.java:152)
// 	at android.widget.ImageView.<init>(ImageView.java:140)
// 	at android.widget.ImageView.<init>(ImageView.java:136)
// 	... 26 more

```



