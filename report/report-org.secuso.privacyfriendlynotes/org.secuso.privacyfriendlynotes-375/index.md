title: org.secuso.privacyfriendlynotes

# org.secuso.privacyfriendlynotes

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.NullPointerException: Attempt to invoke virtual method 'void java.nio.channels.FileChannel.close()' on a null object reference
// 	at org.secuso.privacyfriendlynotes.AudioNoteActivity.saveToExternalStorage(AudioNoteActivity.java:689)
// 	at org.secuso.privacyfriendlynotes.AudioNoteActivity.onOptionsItemSelected(AudioNoteActivity.java:347)
// 	at android.app.Activity.onMenuItemSelected(Activity.java:2914)
// 	at android.support.v4.app.FragmentActivity.onMenuItemSelected(FragmentActivity.java:408)
// 	at android.support.v7.app.AppCompatActivity.onMenuItemSelected(AppCompatActivity.java:198)
// 	at android.support.v7.view.WindowCallbackWrapper.onMenuItemSelected(WindowCallbackWrapper.java:107)
// 	at android.support.v7.app.AppCompatDelegateImplV9.onMenuItemSelected(AppCompatDelegateImplV9.java:671)
// 	at android.support.v7.view.menu.MenuBuilder.dispatchMenuItemSelected(MenuBuilder.java:817)
// 	at android.support.v7.view.menu.MenuItemImpl.invoke(MenuItemImpl.java:156)
// 	at android.support.v7.view.menu.MenuBuilder.performItemAction(MenuBuilder.java:964)
// 	at android.support.v7.view.menu.MenuBuilder.performItemAction(MenuBuilder.java:954)
// 	at android.support.v7.widget.ActionMenuView.invokeItem(ActionMenuView.java:624)
// 	at android.support.v7.view.menu.ActionMenuItemView.onClick(ActionMenuItemView.java:157)
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



