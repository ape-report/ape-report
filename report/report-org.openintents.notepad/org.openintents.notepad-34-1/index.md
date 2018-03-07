title: org.openintents.notepad

# org.openintents.notepad

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
android.database.StaleDataException
	at android.database.AbstractWindowedCursor.checkPosition(AbstractWindowedCursor.java:139)
	at android.database.AbstractWindowedCursor.getInt(AbstractWindowedCursor.java:68)
	at android.database.CursorWrapper.getInt(CursorWrapper.java:122)
	at org.openintents.notepad.NoteEditor.isNoteUnencrypted(NoteEditor.java:1301)
	at org.openintents.notepad.NoteEditor.onPrepareOptionsMenu(NoteEditor.java:1448)
	at android.app.Activity.onPreparePanel(Activity.java:2870)
	at com.android.internal.policy.PhoneWindow.preparePanel(PhoneWindow.java:595)
	at com.android.internal.policy.PhoneWindow.doInvalidatePanelMenu(PhoneWindow.java:939)
	at com.android.internal.policy.PhoneWindow$1.run(PhoneWindow.java:271)
	at android.os.Handler.handleCallback(Handler.java:739)
	at android.os.Handler.dispatchMessage(Handler.java:95)
	at android.os.Looper.loop(Looper.java:148)
	at android.app.ActivityThread.main(ActivityThread.java:5417)
	at java.lang.reflect.Method.invoke(Native Method)
	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)

```



