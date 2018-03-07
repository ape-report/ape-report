title: ru.equestriadev.mgke

# ru.equestriadev.mgke

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.NullPointerException: Attempt to invoke virtual method 'android.content.SharedPreferences android.content.Context.getSharedPreferences(java.lang.String, int)' on a null object reference
// 	at ru.equestriadev.mgke.Teacher.setAdapter(Teacher.java:143)
// 	at ru.equestriadev.netwerking.RequestPairs.onPostExecute(RequestPairs.java:94)
// 	at ru.equestriadev.netwerking.RequestPairs.onPostExecute(RequestPairs.java:23)
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



