title: org.primftpd

# org.primftpd

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.NumberFormatException: Invalid int: ""
// 	at java.lang.Integer.invalidInt(Integer.java:138)
// 	at java.lang.Integer.parseInt(Integer.java:358)
// 	at java.lang.Integer.parseInt(Integer.java:334)
// 	at org.primftpd.prefs.PortEditTextPreference.onPreferenceChange(PortEditTextPreference.java:31)
// 	at android.preference.Preference.callChangeListener(Preference.java:939)
// 	at android.preference.EditTextPreference.onDialogClosed(EditTextPreference.java:145)
// 	at android.preference.DialogPreference.onDismiss(DialogPreference.java:395)
// 	at android.app.Dialog$ListenersHandler.handleMessage(Dialog.java:1323)
// 	at android.os.Handler.dispatchMessage(Handler.java:102)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)

```



