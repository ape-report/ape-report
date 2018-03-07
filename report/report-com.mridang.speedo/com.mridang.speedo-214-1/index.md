title: com.mridang.speedo

# com.mridang.speedo

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.RuntimeException: Unable to start activity ComponentInfo{com.mridang.speedo/com.mridang.speedo.SettingsActivity}: java.lang.NullPointerException: Attempt to read from field 'int com.mridang.colorpicker.ColorPreference.mNumColumns' on a null object reference
// 	at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:2416)
// 	at android.app.ActivityThread.handleLaunchActivity(ActivityThread.java:2476)
// 	at android.app.ActivityThread.handleRelaunchActivity(ActivityThread.java:4077)
// 	at android.app.ActivityThread.-wrap15(ActivityThread.java)
// 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1350)
// 	at android.os.Handler.dispatchMessage(Handler.java:102)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
// Caused by: java.lang.NullPointerException: Attempt to read from field 'int com.mridang.colorpicker.ColorPreference.mNumColumns' on a null object reference
// 	at com.mridang.colorpicker.ColorPreference.access$000(ColorPreference.java:33)
// 	at com.mridang.colorpicker.ColorPreference$ColorDialogFragment.onCreateDialog(ColorPreference.java:177)
// 	at android.app.DialogFragment.getLayoutInflater(DialogFragment.java:407)
// 	at android.app.FragmentManagerImpl.moveToState(FragmentManager.java:973)
// 	at android.app.FragmentManagerImpl.moveToState(FragmentManager.java:1148)
// 	at android.app.FragmentManagerImpl.moveToState(FragmentManager.java:1130)
// 	at android.app.FragmentManagerImpl.dispatchActivityCreated(FragmentManager.java:1953)
// 	at android.app.FragmentController.dispatchActivityCreated(FragmentController.java:152)
// 	at android.app.Activity.performCreateCommon(Activity.java:6245)
// 	at android.app.Activity.performCreate(Activity.java:6253)
// 	at android.app.Instrumentation.callActivityOnCreate(Instrumentation.java:1107)
// 	at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:2369)
// 	... 10 more

```



