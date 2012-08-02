robotium-maps
=============

This is an extension to the robotium project and provides testing support for maps on Android.

The Android maps API is not available through maven, you'll have to install it into your own repository:

	mvn install:install-file -Dfile="%ANDROID_HOME%/add-ons/addon-google_apis-google-15/libs/maps.jar" -DgroupId=com.google.android.maps -DartifactId=maps -Dversion=4.0.3 -Dpackaging=jar


The project home page is at http://www.robotium.org/
The robotium source code is available at https://github.com/jayway/robotium