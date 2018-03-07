title: net.tedstein.AndroSS

# net.tedstein.AndroSS

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
// Build fingerprint: 'google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys'
// Revision: '11'
// ABI: 'arm'
// pid: 25815, tid: 25842, name: Binder_3  >>> net.tedstein.AndroSS <<<
// signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x24585230
//     r0 24585230  r1 00000001  r2 b4002600  r3 b4cb4470
//     r4 aa768200  r5 b4002600  r6 b6d3eec0  r7 b38937dc
//     r8 b38938cc  r9 00000000  sl 000028d9  fp 000064d7
//     ip b6f38c24  sp b38937a0  lr b6f2d739  pc b6f2d79e  cpsr 00070030
// 
// backtrace:
//     #00 pc 0000e79e  /system/lib/libutils.so (_ZN7android7RefBase12weakref_type16attemptIncStrongEPKv+113)
//     #01 pc 0001ecad  /system/lib/libbinder.so (_ZN7android14IPCThreadState14executeCommandEi+508)
//     #02 pc 0001ee31  /system/lib/libbinder.so (_ZN7android14IPCThreadState20getAndExecuteCommandEv+64)
//     #03 pc 0001ee95  /system/lib/libbinder.so (_ZN7android14IPCThreadState14joinThreadPoolEb+48)
//     #04 pc 000237e1  /system/lib/libbinder.so
//     #05 pc 00010075  /system/lib/libutils.so (_ZN7android6Thread11_threadLoopEPv+112)
//     #06 pc 0005ee23  /system/lib/libandroid_runtime.so (_ZN7android14AndroidRuntime15javaThreadShellEPv+70)
//     #07 pc 0003f45f  /system/lib/libc.so (_ZL15__pthread_startPv+30)
//     #08 pc 00019b43  /system/lib/libc.so (__start_thread+6)

```



