title: de.schildbach.wallet

# de.schildbach.wallet

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// org.bitcoinj.core.WrongNetworkException: Version code of address did not match acceptable versions for network: 111 not in [0, 5]
// 	at org.bitcoinj.core.Address.<init>(Address.java:113)
// 	at org.bitcoinj.core.Address.fromBase58(Address.java:93)
// 	at de.schildbach.wallet.ui.EditAddressBookEntryFragment.onCreateDialog(EditAddressBookEntryFragment.java:96)
// 	at android.app.DialogFragment.getLayoutInflater(DialogFragment.java:407)
// 	at android.app.FragmentManagerImpl.moveToState(FragmentManager.java:973)
// 	at android.app.FragmentManagerImpl.moveToState(FragmentManager.java:1148)
// 	at android.app.BackStackRecord.run(BackStackRecord.java:793)
// 	at android.app.FragmentManagerImpl.execPendingActions(FragmentManager.java:1535)
// 	at android.app.FragmentManagerImpl$1.run(FragmentManager.java:482)
// 	at android.os.Handler.handleCallback(Handler.java:739)
// 	at android.os.Handler.dispatchMessage(Handler.java:95)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)

```



