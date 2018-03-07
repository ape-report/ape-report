title: com.rascarlo.aurdroid

# com.rascarlo.aurdroid

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// android.view.InflateException: Binary XML file line #27: Binary XML file line #27: Error inflating class TextView
// 	at android.view.LayoutInflater.inflate(LayoutInflater.java:539)
// 	at android.view.LayoutInflater.inflate(LayoutInflater.java:423)
// 	at android.view.LayoutInflater.inflate(LayoutInflater.java:374)
// 	at android.widget.Toast.makeText(Toast.java:263)
// 	at com.rascarlo.aurdroid.AurPackageDetailsFragment.onOptionsItemSelected(AurPackageDetailsFragment.java:214)
// 	at android.support.v4.app.Fragment.performOptionsItemSelected(Fragment.java:2394)
// 	at android.support.v4.app.FragmentManagerImpl.dispatchOptionsItemSelected(FragmentManager.java:3326)
// 	at android.support.v4.app.FragmentController.dispatchOptionsItemSelected(FragmentController.java:344)
// 	at android.support.v4.app.FragmentActivity.onMenuItemSelected(FragmentActivity.java:386)
// 	at android.support.v7.app.AppCompatActivity.onMenuItemSelected(AppCompatActivity.java:195)
// 	at android.support.v7.view.WindowCallbackWrapper.onMenuItemSelected(WindowCallbackWrapper.java:108)
// 	at android.support.v7.view.WindowCallbackWrapper.onMenuItemSelected(WindowCallbackWrapper.java:108)
// 	at android.support.v7.app.ToolbarActionBar$2.onMenuItemClick(ToolbarActionBar.java:63)
// 	at android.support.v7.widget.Toolbar$1.onMenuItemClick(Toolbar.java:203)
// 	at android.support.v7.widget.ActionMenuView$MenuBuilderCallback.onMenuItemSelected(ActionMenuView.java:780)
// 	at android.support.v7.view.menu.MenuBuilder.dispatchMenuItemSelected(MenuBuilder.java:822)
// 	at android.support.v7.view.menu.MenuItemImpl.invoke(MenuItemImpl.java:171)
// 	at android.support.v7.view.menu.MenuBuilder.performItemAction(MenuBuilder.java:973)
// 	at android.support.v7.view.menu.MenuPopup.onItemClick(MenuPopup.java:127)
// 	at android.widget.AdapterView.performItemClick(AdapterView.java:310)
// 	at android.widget.AbsListView.performItemClick(AbsListView.java:1145)
// 	at android.widget.AbsListView$PerformClick.run(AbsListView.java:3066)
// 	at android.widget.AbsListView$3.run(AbsListView.java:3903)
// 	at android.os.Handler.handleCallback(Handler.java:739)
// 	at android.os.Handler.dispatchMessage(Handler.java:95)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
// Caused by: android.view.InflateException: Binary XML file line #27: Error inflating class TextView
// 	at android.view.LayoutInflater.createViewFromTag(LayoutInflater.java:782)
// 	at android.view.LayoutInflater.createViewFromTag(LayoutInflater.java:704)
// 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:835)
// 	at android.view.LayoutInflater.rInflateChildren(LayoutInflater.java:798)
// 	at android.view.LayoutInflater.inflate(LayoutInflater.java:515)
// 	... 29 more
// Caused by: java.lang.ArrayIndexOutOfBoundsException: length=16; index=65
// 	at android.content.res.StringBlock.get(StringBlock.java:65)
// 	at android.content.res.XmlBlock$Parser.getPooledString(XmlBlock.java:458)
// 	at android.content.res.TypedArray.loadStringValueAt(TypedArray.java:1151)
// 	at android.content.res.TypedArray.getString(TypedArray.java:195)
// 	at android.support.v7.widget.TintTypedArray.getString(TintTypedArray.java:142)
// 	at android.support.v7.widget.AppCompatTextHelper.updateTypefaceAndStyle(AppCompatTextHelper.java:243)
// 	at android.support.v7.widget.AppCompatTextHelper.loadFromAttributes(AppCompatTextHelper.java:165)
// 	at android.support.v7.widget.AppCompatTextHelperV17.loadFromAttributes(AppCompatTextHelperV17.java:38)
// 	at android.support.v7.widget.AppCompatTextView.<init>(AppCompatTextView.java:82)
// 	at android.support.v7.widget.AppCompatTextView.<init>(AppCompatTextView.java:72)
// 	at android.support.v7.app.AppCompatViewInflater.createView(AppCompatViewInflater.java:103)
// 	at android.support.v7.app.AppCompatDelegateImplV9.createView(AppCompatDelegateImplV9.java:1016)
// 	at android.support.v7.app.AppCompatDelegateImplV9.onCreateView(AppCompatDelegateImplV9.java:1073)
// 	at android.view.LayoutInflater.createViewFromTag(LayoutInflater.java:746)
// 	... 33 more

```



