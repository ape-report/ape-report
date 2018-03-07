title: app.librenews.io.librenews

# app.librenews.io.librenews

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
java.lang.NullPointerException
	at app.librenews.io.librenews.views.SettingsActivityFragment.onSharedPreferenceChanged(SettingsActivityFragment.java:26)
	at android.app.SharedPreferencesImpl$EditorImpl.notifyListeners(SharedPreferencesImpl.java:479)
	at android.app.SharedPreferencesImpl$EditorImpl.apply(SharedPreferencesImpl.java:387)
	at android.preference.Preference.tryCommit(Preference.java:1415)
	at android.preference.Preference.persistString(Preference.java:1448)
	at android.preference.ListPreference.setValue(ListPreference.java:148)
	at android.preference.ListPreference.onDialogClosed(ListPreference.java:283)
	at android.preference.DialogPreference.onDismiss(DialogPreference.java:395)
	at android.app.Dialog$ListenersHandler.handleMessage(Dialog.java:1323)
	at android.os.Handler.dispatchMessage(Handler.java:102)
	at android.os.Looper.loop(Looper.java:148)
	at android.app.ActivityThread.main(ActivityThread.java:5417)
	at java.lang.reflect.Method.invoke(Native Method)
	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)

```



