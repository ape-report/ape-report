title: de.fmaul.android.cmis

# de.fmaul.android.cmis

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.NullPointerException: Attempt to invoke interface method 'java.lang.Object java.util.Map.get(java.lang.Object)' on a null object reference
// 	at de.fmaul.android.cmis.asynctask.ServerInfoLoadingTask.onPostExecute(ServerInfoLoadingTask.java:61)
// 	at de.fmaul.android.cmis.asynctask.ServerInfoLoadingTask.onPostExecute(ServerInfoLoadingTask.java:19)
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



