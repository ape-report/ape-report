title: net.tedstein.AndroSS

# net.tedstein.AndroSS

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
// Build fingerprint: 'google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys'
// Revision: '11'
// ABI: 'arm'
// pid: 21840, tid: 21851, name: Binder_2  >>> net.tedstein.AndroSS <<<
// signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x14
//     r0 b3762c20  r1 00000000  r2 b3cfd7dc  r3 b3cfd810
//     r4 b4002300  r5 b3cfd810  r6 b6d3eec0  r7 b3cfd7dc
//     r8 b3cfd8cc  r9 00000000  sl 000028d9  fp 00005550
//     ip b6f38c24  sp b3cfd7c0  lr b6f2d739  pc b6f00cbe  cpsr 00070030
// 
// backtrace:
//     #00 pc 0001ecbe  /system/lib/libbinder.so (_ZN7android14IPCThreadState14executeCommandEi+525)
//     #01 pc 0001ee31  /system/lib/libbinder.so (_ZN7android14IPCThreadState20getAndExecuteCommandEv+64)
//     #02 pc 0001ee95  /system/lib/libbinder.so (_ZN7android14IPCThreadState14joinThreadPoolEb+48)
//     #03 pc 000237e1  /system/lib/libbinder.so
//     #04 pc 00010075  /system/lib/libutils.so (_ZN7android6Thread11_threadLoopEPv+112)
//     #05 pc 0005ee23  /system/lib/libandroid_runtime.so (_ZN7android14AndroidRuntime15javaThreadShellEPv+70)
//     #06 pc 0003f45f  /system/lib/libc.so (_ZL15__pthread_startPv+30)
//     #07 pc 00019b43  /system/lib/libc.so (__start_thread+6)

```



