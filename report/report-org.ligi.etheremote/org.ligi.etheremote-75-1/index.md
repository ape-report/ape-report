title: org.ligi.etheremote

# org.ligi.etheremote

```
// java.lang.IndexOutOfBoundsException: setSpan (22 ... 22) ends beyond length 9
// 	at android.text.SpannableStringBuilder.checkRange(SpannableStringBuilder.java:1090)
// 	at android.text.SpannableStringBuilder.setSpan(SpannableStringBuilder.java:665)
// 	at android.text.SpannableStringBuilder.setSpan(SpannableStringBuilder.java:658)
// 	at android.text.Selection.setSelection(Selection.java:76)
// 	at android.text.Selection.setSelection(Selection.java:87)
// 	at android.widget.EditText.setSelection(EditText.java:98)
// 	at org.ligi.etheremote.BlockListActivity.refresh(BlockListActivity.kt:65)
// 	at org.ligi.etheremote.BlockListActivity$onCreate$$inlined$verticalLayout$lambda$3.invoke(BlockListActivity.kt:48)
// 	at org.ligi.etheremote.BlockListActivity$onCreate$$inlined$verticalLayout$lambda$3.invoke(BlockListActivity.kt:11)
// 	at org.jetbrains.anko.Sdk15ListenersKt__ListenersKt$sam$OnClickListener$6dc65f2d.onClick(Listeners.kt)
// 	at android.view.View.performClick(View.java:5204)
// 	at android.view.View$PerformClick.run(View.java:21153)
// 	at android.os.Handler.handleCallback(Handler.java:739)
// 	at android.os.Handler.dispatchMessage(Handler.java:95)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)

```



