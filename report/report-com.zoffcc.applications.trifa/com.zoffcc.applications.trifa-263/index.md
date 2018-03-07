title: com.zoffcc.applications.trifa

# com.zoffcc.applications.trifa

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
// Build fingerprint: 'google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys'
// Revision: '11'
// ABI: 'arm'
// pid: 23497, tid: 23497, name: lications.trifa  >>> com.zoffcc.applications.trifa <<<
// signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x8bc
//     r0 00000000  r1 be9fd128  r2 be9fd124  r3 b3962198
//     r4 be9fd124  r5 be9fd128  r6 00000000  r7 9f01f250
//     r8 12ca9b00  r9 b4db6500  sl 12da5470  fp be9fd108
//     ip 00010026  sp be9fd0f0  lr b372faf0  pc b374cf68  cpsr a0070010
// 
// backtrace:
//     #00 pc 00045f68  /data/app/com.zoffcc.applications.trifa-1/lib/arm/libjni-c-toxcore.so (getfriend_id+16)
//     #01 pc 00028aec  /data/app/com.zoffcc.applications.trifa-1/lib/arm/libjni-c-toxcore.so (tox_friend_by_public_key+20)
//     #02 pc 0002632c  /data/app/com.zoffcc.applications.trifa-1/lib/arm/libjni-c-toxcore.so (Java_com_zoffcc_applications_trifa_MainActivity_tox_1friend_1by_1public_1key+108)
//     #03 pc 011d5f59  /data/app/com.zoffcc.applications.trifa-1/oat/arm/base.odex (offset 0xc1e000)

```



