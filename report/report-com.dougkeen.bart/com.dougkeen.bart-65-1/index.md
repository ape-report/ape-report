title: com.dougkeen.bart

# com.dougkeen.bart

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
java.lang.NullPointerException
	at com.dougkeen.bart.services.EtdService$EtdServiceEngine.applyScheduleInformation(EtdService.java:285)
	at com.dougkeen.bart.services.EtdService$EtdServiceEngine$2.onResult(EtdService.java:233)
	at com.dougkeen.bart.networktasks.GetScheduleInformationTask.onPostExecute(GetScheduleInformationTask.java:104)
	at com.dougkeen.bart.networktasks.GetScheduleInformationTask.onPostExecute(GetScheduleInformationTask.java:20)
	at android.os.AsyncTask.finish(AsyncTask.java:651)
	at android.os.AsyncTask.-wrap1(AsyncTask.java)
	at android.os.AsyncTask$InternalHandler.handleMessage(AsyncTask.java:668)
	at android.os.Handler.dispatchMessage(Handler.java:102)
	at android.os.Looper.loop(Looper.java:148)
	at android.app.ActivityThread.main(ActivityThread.java:5417)
	at java.lang.reflect.Method.invoke(Native Method)
	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)

```



