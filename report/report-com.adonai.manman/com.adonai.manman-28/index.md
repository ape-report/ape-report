title: com.adonai.manman

# com.adonai.manman

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.RuntimeException: An error occurred while executing doInBackground()
// 	at android.support.v4.c.k$3.done(Unknown Source)
// 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:354)
// 	at java.util.concurrent.FutureTask.setException(FutureTask.java:223)
// 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
// 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
// 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
// 	at java.lang.Thread.run(Thread.java:818)
// Caused by: java.lang.NullPointerException: Attempt to invoke virtual method 'org.jsoup.select.Elements org.jsoup.nodes.Element.select(java.lang.String)' on a null object reference
// 	at com.adonai.manman.ManPageDialogFragment$RetrieveManPageCallback$1.getLinks(Unknown Source)
// 	at com.adonai.manman.ManPageDialogFragment$RetrieveManPageCallback$1.loadInBackground(Unknown Source)
// 	at com.adonai.manman.ManPageDialogFragment$RetrieveManPageCallback$1.loadInBackground(Unknown Source)
// 	at com.adonai.manman.misc.AbstractNetworkAsyncLoader.onLoadInBackground(Unknown Source)
// 	at android.support.v4.c.a$a.a(Unknown Source)
// 	at android.support.v4.c.a$a.a(Unknown Source)
// 	at android.support.v4.c.k$2.call(Unknown Source)
// 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
// 	... 3 more

```



