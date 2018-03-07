title: net.tedstein.AndroSS

# net.tedstein.AndroSS

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
// Build fingerprint: 'google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys'
// Revision: '11'
// ABI: 'arm'
// pid: 19842, tid: 20650, name: Binder_4  >>> net.tedstein.AndroSS <<<
// signal 6 (SIGABRT), code -6 (SI_TKILL), fault addr --------
// Abort message: 'Pure virtual function called!'
//     r0 00000000  r1 000050aa  r2 00000006  r3 aed27978
//     r4 aed27980  r5 aed27930  r6 00000000  r7 0000010c
//     r8 aed278cc  r9 00000000  sl 000028d9  fp 00004d82
//     ip 00000006  sp aed27738  lr b6d04b61  pc b6d06f50  cpsr 400d0010
// 
// backtrace:
//     #00 pc 00041f50  /system/lib/libc.so (tgkill+12)
//     #01 pc 0003fb5d  /system/lib/libc.so (pthread_kill+32)
//     #02 pc 0001c30f  /system/lib/libc.so (raise+10)
//     #03 pc 000194c1  /system/lib/libc.so (__libc_android_abort+34)
//     #04 pc 000174ac  /system/lib/libc.so (abort+4)
//     #05 pc 00032a91  /system/lib/libc++.so
//     #06 pc 000494c9  /system/lib/libc++.so (__cxa_pure_virtual+12)
//     #07 pc 0001ecc5  /system/lib/libbinder.so (_ZN7android14IPCThreadState14executeCommandEi+532)
//     #08 pc 0001ee31  /system/lib/libbinder.so (_ZN7android14IPCThreadState20getAndExecuteCommandEv+64)
//     #09 pc 0001ee95  /system/lib/libbinder.so (_ZN7android14IPCThreadState14joinThreadPoolEb+48)
//     #10 pc 000237e1  /system/lib/libbinder.so
//     #11 pc 00010075  /system/lib/libutils.so (_ZN7android6Thread11_threadLoopEPv+112)
//     #12 pc 0005ee23  /system/lib/libandroid_runtime.so (_ZN7android14AndroidRuntime15javaThreadShellEPv+70)
//     #13 pc 0003f45f  /system/lib/libc.so (_ZL15__pthread_startPv+30)
//     #14 pc 00019b43  /system/lib/libc.so (__start_thread+6)

```



