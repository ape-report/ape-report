title: com.darshancomputing.BatteryIndicatorPro

# com.darshancomputing.BatteryIndicatorPro

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
java.lang.IllegalStateException
	at android.support.v4.app.Fragment.startActivityForResult(Fragment.java:847)
	at com.darshancomputing.BatteryIndicatorPro.CurrentInfoFragment.mStartActivity(CurrentInfoFragment.java:453)
	at com.darshancomputing.BatteryIndicatorPro.CurrentInfoFragment.onOptionsItemSelected(CurrentInfoFragment.java:262)
	at android.support.v4.app.Fragment.performOptionsItemSelected(Fragment.java:1568)
	at android.support.v4.app.FragmentManagerImpl.dispatchOptionsItemSelected(FragmentManager.java:1978)
	at android.support.v4.app.FragmentActivity.onMenuItemSelected(FragmentActivity.java:367)
	at com.android.internal.policy.PhoneWindow.onMenuItemSelected(PhoneWindow.java:1151)
	at com.android.internal.view.menu.MenuBuilder.dispatchMenuItemSelected(MenuBuilder.java:761)
	at com.android.internal.view.menu.MenuItemImpl.invoke(MenuItemImpl.java:152)
	at com.android.internal.view.menu.MenuBuilder.performItemAction(MenuBuilder.java:904)
	at com.android.internal.view.menu.MenuBuilder.performItemAction(MenuBuilder.java:894)
	at android.widget.ActionMenuView.invokeItem(ActionMenuView.java:616)
	at com.android.internal.view.menu.ActionMenuItemView.onClick(ActionMenuItemView.java:141)
	at android.view.View.performClick(View.java:5204)
	at android.view.View$PerformClick.run(View.java:21153)
	at android.os.Handler.handleCallback(Handler.java:739)
	at android.os.Handler.dispatchMessage(Handler.java:95)
	at android.os.Looper.loop(Looper.java:148)
	at android.app.ActivityThread.main(ActivityThread.java:5417)
	at java.lang.reflect.Method.invoke(Native Method)
	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)

```



