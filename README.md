# Webview Android Studio
Membuat Aplikasi WebView dengan Swipe Refresh di Android Studio 

**Library <b>SwipeReflesh</b>**
```gradle
dependencies {
   implementation 'androidx.swiperefreshlayout:swiperefreshlayout:1.1.0'
}
```
**use-permission internet &write external storage**
```gradle
   <uses-permission android:name="android.permission.INTERNET" />
    <uses-permission android:name="android.permission.WRITE_EXTERNAL_STORAGE"/>
```

**orentation (cocok untuk webview & pdf)**
```AndroidManifest.xml
   <action android:name="android.intent.action.MAIN"
   android:configChanges="orientation|keyboardHidden|screenSize"/>
```
```MainActivity.java
     @Override
    public void onConfigurationChanged(Configuration newConfig){
        super.onConfigurationChanged(newConfig);
    }
```

  


