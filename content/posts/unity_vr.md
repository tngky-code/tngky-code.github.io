---
title: "Unity_vr"
date: 2021-05-30T13:52:02+08:00

---

## Requirements

* Unity Editor(minimum supported version 2019.4 LTS)
* [Oculus companion app](https://www.oculus.com/lynx/?u=https%3A%2F%2Fplay.google.com%2Fstore%2Fapps%2Fdetails%3Fid%3Dcom.oculus.twilight&e=AT063CdpaqxSP1VURoy084VY4OG48pRqErbSIEFgkGvc84xhQfOdRxDcK_GZVWlAdfcqMkyuOdOZvyZ1QgYYMH3DjKRZMDMR2dzGJyFyG7ztiqI9hSCOuCGLmm0dgaBMUjVfztbrZg1hX7SMLkfK)

## Configuration

### Oculus
1. Download the Oculus companion app and set up user account.
2. Go to Devices > Configure Rift > Full Setup.
3. Follow the on-screen instructions to run the full setup.
4. Follow the in-VR instructions to complete the generic device settings.

### Unity

#### Unity Hub

1. Open Unity Hub and click the Installs tab.
2. Click the three dots next to the Unity 2019.x version and click Add Modules.
3. In the Add Modules window, select Android Build Support and expand it, select Android SDK & NDK Tools and OpenJDK, and click Done.

安装所需版本的Unity Editor,并添加Modules - Android Build Support

#### Unity Editor

**Window->Package Manager:**

    Install XR Interaction Toolkit&OpenXR Plugin
    XR Interaction Toolkit->Import Sample Default Input ACctions

**Assets/Samples/XR Interaction Toolkit/1.0.0-pre.4/Default Input Actions:**

    Add All ActionBasedController default

**Edit->Project Settings->**

    Package Manager:
        Enabled Preview Packages = true
    XR Plugin Management:
        Install XR Plugin Management
        Check OpenXR->Fix All
    Quality:
        Pixel Light Count = 1
        Anisotropic Textures = Per Texture
        Anti Aliasing = 4x Multi Sampling
        Soft Particles = false
    Preset Manager->ActionBasedController:
        Type "Left/Right" in correct box

