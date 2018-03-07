title: mobi.boilr.boilr

# mobi.boilr.boilr

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.NumberFormatException: Invalid long: ""
// 	at java.lang.Long.invalidLong(Long.java:124)
// 	at java.lang.Long.parseLong(Long.java:345)
// 	at java.lang.Long.parseLong(Long.java:321)
// 	at mobi.boilr.boilr.views.fragments.AlarmSettingsFragment$OnAlarmSettingsPreferenceChangeListener.onPreferenceChange(AlarmSettingsFragment.java:113)
// 	at mobi.boilr.boilr.views.fragments.PriceChangeAlarmSettingsFragment$OnPriceChangeSettingsPreferenceChangeListener.onPreferenceChange(PriceChangeAlarmSettingsFragment.java:49)
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



