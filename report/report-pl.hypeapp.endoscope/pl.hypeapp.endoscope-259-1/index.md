title: pl.hypeapp.endoscope

# pl.hypeapp.endoscope

```
// java.lang.RuntimeException: Unable to start activity ComponentInfo{pl.hypeapp.endoscope/pl.hypeapp.endoscope.ui.activity.StartStreamActivity}: java.lang.IllegalStateException: You must disable foreground dispatching while your activity is still resumed
// 	at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:2416)
// 	at android.app.ActivityThread.handleLaunchActivity(ActivityThread.java:2476)
// 	at android.app.ActivityThread.-wrap11(ActivityThread.java)
// 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
// 	at android.os.Handler.dispatchMessage(Handler.java:102)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
// Caused by: java.lang.IllegalStateException: You must disable foreground dispatching while your activity is still resumed
// 	at android.nfc.NfcAdapter.disableForegroundDispatchInternal(NfcAdapter.java:1247)
// 	at android.nfc.NfcAdapter.disableForegroundDispatch(NfcAdapter.java:1233)
// 	at pl.hypeapp.endoscope.ui.fragment.NfcFragment.initNfcAdapter(NfcFragment.java:42)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at net.grandcentrix.thirtyinch.callonmainthread.CallOnMainThreadInvocationHandler.handleInvocation(CallOnMainThreadInvocationHandler.java:55)
// 	at net.grandcentrix.thirtyinch.util.AbstractInvocationHandler.invoke(AbstractInvocationHandler.java:84)
// 	at java.lang.reflect.Proxy.invoke(Proxy.java:393)
// 	at $Proxy3.initNfcAdapter(Unknown Source)
// 	at pl.hypeapp.endoscope.presenter.NfcPresenter.onAttachView(NfcPresenter.java:32)
// 	at pl.hypeapp.endoscope.presenter.NfcPresenter.onAttachView(NfcPresenter.java:14)
// 	at net.grandcentrix.thirtyinch.TiPresenter.attachView(TiPresenter.java:186)
// 	at net.grandcentrix.thirtyinch.internal.PresenterViewBinder.bindView(PresenterViewBinder.java:83)
// 	at net.grandcentrix.thirtyinch.internal.TiFragmentDelegate$1.run(TiFragmentDelegate.java:242)
// 	at net.grandcentrix.thirtyinch.internal.UiThreadExecutor.execute(UiThreadExecutor.java:39)
// 	at net.grandcentrix.thirtyinch.internal.TiFragmentDelegate.onStart_afterSuper(TiFragmentDelegate.java:238)
// 	at net.grandcentrix.thirtyinch.TiFragment.onStart(TiFragment.java:154)
// 	at android.support.v4.app.Fragment.performStart(Fragment.java:2215)
// 	at android.support.v4.app.FragmentManagerImpl.moveToState(FragmentManager.java:1340)
// 	at android.support.v4.app.FragmentManagerImpl.moveFragmentToExpectedState(FragmentManager.java:1528)
// 	at android.support.v4.app.FragmentManagerImpl.moveToState(FragmentManager.java:1595)
// 	at android.support.v4.app.FragmentManagerImpl.dispatchStart(FragmentManager.java:2893)
// 	at android.support.v4.app.FragmentController.dispatchStart(FragmentController.java:212)
// 	at android.support.v4.app.FragmentActivity.onStart(FragmentActivity.java:613)
// 	at android.support.v7.app.AppCompatActivity.onStart(AppCompatActivity.java:178)
// 	at net.grandcentrix.thirtyinch.TiActivity.onStart(TiActivity.java:203)
// 	at android.app.Instrumentation.callActivityOnStart(Instrumentation.java:1237)
// 	at android.app.Activity.performStart(Activity.java:6268)
// 	at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:2379)
// 	... 9 more

```



