# file-uploads

## File list

### OrganicMaps-25021701-web-debug.apk

- License: Apatch-2.0
- Repository: https://github.com/organicmaps/organicmaps
- Description: Build for Android automotive OS with adding following intent:
```diff
--- a/android/app/src/main/AndroidManifest.xml
+++ b/android/app/src/main/AndroidManifest.xml
@@ -354,6 +354,8 @@
       <intent-filter>
         <action android:name="android.intent.action.MAIN"/>
         <category android:name="android.intent.category.LAUNCHER"/>
+        <category android:name="android.intent.category.DEFAULT"/>
+        <category android:name="android.intent.category.APP_MAPS"/>
       </intent-filter>
     </activity-alias>
```

### MUKASHISound-automotive-debug.apk

- License: GPL-3.0
- Repository: https://github.com/mikkikimasutaro/MUKASHISound_src
- Description: Because apk is't provided on github, built it as-is.


