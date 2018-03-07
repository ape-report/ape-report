title: info.guardianproject.pixelknot

# info.guardianproject.pixelknot

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.OutOfMemoryError: Failed to allocate a 34310156 byte allocation with 16753184 free bytes and 24MB until OOM
// 	at java.lang.StringFactory.newStringFromChars(Native Method)
// 	at java.lang.StringFactory.newStringFromChars(StringFactory.java:218)
// 	at java.lang.StringFactory.newStringFromBytes(StringFactory.java:203)
// 	at java.lang.StringFactory.newStringFromBytes(StringFactory.java:63)
// 	at android.util.Base64.encodeToString(Base64.java:456)
// 	at info.guardianproject.pixelknot.crypto.Aes.EncryptWithPassword(Aes.java:90)
// 	at info.guardianproject.pixelknot.StegoEncryptionJob$2.run(StegoEncryptionJob.java:78)
// 	at info.guardianproject.pixelknot.StegoJob$1.run(StegoJob.java:79)

```



