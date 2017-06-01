* Download the [AndroidAPS repository](https://github.com/MilosKozak/AndroidAPS) and extract the files.

* Run Android Studio and select 'Open an existing Android Studio project', selecting the location of the extracted files.

* Click on BuildVariants button on the bottom left of the Android Studio, and notice that you have several kinds of build types.

[[https://github.com/MilosKozak/AndroidAPS/wiki/images/androidstudio1.png]]

* Select the build type you want to build. There are different modular options for pump, phone and watch, for example to have just a display on the watch (wear) or to be able to bolus from the watch (wearcontrol).  If you want the full option, then select 'fullWearcontrol-release'

* Go to Build Menu and click on Generate Signed APK, select the same build type, and when asked select v1.  For more information about using the keystore see [https://developer.android.com/studio/publish/app-signing.html#generate-key](https://developer.android.com/studio/publish/app-signing.html#generate-key)

* Please wait for some time until the APK is created. You will get the pop-up below when the process is done.

[[https://github.com/MilosKozak/AndroidAPS/wiki/images/androidstudio3.png]]

* Click on 'Show in Explorer'. You'll find the APK is generated, sometimes it may take time to display.

* Copy the APK to your android phone, and install it.  If you have an older version of AndroidAPS on your phone then you will need to uninstall this first, remember to export your settings if so.