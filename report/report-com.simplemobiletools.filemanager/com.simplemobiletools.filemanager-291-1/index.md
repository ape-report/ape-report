title: com.simplemobiletools.filemanager

# com.simplemobiletools.filemanager

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.io.FileNotFoundException: /4.zip: open failed: EROFS (Read-only file system)
// 	at libcore.io.IoBridge.open(IoBridge.java:452)
// 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
// 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
// 	at com.simplemobiletools.commons.extensions.ActivityKt.getFileOutputStreamSync(SourceFile:594)
// 	at com.simplemobiletools.commons.extensions.ActivityKt.getFileOutputStreamSync$default(SourceFile:580)
// 	at com.simplemobiletools.filemanager.adapters.ItemsAdapter.zipPaths(SourceFile:293)
// 	at com.simplemobiletools.filemanager.adapters.ItemsAdapter.access$zipPaths(SourceFile:40)
// 	at com.simplemobiletools.filemanager.adapters.ItemsAdapter$compressSelection$1$1$1.run(SourceFile:223)
// 	at java.lang.Thread.run(Thread.java:818)
// Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
// 	at libcore.io.Posix.open(Native Method)
// 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
// 	at libcore.io.IoBridge.open(IoBridge.java:438)
// 	... 8 more

```



