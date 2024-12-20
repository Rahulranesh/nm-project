#  Travel APP (Kotlin Multiplatform Mobile)

Travel App is a simple **mobile application** built to demonstrate the use of
_**Kotlin Multiplatform Mobile**_ for developing _Android and iOS_ applications
using **Jetpack Compose** 🚀.

#)


  





## Built with 

- [Kotlin](kotlinlang.org): Programming language
- [Kotlin Multiplatform](https://kotlinlang.org/docs/multiplatform.html): For building multi-platform applications in the single codebase.
- [Jetpack/JetBrains Compose Multiplatform](https://www.jetbrains.com/lp/compose-multiplatform/): For a shared UI between multi-platforms i.e. Android and iOS in this project.
- [Moko Resources](https://github.com/icerockdev/moko-resources): This is a Kotlin MultiPlatform library (and Gradle plugin) that provides access to the resources on macOS, iOS, Android the JVM and JS/Browser with the support of the default system localization.
-  [Compose Image Loader](https://github.com/qdsfdhvh/compose-imageloader): Compose Image library for Kotlin Multiplatform.


## Project structure 

This Compose Multiplatform project includes three modules:

### [`composeApp`](/composeApp)
This is a Kotlin module that contains the common UI/logic for both Android and iOS applications, the code you share between platforms.
This shared module is also where you write your Compose Multiplatform code. In `composeApp/src/commonMain/kotlin/App.kt`, you can find the shared root `@Composable` function for your app.
It uses Gradle as the build system. You can add dependencies and change settings in `composeApp/build.gradle.kts`. The shared module builds into an Android library and an iOS framework.

### [`iosApp`](/iosApp)
This is an Xcode project that builds into an iOS application. It depends on and uses the shared module as a CocoaPods dependency.


## Setting up project 👨🏻‍💻

- Refer to the ***"Setting up environment"*** section of [this repository](https://github.com/JetBrains/compose-multiplatform-ios-android-template/main/README.md) 
for knowing the setup guidelines
- After validating requirements as per the above guide, clone this repository.
- Open this project in Android Studio Electric Eel or newer version.
- Build project 🔨 and see if everything is working fine.
- Run App
  - Select "androidApp" as run configuration and you'll be able to run the Android app.
  - Select "iosApp" as run configuration and you'll be able to run the iOS app _(XCode can also be used to run the app)_.
  - Desktop
    <img width="968" alt="Screenshot 2024-07-24 at 1 29 16 PM" src="https://github.com/user-attachments/assets/69bc6a8d-f169-402d-ac73-05c3af821f26">
    <img width="353" alt="Screenshot 2024-07-24 at 1 29 49 PM" src="https://github.com/user-attachments/assets/e423e531-ab38-4a79-b716-f02fd40b2660">



Thank you!
