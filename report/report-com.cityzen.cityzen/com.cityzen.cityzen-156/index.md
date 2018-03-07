title: com.cityzen.cityzen

# com.cityzen.cityzen

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// android.view.ViewRootImpl$CalledFromWrongThreadException: Only the original thread that created a view hierarchy can touch its views.
// 	at android.view.ViewRootImpl.checkThread(ViewRootImpl.java:6556)
// 	at android.view.ViewRootImpl.requestLayout(ViewRootImpl.java:907)
// 	at android.view.View.requestLayout(View.java:18728)
// 	at android.view.View.requestLayout(View.java:18728)
// 	at android.view.View.requestLayout(View.java:18728)
// 	at android.view.View.requestLayout(View.java:18728)
// 	at android.view.View.requestLayout(View.java:18728)
// 	at android.view.View.requestLayout(View.java:18728)
// 	at android.widget.RelativeLayout.requestLayout(RelativeLayout.java:360)
// 	at android.view.View.requestLayout(View.java:18728)
// 	at android.widget.RelativeLayout.requestLayout(RelativeLayout.java:360)
// 	at android.view.View.requestLayout(View.java:18728)
// 	at android.widget.RelativeLayout.requestLayout(RelativeLayout.java:360)
// 	at android.view.View.requestLayout(View.java:18728)
// 	at android.support.v7.widget.RecyclerView.requestLayout(RecyclerView.java:3852)
// 	at android.support.v7.widget.RecyclerView$RecyclerViewDataObserver.onChanged(RecyclerView.java:4937)
// 	at android.support.v7.widget.RecyclerView$AdapterDataObservable.notifyChanged(RecyclerView.java:11359)
// 	at android.support.v7.widget.RecyclerView$Adapter.notifyDataSetChanged(RecyclerView.java:6636)
// 	at com.cityzen.cityzen.Adapters.PlaceListAdapter.resetAdapter(PlaceListAdapter.java:71)
// 	at com.cityzen.cityzen.Fragments.SearchFragment$1$1.run(SearchFragment.java:149)
// 	at java.util.Timer$TimerImpl.run(Timer.java:284)

```



