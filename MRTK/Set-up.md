# Getting Starting and Installation Notes

## Installations Required
[Installation Checklist](https://learn.microsoft.com/en-us/windows/mixed-reality/develop/install-the-tools?tabs=unity)

1. Windows 10 or 11 on development PC
2. VS Studio 2022
3. Hololens Emulator (if want to run without the physical headset)
4. Unity or Unreal

#### Game Engine Options
+ [Unity](https://learn.microsoft.com/en-us/windows/mixed-reality/develop/unity/choosing-unity-version)
+ Unreal: "As of Unreal Engine 4.25, HoloLens support is full-featured and production-ready. With capabilities such as the flexible Blueprints Visual Scripting system, designers can virtually use the full range of concepts and tools generally only available to programmers. Creators across industries can leverage the freedom and control to deliver cutting-edge content, interactive experiences, and immersive virtual worlds."

#### Hololens Emulator
In Repo at: MRTK/HoloLensEmulatorSetup.exe

The HoloLens Emulator lets you test holographic applications on your PC without a physical HoloLens, including the HoloLens development toolset. The emulator uses a Hyper-V virtual machine, which means human and environmental inputs being read by HoloLens sensors are simulated from your keyboard, mouse, or Xbox controller. You don't even need to modify your projects to run on the emulator, the app doesn't know it isn't running on a real HoloLens.

System Requirements:
The HoloLens Emulator uses Hyper-V with RemoteFx (first Gen Emulator) or GPU-PV (HoloLens 2 Emulator) for hardware accelerated graphics. To use the emulator, make sure your PC meets the following hardware requirements:

+ 64-bit Windows 10 Pro, Enterprise, or Education
+ 64-bit CPU
+ CPU with four cores (or multiple CPUs with a total of four cores)
+ 8 GB of RAM or more
+ In the BIOS, the following features must be supported and enabled: Hardware-assisted virtualization, Second Level Address Translation (SLAT), Hardware-based Data Execution Prevention (DEP)
+ GPU requirements: DirectX 11.0 or later, WDDM 1.2 graphics driver or later (first gen), WDDM 2.5 graphics driver (HoloLens 2 Emulator)
*The emulator might work with an unsupported GPU, but will be slower*

If your system meets the requirements listed above, ensure that the "Hyper-V" feature has been enabled on your system. Go to Control Panel -> Programs -> Programs and Features -> Turn Windows Features on or off and check that Hyper-V is selected.
