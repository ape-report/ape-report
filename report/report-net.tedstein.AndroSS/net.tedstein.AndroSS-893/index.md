title: net.tedstein.AndroSS

# net.tedstein.AndroSS

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
// Build fingerprint: 'google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys'
// Revision: '11'
// ABI: 'arm'
// pid: 26899, tid: 26910, name: Binder_1  >>> net.tedstein.AndroSS <<<
// signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0xfffffff5
//     r0 ab235310  r1 b3a0f2c0  r2 00000001  r3 aa769734
//     r4 b4d7d2c0  r5 00000002  r6 00000002  r7 acc0eb4c
//     r8 b3dfc8cc  r9 be9fd3ec  sl b3cfe000  fp b6f2ebb5
//     ip 00000000  sp b3dfc898  lr 00000001  pc b6f0055a  cpsr 00070030
// 
// backtrace:
//     #00 pc 0001e55a  /system/lib/libbinder.so (_ZN7android14IPCThreadState20processPendingDerefsEv+73)
//     #01 pc 0001ee8f  /system/lib/libbinder.so (_ZN7android14IPCThreadState14joinThreadPoolEb+42)
//     #02 pc 000237e1  /system/lib/libbinder.so
//     #03 pc 00010075  /system/lib/libutils.so (_ZN7android6Thread11_threadLoopEPv+112)
//     #04 pc 0005ee23  /system/lib/libandroid_runtime.so (_ZN7android14AndroidRuntime15javaThreadShellEPv+70)
//     #05 pc 0003f45f  /system/lib/libc.so (_ZL15__pthread_startPv+30)
//     #06 pc 00019b43  /system/lib/libc.so (__start_thread+6)

```



