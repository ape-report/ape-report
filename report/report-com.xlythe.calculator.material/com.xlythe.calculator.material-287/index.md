title: com.xlythe.calculator.material

# com.xlythe.calculator.material

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.RuntimeException: Unable to start activity ComponentInfo{com.xlythe.calculator.material/com.xlythe.calculator.material.Calculator}: java.lang.IllegalStateException: Cannot start this animator on a detached view!
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
// Caused by: java.lang.IllegalStateException: Cannot start this animator on a detached view!
// 	at android.view.RenderNode.addAnimator(RenderNode.java:812)
// 	at android.view.RenderNodeAnimator.setTarget(RenderNodeAnimator.java:300)
// 	at android.view.RenderNodeAnimator.setTarget(RenderNodeAnimator.java:282)
// 	at android.animation.RevealAnimator.<init>(RevealAnimator.java:37)
// 	at android.view.ViewAnimationUtils.createCircularReveal(ViewAnimationUtils.java:55)
// 	at io.codetail.animation.ViewAnimationUtils.createCircularReveal(ViewAnimationUtils.java:47)
// 	at com.xlythe.calculator.material.BasicCalculator.reveal(BasicCalculator.java:552)
// 	at com.xlythe.calculator.material.BasicCalculator.onError(BasicCalculator.java:616)
// 	at com.xlythe.calculator.material.BasicCalculator.onEvaluate(BasicCalculator.java:453)
// 	at com.xlythe.calculator.material.GraphingCalculator.onEvaluate(GraphingCalculator.java:234)
// 	at com.xlythe.calculator.material.CalculatorExpressionEvaluator.evaluate(CalculatorExpressionEvaluator.java:53)
// 	at com.xlythe.calculator.material.BasicCalculator.onCreate(BasicCalculator.java:135)
// 	at android.app.Activity.performCreate(Activity.java:6251)
// 	at android.app.Instrumentation.callActivityOnCreate(Instrumentation.java:1107)
// 	at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:2369)
// 	... 10 more

```



