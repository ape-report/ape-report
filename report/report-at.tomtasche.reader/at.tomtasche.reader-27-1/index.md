title: at.tomtasche.reader

# at.tomtasche.reader

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
java.lang.NullPointerException
	at xml.Node.<init>(Node.java:46)
	at openoffice.html.odt.TranslatorOdt.handleContentImpl(TranslatorOdt.java:232)
	at openoffice.html.odt.TranslatorOdt.handleContentImpl(TranslatorOdt.java:258)
	at openoffice.html.odt.TranslatorOdt.handleContentImpl(TranslatorOdt.java:258)
	at openoffice.html.odt.TranslatorOdt.handleContent(TranslatorOdt.java:218)
	at openoffice.html.odt.TranslatorOdt.translate(TranslatorOdt.java:149)
	at at.tomtasche.reader.background.openoffice.OpenDocumentWrapper.translate(OpenDocumentWrapper.java:34)
	at at.tomtasche.reader.background.openoffice.JOpenDocumentWrapper.getPage(JOpenDocumentWrapper.java:145)
	at at.tomtasche.reader.background.DocumentLoader.getPage(DocumentLoader.java:207)
	at at.tomtasche.reader.background.service.DocumentService.getData(DocumentService.java:92)
	at at.tomtasche.reader.ui.widget.DocumentFragment.reload(DocumentFragment.java:47)
	at at.tomtasche.reader.ui.widget.DocumentFragment.onConnected(DocumentFragment.java:75)
	at at.tomtasche.reader.background.service.DocumentServiceConnection.onServiceConnected(DocumentServiceConnection.java:54)
	at android.app.LoadedApk$ServiceDispatcher.doConnected(LoadedApk.java:1223)
	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1240)
	at android.os.Handler.handleCallback(Handler.java:739)
	at android.os.Handler.dispatchMessage(Handler.java:95)
	at android.os.Looper.loop(Looper.java:148)
	at android.app.ActivityThread.main(ActivityThread.java:5417)
	at java.lang.reflect.Method.invoke(Native Method)
	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)

```



