title: org.horaapps.leafpic

# org.horaapps.leafpic

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.NullPointerException: Attempt to invoke virtual method 'int java.lang.String.lastIndexOf(int)' on a null object reference
// 	at org.horaapps.leafpic.util.StringUtils.getMimeType(StringUtils.java:17)
// 	at org.horaapps.leafpic.data.Media.<init>(Media.java:53)
// 	at org.horaapps.leafpic.data.Media.<init>(Media.java:63)
// 	at org.horaapps.leafpic.activities.PlayerActivity.onOptionsItemSelected(PlayerActivity.java:183)
// 	at android.app.Activity.onMenuItemSelected(Activity.java:2914)
// 	at android.support.v4.app.FragmentActivity.onMenuItemSelected(FragmentActivity.java:421)
// 	at android.support.v7.app.AppCompatActivity.onMenuItemSelected(AppCompatActivity.java:188)
// 	at android.support.v7.view.WindowCallbackWrapper.onMenuItemSelected(WindowCallbackWrapper.java:103)
// 	at android.support.v7.view.WindowCallbackWrapper.onMenuItemSelected(WindowCallbackWrapper.java:103)
// 	at android.support.v7.app.ToolbarActionBar$2.onMenuItemClick(ToolbarActionBar.java:69)
// 	at android.support.v7.widget.Toolbar$1.onMenuItemClick(Toolbar.java:202)
// 	at android.support.v7.widget.ActionMenuView$MenuBuilderCallback.onMenuItemSelected(ActionMenuView.java:761)
// 	at android.support.v7.view.menu.MenuBuilder.dispatchMenuItemSelected(MenuBuilder.java:810)
// 	at android.support.v7.view.menu.MenuItemImpl.invoke(MenuItemImpl.java:152)
// 	at android.support.v7.view.menu.MenuBuilder.performItemAction(MenuBuilder.java:957)
// 	at android.support.v7.view.menu.MenuBuilder.performItemAction(MenuBuilder.java:947)
// 	at android.support.v7.widget.ActionMenuView.invokeItem(ActionMenuView.java:618)
// 	at android.support.v7.view.menu.ActionMenuItemView.onClick(ActionMenuItemView.java:155)
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



