# Vidinoti Android SDK

## Getting started

In your project's `build.gradle` file, add the following

```
allprojects {
    repositories {
        maven { url "https://jitpack.io" }
    }
}
```

And add the dependency in your app's `build.gradle` file:

```
implementation 'com.github.vidinoti:android-sdk:<latest-release>'
```

## How to release a new version

1. Replace the `vdarsdk-release.aar` file
2. Update the version number in `jitpack.yml`
3. Update the version number in `pom.xml` and any dependency if needed
4. Commit, push and create a new release in GitHub