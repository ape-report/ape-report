title: edu.rit.poe.atomix

# edu.rit.poe.atomix

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
java.lang.IllegalStateException
	at android.database.sqlite.SQLiteConnectionPool.throwIfClosedLocked(SQLiteConnectionPool.java:962)
	at android.database.sqlite.SQLiteConnectionPool.waitForConnection(SQLiteConnectionPool.java:599)
	at android.database.sqlite.SQLiteConnectionPool.acquireConnection(SQLiteConnectionPool.java:348)
	at android.database.sqlite.SQLiteSession.acquireConnection(SQLiteSession.java:894)
	at android.database.sqlite.SQLiteSession.executeForCursorWindow(SQLiteSession.java:834)
	at android.database.sqlite.SQLiteQuery.fillWindow(SQLiteQuery.java:62)
	at android.database.sqlite.SQLiteCursor.fillWindow(SQLiteCursor.java:151)
	at android.database.sqlite.SQLiteCursor.onMove(SQLiteCursor.java:123)
	at android.database.AbstractCursor.moveToPosition(AbstractCursor.java:236)
	at android.database.AbstractCursor.moveToFirst(AbstractCursor.java:258)
	at edu.rit.poe.atomix.MenuActivity$1.onClick(MenuActivity.java:147)
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



