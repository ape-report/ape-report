title: com.shurik.droidzebra

# com.shurik.droidzebra

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
// Build fingerprint: 'google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys'
// Revision: '11'
// ABI: 'arm'
// pid: 3085, tid: 3885, name: Thread-6616  >>> com.shurik.droidzebra <<<
// signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x1a269c
//     r0 0000055b  r1 000689a7  r2 000f3822  r3 51819e16
//     r4 b388e7d8  r5 000f3822  r6 00000000  r7 5287f2f3
//     r8 518827bd  r9 9fa9f278  sl b3802efc  fp 00000000
//     ip 51871f9f  sp 9fa9f070  lr b37d9c85  pc b37d9c88  cpsr 20070030
// 
// backtrace:
//     #00 pc 00038c88  /data/app/com.shurik.droidzebra-1/lib/arm/libdroidzebra.so (fill_move_alternatives+71)
//     #01 pc 0002226b  /data/app/com.shurik.droidzebra-1/lib/arm/libdroidzebra.so (compute_move+1994)
//     #02 pc 00008467  /data/app/com.shurik.droidzebra-1/lib/arm/libdroidzebra.so (Java_com_shurik_droidzebra_ZebraEngine_zePlay+2470)
//     #03 pc 00156565  /data/app/com.shurik.droidzebra-1/oat/arm/base.odex (offset 0xf8000)

```



