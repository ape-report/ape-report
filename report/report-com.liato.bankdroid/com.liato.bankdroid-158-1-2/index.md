title: com.liato.bankdroid

# com.liato.bankdroid

```
java.lang.RuntimeException
	at android.os.AsyncTask$3.done(AsyncTask.java:309)
	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:354)
	at java.util.concurrent.FutureTask.setException(FutureTask.java:223)
	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:234)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
	at java.lang.Thread.run(Thread.java:818)
Caused by: java.lang.IllegalArgumentException
	at java.net.URI.create(URI.java:733)
	at org.apache.http.client.methods.HttpGet.<init>(HttpGet.java:80)
	at eu.nullbyte.android.urllib.Urllib.openAsHttpResponse(Urllib.java:211)
	at eu.nullbyte.android.urllib.Urllib.openAsHttpResponse(Urllib.java:190)
	at eu.nullbyte.android.urllib.Urllib.openAsHttpResponse(Urllib.java:179)
	at eu.nullbyte.android.urllib.Urllib.open(Urllib.java:168)
	at eu.nullbyte.android.urllib.Urllib.open(Urllib.java:163)
	at eu.nullbyte.android.urllib.Urllib.open(Urllib.java:154)
	at com.liato.bankdroid.banking.banks.AppeakPoker.login(AppeakPoker.java:89)
	at com.liato.bankdroid.banking.banks.AppeakPoker.update(AppeakPoker.java:106)
	at com.liato.bankdroid.BankEditActivity$DataRetrieverTask.doInBackground(BankEditActivity.java:312)
	at com.liato.bankdroid.BankEditActivity$DataRetrieverTask.doInBackground(BankEditActivity.java:287)
	at android.os.AsyncTask$2.call(AsyncTask.java:295)
	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
	... 4 more

```



