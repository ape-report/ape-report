title: com.notriddle.budget

# com.notriddle.budget

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.RuntimeException: Unable to destroy activity {com.notriddle.budget/com.notriddle.budget.EnvelopesActivity}: java.lang.IllegalStateException: Can not perform this action inside of onLoaderReset
// 	at android.app.ActivityThread.performDestroyActivity(ActivityThread.java:3831)
// 	at android.app.ActivityThread.handleDestroyActivity(ActivityThread.java:3849)
// 	at android.app.ActivityThread.-wrap5(ActivityThread.java)
// 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1398)
// 	at android.os.Handler.dispatchMessage(Handler.java:102)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
// Caused by: java.lang.IllegalStateException: Can not perform this action inside of onLoaderReset
// 	at android.app.FragmentManagerImpl.checkStateLoss(FragmentManager.java:1415)
// 	at android.app.FragmentManagerImpl.enqueueAction(FragmentManager.java:1429)
// 	at android.app.BackStackRecord.commitInternal(BackStackRecord.java:687)
// 	at android.app.BackStackRecord.commit(BackStackRecord.java:663)
// 	at android.app.DialogFragment.dismissInternal(DialogFragment.java:301)
// 	at android.app.DialogFragment.dismiss(DialogFragment.java:267)
// 	at com.notriddle.budget.OkFragment.dismiss(OkFragment.java:79)
// 	at com.notriddle.budget.TransferFragment.onLoaderReset(TransferFragment.java:143)
// 	at android.app.LoaderManagerImpl$LoaderInfo.destroy(LoaderManager.java:364)
// 	at android.app.LoaderManagerImpl.doDestroy(LoaderManager.java:834)
// 	at android.app.Fragment.onDestroy(Fragment.java:1606)
// 	at android.app.Fragment.performDestroy(Fragment.java:2433)
// 	at android.app.FragmentManagerImpl.moveToState(FragmentManager.java:1098)
// 	at android.app.FragmentManagerImpl.moveToState(FragmentManager.java:1148)
// 	at android.app.FragmentManagerImpl.moveToState(FragmentManager.java:1130)
// 	at android.app.FragmentManagerImpl.dispatchDestroy(FragmentManager.java:1981)
// 	at android.app.FragmentController.dispatchDestroy(FragmentController.java:218)
// 	at android.app.Activity.performDestroy(Activity.java:6421)
// 	at android.app.Instrumentation.callActivityOnDestroy(Instrumentation.java:1142)
// 	at android.app.ActivityThread.performDestroyActivity(ActivityThread.java:3818)
// 	... 9 more

```



