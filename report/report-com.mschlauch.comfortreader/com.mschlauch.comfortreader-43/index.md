title: com.mschlauch.comfortreader

# com.mschlauch.comfortreader

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.RuntimeException: An error occurred while executing doInBackground()
// 	at android.os.AsyncTask$3.done(AsyncTask.java:309)
// 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:354)
// 	at java.util.concurrent.FutureTask.setException(FutureTask.java:223)
// 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
// 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:234)
// 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
// 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
// 	at java.lang.Thread.run(Thread.java:818)
// Caused by: java.lang.StringIndexOutOfBoundsException: length=0; regionStart=0; regionLength=-1
// 	at java.lang.String.startEndAndLength(String.java:298)
// 	at java.lang.String.substring(String.java:1087)
// 	at com.mschlauch.comfortreader.SettingsLoader.loadTextfromFilePath(SettingsLoader.java:621)
// 	at com.mschlauch.comfortreader.CRPreferenceActivity$MyPreferenceFragment$7$1.doInBackground(CRPreferenceActivity.java:314)
// 	at com.mschlauch.comfortreader.CRPreferenceActivity$MyPreferenceFragment$7$1.doInBackground(CRPreferenceActivity.java:306)
// 	at android.os.AsyncTask$2.call(AsyncTask.java:295)
// 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
// 	... 4 more

```



