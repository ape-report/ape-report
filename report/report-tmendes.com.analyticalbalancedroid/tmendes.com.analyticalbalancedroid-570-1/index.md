title: tmendes.com.analyticalbalancedroid

# tmendes.com.analyticalbalancedroid

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
java.lang.NumberFormatException
	at java.lang.StringToReal.invalidReal(StringToReal.java:63)
	at java.lang.StringToReal.initialParse(StringToReal.java:164)
	at java.lang.StringToReal.parseFloat(StringToReal.java:323)
	at java.lang.Float.parseFloat(Float.java:306)
	at java.lang.Float.valueOf(Float.java:343)
	at tmendes.com.analyticalbalancedroid.MainActivity.j(Unknown Source)
	at tmendes.com.analyticalbalancedroid.MainActivity.b(Unknown Source)
	at tmendes.com.analyticalbalancedroid.MainActivity$2.onTextChanged(Unknown Source)
	at android.widget.TextView.sendOnTextChanged(TextView.java:7988)
	at android.widget.TextView.handleTextChanged(TextView.java:8050)
	at android.widget.TextView$ChangeWatcher.onTextChanged(TextView.java:10154)
	at android.text.SpannableStringBuilder.sendTextChanged(SpannableStringBuilder.java:1033)
	at android.text.SpannableStringBuilder.replace(SpannableStringBuilder.java:559)
	at android.text.SpannableStringBuilder.replace(SpannableStringBuilder.java:492)
	at android.text.SpannableStringBuilder.replace(SpannableStringBuilder.java:491)
	at android.view.inputmethod.BaseInputConnection.replaceText(BaseInputConnection.java:685)
	at android.view.inputmethod.BaseInputConnection.commitText(BaseInputConnection.java:197)
	at com.android.internal.widget.EditableInputConnection.commitText(EditableInputConnection.java:184)
	at com.android.internal.view.IInputConnectionWrapper.executeMessage(IInputConnectionWrapper.java:286)
	at com.android.internal.view.IInputConnectionWrapper$MyHandler.handleMessage(IInputConnectionWrapper.java:78)
	at android.os.Handler.dispatchMessage(Handler.java:102)
	at android.os.Looper.loop(Looper.java:148)
	at android.app.ActivityThread.main(ActivityThread.java:5417)
	at java.lang.reflect.Method.invoke(Native Method)
	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)

```



