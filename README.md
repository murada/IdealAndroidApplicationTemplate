# IdealAndroidApplicationTemplate

in this project i'll try to configure a good android project structure that support ( ar - en - themes ) and
add some useful librarys .

the project structure now :

- Drawbles ( default - night - notnight ) ( ldpi - mdpi - hdpi - xhdpi - xxhdpi - xxhdpi )

- Values
  
  - strings ( default - ar - en )
  - colors ( default - night - notnight )
  - dimes ( default - ldpi - mdpi - hdpi - xhdpi - xxhpi - xxxhdpi )
  
- Libraries 
 
  - firebase messaging ===> implementation 'com.google.firebase:firebase-messaging:17.3.4'
         
  - google gson ===> implementation 'com.google.code.gson:gson:2.8.5'
          
  - eventbus ===> implementation 'org.greenrobot:eventbus:3.1.1'
          
  - butterknife ===> annotationProcessor 'com.jakewharton:butterknife-compiler:10.0.0'
           ===> implementation 'com.jakewharton:butterknife:10.0.0'
           
  - volley ===> implementation 'com.android.volley:volley:1.1.0'

Dimens Based on : mdpi - hdpi - xhdpi - xxhdpi - xxxhpi ( 1x - 1.5x - 2x - 3x - 4x )

Images & Icons Size : from : http://iconhandbook.co.uk/reference/chart/android/

Launcher icons
48 × 48 (mdpi)
72 × 72 (hdpi)
96 × 96 (xhdpi)
144 × 144 (xxhdpi)
192 × 192 (xxxhdpi)
512 × 512 (Google Play store)	.png	Three-dimensional, front view, with a slight perspective as if viewed from above, so that users perceive some depth.

Action bar, Dialog & Tab icons
24 × 24 area in 32 × 32 (mdpi)
36 × 36 area in 48 × 48 (hdpi)
48 × 48 area in 64 × 64 (xhdpi)
72 × 72 area in 96 × 96 (xxhdpi)
96 × 96 area in 128 × 128 (xxxhdpi)	.png	These icons are used in the action bar menu. The first number is the size of the icon area, and the second is file size.

Small Contextual Icons
16 × 16 (mdpi)
24 × 24 (hdpi)
32 × 32 (xhdpi)
48 × 48 (xxhdpi)
64 × 64 (xxxhdpi)
.png	
Small icons are used to surface actions and/or provide status for specific items. For example, in the Gmail app, each message has a star icon that marks the message as important.

Notification icons
22 × 22 area in 24 × 24 (mdpi)
33 × 33 area in 36 × 36 (hdpi)
44 × 44 area in 48 × 48 (xhdpi)
66 × 66 area in 72 × 72 (xxhdpi)
88 × 88 area in 96 × 96 (xxxhdpi)
.png	These are used to represent application notifications in the status bar. They should be flat (no gradients), white and face-on perspective
