title: com.ihunda.android.binauralbeat

# com.ihunda.android.binauralbeat

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
// Build fingerprint: 'google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys'
// Revision: '11'
// ABI: 'arm'
// pid: 12621, tid: 13867, name: GLThread 9987  >>> com.ihunda.android.binauralbeat <<<
// signal 7 (SIGBUS), code 2 (BUS_ADRERR), fault addr 0x9c22d1e4
//     r0 9c22cb18  r1 9c22cfb0  r2 000000c0  r3 9c22d1e4
//     r4 0000024c  r5 9c22cd64  r6 9c22d1e4  r7 a0b28800
//     r8 a0b10000  r9 00000000  sl 00000004  fp 00000000
//     ip 00000070  sp 9deb87c8  lr 00000018  pc a9c87622  cpsr 800d0030
// 
// backtrace:
//     #00 pc 000bc622  /system/vendor/lib/egl/libGLESv2_adreno.so (oxili_tile_texture+1597)
//     #01 pc 000918a9  /system/vendor/lib/egl/libGLESv2_adreno.so
//     #02 pc 00093673  /system/vendor/lib/egl/libGLESv2_adreno.so (rb_texture_update_hw_subimage+4142)
//     #03 pc 00094a59  /system/vendor/lib/egl/libGLESv2_adreno.so (rb_texture_loadimage+224)
//     #04 pc 0006e99d  /system/vendor/lib/egl/libGLESv2_adreno.so (TexImageLoad+216)
//     #05 pc 0006ec17  /system/vendor/lib/egl/libGLESv2_adreno.so (core_glTexImage2D+234)
//     #06 pc 0004d06f  /system/vendor/lib/egl/libGLESv2_adreno.so (glTexImage2D+50)
//     #07 pc 0001b7e5  /system/vendor/lib/egl/libGLESv1_CM_adreno.so (qglDrvAPI_glTexImage2D+124)
//     #08 pc 0005a4ec  /system/lib/libandroid_runtime.so
//     #09 pc 7380375d  /data/dalvik-cache/arm/system@framework@boot.oat (offset 0x1ed6000)

```



