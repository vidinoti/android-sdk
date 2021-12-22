# Vidinoti Android SDK

[![Release](https://jitpack.io/v/vidinoti/android-sdk.svg)](https://jitpack.io/#vidinoti/android-sdk)

## Getting started

In your project's `build.gradle` file, add the following

```gradle
allprojects {
    repositories {
        maven { url "https://jitpack.io" }
    }
}
```

And add the dependency in your app's `build.gradle` file:

```gradle
implementation 'com.github.vidinoti:android-sdk:<latest-release>'
```

## How to release a new version

1. Replace the `vdarsdk-release.aar` file
2. Update the version number in `jitpack.yml`
3. Update the version number in `pom.xml` and any dependency if needed
4. Commit, push
5. Create a new release in GitHub

### Create a GitHub release with GitHub CLI

``` sh
gh release create <tag> --notes "<release notes>"
# For instance
gh release create 7.3.3 --notes "Vidinoti SDK 7.3.3"
```
