## Instalation order
* Install xDrip latest beta https://github.com/StephenBlackWasAlreadyTaken/xDrip/wiki/xDrip-Beta . This is needed until we remove permissions from xDrip manifest
* Install and configure NSClient first from https://github.com/nightscout/NSClient-Android/releases . Minimal required version is 1.20
* Install AndroidAPS
* On Android 6 give permission for alarming in Settings -> Apps -> Draw over other apps

## Recommended NSClient configuration
* disable xDrip emulation. It's not needed anymore. AndroidAPS uses native NSClient SGV broadcasts to get BGs.
* DanaApp support is not needed and not used