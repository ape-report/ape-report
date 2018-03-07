title: com.zeapo.pwdstore

# com.zeapo.pwdstore

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.RuntimeException: Failure delivering result ResultInfo{who=null, request=403, result=-1, data=null} to activity {com.zeapo.pwdstore/com.zeapo.pwdstore.PasswordStore}: java.lang.IllegalStateException: Can not perform this action after onSaveInstanceState
// 	at android.app.ActivityThread.deliverResults(ActivityThread.java:3699)
// 	at android.app.ActivityThread.handleSendResult(ActivityThread.java:3742)
// 	at android.app.ActivityThread.-wrap16(ActivityThread.java)
// 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1393)
// 	at android.os.Handler.dispatchMessage(Handler.java:102)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
// Caused by: java.lang.IllegalStateException: Can not perform this action after onSaveInstanceState
// 	at android.support.v4.app.FragmentManagerImpl.checkStateLoss(FragmentManager.java:2054)
// 	at android.support.v4.app.FragmentManagerImpl.enqueueAction(FragmentManager.java:2077)
// 	at android.support.v4.app.FragmentManagerImpl.popBackStack(FragmentManager.java:799)
// 	at com.zeapo.pwdstore.PasswordStore.checkLocalRepository(PasswordStore.java:379)
// 	at com.zeapo.pwdstore.PasswordStore.checkLocalRepository(PasswordStore.java:351)
// 	at com.zeapo.pwdstore.PasswordStore.onActivityResult(PasswordStore.java:605)
// 	at android.app.Activity.dispatchActivityResult(Activity.java:6456)
// 	at android.app.ActivityThread.deliverResults(ActivityThread.java:3695)
// 	... 9 more

```



