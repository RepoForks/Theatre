<img alt="Icon" src="presentation/src/main/res/mipmap-xxhdpi/ic_launcher.png?raw=true" align="left" hspace="1" vspace="1">

<a alt='Buy Me a Coffee at ko-fi.com' href='https://ko-fi.com/T6T05M4O' target='_blank' align='right'><img align='right' height='36' style='border:0px;height:36px;' src='https://az743702.vo.msecnd.net/cdn/kofi4.png?v=0' border='0' /></a>
<a alt='Try it on Google Play' href='https://play.google.com/store/apps/details?id=com.andremion.theatre' target='_blank' align='right'><img 
align='right' height='36' style='border:0px;height:36px;' src='https://developer.android.com/images/brand/en_generic_rgb_wo_60.png' border='0' /></a>
# Theatre

A pet project using a simple version of Clean Architecture + MVVM + Reactive Extensions and Android Architecture Components.</br>
All this fetching data from [London Theatre Direct API](https://developer.londontheatredirect.com/).
The main purpose is using the latest practices and libraries.

</br>

[![License Apache 2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg?style=true)](http://www.apache.org/licenses/LICENSE-2.0)
![minSdkVersion 16](https://img.shields.io/badge/minSdkVersion-16-red.svg?style=true)
![compileSdkVersion 27](https://img.shields.io/badge/compileSdkVersion-27-yellow.svg?style=true)

<p align="center">
  <img alt='Sample' src="https://raw.githubusercontent.com/andremion/Theatre/master/art/sample.gif"></br>
  <i>*Data from London Theatre Direct</i>
</p>

## Credentials

Register your account [here](https://iodocs.londontheatredirect.com/member/register) to get your developer key and put it into [gradle.properties](data/gradle.properties) file

## Libraries and tools used in the project

* [RX Java](https://github.com/ReactiveX/RxJava)
A library for composing asynchronous and event-based programs using observable sequences for the Java VM.
* [RX Kotlin](https://github.com/ReactiveX/RxKotlin)
RxJava bindings for Kotlin.
* [RX Android](https://github.com/ReactiveX/RxAndroid)
RxJava bindings for Android.
* [Android KTX](https://github.com/android/android-ktx)
A set of Kotlin extensions for Android app development.

* [Android Support Library](https://developer.android.com/topic/libraries/support-library/index.html)
Provides additional convenience classes and features not available in the standard Framework API for easier development and support across more devices.
* [Data Binding](https://developer.android.com/topic/libraries/data-binding)
Write declarative layouts and minimize the glue code necessary to bind application logic and layouts.

* [ConstraintLayout](https://developer.android.com/training/constraint-layout/index.html)
Allows you to create large and complex layouts with a flat view hierarchy (no nested view groups).
* [RecyclerView](http://developer.android.com/reference/android/support/v7/widget/RecyclerView.html)
A flexible view for providing a limited window into a large data set.
* [Glide](https://github.com/bumptech/glide)
An image loading and caching library for Android focused on smooth scrolling

* [Retrofit](http://square.github.io/retrofit/)
A type-safe HTTP client for Android and Java.
* [OkHttp](http://square.github.io/okhttp/)
An HTTP & HTTP/2 client for Android and Java applications.
* [Moshi](https://github.com/square/moshi)
A modern JSON library for Android and Java.

* [Android Architecture Components](https://developer.android.com/topic/libraries/architecture/index.html)
A collection of libraries that help you design robust, testable, and maintainable apps.
Start with classes for managing your UI component lifecycle and handling data persistence.
* [Dagger](https://google.github.io/dagger/)
A fully static, compile-time dependency injection framework for both Java and Android.

* [Leak Canary](https://github.com/square/leakcanary)
A memory leak detection library for Android and Java.
* [Stetho](http://facebook.github.io/stetho/)
A debug bridge for Android applications.

## TODO

* Add more unit tests.

## Contributing

Contributions are always welcome!

**Issues:**
Fell free to open a new issue. Follow the [ISSUE_TEMPLATE.MD](https://github.com/andremion/Theatre/tree/master/ISSUE_TEMPLATE.md)

Follow the "fork-and-pull" Git workflow.

 1. **Fork** the repo on GitHub
 2. **Clone** the project to your own machine
 3. **Commit** changes to your own branch
 4. **Merge** with current *development* branch
 5. **Push** your work back up to your fork
 7. Submit a **Pull request** your changes can be reviewed (please refere the issue if reported)

**Prevent** code-style related changes. Format the code before commiting.

## License

    Copyright 2018 André Mion

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
