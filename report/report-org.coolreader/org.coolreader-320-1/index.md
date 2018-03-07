title: org.coolreader

# org.coolreader

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
java.lang.NullPointerException
	at org.coolreader.crengine.FileBrowser.<init>(FileBrowser.java:192)
	at org.coolreader.CoolReader$7.run(CoolReader.java:650)
	at org.coolreader.db.CRDBServiceAccessor.bind(CRDBServiceAccessor.java:40)
	at org.coolreader.crengine.BaseActivity.waitForCRDBService(BaseActivity.java:85)
	at org.coolreader.CoolReader.runInBrowser(CoolReader.java:643)
	at org.coolreader.CoolReader.showBrowser(CoolReader.java:772)
	at org.coolreader.CoolReader.showDirectory(CoolReader.java:811)
	at org.coolreader.crengine.CRRootView$14.onClick(CRRootView.java:494)
	at android.view.View.performClick(View.java:5204)
	at android.view.View$PerformClick.run(View.java:21153)
	at android.os.Handler.handleCallback(Handler.java:739)
	at android.os.Handler.dispatchMessage(Handler.java:95)
	at android.os.Looper.loop(Looper.java:148)
	at android.app.ActivityThread.main(ActivityThread.java:5417)
	at java.lang.reflect.Method.invoke(Native Method)
	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)

```



