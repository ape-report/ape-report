title: com.zeapo.pwdstore

# com.zeapo.pwdstore

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.RuntimeException: Unable to start activity ComponentInfo{com.zeapo.pwdstore/com.zeapo.pwdstore.git.GitActivity}: java.lang.NullPointerException: Attempt to invoke virtual method 'org.eclipse.jgit.lib.StoredConfig org.eclipse.jgit.lib.Repository.getConfig()' on a null object reference
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
// Caused by: java.lang.NullPointerException: Attempt to invoke virtual method 'org.eclipse.jgit.lib.StoredConfig org.eclipse.jgit.lib.Repository.getConfig()' on a null object reference
// 	at com.zeapo.pwdstore.utils.PasswordRepository.addRemote(PasswordRepository.java:68)
// 	at com.zeapo.pwdstore.git.GitActivity.syncRepository(GitActivity.java:648)
// 	at com.zeapo.pwdstore.git.GitActivity.onCreate(GitActivity.java:270)
// 	at android.app.Activity.performCreate(Activity.java:6251)
// 	at android.app.Instrumentation.callActivityOnCreate(Instrumentation.java:1107)
// 	at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:2369)
// 	... 9 more

```



