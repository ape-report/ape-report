title: com.ihunda.android.binauralbeat

# com.ihunda.android.binauralbeat

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
// Build fingerprint: 'google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys'
// Revision: '11'
// ABI: 'arm'
// pid: 17645, tid: 18146, name: GLThread 9891  >>> com.ihunda.android.binauralbeat <<<
// signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0xa08c00e0
//     r0 00000002  r1 0000002b  r2 ffffffd0  r3 b6cd82f0
//     r4 b6cd82e8  r5 a08ed9c0  r6 a0525000  r7 a08c0000
//     r8 a050d348  r9 b6ccb594  sl 00000001  fp 00000002
//     ip a08c00ac  sp a0a33288  lr b6cae25b  pc b6cab2da  cpsr 200d0030
// 
// backtrace:
//     #00 pc 000552da  /system/lib/libc.so (ifree+49)
//     #01 pc 00058257  /system/lib/libc.so (je_free+374)
//     #02 pc 0027d9fb  /system/lib/libart.so (_ZN3art3JNI29ReleasePrimitiveArrayCriticalEP7_JNIEnvP7_jarrayPvi+642)
//     #03 pc 0005a510  /system/lib/libandroid_runtime.so
//     #04 pc 7380375d  /data/dalvik-cache/arm/system@framework@boot.oat (offset 0x1ed6000)

```



