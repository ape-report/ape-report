title: fr.masciulli.drinks

# fr.masciulli.drinks

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
java.lang.IllegalArgumentException
	at android.os.Parcel.readException(Parcel.java:1624)
	at android.os.Parcel.readException(Parcel.java:1573)
	at android.app.ActivityManagerProxy.isTopOfTask(ActivityManagerNative.java:4787)
	at android.app.Activity.isTopOfTask(Activity.java:5633)
	at android.app.Activity.cancelInputsAndStartExitTransition(Activity.java:3972)
	at android.app.Activity.startActivityForResult(Activity.java:3949)
	at android.support.v4.app.BaseFragmentActivityJB.startActivityForResult(BaseFragmentActivityJB.java:48)
	at android.support.v4.app.FragmentActivity.startActivityForResult(FragmentActivity.java:77)
	at android.app.Activity.startActivity(Activity.java:4209)
	at fr.masciulli.drinks.ui.activity.LiquorActivity.onDrinkClick(LiquorActivity.java:107)
	at fr.masciulli.drinks.ui.activity.LiquorActivity.access$lambda$0(LiquorActivity.java)
	at fr.masciulli.drinks.ui.activity.LiquorActivity$$Lambda$2.onItemClick(Unknown Source)
	at fr.masciulli.drinks.ui.adapter.LiquorRelatedAdapter.lambda$null$1(LiquorRelatedAdapter.java:86)
	at fr.masciulli.drinks.ui.adapter.LiquorRelatedAdapter$$Lambda$3.run(Unknown Source)
	at android.view.ViewPropertyAnimator$AnimatorEventListener.onAnimationEnd(ViewPropertyAnimator.java:1119)
	at android.animation.ValueAnimator.endAnimation(ValueAnimator.java:1239)
	at android.animation.ValueAnimator$AnimationHandler.doAnimationFrame(ValueAnimator.java:766)
	at android.animation.ValueAnimator$AnimationHandler$1.run(ValueAnimator.java:801)
	at android.view.Choreographer$CallbackRecord.run(Choreographer.java:858)
	at android.view.Choreographer.doCallbacks(Choreographer.java:670)
	at android.view.Choreographer.doFrame(Choreographer.java:603)
	at android.view.Choreographer$FrameDisplayEventReceiver.run(Choreographer.java:844)
	at android.os.Handler.handleCallback(Handler.java:739)
	at android.os.Handler.dispatchMessage(Handler.java:95)
	at android.os.Looper.loop(Looper.java:148)
	at android.app.ActivityThread.main(ActivityThread.java:5417)
	at java.lang.reflect.Method.invoke(Native Method)
	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)

```



