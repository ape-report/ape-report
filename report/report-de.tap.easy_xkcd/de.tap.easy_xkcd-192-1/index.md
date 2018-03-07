title: de.tap.easy_xkcd

# de.tap.easy_xkcd

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.IllegalStateException: Fragment has not been attached yet.
// 	at android.support.v4.app.Fragment.instantiateChildFragmentManager(Fragment.java:2154)
// 	at android.support.v4.app.Fragment.getChildFragmentManager(Fragment.java:704)
// 	at de.tap.easy_xkcd.fragments.whatIf.WhatIfOverviewFragment$GetDoc.onPostExecute(WhatIfOverviewFragment.java:143)
// 	at de.tap.easy_xkcd.fragments.whatIf.WhatIfOverviewFragment$GetDoc.onPostExecute(WhatIfOverviewFragment.java:109)
// 	at android.os.AsyncTask.finish(AsyncTask.java:651)
// 	at android.os.AsyncTask.-wrap1(AsyncTask.java)
// 	at android.os.AsyncTask$InternalHandler.handleMessage(AsyncTask.java:668)
// 	at android.os.Handler.dispatchMessage(Handler.java:102)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)

```



