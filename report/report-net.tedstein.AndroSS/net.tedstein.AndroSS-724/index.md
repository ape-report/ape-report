title: net.tedstein.AndroSS

# net.tedstein.AndroSS

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
// Build fingerprint: 'google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys'
// Revision: '11'
// ABI: 'arm'
// pid: 25156, tid: 25240, name: Binder_3  >>> net.tedstein.AndroSS <<<
// signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x0
//     r0 b3b8ee94  r1 00000001  r2 b4d7dbc0  r3 00000000
//     r4 aa7694a0  r5 b4d7dbc0  r6 b6d3eec0  r7 b39bf7dc
//     r8 b39bf8cc  r9 00000000  sl 000028d9  fp 00006244
//     ip b6f38c24  sp b39bf7a0  lr b6f2d7a5  pc 00000000  cpsr 00070010
// 
// backtrace:
//     #00 pc 00000000  <unknown>
//     #01 pc 0000e7a3  /system/lib/libutils.so (_ZN7android7RefBase12weakref_type16attemptIncStrongEPKv+118)
//     #02 pc 0001ecad  /system/lib/libbinder.so (_ZN7android14IPCThreadState14executeCommandEi+508)
//     #03 pc 0001ee31  /system/lib/libbinder.so (_ZN7android14IPCThreadState20getAndExecuteCommandEv+64)
//     #04 pc 0001ee95  /system/lib/libbinder.so (_ZN7android14IPCThreadState14joinThreadPoolEb+48)
//     #05 pc 000237e1  /system/lib/libbinder.so
//     #06 pc 00010075  /system/lib/libutils.so (_ZN7android6Thread11_threadLoopEPv+112)
//     #07 pc 0005ee23  /system/lib/libandroid_runtime.so (_ZN7android14AndroidRuntime15javaThreadShellEPv+70)
//     #08 pc 0003f45f  /system/lib/libc.so (_ZL15__pthread_startPv+30)
//     #09 pc 00019b43  /system/lib/libc.so (__start_thread+6)

```



