min3d-AndroidStudio
===================

The min3d sample project Android Studio (v1.3.2+) and Gradle (v2.4+).

The code is written for OpenGL ES 1.0.

There are 2 modules in this project:

* app is the Android application with several examples using min3d.
* min3d is the min3d framework that the Android application examples use.

License
-------

MIT LICENSE

http://opensource.org/licenses/mit-license.php


Acknowledgements
----------------

Lee Felarca wrote the original source.
See http://zeropointnine.com/blog/a-3d-framework-for-android-min3d/

Mario Viviani did the original port to Android Studio (version 0.4.4)
from which this project was created.
See https://github.com/Mariuxtheone/min3dSampleProject-AndroidStudio

Notes
------

Before importing the project into Android Studio you may want to modify
the Android SDK version targets found in:

* app/build.gradle
* min3d/build.gradle
* app/src/main/AndroidManifest.xml
