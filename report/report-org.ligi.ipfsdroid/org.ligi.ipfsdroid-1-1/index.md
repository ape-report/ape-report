title: org.ligi.ipfsdroid

# org.ligi.ipfsdroid

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
java.net.UnknownHostException
	at java.net.InetAddress.lookupHostByName(InetAddress.java:470)
	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:252)
	at java.net.InetAddress.getAllByName(InetAddress.java:215)
	at okhttp3.Dns$1.lookup(Dns.java:39)
	at okhttp3.internal.connection.RouteSelector.resetNextInetSocketAddress(RouteSelector.java:171)
	at okhttp3.internal.connection.RouteSelector.nextProxy(RouteSelector.java:137)
	at okhttp3.internal.connection.RouteSelector.next(RouteSelector.java:82)
	at okhttp3.internal.connection.StreamAllocation.findConnection(StreamAllocation.java:171)
	at okhttp3.internal.connection.StreamAllocation.findHealthyConnection(StreamAllocation.java:121)
	at okhttp3.internal.connection.StreamAllocation.newStream(StreamAllocation.java:100)
	at okhttp3.internal.connection.ConnectInterceptor.intercept(ConnectInterceptor.java:42)
	at okhttp3.internal.http.RealInterceptorChain.proceed(RealInterceptorChain.java:92)
	at okhttp3.internal.http.RealInterceptorChain.proceed(RealInterceptorChain.java:67)
	at okhttp3.internal.cache.CacheInterceptor.intercept(CacheInterceptor.java:93)
	at okhttp3.internal.http.RealInterceptorChain.proceed(RealInterceptorChain.java:92)
	at okhttp3.internal.http.RealInterceptorChain.proceed(RealInterceptorChain.java:67)
	at okhttp3.internal.http.BridgeInterceptor.intercept(BridgeInterceptor.java:93)
	at okhttp3.internal.http.RealInterceptorChain.proceed(RealInterceptorChain.java:92)
	at okhttp3.internal.http.RetryAndFollowUpInterceptor.intercept(RetryAndFollowUpInterceptor.java:120)
	at okhttp3.internal.http.RealInterceptorChain.proceed(RealInterceptorChain.java:92)
	at okhttp3.internal.http.RealInterceptorChain.proceed(RealInterceptorChain.java:67)
	at okhttp3.RealCall.getResponseWithInterceptorChain(RealCall.java:185)
	at okhttp3.RealCall.execute(RealCall.java:69)
	at org.ligi.ipfsdroid.IPFSDaemon.downloadFile(IPFSDaemon.kt:72)
	at org.ligi.ipfsdroid.IPFSDaemon.access$downloadFile(IPFSDaemon.kt:14)
	at org.ligi.ipfsdroid.IPFSDaemon$download$1.run(IPFSDaemon.kt:35)
	at java.lang.Thread.run(Thread.java:818)
Caused by: android.system.GaiException
	at libcore.io.Posix.android_getaddrinfo(Native Method)
	at libcore.io.ForwardingOs.android_getaddrinfo(ForwardingOs.java:55)
	at java.net.InetAddress.lookupHostByName(InetAddress.java:451)
	... 26 more

```



