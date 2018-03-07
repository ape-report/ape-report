title: com.bmco.cratesiounofficial

# com.bmco.cratesiounofficial

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.RuntimeException: Parcelable encountered IOException writing serializable object (name = com.bmco.cratesiounofficial.models.Crate)
// 	at android.os.Parcel.writeSerializable(Parcel.java:1468)
// 	at android.os.Parcel.writeValue(Parcel.java:1416)
// 	at android.os.Parcel.writeArrayMapInternal(Parcel.java:686)
// 	at android.os.BaseBundle.writeToParcelInner(BaseBundle.java:1330)
// 	at android.os.Bundle.writeToParcel(Bundle.java:1079)
// 	at android.os.Parcel.writeBundle(Parcel.java:711)
// 	at android.content.Intent.writeToParcel(Intent.java:7793)
// 	at android.app.ActivityManagerProxy.startActivity(ActivityManagerNative.java:2640)
// 	at android.app.Instrumentation.execStartActivity(Instrumentation.java:1507)
// 	at android.app.Activity.startActivityForResult(Activity.java:3930)
// 	at android.support.v4.app.BaseFragmentActivityApi16.startActivityForResult(BaseFragmentActivityApi16.java:54)
// 	at android.support.v4.app.FragmentActivity.startActivityForResult(FragmentActivity.java:67)
// 	at android.app.Activity.startActivityForResult(Activity.java:3890)
// 	at android.support.v4.app.FragmentActivity.startActivityForResult(FragmentActivity.java:720)
// 	at android.app.Activity.startActivity(Activity.java:4213)
// 	at android.app.Activity.startActivity(Activity.java:4181)
// 	at com.bmco.cratesiounofficial.CrateActivity$5$1$1.run(CrateActivity.java:183)
// Caused by: java.io.NotSerializableException: com.bmco.cratesiounofficial.models.Version
// 	at java.io.ObjectOutputStream.writeNewObject(ObjectOutputStream.java:1344)
// 	at java.io.ObjectOutputStream.writeObjectInternal(ObjectOutputStream.java:1651)
// 	at java.io.ObjectOutputStream.writeObject(ObjectOutputStream.java:1497)
// 	at java.io.ObjectOutputStream.writeObject(ObjectOutputStream.java:1461)
// 	at java.util.ArrayList.writeObject(ArrayList.java:648)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at java.io.ObjectOutputStream.writeHierarchy(ObjectOutputStream.java:1033)
// 	at java.io.ObjectOutputStream.writeNewObject(ObjectOutputStream.java:1384)
// 	at java.io.ObjectOutputStream.writeObjectInternal(ObjectOutputStream.java:1651)
// 	at java.io.ObjectOutputStream.writeObject(ObjectOutputStream.java:1497)
// 	at java.io.ObjectOutputStream.writeObject(ObjectOutputStream.java:1461)
// 	at java.io.ObjectOutputStream.writeFieldValues(ObjectOutputStream.java:959)
// 	at java.io.ObjectOutputStream.defaultWriteObject(ObjectOutputStream.java:360)
// 	at java.io.ObjectOutputStream.writeHierarchy(ObjectOutputStream.java:1054)
// 	at java.io.ObjectOutputStream.writeNewObject(ObjectOutputStream.java:1384)
// 	at java.io.ObjectOutputStream.writeObjectInternal(ObjectOutputStream.java:1651)
// 	at java.io.ObjectOutputStream.writeObject(ObjectOutputStream.java:1497)
// 	at java.io.ObjectOutputStream.writeObject(ObjectOutputStream.java:1461)
// 	at android.os.Parcel.writeSerializable(Parcel.java:1463)
// 	... 16 more

```



