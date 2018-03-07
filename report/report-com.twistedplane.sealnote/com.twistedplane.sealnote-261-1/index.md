title: com.twistedplane.sealnote

# com.twistedplane.sealnote

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
java.lang.RuntimeException
	at android.os.AsyncTask$3.done(AsyncTask.java:309)
	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:354)
	at java.util.concurrent.FutureTask.setException(FutureTask.java:223)
	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
	at java.lang.Thread.run(Thread.java:818)
Caused by: java.lang.IllegalArgumentException
	at com.twistedplane.sealnote.data.DatabaseHandler.update(DatabaseHandler.java:84)
	at com.twistedplane.sealnote.data.DatabaseHandler.getWritableDatabase(DatabaseHandler.java:110)
	at com.twistedplane.sealnote.data.DatabaseHandler.getReadableDatabase(DatabaseHandler.java:115)
	at com.twistedplane.sealnote.data.DatabaseHandler.getNotesCursor(DatabaseHandler.java:558)
	at com.twistedplane.sealnote.data.AdapterLoader.loadInBackground(AdapterLoader.java:30)
	at com.twistedplane.sealnote.data.AdapterLoader.loadInBackground(AdapterLoader.java:13)
	at android.content.AsyncTaskLoader.onLoadInBackground(AsyncTaskLoader.java:312)
	at android.content.AsyncTaskLoader$LoadTask.doInBackground(AsyncTaskLoader.java:69)
	at android.content.AsyncTaskLoader$LoadTask.doInBackground(AsyncTaskLoader.java:66)
	at android.os.AsyncTask$2.call(AsyncTask.java:295)
	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
	... 3 more

```



