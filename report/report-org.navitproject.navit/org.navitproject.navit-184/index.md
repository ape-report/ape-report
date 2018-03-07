title: org.navitproject.navit

# org.navitproject.navit

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
// Build fingerprint: 'google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys'
// Revision: '11'
// ABI: 'arm'
// pid: 30321, tid: 30321, name: itproject.navit  >>> org.navitproject.navit <<<
// signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x29
//     r0 00000029  r1 00000029  r2 0000ffff  r3 00000007
//     r4 be9fd148  r5 a0354ab8  r6 9fc31340  r7 9fc31374
//     r8 be9fd148  r9 00000001  sl b3924e1c  fp 00000001
//     ip 80000000  sp be9fd0a8  lr b38cbbb8  pc b6cdd87a  cpsr a00a0030
// 
// backtrace:
//     #00 pc 0001887a  /system/lib/libc.so (strlen+21)
//     #01 pc 00016bb4  /data/app/org.navitproject.navit-1/lib/arm/libnavit.so (attr_data_size+52)
//     #02 pc 00016fc4  /data/app/org.navitproject.navit-1/lib/arm/libnavit.so (attr_dup_content+196)
//     #03 pc 00017018  /data/app/org.navitproject.navit-1/lib/arm/libnavit.so (attr_dup+28)
//     #04 pc 0004bca0  /data/app/org.navitproject.navit-1/lib/arm/libnavit.so (search_list_search+448)
//     #05 pc 0005b9c4  /data/app/org.navitproject.navit-1/lib/arm/libnavit.so (android_search_idle+1216)
//     #06 pc 00018ca0  /data/app/org.navitproject.navit-1/lib/arm/libnavit.so (callback_call+640)
//     #07 pc 00018e24  /data/app/org.navitproject.navit-1/lib/arm/libnavit.so (callback_call_args+84)
//     #08 pc 000011a0  /data/app/org.navitproject.navit-1/lib/arm/libgraphics_android.so (event_android_handle_timeout+16)
//     #09 pc 0005b25c  /data/app/org.navitproject.navit-1/lib/arm/libnavit.so (Java_org_navitproject_navit_NavitTimeout_TimeoutCallback+104)
//     #10 pc 000bb7eb  /data/app/org.navitproject.navit-1/oat/arm/base.odex (offset 0x88000)

```



