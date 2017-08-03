**For users of Dexcom:**<Br>
_If using xdrip…_<br>
* If not already set up then download [xdrip](https://github.com/NightscoutFoundation/xDrip) and follow instructions on nightscout ([G4 without share](http://www.nightscout.info/wiki/welcome/nightscout-with-xdrip-wireless-bridge), [G4 share](http://www.nightscout.info/wiki/welcome/nightscout-with-xdrip-and-dexcom-share-wireless), [G5](http://www.nightscout.info/wiki/welcome/nightscout-with-xdrip-and-dexcom-share-wireless/xdrip-with-g5-support)).
* In xdrip go to Settings > Interapp Compatibility > Broadcast Data Locally and select ON.
* In xdrip go to Settings > Interapp Compatibility > Accept Treatments and select OFF.
* If you want to be able to use AndroidAPS to calibrate then in xdrip go to Settings > Interapp Compatibility > Accept Calibrations and select ON.  You may also want to review the options in Settings > Less Common Settings > Advanced Calibration Settings.
* Select xdrip in ConfigBuilder.

_If using OTG cable ('traditional' Nightscout)…_<br>
* If not already set up then download Nightscout Uploader app from the Play Store and follow instructions on [Nightscout](http://www.nightscout.info/wiki/welcome/basic-requirements).
* In AndroidAPS Preferences enter your nightscout website and API secret.
* Select NSClient in ConfigBuilder.


**For users of Libre:**<br>

_If using xdrip..._<br>
* If not already set up then download xdrip and follow instructions on [LimiTTEer](https://github.com/JoernL/LimiTTer),  [Libre Alarm](https://github.com/pimpimmi/LibreAlarm/wiki) or [BlueReader](https://unendlichkeit.net/wordpress/?p=680&lang=en)([Hardware](https://bluetoolz.de/wordpress/)).
* In xdrip go to Settings > Interapp Compatibility > Broadcast Data Locally and select ON.
* In xdrip go to Settings > Interapp Compatibility > Accept Treatments and select OFF.
* If you want to be able to use AndroidAPS to calibrate then in xdrip go to Settings > Interapp Compatibility > Accept Calibrations and select ON.  You may also want to review the options in Settings > Less Common Settings > Advanced Calibration Settings.
* Select xdrip in ConfigBuilder.

_If using Glimp..._<br>
* If not already set up then download Glimp and follow instructions on [nightscout](http://www.nightscout.info/wiki/welcome/nightscout-for-libre).
* Select Glimp in ConfigBuilder.

**For users of MM640g or MM630g:**<br>
* If not already set up then download [600SeriesAndroidUploaer](http://pazaan.github.io/600SeriesAndroidUploader/) and follow instructions on [nightscout](http://www.nightscout.info/wiki/welcome/nightscout-and-medtronic-640g).
* In 600 Series Uploader go to Settings > Send to xdrip+ and select ON (tick).
* Select MM640g in ConfigBuilder.


**For users of other CGM uploaded to nightscout:**<br>
If you have any other CGM set up that sends your data to [Nightscout](http://www.nightscout.info) then<br>
* In AndroidAPS Preferences enter your nightscout website and API secret.
* Select NSClient in ConfigBuilder.