title: net.tedstein.AndroSS

# net.tedstein.AndroSS

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
// Build fingerprint: 'google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys'
// Revision: '11'
// ABI: 'arm'
// pid: 22826, tid: 22837, name: Binder_2  >>> net.tedstein.AndroSS <<<
// signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0xec7d3f1a
//     r0 ec7d3f1a  r1 00000001  r2 b4002000  r3 b4cb4470
//     r4 aa768690  r5 b4002000  r6 b6d3eec0  r7 b3cfd7dc
//     r8 b3cfd8cc  r9 00000000  sl 000028d9  fp 0000592a
//     ip b6f38c24  sp b3cfd7a0  lr b6f2d739  pc b6f2d79e  cpsr 000d0030
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



