# Awesome iBeacon Tech Resources

A curated list of awesome iBeacon software, libraries and use cases. Inspired by [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness).

---

## Official iBeacon Resources

* [Official iBeacon Portal - developer.apple.com/ibeacon](https://developer.apple.com/ibeacon)
* [Apple Getting Started with iBeacon Guide](https://developer.apple.com/ibeacon/Getting-Started-with-iBeacon.pdf)
* [iOS: Understanding iBeacon device compatibility)](http://support.apple.com/kb/HT6048)
* [iOS 7: Understanding Location Services](http://support.apple.com/kb/HT5594)
* [Apple AirLocate Sample Code](https://developer.apple.com/library/ios/samplecode/AirLocate/Introduction/Intro.html) ([iOS8 fix](http://stackoverflow.com/questions/26079530/apple-airlocation-demo-app-ranging-not-shows-beacons))
* [Location and Maps Programming Guide](https://developer.apple.com/library/ios/documentation/userexperience/conceptual/LocationAwarenessPG/LocationAwarenessPG.pdf)


---

## iBeacon Ecosystem

* [The Open and Interoperable Proximity Beacon Specification](http://altbeacon.org/)
* [Open iBeacon Credentials](http://blog.awwapps.com/blog/2014/05/29/open-ibeacon-credentials/)  [on Github](https://github.com/AwwApps/Open-Beacon-Credentials)
* [Policies about beacon IDs](http://blog.awwapps.com/blog/2014/05/20/manual-ibeacon-entry-to-be-removed/)
* [LibreBeacon - open implementation of iBeacon](http://www.librebeacon.org/)


---

## iBeacon Outlook

* [Wired: 4 Reasons Why Apple’s iBeacon Is About to Disrupt Interaction Design](http://www.wired.com/2013/12/4-use-cases-for-ibeacon-the-most-exciting-tech-you-havent-heard-of/)


---

## iBeacon Basics

* [Building Applications with iBeacon](http://shop.oreilly.com/product/0636920033813.do)
* [Cisco iBeacon FAQ](http://www.cisco.com/c/dam/en/us/solutions/collateral/enterprise-networks/connected-mobile-experiences/ibeacon_faq.pdf)
* [5 Minute Overview - What is iBeacon? by ThoughtWorks](http://www.thoughtworks.com/insights/blog/what-is-ibeacon-in-5-minutes)
* [A Semi-Technical Lowdown on Working with iBeacons](http://www.thoughtworks.com/insights/blog/semi-technical-lowdown-working-ibeacons)
* [CapTech Webinar: iBeacon Demystified](https://www.youtube.com/watch?v=0IGeQqEGhx4)
* [5 fundamental misconceptions about Beacon technology by RadiusNetworks](http://developer.radiusnetworks.com/2014/01/10/ibeacon-misconceptions.html)
* [Ask a Dev: What Are the Limitations of Beacons?](http://mashable.com/2014/05/09/beacons-limitations/)
* [What's the Difference Between Beacons and Geofencing?](http://mashable.com/2014/02/24/beacons-geofencing-location/)
* [Guide to iBeacon Hardware by beekn.net](http://beekn.net/guide-to-ibeacons/)
* [Developing an iBeacon App by beekn.net](http://beekn.net/developing-ibeacon-app/)

---

## Practical Advice

* [Brooklyn Museum - Positioning Visitors with iBeacons](http://www.brooklynmuseum.org/community/blogosphere/2014/10/14/positioning-visitors-with-ibeacons/)

---

## iOS


### Tools

* [Generic iBeacon Management and Utilities by KinveyLabs](https://github.com/KinveyLabs/KCSIBeacon/)
* [Generic SDK & Demo App by BEACONinside](https://github.com/beaconinside/BEACONinside-SDK-iOS)
* [Replicates detecting and broadcasting iBeacons in the background](https://github.com/Instrument/Vicinity)


### Beacon Scanner

* [Locate Beacon by RadiusNetworks](https://itunes.apple.com/us/app/locate-for-ibeacon/id738709014?mt=8)
* [Locate by Radius Networks - Virtual iBeacon](https://itunes.apple.com/us/app/locate-beacon/id738709014?mt=8)


### Swift

* [PubNub.com - Two-Way iBeacon Communication with Swift Programming Language](http://www.pubnub.com/blog/smart-ibeacon-communication-in-the-swift-programming-language/)

### Open Source

* [Roverlabs - Beacon Platform](https://github.com/RoverPlatform/rover-ios)
* [PunchClock - An in/out tracking app for iOS 7+ that uses iBeacon and Geofencing.](https://github.com/panicinc/PunchClock)

### Stackoverflow Q&A

* [iBeacon detection time in background](http://stackoverflow.com/questions/25495804/ibeacon-detection-time-in-background-home-automation-use-case/25496669#25496669)
* [iBeacon region monitoring AND proximity for >20 beacons?](http://stackoverflow.com/questions/25387660/ibeacon-region-monitoring-and-proximity-for-20-beacons)
* [How to make iBeacon foreground ranging for CLProximityImmediate faster in iOS?](http://stackoverflow.com/questions/23991733/how-to-make-ibeacon-foreground-ranging-for-clproximityimmediate-faster-in-ios/23992584#23992584)
* [Can we start iBeacon transmitter in background?](http://stackoverflow.com/questions/24164523/can-we-start-ibeacon-transmitter-in-background/24165073#24165073)
* [How does iBeacon wake up our app?](http://stackoverflow.com/questions/24590534/how-does-ibeacon-wake-up-our-app-for-how-long-and-how-to-extend-that-time/24590886#24590886)
* [Use Core Bluetooth instead of iBeacon - Any Downsides?](http://stackoverflow.com/questions/24267421/use-core-bluetooth-instead-of-ibeacon-any-downsides/24268389#24268389)

---

## Android

### Beacon Development

* [Android Lolipop Bluetooth Low Energy Enhancements.](https://developer.android.com/about/versions/android-5.0.html) Support OS-level scan filter & peripheral mode.
* [Android beacon library based on AltBeacon.](https://github.com/AltBeacon/android-beacon-library) Use a custom beacon parser for iBeacon device compatibility.
* [BeaconKeeper - the simple library for locating iBeacons in background](https://github.com/m039/beacon-keeper)

* [Android iBeacon Patterns](http://blog.surecase.eu/androidbeaconpatterns/)
* [Android & BLE](https://developer.android.com/guide/topics/connectivity/bluetooth-le.html)
* [DevBytes: Bluetooth Low Energy API in Android 4.3](https://www.youtube.com/watch?v=vUbFB1Qypg8)
* [BLE SDK for Android](https://github.com/RedBearLab/Android)


### Beacon Scanner Apps

* [Android app that scans for BLE Beacons/iBeacons and logs the results to a file](https://github.com/justinodwyer/Beacon-Scanner-and-Logger)
* [iBeacon Detector](https://play.google.com/store/apps/details?id=youten.redo.ble.ibeacondetector&hl=de)
* [Bluetooth 4.0 Scanner](https://play.google.com/store/apps/details?id=com.bluemotionlabs.bluescan&hl=de)
* [Beacon Keeper](https://play.google.com/store/apps/details?id=com.m039.beacon.keeper.app)

### Stackoverflow Q&A

* [BLE Distancing](http://stackoverflow.com/questions/20416218/understanding-ibeacon-distancing/20434019#20434019)


---

## Cordova, Phonegap, Xamarin

* [Cordova iBeacon Plugin](https://github.com/petermetz/cordova-plugin-ibeacon)
* [Using iBeacon with Xamarin.iOS and Xamarin.Android](http://de.slideshare.net/glennthomasstephens/ibeacon-support)

---

## MAC OSX

* [iBeacon Scanner - Scan for nearby iBeacons regardless of their UUID](https://github.com/liamnichols/iBeaconScanner)
* [MacBeacon by RadiusNetworks (9,99 USD)](http://www.radiusnetworks.com/ibeacon/macbeacon/)
* [Beacon OSX - Mavericks as an iBeacon](https://github.com/mttrb/BeaconOSX)


---

## Node.js

* [A node.js BLE (Bluetooth low energy) central module](https://github.com/sandeepmistry/noble)
* [A node.js module for implementing BLE (Bluetooth low energy) peripherals](https://github.com/sandeepmistry/bleno)

---

## Bluetooth Low Energy

* [Official Bluetooth Smart Portal](http://www.bluetooth.com/Pages/Bluetooth-Smart.aspx)
* [LightBlue can test all of your devices that use Bluetooth 4.0 Low Energy (Mac OSX))](https://itunes.apple.com/de/app/lightblue/id639944780?mt=12)
* [LightBlue for iOS](https://itunes.apple.com/us/app/lightblue-bluetooth-low-energy/id557428110?mt=8)
* [BlueSpeed for iOS by Punch Through](https://itunes.apple.com/us/app/bluespeed/id579118786?mt=8)

---

## Beacon Proximity Applications

* [The future of call routing with NewAer technology](http://www2.alcatel-lucent.com/techzine/future-call-routing-newaer-technology/)
* [Stack’s Smart Sensor-Packed Light Bulbs Run Autonomously, No App Interactions Required](http://techcrunch.com/2014/09/09/stacks-smart-sensor-packed-light-bulbs-run-autonomously-no-app-interactions-required/)



---

## Blogs & Presentations

* [beekn.net - Beacons, brands, and culture on the Internet of Things](http://beekn.net)
* [Radius Networks Dev Blog](http://developer.radiusnetworks.com/blog/)
* [The Talking Llama. Beacons, Mobile, Web Apps, Tech.](http://www.thetalkingllama.com/)
* [LOCPlace - LBMA Slides](http://de.slideshare.net/LOCplace/)


---

## Hacks & Cool Apps

* [Google Glass & Beacons](https://github.com/tmwagency/Glasstimote)
* [LaunchHere for iOS - iBeacon based app shortcuts](http://launchhere.awwapps.com/)

---

## Beacon Developer Kits & BLE Chips

* [Dialog Semiconductor Beacon Reference Design](http://support.dialog-semiconductor.com/ref-designs#beacon)
* [Nordic Semiconductor nRF51822 Bluetooth Smart Beacon Kit](https://www.nordicsemi.com/eng/Products/Bluetooth-R-low-energy/nRF51822-Bluetooth-Smart-Beacon-Kit)
* [Texas Instruments - BLE Portal](http://ti.com/ble)
* [Texas Instruments - SensorTag DeveloperKit](http://makezine.com/2014/04/16/the-ti-sensortag-now-with-added-ibeacon/)
* [TI SensorTag Android Sources](http://git.ti.com/sensortag-android)
* [TI Mini Bluetooth® Low Energy Broadcaster](http://www.ti.com/tool/TIDC-MINI-BLUETOOTH-LOW-ENERGY-BROADCASTER)
* [Broadcom - WICED™ Sense Development Kit](http://www.broadcom.com/products/wiced/sense/)
* [Dialog Semiconductor](http://www.dialog-semiconductor.com/products/bluetooth-smart)
* [CSR](https://wiki.csr.com/wiki/Main_Page#Bluetooth_Smart) & [CSR Mesh](https://wiki.csr.com/wiki/CSRmesh)
* [EMMicroelectronics](http://www.emmicroelectronic.com/products/wireless-rf/beacons/embc01)

Beacons can come in a variety of form factors. Pure beacons, BLE Arduinos, Raspberry Pi, iOS or Mac software... See [RedBear Labs](http://redbearlab.com/) for a good overview.


---

## Bluetooth Smart & BLE Tools

* [Bluetooth Smart Go To Market Toolkit: Four Steps to Success](https://www.bluetooth.org/en-us/bluetooth-brand/go-to-market-toolkit)
* [Nordic BLE nRF Sniffer](https://www.nordicsemi.com/eng/Products/Bluetooth-Smart-Bluetooth-low-energy/nRF-Sniffer)



---

# Housekeeping

---

## Contribute

* **To add to the list:** Submit a pull request
* **To remove from the list:** Open an issue

Please open an issue if you find anything that could be improved or have suggestions for making the list a more valuable resource.

---

## License

[![Creative Commons License](http://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)

This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).

iBeacon is a trademark of Apple Inc.
