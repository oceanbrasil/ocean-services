# Samsung Services

[![Latest Stable Version](https://img.shields.io/badge/version-1.0.0-green.svg)](http://developer.samsung.com/galaxy)

With Samsung Services, your app can take advantage of the latest, Samsung-powered features such as Connect Smart Devices, Edge(Look), Camera, Gestures, use the Pen and more, with automatic updates. This makes it faster for your users to receive updates and easier for you to integrate the newest features that Samsung has to offer.

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
    compile 'com.github.oceanbrasil:samsung-services:1.0.0'
}
```

Individual APIs and corresponding __build.gradle__ descriptions.

| Samsung Service API | Description in build.gradle  | 
|:-----:|---|
| [Acessory](https://github.com/oceanbrasil/samsung-services-accessory-sdk) | com.github.oceanbrasil:samsung-services-accesory-sdk:2.5.1  |
| [Camera](https://github.com/oceanbrasil/samsung-services-camera-sdk)      | com.github.oceanbrasil:samsung-services-camera-sdk:1.2.2    |
| [Edge(look)](https://github.com/oceanbrasil/samsung-services-edge-look)   | com.github.oceanbrasil:samsung-services-edge-look:1.4.0     |
| [Motion](https://github.com/oceanbrasil/samsung-services-motion)          | com.github.oceanbrasil:samsung-services-motion:2.2.1        |
| [MultiWindow](https://github.com/oceanbrasil/samsung-services-multiwindow)| com.github.oceanbrasil:samsung-services-multiwindow:1.3.2   |


## How it works

Samsung services gives you a high level interface from all SDK available into oficial [Samsung SDK](http://developer.samsung.com/galaxy/sdks) for Galaxy. You can select a specific SDK if you would.

## The benefits for your app

Samsung services gives you the freedom to use the newest APIs for popular Samsung SDK without worrying about device support. This makes it easy for you to focus on what's important: your users' experience.

## LICENSE

Copyright © 2010 - 2017 SAMSUNG All rights reserved.

Portions of this page are reproduced from work created and shared by the Android Open Source Project and used according to terms described in the [Creative Commons 2.5](https://creativecommons.org/licenses/by/2.5/) Attribution License.
