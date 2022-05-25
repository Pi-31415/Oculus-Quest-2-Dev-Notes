# Oculus-Quest-2-Dev-Notes
Development Notes for Oculus Quest 2 for Haptics Research

- Oculus Setup on Mac [Tutorial](https://medium.com/@sofaracing/how-to-develop-for-oculus-quest-on-macos-with-unity-5aa487b80d13)

## Limitations

- Note: There is a known issue with the thumb trapezium bone (Thumb0) in the OpenXR backend. The Thumb0 bone pose does not pinch all the way and there is about a 1/8 of an inch gap between the index finger and thumb when using the system gestures.

## Workflow

- We will be directly compiling an android app on the Oculus Quest 2 directly.

## Relevant Unity Tutorials

- [Oculus Input](https://docs.unity3d.com/560/Documentation/Manual/OculusControllers.html)

## Relevant Oculus Tutorials

- [HAND TRACKING with the Oculus Quest](https://www.youtube.com/watch?v=vSia7t_WlbQ&ab_channel=Valem)
- [A good YouTube channel for anything VR](https://www.youtube.com/c/ValemVR/videos)

## Relevant Leapmotion Tutorials
- [How To Get Started With The Hands Module | Ultraleap](https://www.youtube.com/watch?v=JTnSuwcfcWc&ab_channel=Ultraleap)
- [Leapmotin Unity Integration](https://developer.leapmotion.com/unity/)

## Troubleshooting

- Fails with Error "THE VULKAN GRAPHICS API DOES NOT SUPPORT XR IN YOUR CONFIGURATION" WHEN USING VULKAN GRAPHICS API ([Solution](https://issuetracker.unity3d.com/issues/build-fails-with-error-the-vulkan-graphics-api-does-not-support-xr-in-your-configuration-when-using-vulkan-graphics-api))
- NullReferenceException: Object reference not set to an instance of an object
OculusSampleFrameworkUtil.HandlePlayModeState (UnityEditor.PlayModeStateChange state) ([Solution](https://forums.oculusvr.com/t5/Oculus-Go-Development/NullReferenceException-from-Oculus-package/td-p/758571/page/2))
