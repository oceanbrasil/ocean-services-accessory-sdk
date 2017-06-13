# Motion SDK

[![Latest Stable Version](https://img.shields.io/badge/version-2.2.1-green.svg)](http://developer.samsung.com/galaxy/motion)

Motion SDK allows you to collect motion information from the device and use it in your applications. You can collect from the device sensors raw data related to pedometer or activity recognition or the motions associated with answering the phone.

![Motion](http://developer.samsung.com/sd2_images/galaxy/content/SMS_Motion_01_2.jpg)

You can use the Motion SDK to:

  - Detecting call motion
  - Using pedometer data
  - Recognizing activities
  
__Detecting Call Motion__

Motion SDK recognizes the action when the user first watches the device and then subsequently brings the device up to the ear. You can use this motion to answer an incoming call. If the user is reading a message, you can use the motion to call the number from which the message was sent.

![Motion](http://developer.samsung.com/sd2_images/galaxy/content/SMS_Motion_02.jpg)

## Download

Add into gradle project level

``` Gradle
allprojects {
  repositories {
    ...
    maven { url "https://jitpack.io" }
  }
}
```

Add into app project level

``` Gradle
dependecies{
    compile 'com.github.oceanbrasil:samsung-services-motion:2.2.1'
}
```

## LICENSE

Copyright © 2010 - 2017 SAMSUNG All rights reserved.

Portions of this page are reproduced from work created and shared by the Android Open Source Project and used according to terms described in the [Creative Commons 2.5](https://creativecommons.org/licenses/by/2.5/) Attribution License.
