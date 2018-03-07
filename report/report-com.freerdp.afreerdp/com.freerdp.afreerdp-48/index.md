title: com.freerdp.afreerdp

# com.freerdp.afreerdp

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
// Build fingerprint: 'google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys'
// Revision: '11'
// ABI: 'arm'
// pid: 2772, tid: 2788, name: RenderThread  >>> com.freerdp.afreerdp <<<
// signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0xc04c12f0
//     r0 a04c12ec  r1 b6d46958  r2 00000001  r3 ffffffe1
//     r4 07ffffff  r5 a04c12f4  r6 00000001  r7 40000000
//     r8 b6d46974  r9 40000003  sl 00000001  fp b6d46920
//     ip 00000001  sp af05f590  lr b6d0ff03  pc b6d0e138  cpsr 000e0030
// 
// backtrace:
//     #00 pc 00049138  /system/lib/libc.so (arena_run_reg_alloc+87)
//     #01 pc 0004aeff  /system/lib/libc.so (je_arena_tcache_fill_small+94)
//     #02 pc 0005c23b  /system/lib/libc.so (je_tcache_alloc_small_hard+18)
//     #03 pc 00056d2d  /system/lib/libc.so (je_malloc+1112)
//     #04 pc 00020ccf  /system/vendor/lib/libgsl.so (os_malloc+6)
//     #05 pc 00020d30  /system/vendor/lib/egl/libEGL_adreno.so (eglTimestampListCopy+72)
//     #06 pc 00014d04  /system/vendor/lib/egl/libEGL_adreno.so (qeglDrvAPI_eglSwapBuffers+1716)
//     #07 pc 00015e6f  /system/lib/libEGL.so (eglSwapBuffersWithDamageKHR+326)
//     #08 pc 0001d333  /system/lib/libhwui.so
//     #09 pc 0001a6df  /system/lib/libhwui.so
//     #10 pc 0001c417  /system/lib/libhwui.so
//     #11 pc 0001f405  /system/lib/libhwui.so (_ZN7android10uirenderer12renderthread12RenderThread10threadLoopEv+80)
//     #12 pc 00010075  /system/lib/libutils.so (_ZN7android6Thread11_threadLoopEPv+112)
//     #13 pc 0005ee23  /system/lib/libandroid_runtime.so (_ZN7android14AndroidRuntime15javaThreadShellEPv+70)
//     #14 pc 0003f45f  /system/lib/libc.so (_ZL15__pthread_startPv+30)
//     #15 pc 00019b43  /system/lib/libc.so (__start_thread+6)

```



