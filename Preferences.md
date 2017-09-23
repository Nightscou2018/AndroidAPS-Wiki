## Password for settings
This allows you to set a password in order to prevent accidental or unauthorised changes to Preferences. After you enter a password here you will be required to enter it in order to access Preferences.
## Patient age
_ENTER CONTENT HERE_
## Treatments safety
### Max allowed bolus [U]
This is the maximum amount of bolus insulin that AAPS is allowed to deliver. This setting exists as a safety limit to prevent the delivery of a massive bolus due to accidental input or user error. It is recommended to set this to a sensible amount that corresponds roughly to the maximum amount of bolus insulin that you are ever likely to need for a meal or correction dose. This restriction is also applied to the results of the Bolus Calculator.
## Advanced Settings
### ApenAPS MA
#### Always use short average delta instead of...
Enabling this setting is useful when you are using data from unfiltered sources such as xDrip+, as opposed to filtered sources such as an official Dexcom Receiver. Filtered data appears to be smooth, whereas unfiltered data can appear to be jumpy. This unfiltered data could cause AndroidAPS to apply Temporary Basal Rate changes more frequently than are really needed, as the OpenAPS algorithm reacts to the jumpy data. With this setting enabled, the OpenAPS algorithm will use the Short Average Delta (the average change in blood glucose over the past 15 minutes) instead of the last blood glucose reading received. This effectively has a "smoothing" effect on the data and attempts to compensate for any jumpy readings.

Users of Abbot Freestyle Libre sensors collecting their glucose data via devices such as LimiTTers may find this setting provides better results with AAPS.

For further tips regarding data smoothing when using xDrip+ as the data source, see this page.