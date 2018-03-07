title: edu.cmu.cs.speech.tts.flite

# edu.cmu.cs.speech.tts.flite

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
// Build fingerprint: 'google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys'
// Revision: '11'
// ABI: 'arm'
// pid: 15294, tid: 15294, name: peech.tts.flite  >>> edu.cmu.cs.speech.tts.flite <<<
// signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0xc0301440
//     r0 a030143c  r1 b6d469c8  r2 00000001  r3 ffffffe1
//     r4 07ffffff  r5 a0301444  r6 00000001  r7 40000000
//     r8 b6d469e4  r9 40000003  sl 00000003  fp b6d46920
//     ip 00000001  sp be9fccb8  lr b6d0ff03  pc b6d0e138  cpsr 00000030
// 
// backtrace:
//     #00 pc 00049138  /system/lib/libc.so (arena_run_reg_alloc+87)
//     #01 pc 0004aeff  /system/lib/libc.so (je_arena_tcache_fill_small+94)
//     #02 pc 0005c23b  /system/lib/libc.so (je_tcache_alloc_small_hard+18)
//     #03 pc 00057393  /system/lib/libc.so (je_calloc+1158)
//     #04 pc 0001d228  /data/app/edu.cmu.cs.speech.tts.flite-1/lib/arm/libttsflite.so (cst_safe_alloc+28)

```



