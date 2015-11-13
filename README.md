min3d-AndroidStudio
===================

This is the min3d framework and examples project ported to Android Studio (v1.3.2+) and Gradle (v2.4+).  It was originally built in 2010.  That source code is at https://code.google.com/p/min3d/.

The min3d framework simplifies writing OpenGl on Android.  Though it was written for OpenGL ES 1.0, it's a great introduction to OpenGL on Android and has lots of useful utilities and examples for the following:

* Vertex index lists
* Per-vertex colors
* Vertex normals
* Texture mapping
* Light source (just the one, for now)
* Camera class, with view frustrum settings
* Object scale, euler rotation, and translation properties as expected
* Object children that inherit parent's transform properties
* Ability to render a subset of an object's list of faces
* Triangle or point rendermodes (just the two, for now)
* A few canned object primitives
* Reading 3D objects from different file formats:
  * WaveFront OBJ
  * AutoDesk 3DS
  * id Tech 2 MD2

There are 2 modules in this project:

* app is the Android application with several examples using min3d.
* min3d is the min3d framework that the Android application examples use.

License
-------

MIT LICENSE

http://opensource.org/licenses/mit-license.php


Acknowledgements
----------------

Lee Felarca and Dennis Ippel wrote the original code.
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
