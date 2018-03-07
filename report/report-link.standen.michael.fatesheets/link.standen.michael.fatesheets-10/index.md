title: link.standen.michael.fatesheets

# link.standen.michael.fatesheets

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.IllegalStateException: Observer link.standen.michael.fatesheets.view.AdapterLinearLayout$1@bb65e44 was not registered.
// 	at android.database.Observable.unregisterObserver(Observable.java:69)
// 	at android.widget.BaseAdapter.unregisterDataSetObserver(BaseAdapter.java:42)
// 	at link.standen.michael.fatesheets.view.AdapterLinearLayout.onDetachedFromWindow(AdapterLinearLayout.java:62)
// 	at android.view.View.dispatchDetachedFromWindow(View.java:14561)
// 	at android.view.ViewGroup.dispatchDetachedFromWindow(ViewGroup.java:3071)
// 	at android.view.ViewGroup.dispatchDetachedFromWindow(ViewGroup.java:3063)
// 	at android.view.ViewGroup.dispatchDetachedFromWindow(ViewGroup.java:3063)
// 	at android.view.ViewGroup.removeViewInternal(ViewGroup.java:4603)
// 	at android.view.ViewGroup.removeViewInternal(ViewGroup.java:4576)
// 	at android.view.ViewGroup.removeView(ViewGroup.java:4507)
// 	at android.support.v4.app.FragmentManagerImpl.moveToState(FragmentManager.java:1411)
// 	at android.support.v4.app.FragmentManagerImpl.moveFragmentToExpectedState(FragmentManager.java:1528)
// 	at android.support.v4.app.BackStackRecord.executeOps(BackStackRecord.java:753)
// 	at android.support.v4.app.FragmentManagerImpl.executeOps(FragmentManager.java:2363)
// 	at android.support.v4.app.FragmentManagerImpl.executeOpsTogether(FragmentManager.java:2149)
// 	at android.support.v4.app.FragmentManagerImpl.optimizeAndExecuteOps(FragmentManager.java:2103)
// 	at android.support.v4.app.FragmentManagerImpl.execPendingActions(FragmentManager.java:2013)
// 	at android.support.v4.app.Fragment.performStart(Fragment.java:2214)
// 	at android.support.v4.app.FragmentManagerImpl.moveToState(FragmentManager.java:1340)
// 	at android.support.v4.app.FragmentManagerImpl.performPendingDeferredStart(FragmentManager.java:1132)
// 	at android.support.v4.app.FragmentManagerImpl.startPendingDeferredFragments(FragmentManager.java:1632)
// 	at android.support.v4.app.FragmentManagerImpl.doPendingDeferredStart(FragmentManager.java:2465)
// 	at android.support.v4.app.FragmentManagerImpl.execSingleAction(FragmentManager.java:1990)
// 	at android.support.v4.app.BackStackRecord.commitNowAllowingStateLoss(BackStackRecord.java:626)
// 	at android.support.v4.app.FragmentPagerAdapter.finishUpdate(FragmentPagerAdapter.java:143)
// 	at android.support.v4.view.ViewPager.populate(ViewPager.java:1268)
// 	at android.support.v4.view.ViewPager.setCurrentItemInternal(ViewPager.java:668)
// 	at android.support.v4.view.ViewPager.setCurrentItemInternal(ViewPager.java:630)
// 	at android.support.v4.view.ViewPager.setCurrentItem(ViewPager.java:611)
// 	at android.support.design.widget.TabLayout$ViewPagerOnTabSelectedListener.onTabSelected(TabLayout.java:2191)
// 	at android.support.design.widget.TabLayout.dispatchTabSelected(TabLayout.java:1164)
// 	at android.support.design.widget.TabLayout.selectTab(TabLayout.java:1157)
// 	at android.support.design.widget.TabLayout.selectTab(TabLayout.java:1127)
// 	at android.support.design.widget.TabLayout$Tab.select(TabLayout.java:1426)
// 	at android.support.design.widget.TabLayout$TabView.performClick(TabLayout.java:1536)
// 	at android.view.View$PerformClick.run(View.java:21153)
// 	at android.os.Handler.handleCallback(Handler.java:739)
// 	at android.os.Handler.dispatchMessage(Handler.java:95)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)

```



