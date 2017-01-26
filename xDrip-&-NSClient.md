## xDrip
* In xDrip or xDrip+, go into settings and enable "Broadcast locally"

[[https://github.com/MilosKozak/AndroidAPS/wiki/images/xdrip1.png]]

## NSClient
* Install NSClient from https://github.com/nightscout/NSClient-Android/releases . Minimal required version is 1.21
* In NSClient, select Menu by tapping the 3 dots in the top right. Select Preferences.
* Enable Connect to Nightscout"
* Enter "Nightscout URL" and "Nightscout API secret"
* Enter 24 in "Hours to fetch"

[[https://github.com/MilosKozak/AndroidAPS/wiki/images/nsclient1.png]]

### Recommended NSClient configuration
 * Disable xDrip emulation. It's not needed anymore. AndroidAPS uses native NSClient SGV broadcasts to get BGs.
 * DanaApp support is not needed and not used