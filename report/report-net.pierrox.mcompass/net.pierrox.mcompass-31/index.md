title: net.pierrox.mcompass

# net.pierrox.mcompass

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
// Build fingerprint: 'google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys'
// Revision: '11'
// ABI: 'arm'
// pid: 27186, tid: 27248, name: GLThread 16800  >>> net.pierrox.mcompass <<<
// signal 6 (SIGABRT), code -6 (SI_TKILL), fault addr --------
// Abort message: 'Invalid address 0xa1bee00c passed to free: value not allocated'
//     r0 00000000  r1 00006a70  r2 00000006  r3 b3a7f978
//     r4 b3a7f980  r5 b3a7f930  r6 00000002  r7 0000010c
//     r8 b3aa10c8  r9 b6d3a594  sl 00000001  fp 00000002
//     ip 00000006  sp b3a7f248  lr b6d04b61  pc b6d06f50  cpsr 40070010
// 
// backtrace:
//     #00 pc 00041f50  /system/lib/libc.so (tgkill+12)
//     #01 pc 0003fb5d  /system/lib/libc.so (pthread_kill+32)
//     #02 pc 0001c30f  /system/lib/libc.so (raise+10)
//     #03 pc 000194c1  /system/lib/libc.so (__libc_android_abort+34)
//     #04 pc 000174ac  /system/lib/libc.so (abort+4)
//     #05 pc 0001af23  /system/lib/libc.so (__libc_fatal+16)
//     #06 pc 00055373  /system/lib/libc.so (ifree+202)
//     #07 pc 00058257  /system/lib/libc.so (je_free+374)
//     #08 pc 0027d9fb  /system/lib/libart.so (_ZN3art3JNI29ReleasePrimitiveArrayCriticalEP7_JNIEnvP7_jarrayPvi+642)
//     #09 pc 0005a510  /system/lib/libandroid_runtime.so
//     #10 pc 7380375d  /data/dalvik-cache/arm/system@framework@boot.oat (offset 0x1ed6000)
// 
Encounter abort but we are in continuous mode.
Force to stop all activites and make a restart.
*** WARNNING: the top activity package com.google.android.googlequicksearchbox is not allowed.
Generate activity event for activity ComponentInfo{net.pierrox.mcompass/net.pierrox.mcompass.MCompass} from 0 of 1
// CRASH: net.pierrox.mcompass (pid 27274) (elapsed nanos: 357481756337593)
// Short Msg: Native crash
// Long Msg: Native crash: Aborted
// Build Label: google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys
// Build Changelist: 3437181
// Build Time: 1478203422000
// *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
// Build fingerprint: 'google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys'
// Revision: '11'
// ABI: 'arm'
// pid: 27274, tid: 27301, name: GLThread 16803  >>> net.pierrox.mcompass <<<
// signal 6 (SIGABRT), code -6 (SI_TKILL), fault addr --------
// Abort message: 'Invalid address 0xa1aec00c passed to free: value not allocated'
//     r0 00000000  r1 00006aa5  r2 00000006  r3 b3a7a978
//     r4 b3a7a980  r5 b3a7a930  r6 00000002  r7 0000010c
//     r8 b4d89988  r9 b6d3a594  sl 00000001  fp 00000002
//     ip 00000006  sp b3a7a248  lr b6d04b61  pc b6d06f50  cpsr 40070010
// 
// backtrace:
//     #00 pc 00041f50  /system/lib/libc.so (tgkill+12)
//     #01 pc 0003fb5d  /system/lib/libc.so (pthread_kill+32)
//     #02 pc 0001c30f  /system/lib/libc.so (raise+10)
//     #03 pc 000194c1  /system/lib/libc.so (__libc_android_abort+34)
//     #04 pc 000174ac  /system/lib/libc.so (abort+4)
//     #05 pc 0001af23  /system/lib/libc.so (__libc_fatal+16)
//     #06 pc 00055373  /system/lib/libc.so (ifree+202)
//     #07 pc 00058257  /system/lib/libc.so (je_free+374)
//     #08 pc 0027d9fb  /system/lib/libart.so (_ZN3art3JNI29ReleasePrimitiveArrayCriticalEP7_JNIEnvP7_jarrayPvi+642)
//     #09 pc 0005a510  /system/lib/libandroid_runtime.so
//     #10 pc 7380375d  /data/dalvik-cache/arm/system@framework@boot.oat (offset 0x1ed6000)
// 
Encounter abort but we are in continuous mode.
Force to stop all activites and make a restart.
*** WARNNING: the top activity package com.google.android.googlequicksearchbox is not allowed.
Generate activity event for activity ComponentInfo{net.pierrox.mcompass/net.pierrox.mcompass.MCompass} from 0 of 1
// CRASH: net.pierrox.mcompass (pid 27336) (elapsed nanos: 357485908588061)
// Short Msg: Native crash
// Long Msg: Native crash: Aborted
// Build Label: google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys
// Build Changelist: 3437181
// Build Time: 1478203422000
// *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
// Build fingerprint: 'google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys'
// Revision: '11'
// ABI: 'arm'
// pid: 27336, tid: 27381, name: GLThread 16807  >>> net.pierrox.mcompass <<<
// signal 6 (SIGABRT), code -6 (SI_TKILL), fault addr --------
// Abort message: 'Invalid address 0xa1bee00c passed to free: value not allocated'
//     r0 00000000  r1 00006af5  r2 00000006  r3 b3b7f978
//     r4 b3b7f980  r5 b3b7f930  r6 00000002  r7 0000010c
//     r8 b4d89f48  r9 b6d3a594  sl 00000001  fp 00000002
//     ip 00000006  sp b3b7f248  lr b6d04b61  pc b6d06f50  cpsr 40070010
// 
// backtrace:
//     #00 pc 00041f50  /system/lib/libc.so (tgkill+12)
//     #01 pc 0003fb5d  /system/lib/libc.so (pthread_kill+32)
//     #02 pc 0001c30f  /system/lib/libc.so (raise+10)
//     #03 pc 000194c1  /system/lib/libc.so (__libc_android_abort+34)
//     #04 pc 000174ac  /system/lib/libc.so (abort+4)
//     #05 pc 0001af23  /system/lib/libc.so (__libc_fatal+16)
//     #06 pc 00055373  /system/lib/libc.so (ifree+202)
//     #07 pc 00058257  /system/lib/libc.so (je_free+374)
//     #08 pc 0027d9fb  /system/lib/libart.so (_ZN3art3JNI29ReleasePrimitiveArrayCriticalEP7_JNIEnvP7_jarrayPvi+642)
//     #09 pc 0005a510  /system/lib/libandroid_runtime.so
//     #10 pc 7380375d  /data/dalvik-cache/arm/system@framework@boot.oat (offset 0x1ed6000)
// 
Encounter abort but we are in continuous mode.
Force to stop all activites and make a restart.
*** WARNNING: the top activity package com.google.android.googlequicksearchbox is not allowed.
Generate activity event for activity ComponentInfo{net.pierrox.mcompass/net.pierrox.mcompass.MCompass} from 0 of 1
// CRASH: net.pierrox.mcompass (pid 27419) (elapsed nanos: 357489892318736)
// Short Msg: Native crash
// Long Msg: Native crash: Aborted
// Build Label: google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys
// Build Changelist: 3437181
// Build Time: 1478203422000
// *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
// Build fingerprint: 'google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys'
// Revision: '11'
// ABI: 'arm'
// pid: 27419, tid: 27456, name: GLThread 16812  >>> net.pierrox.mcompass <<<
// signal 6 (SIGABRT), code -6 (SI_TKILL), fault addr --------
// Abort message: 'Invalid address 0xb36be00c passed to free: value not allocated'
//     r0 00000000  r1 00006b40  r2 00000006  r3 b3a7f978
//     r4 b3a7f980  r5 b3a7f930  r6 00000002  r7 0000010c
//     r8 b4d89f88  r9 b6d3a594  sl 00000001  fp 00000002
//     ip 00000006  sp b3a7f248  lr b6d04b61  pc b6d06f50  cpsr 40070010
// 
// backtrace:
//     #00 pc 00041f50  /system/lib/libc.so (tgkill+12)
//     #01 pc 0003fb5d  /system/lib/libc.so (pthread_kill+32)
//     #02 pc 0001c30f  /system/lib/libc.so (raise+10)
//     #03 pc 000194c1  /system/lib/libc.so (__libc_android_abort+34)
//     #04 pc 000174ac  /system/lib/libc.so (abort+4)
//     #05 pc 0001af23  /system/lib/libc.so (__libc_fatal+16)
//     #06 pc 00055373  /system/lib/libc.so (ifree+202)
//     #07 pc 00058257  /system/lib/libc.so (je_free+374)
//     #08 pc 0027d9fb  /system/lib/libart.so (_ZN3art3JNI29ReleasePrimitiveArrayCriticalEP7_JNIEnvP7_jarrayPvi+642)
//     #09 pc 0005a510  /system/lib/libandroid_runtime.so
//     #10 pc 7380375d  /data/dalvik-cache/arm/system@framework@boot.oat (offset 0x1ed6000)
// 
Encounter abort but we are in continuous mode.
Force to stop all activites and make a restart.
*** WARNNING: the top activity package com.google.android.googlequicksearchbox is not allowed.
Generate activity event for activity ComponentInfo{net.pierrox.mcompass/net.pierrox.mcompass.MCompass} from 0 of 1
// CRASH: net.pierrox.mcompass (pid 27495) (elapsed nanos: 357494013361963)
// Short Msg: Native crash
// Long Msg: Native crash: Segmentation fault
// Build Label: google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys
// Build Changelist: 3437181
// Build Time: 1478203422000
// *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
// Build fingerprint: 'google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys'
// Revision: '11'
// ABI: 'arm'
// pid: 27495, tid: 27534, name: GLThread 16815  >>> net.pierrox.mcompass <<<
// signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x0
//     r0 00000000  r1 00000000  r2 00000000  r3 00000002
//     r4 00000000  r5 b36fd00c  r6 aa77c000  r7 00000018
//     r8 b4d89f48  r9 aa77ce40  sl 00000001  fp 00000002
//     ip b6d3a600  sp b3b7f2b8  lr b6d213ab  pc b6d1a3dc  cpsr 20070030
// 
// backtrace:
//     #00 pc 000553dc  /system/lib/libc.so (ifree+307)
//     #01 pc 00058257  /system/lib/libc.so (je_free+374)
//     #02 pc 0027d9fb  /system/lib/libart.so (_ZN3art3JNI29ReleasePrimitiveArrayCriticalEP7_JNIEnvP7_jarrayPvi+642)
//     #03 pc 0005a510  /system/lib/libandroid_runtime.so
//     #04 pc 7380375d  /data/dalvik-cache/arm/system@framework@boot.oat (offset 0x1ed6000)
// 
Encounter abort but we are in continuous mode.
Force to stop all activites and make a restart.
*** WARNNING: the top activity package com.google.android.googlequicksearchbox is not allowed.
Generate activity event for activity ComponentInfo{net.pierrox.mcompass/net.pierrox.mcompass.MCompass} from 0 of 1
// CRASH: net.pierrox.mcompass (pid 27574) (elapsed nanos: 357498149337640)
// Short Msg: Native crash
// Long Msg: Native crash: Aborted
// Build Label: google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys
// Build Changelist: 3437181
// Build Time: 1478203422000
// *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
// Build fingerprint: 'google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys'
// Revision: '11'
// ABI: 'arm'
// pid: 27574, tid: 27606, name: GLThread 16820  >>> net.pierrox.mcompass <<<
// signal 6 (SIGABRT), code -6 (SI_TKILL), fault addr --------
// Abort message: 'Invalid address 0xb36be00c passed to free: value not allocated'
//     r0 00000000  r1 00006bd6  r2 00000006  r3 b3a7f978
//     r4 b3a7f980  r5 b3a7f930  r6 00000002  r7 0000010c
//     r8 b4d89f88  r9 b6d3a594  sl 00000001  fp 00000002
//     ip 00000006  sp b3a7f248  lr b6d04b61  pc b6d06f50  cpsr 40070010
// 
// backtrace:
//     #00 pc 00041f50  /system/lib/libc.so (tgkill+12)
//     #01 pc 0003fb5d  /system/lib/libc.so (pthread_kill+32)
//     #02 pc 0001c30f  /system/lib/libc.so (raise+10)
//     #03 pc 000194c1  /system/lib/libc.so (__libc_android_abort+34)
//     #04 pc 000174ac  /system/lib/libc.so (abort+4)
//     #05 pc 0001af23  /system/lib/libc.so (__libc_fatal+16)
//     #06 pc 00055373  /system/lib/libc.so (ifree+202)
//     #07 pc 00058257  /system/lib/libc.so (je_free+374)
//     #08 pc 0027d9fb  /system/lib/libart.so (_ZN3art3JNI29ReleasePrimitiveArrayCriticalEP7_JNIEnvP7_jarrayPvi+642)
//     #09 pc 0005a510  /system/lib/libandroid_runtime.so
//     #10 pc 7380375d  /data/dalvik-cache/arm/system@framework@boot.oat (offset 0x1ed6000)
// 
Encounter abort but we are in continuous mode.
Force to stop all activites and make a restart.
*** WARNNING: the top activity package com.google.android.googlequicksearchbox is not allowed.
Generate activity event for activity ComponentInfo{net.pierrox.mcompass/net.pierrox.mcompass.MCompass} from 0 of 1
// CRASH: net.pierrox.mcompass (pid 27708) (elapsed nanos: 357502242243210)
// Short Msg: Native crash
// Long Msg: Native crash: Aborted
// Build Label: google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys
// Build Changelist: 3437181
// Build Time: 1478203422000
// *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
// Build fingerprint: 'google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys'
// Revision: '11'
// ABI: 'arm'
// pid: 27708, tid: 27756, name: GLThread 16823  >>> net.pierrox.mcompass <<<
// signal 6 (SIGABRT), code -6 (SI_TKILL), fault addr --------
// Abort message: 'Invalid address 0xa1bee00c passed to free: value not allocated'
//     r0 00000000  r1 00006c6c  r2 00000006  r3 b3b7f978
//     r4 b3b7f980  r5 b3b7f930  r6 00000002  r7 0000010c
//     r8 b4d89f48  r9 b6d3a594  sl 00000001  fp 00000002
//     ip 00000006  sp b3b7f248  lr b6d04b61  pc b6d06f50  cpsr 40070010
// 
// backtrace:
//     #00 pc 00041f50  /system/lib/libc.so (tgkill+12)
//     #01 pc 0003fb5d  /system/lib/libc.so (pthread_kill+32)
//     #02 pc 0001c30f  /system/lib/libc.so (raise+10)
//     #03 pc 000194c1  /system/lib/libc.so (__libc_android_abort+34)
//     #04 pc 000174ac  /system/lib/libc.so (abort+4)
//     #05 pc 0001af23  /system/lib/libc.so (__libc_fatal+16)
//     #06 pc 00055373  /system/lib/libc.so (ifree+202)
//     #07 pc 00058257  /system/lib/libc.so (je_free+374)
//     #08 pc 0027d9fb  /system/lib/libart.so (_ZN3art3JNI29ReleasePrimitiveArrayCriticalEP7_JNIEnvP7_jarrayPvi+642)
//     #09 pc 0005a510  /system/lib/libandroid_runtime.so
//     #10 pc 7380375d  /data/dalvik-cache/arm/system@framework@boot.oat (offset 0x1ed6000)
// 
Encounter abort but we are in continuous mode.
Force to stop all activites and make a restart.
*** WARNNING: the top activity package com.google.android.googlequicksearchbox is not allowed.
Generate activity event for activity ComponentInfo{net.pierrox.mcompass/net.pierrox.mcompass.MCompass} from 0 of 1
// CRASH: net.pierrox.mcompass (pid 27794) (elapsed nanos: 357506452425710)
// Short Msg: Native crash
// Long Msg: Native crash: Aborted
// Build Label: google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys
// Build Changelist: 3437181
// Build Time: 1478203422000
// *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
// Build fingerprint: 'google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys'
// Revision: '11'
// ABI: 'arm'
// pid: 27794, tid: 27832, name: GLThread 16827  >>> net.pierrox.mcompass <<<
// signal 6 (SIGABRT), code -6 (SI_TKILL), fault addr --------
// Abort message: 'Invalid address 0xa1aec00c passed to free: value not allocated'
//     r0 00000000  r1 00006cb8  r2 00000006  r3 b3b7f978
//     r4 b3b7f980  r5 b3b7f930  r6 00000002  r7 0000010c
//     r8 b4d89988  r9 b6d3a594  sl 00000001  fp 00000002
//     ip 00000006  sp b3b7f248  lr b6d04b61  pc b6d06f50  cpsr 40070010
// 
// backtrace:
//     #00 pc 00041f50  /system/lib/libc.so (tgkill+12)
//     #01 pc 0003fb5d  /system/lib/libc.so (pthread_kill+32)
//     #02 pc 0001c30f  /system/lib/libc.so (raise+10)
//     #03 pc 000194c1  /system/lib/libc.so (__libc_android_abort+34)
//     #04 pc 000174ac  /system/lib/libc.so (abort+4)
//     #05 pc 0001af23  /system/lib/libc.so (__libc_fatal+16)
//     #06 pc 00055373  /system/lib/libc.so (ifree+202)
//     #07 pc 00058257  /system/lib/libc.so (je_free+374)
//     #08 pc 0027d9fb  /system/lib/libart.so (_ZN3art3JNI29ReleasePrimitiveArrayCriticalEP7_JNIEnvP7_jarrayPvi+642)
//     #09 pc 0005a510  /system/lib/libandroid_runtime.so
//     #10 pc 7380375d  /data/dalvik-cache/arm/system@framework@boot.oat (offset 0x1ed6000)

```



