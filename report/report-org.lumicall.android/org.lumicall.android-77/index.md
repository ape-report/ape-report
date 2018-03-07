title: org.lumicall.android

# org.lumicall.android

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.NullPointerException: Attempt to read from field 'long org.sipdroid.sipua.UserAgentProfile.sipIdentityId' on a null object reference
// 	at org.sipdroid.sipua.SipdroidEngine.call(SipdroidEngine.java:740)
// 	at org.lumicall.android.sip.DialCandidateHelper.call(DialCandidateHelper.java:54)
// 	at org.sipdroid.sipua.ui.Sipdroid.call_menu(Sipdroid.java:763)
// 	at org.sipdroid.sipua.ui.Sipdroid$1.onKey(Sipdroid.java:254)
// 	at android.view.View.dispatchKeyEvent(View.java:9236)
// 	at android.view.ViewGroup.dispatchKeyEvent(ViewGroup.java:1640)
// 	at android.view.ViewGroup.dispatchKeyEvent(ViewGroup.java:1640)
// 	at android.view.ViewGroup.dispatchKeyEvent(ViewGroup.java:1640)
// 	at android.view.ViewGroup.dispatchKeyEvent(ViewGroup.java:1640)
// 	at android.view.ViewGroup.dispatchKeyEvent(ViewGroup.java:1640)
// 	at android.widget.ScrollView.dispatchKeyEvent(ScrollView.java:379)
// 	at android.view.ViewGroup.dispatchKeyEvent(ViewGroup.java:1640)
// 	at android.view.ViewGroup.dispatchKeyEvent(ViewGroup.java:1640)
// 	at android.view.ViewGroup.dispatchKeyEvent(ViewGroup.java:1640)
// 	at android.view.ViewGroup.dispatchKeyEvent(ViewGroup.java:1640)
// 	at android.view.ViewGroup.dispatchKeyEvent(ViewGroup.java:1640)
// 	at android.view.ViewGroup.dispatchKeyEvent(ViewGroup.java:1640)
// 	at com.android.internal.policy.PhoneWindow$DecorView.superDispatchKeyEvent(PhoneWindow.java:2395)
// 	at com.android.internal.policy.PhoneWindow.superDispatchKeyEvent(PhoneWindow.java:1727)
// 	at android.app.Activity.dispatchKeyEvent(Activity.java:2731)
// 	at com.android.internal.policy.PhoneWindow$DecorView.dispatchKeyEvent(PhoneWindow.java:2310)
// 	at android.view.ViewRootImpl$ViewPostImeInputStage.processKeyEvent(ViewRootImpl.java:4127)
// 	at android.view.ViewRootImpl$ViewPostImeInputStage.onProcess(ViewRootImpl.java:4089)
// 	at android.view.ViewRootImpl$InputStage.deliver(ViewRootImpl.java:3642)
// 	at android.view.ViewRootImpl$InputStage.onDeliverToNext(ViewRootImpl.java:3695)
// 	at android.view.ViewRootImpl$InputStage.forward(ViewRootImpl.java:3661)
// 	at android.view.ViewRootImpl$AsyncInputStage.forward(ViewRootImpl.java:3787)
// 	at android.view.ViewRootImpl$InputStage.apply(ViewRootImpl.java:3669)
// 	at android.view.ViewRootImpl$AsyncInputStage.apply(ViewRootImpl.java:3844)
// 	at android.view.ViewRootImpl$InputStage.deliver(ViewRootImpl.java:3642)
// 	at android.view.ViewRootImpl$InputStage.onDeliverToNext(ViewRootImpl.java:3695)
// 	at android.view.ViewRootImpl$InputStage.forward(ViewRootImpl.java:3661)
// 	at android.view.ViewRootImpl$InputStage.apply(ViewRootImpl.java:3669)
// 	at android.view.ViewRootImpl$InputStage.deliver(ViewRootImpl.java:3642)
// 	at android.view.ViewRootImpl.deliverInputEvent(ViewRootImpl.java:5922)
// 	at android.view.ViewRootImpl.doProcessInputEvents(ViewRootImpl.java:5896)
// 	at android.view.ViewRootImpl.enqueueInputEvent(ViewRootImpl.java:5857)
// 	at android.view.ViewRootImpl$ViewRootHandler.handleMessage(ViewRootImpl.java:3434)
// 	at android.os.Handler.dispatchMessage(Handler.java:102)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)

```



