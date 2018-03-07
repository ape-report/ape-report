title: com.yubico.yubioath

# com.yubico.yubioath

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.IllegalStateException: currentFocus must not be null
// 	at com.yubico.yubioath.ui.add.AddCredentialFragment.e(Unknown Source)
// 	at com.yubico.yubioath.ui.add.AddCredentialActivity.onOptionsItemSelected(Unknown Source)
// 	at android.app.Activity.onMenuItemSelected(Activity.java:2914)
// 	at android.support.v4.a.j.onMenuItemSelected(Unknown Source)
// 	at android.support.v7.app.c.onMenuItemSelected(Unknown Source)
// 	at android.support.v7.view.i.onMenuItemSelected(Unknown Source)
// 	at android.support.v7.app.k.a(Unknown Source)
// 	at android.support.v7.view.menu.h.a(Unknown Source)
// 	at android.support.v7.view.menu.j.b(Unknown Source)
// 	at android.support.v7.view.menu.h.a(Unknown Source)
// 	at android.support.v7.view.menu.h.a(Unknown Source)
// 	at android.support.v7.widget.ActionMenuView.a(Unknown Source)
// 	at android.support.v7.view.menu.ActionMenuItemView.onClick(Unknown Source)
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



