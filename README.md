

# XR-Templates

This repository contains a starter template for creating XR applications using Unity and OpenXR. This project comes with all the necessary settings and plugins required for an XR Project. It also has premade prefabs that can be used along with locatomotion, Input Manager, and XR Ray Interactor added. OpenXR is an open standard for XR platform interoperability, allowing developers to create a single application that works across multiple XR systems. However, we are using Meta Quest 2 as hardware for testing in this template. 

Last Updated: Feb 6, 2022

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

## Getting Started

Using the following steps, you can set up the project on your machine and run it on an XR Device. For this particular project, we'll be deploying it on a Meta Quest 2.

### Software Setup

- Clone/Download the Project Repository.
- Install Unity Hub for your machine from official [Unity Site](https://unity.com/download).
- Choose Unity Version - 2021.3.1f1 and add “Android Build Support” (You can skip this step as well and do it in next to next step)
- Now, click on open under projects and navigate to the downloaded project repository. Open “OpenXR_Oculus” directory.
  Unity might prompt you by saying that you do not have the correct version of Unity. Make sure you download the required version with  “Android Build Support”.
- Now once you are in Unity, from the top bar, navigate to File> Build Settings > Android
- Make sure, under “Scenes in Build”, “Scene/main” is selected,  and click on Switch Platform.
- That’s it, now we need to prepare our headset to run the project.

### Hardware Setup

- Follow the instructions on [Oculus Device Setup Page](https://developer.oculus.com/documentation/native/android/mobile-device-setup/) to put your device in Developer Mode

### Build App

- Now go back to Unity and under Android Build Settings, click “Refresh” and make sure you can discover your headset in the drop down. If you can’t see it, please complete the previous step.
  Select you headset and click “Build and Run”

## Meta Quest Mixed Reality Template

You can also open Oculus_MixedReality in this repository through Unity Hub. This contains main scene has been configured to use Passthrough and Hand Tracking. You can also easily add other features from Meta Presence Platform to this Project. This project is fully configured to be published on Quest App Lab.

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
* Input System : [VR With Andrew Youtube](https://www.youtube.com/watch?v=jOn0YWoNFVY)
* Animations : [iHeartGameDev Youtube](https://youtu.be/-FhvQDqmgmU)
* Avatars : [Ready Player Me](https://docs.readyplayer.me/ready-player-me/integration-guides/unity-sdk)
* Meta Exclusive : [Passthrough](https://developer.oculus.com/documentation/unity/unity-passthrough/) , [Hand Tracking](https://developer.oculus.com/documentation/unity/unity-handtracking/) ,  [Hand Gestures](https://www.youtube.com/watch?v=lBzwUKQ3tbw)
* 360 Video System : [Valem Youtube](https://www.youtube.com/watch?v=RxlQnPcOoYc)
* Any Other General XR Tutorials : [Dilmerv Youtube Channel](https://www.youtube.com/@dilmerv)

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


