# AcademyXI Cardboard Demo - Android & iOS
> a basic unity project for building [Google Cardboard] applications for [Android] and [iOS].

## Overview
<!-- TODO: Write up overview of the project and what it contains. -->

## Pre-Requisites
There are a few things you will need installed on your computer to make this work.
* For [Android] and [iOS] you will need [Unity] installed. To get [Unity] go to their [download page][Unity Personal Download] and download the installer.
	* When installing [Unity] make sure to select `Android Build Support` and `iOS Build Support` when you are asked to choose the components you want installed.
	* If you already have installed [Unity] you can get the `iOS Build Support` component from [here](http://download.unity3d.com/download_unity/649f48bbbf0f/MacEditorTargetInstaller/UnitySetup-iOS-Support-for-Editor-5.4.1f1.pkg) and the `Android Build Support` component from [here](http://download.unity3d.com/download_unity/649f48bbbf0f/MacEditorTargetInstaller/UnitySetup-Android-Support-for-Editor-5.4.1f1.pkg).
* You will also need the [Google VR SDK for Unity]. The simplest way to get this is to just download the zip file directly from [here](https://github.com/googlevr/gvr-unity-sdk/archive/master.zip), the other option is to clone the repository using [git] => `git clone https://github.com/googlevr/gvr-unity-sdk.git`

_NOTE: The [Google VR SDK for Unity] is bundled into this demo project. So it is not necessary to complete this step, but I am including it here for future reference._

### Pre-Requisites for [Android]
1. Install [Java](https://www.java.com/en/download/mac_download.jsp)
2. Install the Android SDK, the simplest way to get this is to install [Android Studio].
3. After installing Android Studio, you will need to update the Android SDK Tools and install an Android platform. You will need to install/update the following:
  * Android SDK Build Tools
  * Android SDK Platform-tools
  * Android SDK Tools
  * Android SDK Platform
    * ARM System Images

  For a more detailed explanation on what is needed go [here](https://developer.android.com/studio/intro/update.html#sdk-manager).

### Pre-Requisites for [iOS]
> _NOTE: The only way to build an application for [iOS] is on an Apple Computer._

* To get your application running on an [iOS] device you will need an AppleID. Any AppleID will work, but it is recommend that you sign up for a free developer account as well.
	* To sign up for an AppleID go to this [page](https://appleid.apple.com/account#!&page=create).
	* Once you have your AppleID, go to the [Apple Developer Centre], click on the `Account` tab at the top of the page, and log in with your AppleID, and follow the steps to create a developer account.
* Download the latest version of [Xcode][Xcode Download] from the AppStore.
* Finally you will need to add your AppleID to Xcode. [Unity] have a good write on how to do this [here](https://docs.unity3d.com/Manual/iphone-accountsetup.html).

## Getting Started
To get started using this project download the latest version from [here][Project Latest]. 

<!-- TODO: Write up the basic getting started guide for this project. -->

## Building your project
There a couple of settings you will need to set, for both [Android] and [iOS].
1. In `PlayerSettings`, click **Resolution and Presentation** to expand that panel. Set the **Default Orientation** to `Auto Rotation`, and then uncheck all of the **Allowed Orientations** for `Auto Rotation` except for `Landscape Left`.
2. Click **Other Settings** to expand that panel and find the `Bundle Identifier` field. Enter a valid package name for your application _(such as com.mycompany.cardboarddemo)_ that follows the naming rules for Java packages and/or .Net namespaces. Typically this is of the form: com.<yourcompany>.<appname>

### Building for [Android]
<!-- TODO: write up steps on how to build a project for Android. -->
1. You will need to enable developer mode on your [Android] device.
	* Go to `Settings` > `About Phone`, and then scroll down to `Build number`.
	You need to tap `Build number` seven (7) times. After that developer mode will be enabled.
2. You also need to enable `USB debugging`.
	* Go to the new `Developer options` section, and scroll down until you see the `USB debugging` toggle,
	switch this to on.
3. Plug in your [Android] device.
4. Click build and run.

### Building for [iOS]
<!-- TODO: write up steps on how to build a project for iOS. -->
1. Make sure [Xcode] is closed. _(idk why, but I had a few troubles if xcode was open)_
2. Plug in [iOS] device.
3. Click build and run

## Next Steps
<!-- TODO: write up next steps section, with links to some good resources etc. -->

## Links and resources
* [Google VR SDK for Unity]
* [Google Cardboard]
* [Android Studio]
* [Xcode]
* [Unity]

## License
This project is licensed under [MIT](LICENSE).

[Android]: https://www.android.com/ "Android"
[iOS]: http://www.apple.com/ios/ "iOS"

[Google Cardboard]: https://vr.google.com/cardboard/ "Google Cardboard"
[Google VR SDK for Unity]: https://developers.google.com/vr/unity/download "Google VR SDK for Unity"

[Android Studio]: https://developer.android.com/studio/index.html#mac-bundle "Android Studio for macOS"
[Xcode]: https://developer.apple.com/xcode/
[Xcode Download]: https://itunes.apple.com/au/app/xcode/id497799835?mt=12 "Xcode Download"

[Apple Developer Centre]: https://developer.apple.com/ "Apple Developer Centre"

[Unity]: https://unity3d.com/ "Unity"
[Unity Personal Download]: https://store.unity.com/download?ref=personal "Download Unity Personal"

[git]: https://git-scm.com/ "git"

[Project Latest]: https://github.com/benhinchley/AcademyXI_CardboardDemo_Android/archive/master.zip
