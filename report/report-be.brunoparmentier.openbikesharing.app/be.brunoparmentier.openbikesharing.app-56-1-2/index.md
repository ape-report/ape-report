title: be.brunoparmentier.openbikesharing.app

# be.brunoparmentier.openbikesharing.app

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
android.database.sqlite.SQLiteReadOnlyDatabaseException
	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
	at be.brunoparmentier.openbikesharing.app.db.StationsDataSource.clearStations(StationsDataSource.java:71)
	at be.brunoparmentier.openbikesharing.app.db.StationsDataSource.storeStations(StationsDataSource.java:42)
	at be.brunoparmentier.openbikesharing.app.activities.StationsListActivity$JSONDownloadTask.onPostExecute(StationsListActivity.java:488)
	at be.brunoparmentier.openbikesharing.app.activities.StationsListActivity$JSONDownloadTask.onPostExecute(StationsListActivity.java:435)
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



