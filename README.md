# Accessory SDK

[![Latest Stable Version](https://img.shields.io/badge/version-2.5.1-green.svg)](http://developer.samsung.com/galaxy/accessory)

> __Note:__ Samsung Accessory SDK 2.3.0 (and above) is required for devices on Android 6.0 (Marshmallow).

Accessory SDK allows you to connect accessory devices to Samsung smart devices. With Accessory SDK, you can define a new service between the accessory and smart device, enabling you to use the various smart device functions from the accessory device. The service is compatible with various connectivity environments, which makes accessory development efficient and convenient.

Accessory SDK adds new functions to the service as Samsung smart devices improve. Future updates will enable the accessory and the smart device to exchange more information and support more interworking.


![Diagrma](http://developer.samsung.com/sd2_images/galaxy/content/SMS_Accessory_01.jpg)

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
    compile 'com.github.oceanbrasil:samsung-services-accesory-sdk:2.5.1'
}
```

## LICENSE

Copyright © 2010 - 2017 SAMSUNG All rights reserved.

Portions of this page are reproduced from work created and shared by the Android Open Source Project and used according to terms described in the [Creative Commons 2.5](https://creativecommons.org/licenses/by/2.5/) Attribution License.
