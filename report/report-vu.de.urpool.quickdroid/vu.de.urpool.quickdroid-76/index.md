title: vu.de.urpool.quickdroid

# vu.de.urpool.quickdroid

```
// java.lang.SecurityException: Permission Denial: reading com.android.providers.media.MediaProvider uri content://media/external/audio/artists from pid=11567, uid=10326 requires android.permission.READ_EXTERNAL_STORAGE, or grantUriPermission()
// 	at android.os.Parcel.readException(Parcel.java:1620)
// 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:183)
// 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:135)
// 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:421)
// 	at android.content.ContentResolver.query(ContentResolver.java:491)
// 	at android.content.ContentResolver.query(ContentResolver.java:434)
// 	at vu.de.urpool.quickdroid.media.audio.ArtistLauncher.getSuggestions(ArtistLauncher.java:67)
// 	at vu.de.urpool.quickdroid.Searcher$AsyncSearcher.run(Searcher.java:82)
// 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
// 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
// 	at java.lang.Thread.run(Thread.java:818)

```



