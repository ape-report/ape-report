title: com.lostrealm.lembretes

# com.lostrealm.lembretes

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String com.lostrealm.lembretes.Meal.getSummary()' on a null object reference
// 	at com.lostrealm.lembretes.MainIntentService.manageAlwaysOnNotification(MainIntentService.java:125)
// 	at com.lostrealm.lembretes.MainIntentService.onHandleIntent(MainIntentService.java:69)
// 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
// 	at android.os.Handler.dispatchMessage(Handler.java:102)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.os.HandlerThread.run(HandlerThread.java:61)

```



