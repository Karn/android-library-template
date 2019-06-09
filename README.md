![](./docs/assets/logo.svg)


## $android-library-name$

[![Kotlin](https://img.shields.io/badge/Kotlin-1.3.11-blue.svg?style=flat-square)](http://kotlinlang.org)
[![Build Status](https://img.shields.io/travis/$username$/$repo$.svg?style=flat-square)](https://travis-ci.org/$username$/$repo$)
[![Codecov](https://img.shields.io/codecov/c/github/$username$/$repo$.svg?style=flat-square)](https://codecov.io/gh/$username$/$repo$)
[![GitHub (pre-)release](https://img.shields.io/github/release/$username$/$repo$/all.svg?style=flat-square)
](./../../releases)

#### GETTING STARTED
$android-library-name$ (pre-)releases are available via JitPack. It is recommended that a specific release version is selected when using the library in production as there may be breaking changes at anytime.

> **Tip:** Test out the canary channel to try out features by using the latest develop snapshot; `develop-SNAPSHOT`.

```Groovy
// Project level build.gradle
// ...
repositories {
    maven { url 'https://jitpack.io' }
}
// ...

// Module level build.gradle
dependencies {
    // Replace version with release version, e.g. 1.0.0-alpha, -SNAPSHOT
    implementation "com.github.$username$:$repo$:[VERSION]"
}
```


#### USAGE
The most basic case is as follows:

```Kotlin

```

#### CONTRIBUTING
There are many ways to [contribute](./.github/CONTRIBUTING.md), you can
- submit bugs,
- help track issues,
- review code changes.
