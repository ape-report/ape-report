title: github.yaa110.memento

# github.yaa110.memento

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.IllegalStateException: Cannot perform this operation because the connection pool has been closed.
// 	at android.database.sqlite.SQLiteConnectionPool.throwIfClosedLocked(SQLiteConnectionPool.java:962)
// 	at android.database.sqlite.SQLiteConnectionPool.waitForConnection(SQLiteConnectionPool.java:677)
// 	at android.database.sqlite.SQLiteConnectionPool.acquireConnection(SQLiteConnectionPool.java:348)
// 	at android.database.sqlite.SQLiteSession.acquireConnection(SQLiteSession.java:894)
// 	at android.database.sqlite.SQLiteSession.executeForCursorWindow(SQLiteSession.java:834)
// 	at android.database.sqlite.SQLiteQuery.fillWindow(SQLiteQuery.java:62)
// 	at android.database.sqlite.SQLiteCursor.fillWindow(SQLiteCursor.java:143)
// 	at android.database.sqlite.SQLiteCursor.getCount(SQLiteCursor.java:132)
// 	at android.database.AbstractCursor.moveToPosition(AbstractCursor.java:219)
// 	at android.database.AbstractCursor.moveToFirst(AbstractCursor.java:258)
// 	at github.yaa110.memento.a.a.a(Unknown Source)
// 	at github.yaa110.memento.c.a$6.run(Unknown Source)

```



