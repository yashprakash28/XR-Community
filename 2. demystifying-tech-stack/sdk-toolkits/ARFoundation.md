## Introduction
AR Foundation is a cross-platform framework provided by Unity Technologies that enables developers to create AR applications for a variety of devices, including iOS, Android, and Windows. It simplifies the process of building AR experiences by providing a unified API (Application Programming Interface) that abstracts the underlying AR platforms, such as ARKit and ARCore.
## Key Features
AR Foundation provide developers with a versatile and powerful framework to create immersive and interactive AR applications across different platforms, making it a popular choice for AR development with Unity.
1. Cross-Platform Compatibility: AR Foundation is designed to work across multiple platforms, enabling developers to build AR applications that can run on different devices and operating systems without significant modifications. This cross-platform support streamlines development and deployment processes.
2. Device and Environment Tracking: AR Foundation provides access to device sensors like cameras, gyroscopes, and accelerometers, allowing accurate tracking of the device's position and orientation in the real world. It also offers environmental understanding features such as plane detection, enabling virtual content to be placed and interacted with on real-world surfaces.
3. Anchoring and Persistence: AR Foundation supports anchor management, which allows developers to place and persist virtual objects in the real world. Anchors ensure that virtual content stays aligned with the physical environment, even if the device moves or the application restarts.
4. User Interaction: AR Foundation enables developers to implement user interaction with AR content through touch gestures, gestures recognition, and other input methods supported by the target devices. This allows users to engage with virtual objects and enhances the interactivity of AR experiences.
5. Extensions and Platform-Specific Features: AR Foundation supports the integration of platform-specific features and extensions, allowing developers to leverage advanced capabilities unique to specific AR platforms. This enables access to additional functionalities and optimizations for a more customized and platform-specific AR experience.
6. Unity Ecosystem Integration: As part of the Unity ecosystem, AR Foundation seamlessly integrates with other Unity tools, assets, and services. Developers can leverage the extensive library of Unity assets, such as 3D models, animations, and effects, to enhance their AR applications. Additionally, Unity's scripting capabilities and visual editor provide a flexible and powerful environment for AR development.
7. Cloud Anchors and Multiplayer AR: AR Foundation offers support for cloud anchors, allowing multiple devices to share and synchronize AR experiences in real-time. This feature enables multiplayer AR applications where users can collaborate and interact with the same virtual objects in a shared physical space.
## Use Cases
[Official Samples](https://github.com/Unity-Technologies/arfoundation-samples#simple-ar) of work provided by unity 
## Resources
Official Documentation Link : [ARfoundation](https://docs.unity3d.com/Packages/com.unity.xr.arfoundation@5.1/manual/index.html)

Dilmer Valecillos : Youtube playlist by dilmer regarding AR foundation workings ([Unity AR Foundation Tutorials For Beginners](https://youtube.com/playlist?list=PLQMQNmwN3FvzCWfvCvq2AYh1CFnTlv2Es))

Dinesh Pnni : Youtube playlist on [Unity & AR Foundation](https://youtube.com/playlist?list=PL6VJLOFcTt7awvyIGIbLLPOBrW6-Y1R-J)

## Limitations
In android it only works with the devices compatible with ARCore under the [list](https://developers.google.com/ar/devices) provided by Google 

##Latest upadates
1. AR Session Origin is now deprecated and replaced by XR Origin, which is suitable for both AR and VR applications. XR Origin is part of the XR Core Utilities package, a new dependency of AR Foundation.
