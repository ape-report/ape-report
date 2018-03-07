title: com.icechen1.notable.pro

# com.icechen1.notable.pro

```
// java.lang.RuntimeException: Error receiving broadcast Intent { act=com.icechen1.notable.DATABASE_CHANGED flg=0x10 } in com.icechen1.notable.library.HistoryActivity$1@9df50d4
// 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:891)
// 	at android.os.Handler.handleCallback(Handler.java:739)
// 	at android.os.Handler.dispatchMessage(Handler.java:95)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
// Caused by: java.lang.IllegalStateException: attempt to re-open an already-closed object: SQLiteDatabase: /data/user/0/com.icechen1.notable.pro/databases/notifs.db
// 	at android.database.sqlite.SQLiteClosable.acquireReference(SQLiteClosable.java:55)
// 	at android.database.sqlite.SQLiteDatabase.queryWithFactory(SQLiteDatabase.java:1158)
// 	at android.database.sqlite.SQLiteDatabase.query(SQLiteDatabase.java:1034)
// 	at android.database.sqlite.SQLiteDatabase.query(SQLiteDatabase.java:1202)
// 	at com.icechen1.notable.library.utils.d.d(Unknown Source)
// 	at com.icechen1.notable.library.HistoryActivity$1.onReceive(Unknown Source)
// 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:881)
// 	... 7 more

```



