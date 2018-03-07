title: me.dbarnett.acastus

# me.dbarnett.acastus

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
// Build fingerprint: 'google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys'
// Revision: '11'
// ABI: 'arm'
// pid: 5207, tid: 7256, name: Thread-21348  >>> me.dbarnett.acastus <<<
// signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x0
//     r0 00000000  r1 0020052a  r2 b3ad4f38  r3 965c0894
//     r4 8e370b40  r5 965c089c  r6 919e1a00  r7 965c088c
//     r8 98bffcd0  r9 8faf3708  sl 8faf371c  fp 00000000
//     ip b6d3eec0  sp 965c0880  lr 9de241e7  pc 9de2425c  cpsr 40070030
// 
// backtrace:
//     #00 pc 0011225c  /data/app/me.dbarnett.acastus-1/lib/arm/libtangram.so (_ZN7_JNIEnv14CallVoidMethodEP8_jobjectP10_jmethodIDz+31)
//     #01 pc 001121e3  /data/app/me.dbarnett.acastus-1/lib/arm/libtangram.so (_ZNK7Tangram15AndroidPlatform13requestRenderEv+74)
//     #02 pc 0014328d  /data/app/me.dbarnett.acastus-1/lib/arm/libtangram.so (_ZN7Tangram10TileWorker3runEPNS0_6WorkerE+652)
//     #03 pc 00143693  /data/app/me.dbarnett.acastus-1/lib/arm/libtangram.so (_ZNSt6__ndk114__thread_proxyINS_5tupleIJNS_10unique_ptrINS_15__thread_structENS_14default_deleteIS3_EEEEMN7Tangram10TileWorkerEFvPNS8_6WorkerEEPS8_SA_EEEEEPvSF_+42)
//     #04 pc 0003f45f  /system/lib/libc.so (_ZL15__pthread_startPv+30)
//     #05 pc 00019b43  /system/lib/libc.so (__start_thread+6)

```



