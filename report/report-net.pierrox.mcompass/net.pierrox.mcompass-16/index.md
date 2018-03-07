title: net.pierrox.mcompass

# net.pierrox.mcompass

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
// Build fingerprint: 'google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys'
// Revision: '11'
// ABI: 'arm'
// pid: 17786, tid: 17850, name: GLThread 16247  >>> net.pierrox.mcompass <<<
// signal 6 (SIGABRT), code -6 (SI_TKILL), fault addr --------
// Abort message: 'Invalid address 0xa1bee00c passed to free: value not allocated'
//     r0 00000000  r1 000045ba  r2 00000006  r3 b3b7f978
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
// CRASH: net.pierrox.mcompass (pid 17888) (elapsed nanos: 356909264977082)
// Short Msg: Native crash
// Long Msg: Native crash: Aborted
// Build Label: google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys
// Build Changelist: 3437181
// Build Time: 1478203422000
// *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
// Build fingerprint: 'google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys'
// Revision: '11'
// ABI: 'arm'
// pid: 17888, tid: 17919, name: GLThread 16251  >>> net.pierrox.mcompass <<<
// signal 6 (SIGABRT), code -6 (SI_TKILL), fault addr --------
// Abort message: 'Invalid address 0xb370600c passed to free: value not allocated'
//     r0 00000000  r1 000045ff  r2 00000006  r3 b3b7f978
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
// CRASH: net.pierrox.mcompass (pid 17948) (elapsed nanos: 356913329278332)
// Short Msg: Native crash
// Long Msg: Native crash: Aborted
// Build Label: google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys
// Build Changelist: 3437181
// Build Time: 1478203422000
// *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
// Build fingerprint: 'google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys'
// Revision: '11'
// ABI: 'arm'
// pid: 17948, tid: 17979, name: GLThread 16256  >>> net.pierrox.mcompass <<<
// signal 6 (SIGABRT), code -6 (SI_TKILL), fault addr --------
// Abort message: 'Invalid address 0xa1bee00c passed to free: value not allocated'
//     r0 00000000  r1 0000463b  r2 00000006  r3 b3a7f978
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
// CRASH: net.pierrox.mcompass (pid 0) (elapsed nanos: 356917484093747)
// Short Msg: Native crash
// Long Msg: Native crash: Aborted
// Build Label: google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys
// Build Changelist: 3437181
// Build Time: 1478203422000
// *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
// Build fingerprint: 'google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys'
// Revision: '11'
// ABI: 'arm'
// pid: 18010, tid: 18040, name: GLThread 16259  >>> net.pierrox.mcompass <<<
// signal 6 (SIGABRT), code -6 (SI_TKILL), fault addr --------
// Abort message: 'Invalid address 0xb36df00c passed to free: value not allocated'
//     r0 00000000  r1 00004678  r2 00000006  r3 b3b7f978
//     r4 b3b7f980  r5 b3b7f930  r6 00000002  r7 0000010c
//     r8 b3ba6108  r9 b6d3a594  sl 00000001  fp 00000002
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
// CRASH: net.pierrox.mcompass (pid 18070) (elapsed nanos: 356921606790151)
// Short Msg: Native crash
// Long Msg: Native crash: Aborted
// Build Label: google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys
// Build Changelist: 3437181
// Build Time: 1478203422000
// *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
// Build fingerprint: 'google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys'
// Revision: '11'
// ABI: 'arm'
// pid: 18070, tid: 18102, name: GLThread 16264  >>> net.pierrox.mcompass <<<
// signal 6 (SIGABRT), code -6 (SI_TKILL), fault addr --------
// Abort message: 'Invalid address 0xa1adb00c passed to free: value not allocated'
//     r0 00000000  r1 000046b6  r2 00000006  r3 b3a7f978
//     r4 b3a7f980  r5 b3a7f930  r6 00000002  r7 0000010c
//     r8 b4d89a48  r9 b6d3a594  sl 00000001  fp 00000002
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
// CRASH: net.pierrox.mcompass (pid 18132) (elapsed nanos: 356925626935045)
// Short Msg: Native crash
// Long Msg: Native crash: Aborted
// Build Label: google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys
// Build Changelist: 3437181
// Build Time: 1478203422000
// *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
// Build fingerprint: 'google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys'
// Revision: '11'
// ABI: 'arm'
// pid: 18132, tid: 18163, name: GLThread 16267  >>> net.pierrox.mcompass <<<
// signal 6 (SIGABRT), code -6 (SI_TKILL), fault addr --------
// Abort message: 'Invalid address 0xa1bee00c passed to free: value not allocated'
//     r0 00000000  r1 000046f3  r2 00000006  r3 b3b7f978
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
// CRASH: net.pierrox.mcompass (pid 18200) (elapsed nanos: 356929799639212)
// Short Msg: Native crash
// Long Msg: Native crash: Aborted
// Build Label: google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys
// Build Changelist: 3437181
// Build Time: 1478203422000
// *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
// Build fingerprint: 'google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys'
// Revision: '11'
// ABI: 'arm'
// pid: 18200, tid: 18231, name: GLThread 16271  >>> net.pierrox.mcompass <<<
// signal 6 (SIGABRT), code -6 (SI_TKILL), fault addr --------
// Abort message: 'Invalid address 0xb370200c passed to free: value not allocated'
//     r0 00000000  r1 00004737  r2 00000006  r3 b3b7f978
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
// CRASH: net.pierrox.mcompass (pid 18262) (elapsed nanos: 356933977143376)
// Short Msg: Native crash
// Long Msg: Native crash: Aborted
// Build Label: google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys
// Build Changelist: 3437181
// Build Time: 1478203422000
// *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
// Build fingerprint: 'google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys'
// Revision: '11'
// ABI: 'arm'
// pid: 18262, tid: 18281, name: GLThread 16275  >>> net.pierrox.mcompass <<<
// signal 6 (SIGABRT), code -6 (SI_TKILL), fault addr --------
// Abort message: 'Invalid address 0xa1c2000c passed to free: value not allocated'
//     r0 00000000  r1 00004769  r2 00000006  r3 b3b7f978
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



