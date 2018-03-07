title: net.pierrox.mcompass

# net.pierrox.mcompass

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
// Build fingerprint: 'google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys'
// Revision: '11'
// ABI: 'arm'
// pid: 25329, tid: 25386, name: GLThread 16691  >>> net.pierrox.mcompass <<<
// signal 6 (SIGABRT), code -6 (SI_TKILL), fault addr --------
// Abort message: 'Invalid address 0xa1bee00c passed to free: value not allocated'
//     r0 00000000  r1 0000632a  r2 00000006  r3 b3b7f978
//     r4 b3b7f980  r5 b3b7f930  r6 00000002  r7 0000010c
//     r8 b4d89a48  r9 b6d3a594  sl 00000001  fp 00000002
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
// CRASH: net.pierrox.mcompass (pid 25436) (elapsed nanos: 357367337079304)
// Short Msg: Native crash
// Long Msg: Native crash: Aborted
// Build Label: google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys
// Build Changelist: 3437181
// Build Time: 1478203422000
// *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
// Build fingerprint: 'google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys'
// Revision: '11'
// ABI: 'arm'
// pid: 25436, tid: 25462, name: GLThread 16695  >>> net.pierrox.mcompass <<<
// signal 6 (SIGABRT), code -6 (SI_TKILL), fault addr --------
// Abort message: 'Invalid address 0xa1bdd00c passed to free: value not allocated'
//     r0 00000000  r1 00006376  r2 00000006  r3 b3b7f978
//     r4 b3b7f980  r5 b3b7f930  r6 00000002  r7 0000010c
//     r8 b4d89f88  r9 b6d3a594  sl 00000001  fp 00000002
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
// CRASH: net.pierrox.mcompass (pid 25491) (elapsed nanos: 357371553483782)
// Short Msg: Native crash
// Long Msg: Native crash: Aborted
// Build Label: google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys
// Build Changelist: 3437181
// Build Time: 1478203422000
// *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
// Build fingerprint: 'google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys'
// Revision: '11'
// ABI: 'arm'
// pid: 25491, tid: 25522, name: GLThread 16699  >>> net.pierrox.mcompass <<<
// signal 6 (SIGABRT), code -6 (SI_TKILL), fault addr --------
// Abort message: 'Invalid address 0xb370200c passed to free: value not allocated'
//     r0 00000000  r1 000063b2  r2 00000006  r3 b3b7f978
//     r4 b3b7f980  r5 b3b7f930  r6 00000002  r7 0000010c
//     r8 b4d89f88  r9 b6d3a594  sl 00000001  fp 00000002
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
// CRASH: net.pierrox.mcompass (pid 25552) (elapsed nanos: 357375700471802)
// Short Msg: Native crash
// Long Msg: Native crash: Aborted
// Build Label: google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys
// Build Changelist: 3437181
// Build Time: 1478203422000
// *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
// Build fingerprint: 'google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys'
// Revision: '11'
// ABI: 'arm'
// pid: 25552, tid: 25582, name: GLThread 16703  >>> net.pierrox.mcompass <<<
// signal 6 (SIGABRT), code -6 (SI_TKILL), fault addr --------
// Abort message: 'Invalid address 0xb370200c passed to free: value not allocated'
//     r0 00000000  r1 000063ee  r2 00000006  r3 b3b7f978
//     r4 b3b7f980  r5 b3b7f930  r6 00000002  r7 0000010c
//     r8 b3ba7008  r9 b6d3a594  sl 00000001  fp 00000002
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
// CRASH: net.pierrox.mcompass (pid 25617) (elapsed nanos: 357379831605237)
// Short Msg: Native crash
// Long Msg: Native crash: Aborted
// Build Label: google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys
// Build Changelist: 3437181
// Build Time: 1478203422000
// *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
// Build fingerprint: 'google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys'
// Revision: '11'
// ABI: 'arm'
// pid: 25617, tid: 25648, name: GLThread 16707  >>> net.pierrox.mcompass <<<
// signal 6 (SIGABRT), code -6 (SI_TKILL), fault addr --------
// Abort message: 'Invalid address 0xb36cb00c passed to free: value not allocated'
//     r0 00000000  r1 00006430  r2 00000006  r3 b3b7f978
//     r4 b3b7f980  r5 b3b7f930  r6 00000002  r7 0000010c
//     r8 b3bb1048  r9 b6d3a594  sl 00000001  fp 00000002
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
// CRASH: net.pierrox.mcompass (pid 0) (elapsed nanos: 357383827320339)
// Short Msg: Native crash
// Long Msg: Native crash: Aborted
// Build Label: google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys
// Build Changelist: 3437181
// Build Time: 1478203422000
// *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
// Build fingerprint: 'google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys'
// Revision: '11'
// ABI: 'arm'
// pid: 25687, tid: 25718, name: GLThread 16711  >>> net.pierrox.mcompass <<<
// signal 6 (SIGABRT), code -6 (SI_TKILL), fault addr --------
// Abort message: 'Invalid address 0xb370200c passed to free: value not allocated'
//     r0 00000000  r1 00006476  r2 00000006  r3 b3b7f978
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
// CRASH: net.pierrox.mcompass (pid 0) (elapsed nanos: 357387894764765)
// Short Msg: Native crash
// Long Msg: Native crash: Aborted
// Build Label: google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys
// Build Changelist: 3437181
// Build Time: 1478203422000
// *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
// Build fingerprint: 'google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys'
// Revision: '11'
// ABI: 'arm'
// pid: 25758, tid: 25789, name: GLThread 16715  >>> net.pierrox.mcompass <<<
// signal 6 (SIGABRT), code -6 (SI_TKILL), fault addr --------
// Abort message: 'Invalid address 0xa1aec00c passed to free: value not allocated'
//     r0 00000000  r1 000064bd  r2 00000006  r3 b3b7f978
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
// 
Encounter abort but we are in continuous mode.
Force to stop all activites and make a restart.
*** WARNNING: the top activity package com.google.android.googlequicksearchbox is not allowed.
Generate activity event for activity ComponentInfo{net.pierrox.mcompass/net.pierrox.mcompass.MCompass} from 0 of 1
// CRASH: net.pierrox.mcompass (pid 25826) (elapsed nanos: 357391995483721)
// Short Msg: Native crash
// Long Msg: Native crash: Aborted
// Build Label: google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys
// Build Changelist: 3437181
// Build Time: 1478203422000
// *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
// Build fingerprint: 'google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys'
// Revision: '11'
// ABI: 'arm'
// pid: 25826, tid: 25855, name: GLThread 16719  >>> net.pierrox.mcompass <<<
// signal 6 (SIGABRT), code -6 (SI_TKILL), fault addr --------
// Abort message: 'Invalid address 0xb36fe00c passed to free: value not allocated'
//     r0 00000000  r1 000064ff  r2 00000006  r3 b3b7f978
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

```



