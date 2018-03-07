title: com.orgzly

# com.orgzly

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
java.lang.IllegalStateException
	at android.database.sqlite.SQLiteClosable.acquireReference(SQLiteClosable.java:55)
	at android.database.sqlite.SQLiteQuery.fillWindow(SQLiteQuery.java:58)
	at android.database.sqlite.SQLiteCursor.fillWindow(SQLiteCursor.java:151)
	at android.database.sqlite.SQLiteCursor.onMove(SQLiteCursor.java:123)
	at android.database.AbstractCursor.moveToPosition(AbstractCursor.java:236)
	at android.database.CursorWrapper.moveToPosition(CursorWrapper.java:197)
	at android.support.v4.widget.f.getItemId(CursorAdapter.java:241)
	at android.widget.AdapterView.getItemIdAtPosition(AdapterView.java:795)
	at android.widget.AdapterView.setSelectedPositionInt(AdapterView.java:1209)
	at android.widget.ListView.setAdapter(ListView.java:505)
	at android.support.v4.b.z.a(ListFragment.java:184)
	at android.support.v4.b.z.aa(ListFragment.java:367)
	at android.support.v4.b.z.a(ListFragment.java:147)
	at com.orgzly.android.ui.b.j.a(BooksFragment.java:145)
	at android.support.v4.b.s.a(FragmentManager.java:1355)
	at android.support.v4.b.s.d(FragmentManager.java:1569)
	at android.support.v4.b.s.a(FragmentManager.java:1636)
	at android.support.v4.b.g.b(BackStackRecord.java:807)
	at android.support.v4.b.s.b(FragmentManager.java:2412)
	at android.support.v4.b.s.a(FragmentManager.java:2201)
	at android.support.v4.b.s.b(FragmentManager.java:2155)
	at android.support.v4.b.s.e(FragmentManager.java:2064)
	at android.support.v4.b.s$1.run(FragmentManager.java:718)
	at android.os.Handler.handleCallback(Handler.java:739)
	at android.os.Handler.dispatchMessage(Handler.java:95)
	at android.os.Looper.loop(Looper.java:148)
	at android.app.ActivityThread.main(ActivityThread.java:5417)
	at java.lang.reflect.Method.invoke(Native Method)
	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)

```



