# ArtFrame Firmware
For instructions on how to flash the firmware, see the according section in the [handbook](https://framelabs.eu/firmware-update).

# Latest firmware for each device type
* 6" HD, 9.7", 13.3" Artframe: [1.6.3](ArtFrame-Firmware-1.6.3.bin?raw=1)
* 31.2" Artframe: [1.6.3XL](ArtFrame-Firmware-1.6.3XL.bin?raw=1)
* 10.3" HD ArtFrame: [1.6.3M](ArtFrame-Firmware-1.6.3M.bin?raw=1)
* non-HD 6" ArtFrame: [1.5.2b](ArtFrame-Firmware-1.5.2b.bin?raw=1)

# Changelog

## 1.6.3
* Fix regression in feature to remotely change sleep time in WiFi mode

## 1.6.2
* Add option to shuffle the file display order
* Fix various minor bugs in web interface
* **XL:** Fix bug where error messages would not properly appear on the display
* **XL:** Increase display update speed

## 1.6.1
* Increase reliability of connection establishment to an existing WiFi
    * Increase timeout

## 1.6-beta
* Fix WiFi error when exiting Configuration Mode in WiFi mode
* Improve performance for devices in WiFi mode and repaint mode "Reduce ghosting"
* Fix bug where "Server timeout" would appear in WiFi mode, because the HTTP connection would not be closed
    * Respect the "Content-Length" header
    * Don't send "Connection: keep-alive" header
* **XL:** Stability fixes for display initialization
* **XL:** Increased internal display communication performance
* **XL:** Fixed bug in WiFi mode where no image was displayed

## 1.5.5
* Fix a bug where the WiFi would try to connect indefinitely

## 1.5.4
* Stability fixes for the web interface
* Fix bug where button could not be used to leave configuration mode
* Add dedicated error message for server timeout in WiFi mode

## 1.5.2
* Add option to choose between reduction of ghosting (default) or longer battery life
* Send info about desired orientation when fetching images

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
