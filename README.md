# ArtFrame Firmware
For instructions on how to flash the firmware, see the according section in the [handbook](https://framelabs.eu/firmware-update).

# Changelog

## 1.5.5-beta
* Fix a bug where the WiFi would try to connect indefinitely

## 1.5.4
* Stability fixes for the web interface
* Fix bug where button could not be used to leave configuration mode
* Add dedicated error message for server timeout in WiFi mode

## 1.5.2
* Add option to choose between reduction of ghosting (default) or longer battery life
* Send info about desired orientation when fetching images
* for 6" ArtFrames use 1.5.2b (functionally equivalent to 1.5.2)

## 1.5
* Show thumbnails for uploaded pictures in web interface
* Improved performance of picture processing during uploads

## 1.4
* Device sends it's display resolution in WiFi mode
* Make sleep interval configurable remotely in WiFi mode
* Increase sleep interval precision from 1 min to 1 sec
* Configuration for vertically mounted devices added
* Webinterface configuration changes are synced to the device immediately
* Webinterface performance improvements

## 1.2
* Power savings improvement

## 1.1.2
* Performance improvement
* Fix bug where Safari would sometimes not delete files containing special characters
