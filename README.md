# DJI-FPV-Goggles

This is my starting point for reverse engineering the video out through Smart Controller

## What others have found

distric-michael
- Dump of the FPV Live app from the SC https://github.com/district-michael/fpv_live
- Backup https://github.com/Amzd/fpv_live
- Other users that made forks seem not have collected any more data

jseaber
- "I'll try to sniff a Smart Controller when I have a chance." https://intofpv.com/t-scam-dji-fpv-goggles-hdmi-output-input-hacked?pid=114421#pid114421
- USB dump https://pastebin.com/ZZPa8bx8

yngndrw
- "I've noticed that when connecting my goggles to my PC, a RNDIS connection is opened with the IP range 192.168.42.*" https://github.com/dji-sdk/Windows-SDK/issues/68#issuecomment-746053105 
- https://github.com/yngndrw

deleted
- "There's a rumour that someone is hacking the DJI goggles to enable HDMI output so spectators can see the flight... involving custom firmware, additional hardware and some DIY..." https://www.facebook.com/intofpv/posts/theres-a-rumour-that-someone-is-hacking-the-dji-goggles-to-enable-hdmi-output-so/3176521739104699/
- https://intofpv.com/t-dji-fpv-goggles-hdmi-output-input-hacked

amstar & Aerial-Pixel
- Rooted Smart Controller https://mavicpilots.com/threads/successful-rooting-of-rm500-also-known-as-the-smart-controller.62580
- "As of now appears to be designed for running the go4 app and that’s pretty much it, rooted or not"
- "This android device does not have its own google usb driver"

There's a lot more info on facebook but I don't want to make an account just to read it so we'll do without that info.

## Reverse engineering USB

- MITM USB connections https://github.com/usb-tools/Facedancer

## Slightly relevant

- "This wiki is designed to store data relating to reverse engineering of DJI aircraft." https://dji.retroroms.info/start
- "This repository contains tools for reverse engineering DJI products." https://github.com/fvantienen/dji_rev

## For development

- https://stackoverflow.com/questions/27376450/how-does-the-gopro-pair-with-an-iphone
- https://www.avrfreaks.net/forum/any-bluetooth-modules-act-usb-middle-man
- IOKit on iOS https://github.com/guoxuzan/IOKit
- libusb on iOS (IOKit alternative) https://github.com/Brandon-T/iOUSB
- iOS app that uses USB https://mologie.github.io/nxboot/
- Getting unique ID to confirm purchase https://stackoverflow.com/a/44649908/3393964
- "With Apple Business Manager [...] you can privately and securely distribute to specific partners, clients, franchisees. And you can also distribute proprietary apps to your internal employees." https://developer.apple.com/custom-apps/
- How to install app with private frameworks if ABM doesn't work https://getutm.app/install/
