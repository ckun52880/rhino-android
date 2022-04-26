[![Travis](https://img.shields.io/travis/APISENSE/rhino-android.svg)](https://travis-ci.org/APISENSE/rhino-android)
[![Codecov](https://img.shields.io/codecov/c/github/APISENSE/rhino-android.svg)](https://codecov.io/gh/APISENSE/rhino-android)


# Rhino script engine

This project aims to package a minimal Rhino script engine for Android. 

The script engine source code is imported from openjdk implementation, version _7u40-b43_.

## Installation

Add the following repository and dependency to your `build.gradle`:

```
dependencies {
    implementation 'com.github.gedoor:rhino-android:1.8'
}
```

## Usage

You can now call the Rhino script engine by using the jsr223, i.e.:

```
ScriptEngine engine = new ScriptEngineManager().getEngineByName("rhino");
```
