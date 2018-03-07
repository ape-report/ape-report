title: com.freerdp.afreerdp

# com.freerdp.afreerdp

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
// Build fingerprint: 'google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys'
// Revision: '11'
// ABI: 'arm'
// pid: 4157, tid: 4183, name: RenderThread  >>> com.freerdp.afreerdp <<<
// signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0xc04c10a4
//     r0 a04c10a0  r1 b6d46958  r2 00000001  r3 ffffffe1
//     r4 07ffffff  r5 a04c10a8  r6 00000001  r7 40000000
//     r8 b6d46974  r9 40000003  sl 00000001  fp b6d46920
//     ip 00000001  sp af05f220  lr b6d0ff03  pc b6d0e138  cpsr 000e0030
// 
// backtrace:
//     #00 pc 00049138  /system/lib/libc.so (arena_run_reg_alloc+87)
//     #01 pc 0004aeff  /system/lib/libc.so (je_arena_tcache_fill_small+94)
//     #02 pc 0005c23b  /system/lib/libc.so (je_tcache_alloc_small_hard+18)
//     #03 pc 00056d2d  /system/lib/libc.so (je_malloc+1112)
//     #04 pc 00020ccf  /system/vendor/lib/libgsl.so (os_malloc+6)
//     #05 pc 00083b5d  /system/vendor/lib/egl/libGLESv2_adreno.so (rb_linkedlist_allocnode+10)
//     #06 pc 0007eb31  /system/vendor/lib/egl/libGLESv2_adreno.so (rb_cmdbuffer_alloc_binning_pass+38)
//     #07 pc 0007eb69  /system/vendor/lib/egl/libGLESv2_adreno.so (rb_cmdbuffer_reservecmds_binning_pass+26)
//     #08 pc 0007ebb5  /system/vendor/lib/egl/libGLESv2_adreno.so (rb_cmdbuffer_addcmds_binning_pass+6)
//     #09 pc 000839b9  /system/vendor/lib/egl/libGLESv2_adreno.so
//     #10 pc 00083a73  /system/vendor/lib/egl/libGLESv2_adreno.so (rb_execute_state_change_procs+52)
//     #11 pc 000b22af  /system/vendor/lib/egl/libGLESv2_adreno.so (oxili_sethwstate_scissor+86)
//     #12 pc 0008ad49  /system/vendor/lib/egl/libGLESv2_adreno.so (rb_scissor+86)
//     #13 pc 00062457  /system/vendor/lib/egl/libGLESv2_adreno.so (set_framebuffer+242)
//     #14 pc 0005c7a5  /system/vendor/lib/egl/libGLESv2_adreno.so (gl2_context_makecurrent+232)
//     #15 pc 0005e56d  /system/vendor/lib/egl/libGLESv2_adreno.so (oglSetBuffers+256)
//     #16 pc 0001f9fc  /system/vendor/lib/egl/libEGL_adreno.so (eglGLUpdateSurfaces+704)
//     #17 pc 00012c00  /system/vendor/lib/egl/libEGL_adreno.so (qeglDrvAPI_eglMakeCurrent+1340)
//     #18 pc 000127bf  /system/lib/libEGL.so (_ZN7android13egl_display_t11makeCurrentEPNS_13egl_context_tES2_PvS3_S3_S3_S3_S3_+102)
//     #19 pc 00016279  /system/lib/libEGL.so (eglMakeCurrent+280)
//     #20 pc 0001d099  /system/lib/libhwui.so
//     #21 pc 0001a4b5  /system/lib/libhwui.so
//     #22 pc 0001c1eb  /system/lib/libhwui.so
//     #23 pc 0001c39b  /system/lib/libhwui.so
//     #24 pc 0001f405  /system/lib/libhwui.so (_ZN7android10uirenderer12renderthread12RenderThread10threadLoopEv+80)
//     #25 pc 00010075  /system/lib/libutils.so (_ZN7android6Thread11_threadLoopEPv+112)
//     #26 pc 0005ee23  /system/lib/libandroid_runtime.so (_ZN7android14AndroidRuntime15javaThreadShellEPv+70)
//     #27 pc 0003f45f  /system/lib/libc.so (_ZL15__pthread_startPv+30)
//     #28 pc 00019b43  /system/lib/libc.so (__start_thread+6)

```



