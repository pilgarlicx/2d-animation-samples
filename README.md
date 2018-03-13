# 2d-animation-samples

This repository contains samples of the 2D Animation features.

For use with Unity 2018.1b and newer.

## Getting Started
### Get the Unity Editor
To get started, download and install the latest Unity 2018.1 beta, here: https://unity3d.com/unity/beta-download

### Get the Package
These samples already include the necessary manifest in the Packages folder of the project.
If you want to activate these features in another project:
1. Find the manifest.json file in the Packages folder of your new project.
2. Edit it to look like this:

```xml
{
  "dependencies": {
  "com.unity.2d.common":"1.0.8-experimental",
  "com.unity.2d.animation":"1.0.13-experimental",
  "com.unity.2d.ik":"1.0.3-experimental"
  },
  "registry": "https://staging-packages.unity.com",
  "testables" : [ 
    "com.unity.2d.common",
    "com.unity.2d.animation",
    "com.unity.2d.ik"
  ]
}
```
4. Back in Unity, the packaged will be downloaded and imported. 
5. Done!

### Preview Feature Documentation
* **[2D Animation](https://github.com/Unity-Technologies/2d-animation-samples/blob/master/Documentation/2DAnimation.md)**
* **[Inverse Kinematics (IK)](https://github.com/Unity-Technologies/2d-animation-samples/blob/master/Documentation/2DIK.md)**

## Known Challenges:
* Using the Transform Tools for manipulating bones in the Scene while posing and animating is not as fluid as we would like
* The skinning and rigging portion is done in the Scene View along with Hierarchy manipulation and IK setups

## :exclamation::exclamation::exclamation: Warning :exclamation::exclamation::exclamation:
**Project backward compatibility between Preview versions is NOT GUARANTEED. Always backup your project before upgrading. Preview features here are not production ready, please DO NOT use this build for your final production. Preview features may be discontinued/dropped.**

