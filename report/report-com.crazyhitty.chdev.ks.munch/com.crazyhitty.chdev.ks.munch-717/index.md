title: com.crazyhitty.chdev.ks.munch

# com.crazyhitty.chdev.ks.munch

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{5660dd0 V.E...... R.....ID 0,0-1026,710} not attached to window manager
// 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
// 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
// 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
// 	at android.app.Dialog.dismissDialog(Dialog.java:362)
// 	at android.app.Dialog.dismiss(Dialog.java:345)
// 	at com.afollestad.materialdialogs.MaterialDialog.dismiss(MaterialDialog.java:1811)
// 	at com.crazyhitty.chdev.ks.munch.article.ArticleInteractor.articleLoaded(ArticleInteractor.java:64)
// 	at com.crazyhitty.chdev.ks.munch.article.ArticleInteractor$ArticleAsyncLoader.onPostExecute(ArticleInteractor.java:128)
// 	at com.crazyhitty.chdev.ks.munch.article.ArticleInteractor$ArticleAsyncLoader.onPostExecute(ArticleInteractor.java:97)
// 	at android.os.AsyncTask.finish(AsyncTask.java:651)
// 	at android.os.AsyncTask.-wrap1(AsyncTask.java)
// 	at android.os.AsyncTask$InternalHandler.handleMessage(AsyncTask.java:668)
// 	at android.os.Handler.dispatchMessage(Handler.java:102)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)

```



