title: com.fsck.k9

# com.fsck.k9

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
java.lang.NullPointerException
	at android.widget.Editor$SelectionModifierCursorController.onTouchEvent(Editor.java:4866)
	at android.widget.Editor.onTouchEvent(Editor.java:1223)
	at android.widget.TextView.onTouchEvent(TextView.java:8292)
	at android.view.View.dispatchTouchEvent(View.java:9300)
	at android.view.ViewGroup.dispatchTransformedTouchEvent(ViewGroup.java:2553)
	at android.view.ViewGroup.dispatchTouchEvent(ViewGroup.java:2254)
	at android.view.ViewGroup.dispatchTransformedTouchEvent(ViewGroup.java:2553)
	at android.view.ViewGroup.dispatchTouchEvent(ViewGroup.java:2254)
	at android.view.ViewGroup.dispatchTransformedTouchEvent(ViewGroup.java:2553)
	at android.view.ViewGroup.dispatchTouchEvent(ViewGroup.java:2254)
	at android.view.ViewGroup.dispatchTransformedTouchEvent(ViewGroup.java:2553)
	at android.view.ViewGroup.dispatchTouchEvent(ViewGroup.java:2254)
	at android.view.ViewGroup.dispatchTransformedTouchEvent(ViewGroup.java:2553)
	at android.view.ViewGroup.dispatchTouchEvent(ViewGroup.java:2254)
	at android.view.ViewGroup.dispatchTransformedTouchEvent(ViewGroup.java:2553)
	at android.view.ViewGroup.dispatchTouchEvent(ViewGroup.java:2254)
	at com.android.internal.policy.PhoneWindow$DecorView.superDispatchTouchEvent(PhoneWindow.java:2403)
	at com.android.internal.policy.PhoneWindow.superDispatchTouchEvent(PhoneWindow.java:1737)
	at android.app.Activity.dispatchTouchEvent(Activity.java:2771)
	at com.fsck.k9.activity.K9Activity.dispatchTouchEvent(K9Activity.java:25)
	at com.android.internal.policy.PhoneWindow$DecorView.dispatchTouchEvent(PhoneWindow.java:2364)
	at android.view.View.dispatchPointerEvent(View.java:9520)
	at android.view.ViewRootImpl$ViewPostImeInputStage.processPointerEvent(ViewRootImpl.java:4230)
	at android.view.ViewRootImpl$ViewPostImeInputStage.onProcess(ViewRootImpl.java:4096)
	at android.view.ViewRootImpl$InputStage.deliver(ViewRootImpl.java:3642)
	at android.view.ViewRootImpl$InputStage.onDeliverToNext(ViewRootImpl.java:3695)
	at android.view.ViewRootImpl$InputStage.forward(ViewRootImpl.java:3661)
	at android.view.ViewRootImpl$AsyncInputStage.forward(ViewRootImpl.java:3787)
	at android.view.ViewRootImpl$InputStage.apply(ViewRootImpl.java:3669)
	at android.view.ViewRootImpl$AsyncInputStage.apply(ViewRootImpl.java:3844)
	at android.view.ViewRootImpl$InputStage.deliver(ViewRootImpl.java:3642)
	at android.view.ViewRootImpl$InputStage.onDeliverToNext(ViewRootImpl.java:3695)
	at android.view.ViewRootImpl$InputStage.forward(ViewRootImpl.java:3661)
	at android.view.ViewRootImpl$InputStage.apply(ViewRootImpl.java:3669)
	at android.view.ViewRootImpl$InputStage.deliver(ViewRootImpl.java:3642)
	at android.view.ViewRootImpl.deliverInputEvent(ViewRootImpl.java:5922)
	at android.view.ViewRootImpl.doProcessInputEvents(ViewRootImpl.java:5896)
	at android.view.ViewRootImpl.enqueueInputEvent(ViewRootImpl.java:5857)
	at android.view.ViewRootImpl$WindowInputEventReceiver.onInputEvent(ViewRootImpl.java:6025)
	at android.view.InputEventReceiver.dispatchInputEvent(InputEventReceiver.java:185)
	at android.os.MessageQueue.nativePollOnce(Native Method)
	at android.os.MessageQueue.next(MessageQueue.java:323)
	at android.os.Looper.loop(Looper.java:135)
	at android.app.ActivityThread.main(ActivityThread.java:5417)
	at java.lang.reflect.Method.invoke(Native Method)
	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)

```



