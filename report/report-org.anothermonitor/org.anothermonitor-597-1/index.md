title: org.anothermonitor

# org.anothermonitor

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
// Build fingerprint: 'google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys'
// Revision: '11'
// ABI: 'arm'
// pid: 3288, tid: 12541, name: Thread-16739  >>> org.anothermonitor <<<
// signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x9b3a2ee4
//     r0 9b3a2ee4  r1 00000000  r2 00000001  r3 ff0000ff
//     r4 00000001  r5 000000ff  r6 9b3a2ee4  r7 9b3a2ee4
//     r8 9e50200c  r9 00000127  sl 9e4fe32c  fp 00000102
//     ip b6b34b20  sp 9e4fdc18  lr b69db827  pc b69a38f4  cpsr 800b0030
// 
// backtrace:
//     #00 pc 000e78f4  /system/lib/libskia.so (_ZN9SkBlitRow7Color32EPjPKjij+55)
//     #01 pc 0011f825  /system/lib/libskia.so
//     #02 pc 0011fd31  /system/lib/libskia.so (_Z12sk_fill_pathRK6SkPathPK7SkIRectP9SkBlitteriiiRK8SkRegion+316)
//     #03 pc 0011ffff  /system/lib/libskia.so (_ZN6SkScan8FillPathERK6SkPathRK8SkRegionP9SkBlitter+310)
//     #04 pc 0011d73b  /system/lib/libskia.so (_ZN6SkScan8FillPathERK6SkPathRK12SkRasterClipP9SkBlitter+26)
//     #05 pc 000f771d  /system/lib/libskia.so (_ZNK6SkDraw8drawPathERK6SkPathRK7SkPaintPK8SkMatrixbbP9SkBlitter+604)
//     #06 pc 000e073d  /system/lib/libskia.so (_ZN14SkBitmapDevice8drawPathERK6SkDrawRK6SkPathRK7SkPaintPK8SkMatrixb+24)
//     #07 pc 000f8ccb  /system/lib/libskia.so (_ZNK6SkDraw10drawPointsEN8SkCanvas9PointModeEjPK7SkPointRK7SkPaintb+734)
//     #08 pc 000f0267  /system/lib/libskia.so (_ZN8SkCanvas12onDrawPointsENS_9PointModeEjPK7SkPointRK7SkPaint+410)
//     #09 pc 000eef83  /system/lib/libskia.so (_ZN8SkCanvas8drawLineEffffRK7SkPaint+102)
//     #10 pc 72ea27db  /data/dalvik-cache/arm/system@framework@boot.oat (offset 0x1ed6000)

```



