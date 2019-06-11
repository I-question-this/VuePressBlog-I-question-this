# Raspberry Pi 3 B+ Smart Watch

## Parts
* [Raspberry Pi 3 B+](https://www.adafruit.com/product/3055)
* [PiTFT Plus 480x320 3.5" TFT+Touchscreen for Raspberry Pi](https://www.adafruit.com/product/2441)
* [GPIO Ribbon Cable for Raspberry Pi Model A and B - 26 pin](https://www.adafruit.com/product/862)
* [Arduino -- Produced by SunFounder](https://www.sunfounder.com/starter-kit-standard-v2-r3.html)
  * I got it because I was interested in the electronic parts in this kit. Amazon through in the Arduino for a few more bucks. It was only later that I decided to use the Arduino for this project.
* [Raspberry Pi Camera](https://www.adafruit.com/product/3099)

## Bluetooth SSH
[Raspberry Pi Forums](https://www.raspberrypi.org/forums/viewtopic.php?t=36889)
[elinux.org Bluetooth Network](https://elinux.org/Bluetooth_Network)
* Created BluetoothPan in /etc/network/interfaces.d
  * /etc/network/interface includes sources in the above directory
* Created directory /etc/bluetooth/ban
  * created two files dev-{up|down}

[5.x tutorial](http://blog.fraggod.net/2015/03/28/bluetooth-pan-network-setup-with-bluez-5x.html)

[More up to date information?](https://www.pcsuggest.com/linux-bluetooth-setup-hcitool-bluez/)

## Wireless Access Point
[From Raspberry Pi Website](https://www.raspberrypi.org/documentation/configuration/wireless/access-point.md)

## Understanding Pin Layout
[PitTFT Plus pins](https://pinout.xyz/pinout/pitft_plus_35)
