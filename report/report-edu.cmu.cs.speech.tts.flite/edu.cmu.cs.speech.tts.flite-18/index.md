title: edu.cmu.cs.speech.tts.flite

# edu.cmu.cs.speech.tts.flite

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
// Build fingerprint: 'google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys'
// Revision: '11'
// ABI: 'arm'
// pid: 12505, tid: 12505, name: peech.tts.flite  >>> edu.cmu.cs.speech.tts.flite <<<
// signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0xc0f80f54
//     r0 a0f80f50  r1 b6d469c8  r2 00000001  r3 ffffffe1
//     r4 07ffffff  r5 a0f80f58  r6 00000001  r7 40000000
//     r8 b6d469e4  r9 40000003  sl 00000002  fp b6d46920
//     ip 00000001  sp be9fbaa8  lr b6d0ff03  pc b6d0e138  cpsr 000e0030
// 
// backtrace:
//     #00 pc 00049138  /system/lib/libc.so (arena_run_reg_alloc+87)
//     #01 pc 0004aeff  /system/lib/libc.so (je_arena_tcache_fill_small+94)
//     #02 pc 0005c23b  /system/lib/libc.so (je_tcache_alloc_small_hard+18)
//     #03 pc 00056d2d  /system/lib/libc.so (je_malloc+1112)
//     #04 pc 0000e8ad  /system/lib/libutils.so (_ZN7android12SharedBuffer5allocEj+28)
//     #05 pc 00010ef5  /system/lib/libutils.so (_ZN7android10VectorImpl5_growEjj+108)
//     #06 pc 00010ff1  /system/lib/libutils.so (_ZN7android10VectorImpl8insertAtEPKvjj+20)
//     #07 pc 00029c9b  /system/lib/libhwui.so
//     #08 pc 0002d50b  /system/lib/libhwui.so (_ZN7android10uirenderer17DisplayListCanvas15addRenderNodeOpEPNS0_16DrawRenderNodeOpE+26)
//     #09 pc 726dd99b  /data/dalvik-cache/arm/system@framework@boot.oat (offset 0x1ed6000)

```



