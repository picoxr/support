<p align="center">
  <a href="https://www.picoxr.com/es/"> <img src="https://github.com/PicoSupport/PicoSupport/blob/master/banner.png" width="500" align="center"/> </a>
</p>


# PicoXR SDK Official Repository
Welcome to the official PicoXR DevSupport GitHub repository.
In this repository you will find demo projects created with the Pico SDK, as well as useful information and development resources.

## 💡 Features
The Pico SDK provides access to a set of features that can be used for games and applications development in Unity, Unreal and Android. 

Unity 2019.4 LTS is the earliest Unity version supported by the Pico Unity Integration SDK. If you would like to use more features such as Vulkan, Unity 2020.3 LTS and Unity 2021.3 LTS are recommended.

For Unreal development, UE 4.25, 4.26 and 4.27 are supported.
| SDK Version | Supported platform |
|--|--|
| Pico Unity Integration SDK | Pico Neo 3 Series |
| Pico Unity XR Platform SDK (Legacy) | Pico Neo 3 Series / Pico G2 / Pico G2 4K |

For more SDK updates and upcoming features, please follow our [SDK Roadmap](https://bytedance.feishu.cn/docx/doxcnWWl9pXkctpCXfNpOT9sgTc).

## ⬇️ SDK Downloads

|<img src="https://user-images.githubusercontent.com/46362299/179972791-0f04fdc1-6369-4f34-b288-749f58f5f33f.png" width="256" align="center"/>|<img src="https://user-images.githubusercontent.com/46362299/179974256-a3e68fcd-a594-4a67-b56c-87bbaa1338f3.png" width="256" align="center"/>| <img src="https://user-images.githubusercontent.com/46362299/179974575-bb9cadf2-f90c-4a85-841f-c5b90a6dff4c.png" width="256" align="center"/>| <img src="https://user-images.githubusercontent.com/46362299/179974746-0342839e-809e-4522-9cef-7063a953fc64.png" width="256" align="center"/>|
|:--:|:--:|:--:|:--:|
| [Download Unity XR SDK](https://developer.pico-interactive.com/sdk?deviceId=1&platformId=1&itemId=12) | [Download Unreal XR SDK](https://developer.pico-interactive.com/sdk?deviceId=1&platformId=2&itemId=13)  | [Download OpenXR SDK](https://developer.pico-interactive.com/sdk?deviceId=1&platformId=2&itemId=13)| [Download Native XR SDK](https://developer.pico-interactive.com/sdk?deviceId=1&platformId=3&itemId=16)

### Metrics Tool
The Pico Metrics Tool allows developers to monitor performance of applications running on Pico Devices.
| [Download](https://developer.pico-interactive.com/sdk?deviceId=1&platformId=1&itemId=15) | [Documentation](https://developer.pico-interactive.com/docs/unity/en/13136/241044/) |
|--|--|

### Preview Tool
The Pico Preview Tool enables developers to preview their applications in real time using the Unity/Unreal Editor.
| [Download](https://developer.pico-interactive.com/sdk?deviceId=1&platformId=1&itemId=17) | [Documentation (Unity)](https://developer.pico-interactive.com/docs/unity/en/13136/241045/) |[Documentation (Unreal)](https://developer.pico-interactive.com/docs/unreal/en/13156/preview-tool/)|
|--|--|--|

## 📄 SDK Documentation

|Unity XR SDK|Unreal XR SDK| Native XR SDK|
|--|--|--|
| [Documentation](https://developer.pico-interactive.com/document/unity) | [Documentation](https://developer.pico-interactive.com/document/unreal)  | [Documentation](https://developer.pico-interactive.com/document/native) 
|[API Reference](https://pdocor.pico-interactive.com/reference/unity/xr/2.05/)|[API Reference](https://pdocor.pico-interactive.com/reference/unreal/xr/12832/)|[API Reference](https://pdocor.pico-interactive.com/reference/native/xr/2.0.1/)|

### Enterprise Solutions
With the [Pico Enterprise Solutions](https://developer.pico-interactive.com/document/solution), developers can modify and configure advanced settings in their devices for a better Enterprise experience, such as custom Play Boundary, Kiosk Mode, or custom System Key bindings.
**Note**: The Enterprise Solutions are not compatible with Neo 3 Link devices.

### Legacy Documentation
| [Pico Unity Platform SDK](https://developer.pico-interactive.com/docs/unity/en/13136/unity-platform-sdk-quickstart/) | [Pico Unreal Engine 4 SDK](https://developer.pico-interactive.com/docs/unreal/en/13156/ue4-sdk-quickstart/) |
|--|--|


## 🔧 Pico Unity Integration SDK Demos
| [Overlay Demo][001] | [Get Battery Level][002] | [Go to System Settings][003]|
|---------------------|--------------------------|-----------------------------|
| How to use the Overlay component from the VR Compositor Layers Feature. | Obtain the System's battery level from code. | How to access the System's Settings from your application.|
|  [Access G2 4KE Front Camera][004]|[Catch ScreenShot][005]|[VideoPlayer][006]
| How to access the frontal RGB camera in G2 4K devices. | Learn how to a screenshot from your application. | How to create different Video Players in Unity using the Pico SDK.|
|  [Miracast In App][007]|[PlayFab Achievement Leaderboard][008]|[Photon State Sync ][009]
| How to use Pico Unity XR System APIs to implement Miracast in an application. | How to implement achievement and leaderboard features using PlayFab game service. | How to implement state sync using Photon PUN.|
|  [Photon RoomProperties Sync ][010]|[Eye Tracking][011]| [Launcher Demo][012]
| How to use Photon's PUN v2 to synchronize the status of objects in the scene (via Custom Room Properties). | How to use Eye Tracking APIs | How to create your own system launcher.|
|  [Advanced Guardian][013]|[VRTK.Tutorials.VRBowling][014]| [VRTK.Tutorials.FarmYard][015]|
|How to use the advanced guardian feature to enable multiple devices to use the same map.|A tutorial on how to make a VR Bowling game using the components from the VRTK suite within the Unity software.|A Farm Yard example scene of how to use VRTK v4 for rapidly building spatial computing solutions in the Unity software.|
|  [RTC Sync Demo][016]|[Unity-PicoPlatformSDK-LeaderBoard][017]| [Handtracking MiniGame][018]|
| How to use Pico's SDK to achieve RTC (Real-Time-Communication) service.|How to implement leaderboard feature using PICO Unity Integration SDK.|Handtracking MiniGame with 3 features for you to learn from! (Along with mini other things)

[001]: https://github.com/picoxr/Overlay-Demo-UnityXR
[002]: https://github.com/picoxr/get-batterty-level-UnityXR
[003]: https://github.com/picoxr/goto-system-setting-UnityXR
[004]: https://github.com/picoxr/access-g2-4ke-front-camera-UnityXR
[005]: https://github.com/picoxr/capture-screen-UnityXR
[006]: https://github.com/picoxr/VideoPlayer-UnityXR
[007]: https://github.com/picoxr/MiracastInApp-Demo
[008]: https://github.com/picoxr/PlayFab-Achievement-Leaderboard
[009]: https://github.com/picoxr/Photon-state-sync
[010]: https://github.com/picoxr/Photon-RoomProperties-Sync
[011]: https://github.com/picoxr/EyeTrackingDemo
[012]: https://github.com/picoxr/Launcher-Demo-UnityXR
[013]: https://github.com/picoxr/Advanced-Guardian-Example
[014]: https://github.com/picoxr/VRTK.Tutorials.VRBowling
[015]: https://github.com/picoxr/VRTK.Tutorials.FarmYard
[016]: https://github.com/picoxr/RTCSyncDemo
[017]: https://github.com/picoxr/Unity-PicoPlatformSDK-LeaderBoard
[018]: https://github.com/picoxr/Unity_HandTracking_Demo

## 🔧 Pico Unreal Integration SDK Demos
| [UI Interaction](https://github.com/picoxr/UIInteractionDemo) | [Stereo Layer](https://github.com/picoxr/StereoLayer) | [Rendering Techniques](https://github.com/picoxr/RenderingTechniques)|
|---------------------|--------------------------|-----------------------------|
| How to implement VR interaction with different Unreal UI components.| How to implement different Stereo Layer configurations.| How to implement different Unreal Engine rendering techniques on Pico devices.
| [PlatformSDK Identity Friend Rtc](https://github.com/picoxr/PlatformSDK_Identity_Friend_Rtc) | [PlatformSDK Achievement LeaderBoard](https://github.com/picoxr/PlatformSDK_LeaderBoard-Achievement_UE4) |[Haptic](https://github.com/picoxr/Haptic)|
| How to use Pico Unreal Platform SDK to integrate identity/friend list/RTC audio chat services for online games. |  How to use PICO Unreal Platform SDK to integrate achievement/leaderboard for online games. |  How to implement normal or broadband haptic on controllers.|
|[HandTracking](https://github.com/picoxr/HandTracking) |  |  |
| How to input with hands instead of controllers. |  |  |

## 🔧 Pico Native SDK Demos
| [Native CloudXR Client Demo](https://github.com/picoxr/CloudXR_Client_Demo) | [OpenXR CloudXR Client Demo](https://github.com/picoxr/OpenXR_CloudXR_Client_Demo) | [OpenXR VideoPlayer Demo](https://github.com/picoxr/OpenXR_VideoPlayer_Demo) |
|---------------------|---------------------|---------------------|
| How to create your own NVIDIA CloudXR Client with Android Native XR SDK.| How to create your NVIDIA CloudXR Client with PICO OpenXR SDK.| How to create your 3D VieoPlayer with PICO OpenXR SDK.|



## 🔧 Pico Android Sample Code/JAR File

| [Android Helper](https://github.com/picoxr/AndroidHelper)    | [Get Installed Package Name](https://github.com/picoxr/PackageNameManager) |[Launch WebVR Browser](https://github.com/picoxr/LauncherWebVR)| [Launch Pico System Built-in Video Player](https://github.com/picoxr/PicoPlayManager)|
|--|--|--|--|
|The Android Helper .jar file can be used in Unity/Unreal to access and control Pico devices at Android level.|How to get installed package names on the device.|How to launch the built-in WebVR browser with a specified URL.|How to launch the built-in Video Player with a specified video file.|


## 👋 Technical Support

If you have any questions or issues, you can contact us at:

| [Pico DevSupport Portal](https://picodevsupport.freshdesk.com/support/home) | pico_devsupport@bytedance.com|
|--|--|


*Copyright © 2015-2023 Pico Interactive, Inc.*
