title: edu.cmu.cs.speech.tts.flite

# edu.cmu.cs.speech.tts.flite

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
// Build fingerprint: 'google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys'
// Revision: '11'
// ABI: 'arm'
// pid: 16255, tid: 16549, name: AsyncTask #3  >>> edu.cmu.cs.speech.tts.flite <<<
// signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x24
//     r0 00000000  r1 9cb5c300  r2 9720fcd6  r3 b6d3eec0
//     r4 00000000  r5 fffffffe  r6 00000000  r7 9cb5c2c8
//     r8 9cb5c2cc  r9 9cb5c2d0  sl 9cb5c304  fp 12d18c60
//     ip 9cb5c300  sp 9cb5c2b8  lr b3afdad5  pc b3aff0ae  cpsr 60060030
// 
// backtrace:
//     #00 pc 000140ae  /data/app/edu.cmu.cs.speech.tts.flite-1/lib/arm/libttsflite.so (_ZN11FliteEngine6Voices17IsLocaleAvailableENS_6StringES1_S1_+41)
//     #01 pc 00012ad1  /data/app/edu.cmu.cs.speech.tts.flite-1/lib/arm/libttsflite.so (_Z19isLanguageAvailablePvPKcS1_S1_+160)
//     #02 pc 000126d3  /data/app/edu.cmu.cs.speech.tts.flite-1/lib/arm/libttsflite.so (Java_edu_cmu_cs_speech_tts_flite_NativeFliteTTS_nativeIsLanguageAvailable+74)
//     #03 pc 0001561d  /data/app/edu.cmu.cs.speech.tts.flite-1/oat/arm/base.odex (offset 0x10000)

```



