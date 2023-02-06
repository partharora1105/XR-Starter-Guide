

# XR-Templates

This repository contains a starter template for creating XR applications using Unity and OpenXR. This project comes with all the necessary settings and plugins required for an XR Project. It also has premade prefabs that can be used along with locatomotion, Input Manager, and XR Ray Interactor added. OpenXR is an open standard for XR platform interoperability, allowing developers to create a single application that works across multiple XR systems. However, we are using Meta Quest 2 as hardware for testing in this template. 

Last Updated: Feb 6, 2022 

Unity Version : 2021.3.1f1

## Table of Contents
- [Getting Started](#getting-started)
  - [Software Setup](#software-setup)
  - [Hardware Setup](#hardware-setup)
  - [Build App](#build-app)
- [Meta Quest Mixed Reality Template](#meta-quest-mixed-reality-template)
- [Recommended XR Tutorials](#recommended-xr-tutorials)
  - [Basics](#basics)
  - [Additional](#additional)
- [Contributing](#contributing)
- [License](#license)

## Virtual Reality (VR)
Virtual Reality (VR) is a computer-generated simulation of a three-dimensional environment that can be interacted with in a seemingly real or physical way through the use of special electronic equipment, such as a headset.
### Current Template
The current starter template uses Unity and OpenXR. It comes with all the necessary settings and plugins installed and configured for the project. It also has premade prefabs that can be used along with locatomotion, Input Manager, and XR Ray Interactor added. OpenXR is an open standard for XR platform interoperability, allowing developers to create a single application that works across multiple XR systems. 

### Choice of Hardware
All projects in this repository are build for devices with the largest consumer base and this template is build for Meta Quest 2 headset and can be used for any Meta headset released after it.

### Getting Started
Using the following steps, you can set up the project on your machine and run it on your headset.
#### Software Setup

- Clone/Download the Project Repository.
- Install Unity Hub for your machine from official [Unity Site](https://unity.com/download).
- Choose Unity Version - 2021.3.1f1 and add “Android Build Support” (You can skip this step as well and do it in next to next step)
- Now, click on open under projects and navigate to the downloaded project repository. Open “OpenXR_Oculus” directory under VR.
  Unity might prompt you by saying that you do not have the correct version of Unity. Make sure you download the required version with  “Android Build Support”.
- Now once you are in Unity, from the top bar, navigate to File> Build Settings > Android
- Make sure, under “Scenes in Build”, “Scene/main” is selected,  and click on Switch Platform.
- That’s it, now we need to prepare our headset to run the project.

#### Hardware Setup

- Follow the instructions on [Oculus Device Setup Page](https://developer.oculus.com/documentation/native/android/mobile-device-setup/) to put your device in Developer Mode

#### Build App

- Now go back to Unity and under Android Build Settings, click “Refresh” and make sure you can discover your headset in the drop down. If you can’t see it, please complete the previous step.
  Select you headset and click “Build and Run”

## Augmented Reality (AR)
Augmented Reality (AR) is a technology that superimposes digital information onto the real world, often through the use of a camera and display, such as a smartphone or tablet screen.
### Current Template
This repository has templates for both android and IOS devices. The templates just have a rotating cube. They are built on AR Foundation and  use ARCore an ARKit respectively for Android and IOS. These are most popular plugins for building AR apps for smartphones. However you can also build them natively, for example, for IOS you can also use SwiftUI and RealityKit

### Choice of Hardware
All projects in this repository are build for devices with the largest consumer base and this template is build for Android and IOS smartphone which still dominate the AR world. 

### Android 
Make Sure you Android smartphone has USB Debugging enabled. You can refer to [Android Documentation](https://developer.android.com/studio/debug/dev-options) for more info.
#### Getting Started
- Clone/Download the Project Repository.
- Install Unity Hub for your machine from official [Unity Site](https://unity.com/download).
- Choose Unity Version - 2021.3.1f1 and add “Android Build Support” (You can skip this step as well and do it in next to next step)
- Now, click on open under projects and navigate to the downloaded project repository. Open “Android” directory under AR.
  Unity might prompt you by saying that you do not have the correct version of Unity. Make sure you download the required version with  “Android Build Support”.
- Now once you are in Unity, from the top bar, navigate to File> Build Settings > Android
- Make sure, under “Scenes in Build”, “Scene/main” is selected,  and click on Switch Platform.
- Connect you android device and click “Refresh” and make sure you can discover your phone in the drop down.
- Select you phone and click “Build and Run”.

### IOS
Make Sure you Android smartphone has USB Debugging enabled. You can refer to [Android Documentation](https://developer.android.com/studio/debug/dev-options) for more info.
#### Getting Started
- Clone/Download the Project Repository.
- Install Unity Hub for your machine from official [Unity Site](https://unity.com/download).
- You will also need to install XCode for IOS app, which you can install [here](https://apps.apple.com/us/app/xcode/id497799835?mt=12) with [Command Line Tools](https://forum.unity.com/threads/unable-to-create-project-using-arkit-and-ar-foundation-on-apple-silicon-m1-macbook.1302240/) and add them to path (Very Important).
- Choose Unity Version - 2021.3.1f1 and add “IOS Build Support” (You can skip this step as well and do it in next to next step)
- Now, click on open under projects and navigate to the downloaded project repository. Open “Android” directory under AR.
  Unity might prompt you by saying that you do not have the correct version of Unity. Make sure you download the required version with  “IOS Build Support”.
- Now once you are in Unity, from the top bar, navigate to File> Build Settings > IOS
- Make sure, under “Scenes in Build”, “Scene/Main” is selected,  and click on Switch Platform.
- Open XCode on your device.
- Connect you IOS Device and make sure it's unlocked.
- Click “Build and Run”.


## Mixed Reality (MR)
Mixed Reality (MR) is a hybrid of virtual reality (VR) and augmented reality (AR) in which physical and digital objects coexist and interact in a real-time environment. MR combines the real and virtual worlds to produce new environments and visualizations where physical and digital objects can co-exist and interact.
### Current Template
The template in build for Passthrough Mixed Reality for Meta Quest Pro.  This contains main scene has been configured to use Passthrough and Hand Tracking. You can also easily add other features from Meta Presence Platform to this Project. This project is fully configured to be published on Quest App Lab.

### Choice of Hardware
All projects in this repository are build for devices with the largest consumer base and this template is build for Meta Quest Pro (or Quest 2) headset and can be used for any Meta headset released after it.

### Getting Started
Using the following steps, you can set up the project on your machine and run it on your headset.
#### Software Setup

- Clone/Download the Project Repository.
- Install Unity Hub for your machine from official [Unity Site](https://unity.com/download).
- Choose Unity Version - 2021.3.1f1 and add “Android Build Support” (You can skip this step as well and do it in next to next step)
- Now, click on open under projects and navigate to the downloaded project repository. Open “MetaPassthrough” directory under MR.
  Unity might prompt you by saying that you do not have the correct version of Unity. Make sure you download the required version with  “Android Build Support”.
- Now once you are in Unity, from the top bar, navigate to File> Build Settings > Android
- Make sure, under “Scenes in Build”, “Scene/main” is selected,  and click on Switch Platform.
- Click player settings, navigate to Publishing settings and under keystore enter temporary code 123456 for keystore and allias. You can change this as well.
- That’s it, now we need to prepare our headset to run the project.

#### Hardware Setup

- Follow the instructions on [Oculus Device Setup Page](https://developer.oculus.com/documentation/native/android/mobile-device-setup/) to put your device in Developer Mode

#### Build App

- Now go back to Unity and under Android Build Settings, click “Refresh” and make sure you can discover your headset in the drop down. If you can’t see it, please complete the previous step.
  Select you headset and click “Build and Run”



## Recommended XR Tutorials
### Basics
These are some recommended XR Tutorials which we suggest going through in order if you are not sure what you want to do.
* Programming
  * C# (Similar to Java and not needed if you know Java) : [W3Schools](https://www.w3schools.com/cs/index.php)
* Unity
  * 3D Game Development : [Brackeys Youtube Playlist](https://youtu.be/IlKaB1etrik)
* AR
  * AR Enviornment Setup : [Unity Getting Started with AR](https://learn.unity.com/project/get-started-with-ar)
  * AR Application : [Unity AR Marker & Planes](https://learn.unity.com/course/create-with-ar-markers-and-planes?uv=2021.3)
* VR
  * VR Projects :[Unity Create with VR](https://learn.unity.com/course/create-with-vr)

### Additional
* Blender : [Blender Guru Youtube](https://youtu.be/nIoXOplUvAw)
* Multiplayer : [Photon](https://doc.photonengine.com/pun/v2/demos-and-tutorials/pun-basics-tutorial/intro#)
* Input System : [VR With Andrew Youtube](https://www.youtube.com/watch?v=jOn0YWoNFVY)
* Animations : [iHeartGameDev Youtube](https://youtu.be/-FhvQDqmgmU)
* Avatars : [Ready Player Me](https://docs.readyplayer.me/ready-player-me/integration-guides/unity-sdk)
* Meta Exclusive : [Passthrough](https://developer.oculus.com/documentation/unity/unity-passthrough/) , [Hand Tracking](https://developer.oculus.com/documentation/unity/unity-handtracking/) ,  [Hand Gestures](https://www.youtube.com/watch?v=lBzwUKQ3tbw)
* 360 Video System : [Valem Youtube](https://www.youtube.com/watch?v=RxlQnPcOoYc)
* Any Other General XR Tutorials : [Dilmerv Youtube Channel](https://www.youtube.com/@dilmerv)

## Assets
All projects might have some assets imported with them. These are free to use subject to the licenses attached in the folders. Please abide by the licenses before using specefic assets. Additonaly feel free to import free Assets from [Unity Asset Store](https://assetstore.unity.com/). Tip: When you might add assets, they might have a purple material. This might be because they are using standard material shader, and we are using URP for our projects. You can upgrade the materials using steps [here](https://jordancassady.medium.com/how-to-upgrade-materials-to-urp-in-unity-2021-2-and-above-3f1274656989).

## Version Control
If you are using any Unity project like this and using version control like git, make sure you only add specefic folder to you commit. "Assets", "Packages" and "Project Settings" are the three folders that you must add. Folders like "Library" are extremely heavly and are generated by Unity the first time you open the project. Additonally you might wanna add specefic folders that might have been added externally like "Builds" or "Keystore". If any of the asset file is larger than 100MB, it is also suggested using github [lfs](https://docs.github.com/en/repositories/working-with-files/managing-large-files/installing-git-large-file-storage).

## Contributing
Users are encouraged to suggest changes to the repository, esspecially for such an ever-growing field, and they can do so by suggesting changes to the author using the contact information updated on the profile page.

## License
This repository is protected under the MIT License.

Copyright (c) 2023 XR-Templates

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


