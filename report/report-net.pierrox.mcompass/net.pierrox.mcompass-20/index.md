title: net.pierrox.mcompass

# net.pierrox.mcompass

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
// Build fingerprint: 'google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys'
// Revision: '11'
// ABI: 'arm'
// pid: 20366, tid: 20416, name: GLThread 16392  >>> net.pierrox.mcompass <<<
// signal 6 (SIGABRT), code -6 (SI_TKILL), fault addr --------
// Abort message: 'Invalid address 0xa1bee00c passed to free: value not allocated'
//     r0 00000000  r1 00004fc0  r2 00000006  r3 b3a7f978
//     r4 b3a7f980  r5 b3a7f930  r6 00000002  r7 0000010c
//     r8 b4d89f08  r9 b6d3a594  sl 00000001  fp 00000002
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
// CRASH: net.pierrox.mcompass (pid 20432) (elapsed nanos: 357061978618067)
// Short Msg: Native crash
// Long Msg: Native crash: Aborted
// Build Label: google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys
// Build Changelist: 3437181
// Build Time: 1478203422000
// *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
// Build fingerprint: 'google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys'
// Revision: '11'
// ABI: 'arm'
// pid: 20432, tid: 20461, name: GLThread 16395  >>> net.pierrox.mcompass <<<
// signal 6 (SIGABRT), code -6 (SI_TKILL), fault addr --------
// Abort message: 'Invalid address 0xa1bee00c passed to free: value not allocated'
//     r0 00000000  r1 00004fed  r2 00000006  r3 b3b7f978
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
// CRASH: net.pierrox.mcompass (pid 20494) (elapsed nanos: 357066046013064)
// Short Msg: Native crash
// Long Msg: Native crash: Aborted
// Build Label: google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys
// Build Changelist: 3437181
// Build Time: 1478203422000
// *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
// Build fingerprint: 'google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys'
// Revision: '11'
// ABI: 'arm'
// pid: 20494, tid: 20524, name: GLThread 16399  >>> net.pierrox.mcompass <<<
// signal 6 (SIGABRT), code -6 (SI_TKILL), fault addr --------
// Abort message: 'Invalid address 0xa1bee00c passed to free: value not allocated'
//     r0 00000000  r1 0000502c  r2 00000006  r3 b3b7f978
//     r4 b3b7f980  r5 b3b7f930  r6 00000002  r7 0000010c
//     r8 b3ba6048  r9 b6d3a594  sl 00000001  fp 00000002
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
// CRASH: net.pierrox.mcompass (pid 20555) (elapsed nanos: 357070174990147)
// Short Msg: Native crash
// Long Msg: Native crash: Aborted
// Build Label: google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys
// Build Changelist: 3437181
// Build Time: 1478203422000
// *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
// Build fingerprint: 'google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys'
// Revision: '11'
// ABI: 'arm'
// pid: 20555, tid: 20586, name: GLThread 16403  >>> net.pierrox.mcompass <<<
// signal 6 (SIGABRT), code -6 (SI_TKILL), fault addr --------
// Abort message: 'Invalid address 0xb370200c passed to free: value not allocated'
//     r0 00000000  r1 0000506a  r2 00000006  r3 b3b7f978
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
// CRASH: net.pierrox.mcompass (pid 20615) (elapsed nanos: 357074251793739)
// Short Msg: Native crash
// Long Msg: Native crash: Segmentation fault
// Build Label: google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys
// Build Changelist: 3437181
// Build Time: 1478203422000
// *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
// Build fingerprint: 'google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys'
// Revision: '11'
// ABI: 'arm'
// pid: 20615, tid: 20632, name: GLThread 16407  >>> net.pierrox.mcompass <<<
// signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x0
//     r0 00000000  r1 00000000  r2 00000000  r3 00000002
//     r4 00000000  r5 b36fd00c  r6 b3bb1000  r7 00000018
//     r8 b3bb0048  r9 b3bb1e40  sl 00000001  fp 00000002
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
// CRASH: net.pierrox.mcompass (pid 20674) (elapsed nanos: 357078577625300)
// Short Msg: Native crash
// Long Msg: Native crash: Aborted
// Build Label: google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys
// Build Changelist: 3437181
// Build Time: 1478203422000
// *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
// Build fingerprint: 'google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys'
// Revision: '11'
// ABI: 'arm'
// pid: 20674, tid: 20693, name: GLThread 16411  >>> net.pierrox.mcompass <<<
// signal 6 (SIGABRT), code -6 (SI_TKILL), fault addr --------
// Abort message: 'Invalid address 0xb370200c passed to free: value not allocated'
//     r0 00000000  r1 000050d5  r2 00000006  r3 b3b7f978
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
// CRASH: net.pierrox.mcompass (pid 20745) (elapsed nanos: 357082528836913)
// Short Msg: Native crash
// Long Msg: Native crash: Aborted
// Build Label: google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys
// Build Changelist: 3437181
// Build Time: 1478203422000
// *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
// Build fingerprint: 'google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys'
// Revision: '11'
// ABI: 'arm'
// pid: 20745, tid: 20775, name: GLThread 16415  >>> net.pierrox.mcompass <<<
// signal 6 (SIGABRT), code -6 (SI_TKILL), fault addr --------
// Abort message: 'Invalid address 0xa1bee00c passed to free: value not allocated'
//     r0 00000000  r1 00005127  r2 00000006  r3 b3b7f978
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
// CRASH: net.pierrox.mcompass (pid 20816) (elapsed nanos: 357086583655660)
// Short Msg: Native crash
// Long Msg: Native crash: Aborted
// Build Label: google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys
// Build Changelist: 3437181
// Build Time: 1478203422000
// *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
// Build fingerprint: 'google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys'
// Revision: '11'
// ABI: 'arm'
// pid: 20816, tid: 20835, name: GLThread 16419  >>> net.pierrox.mcompass <<<
// signal 6 (SIGABRT), code -6 (SI_TKILL), fault addr --------
// Abort message: 'Invalid address 0xb36df00c passed to free: value not allocated'
//     r0 00000000  r1 00005163  r2 00000006  r3 b3b7f978
//     r4 b3b7f980  r5 b3b7f930  r6 00000002  r7 0000010c
//     r8 b3bb0108  r9 b6d3a594  sl 00000001  fp 00000002
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



