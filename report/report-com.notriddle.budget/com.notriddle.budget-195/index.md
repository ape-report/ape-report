title: com.notriddle.budget

# com.notriddle.budget

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.RuntimeException: Invalid envelope ID: 2
// 	at com.notriddle.budget.EnvelopeDetailsFragment.loadEnvelopeData(EnvelopeDetailsFragment.java:262)
// 	at com.notriddle.budget.EnvelopeDetailsFragment.onLoadFinished(EnvelopeDetailsFragment.java:54)
// 	at android.app.LoaderManagerImpl$LoaderInfo.callOnLoadFinished(LoaderManager.java:483)
// 	at android.app.LoaderManagerImpl$LoaderInfo.onLoadComplete(LoaderManager.java:451)
// 	at android.content.Loader.deliverResult(Loader.java:144)
// 	at android.content.AsyncTaskLoader.dispatchOnLoadComplete(AsyncTaskLoader.java:265)
// 	at android.content.AsyncTaskLoader$LoadTask.onPostExecute(AsyncTaskLoader.java:92)
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



