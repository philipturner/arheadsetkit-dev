# ARHeadsetKit Development Repository

This repository is for exploring the feasibility of "ARHeadsetKit 2.0", rewriting ARHeadsetKit from the ground up. The driving use case is an interactive design environment for [molecular nanotechnology](https://en.wikipedia.org/wiki/Molecular_nanotechnology), building on my work in [molecular-renderer](https://github.com/philipturner/molecular-renderer). This is the perfect application for AR - physically grabbing atoms and placing them, immersing yourself in the nanostructure. Rendering the MD simulation with a speed adjusted for scaling laws, to show how it's just as fast as macroscale mechanical machines.

However, this is hypothetical, and there is no guarantee I will update ARHeadsetKit. If the update does happen, it will be in the far future. For questions or concerns, please open an issue in the main [ARHeadsetKit](https://github.com/philipturner/arheadsetkit) repository.

---

New README draft

ARHeadsetKit is a software library that creates immersive [augmented reality](https://en.wikipedia.org/wiki/Augmented_reality) (AR) experiences on affordable hardware. It goes beyond the conventional handheld AR, and emulates [smart glasses](https://en.wikipedia.org/wiki/Smartglasses). Headset AR - as opposed to "handheld" AR - is like a virtual reality headset, but also incorporates information from the real world. This approach upgrades AR from a 2D camera game to a 3D environment. With good enough graphics, it can be hard to distinguish _reality_ from _reality as displayed inside the headset_. This means headset AR can inject virtual objects into (what we perceive as) the real world. The headset could be a sleek pair of glasses, an industrial HoloLens, or your smartphone's [OLED](https://en.wikipedia.org/wiki/OLED) display. The applications are endless, but not yet realized.

In 2020, the iPhone 12 Pro's LiDAR scanner made headset AR accessible to the average person. This scanner captures the world in 3D using something like radar and sonar. Paired with a [powerful GPU](https://github.com/philipturner/metal-benchmarks) and a [DIY VR headset](https://en.wikipedia.org/wiki/Google_Cardboard), this scanner can replicate $3,000 Microsoft HoloLens or Apple's future smart glasses. However, ARHeadsetKit costs $0 and you can try it now.

Supported devices (ARHeadsetKit 2)
- Anything that can run Metal 3 and has LiDAR
- iPhone 12 Pro, Pro Max
- iPhone 13 Pro, Pro Max
- iPhone 14 Pro, Pro Max
- iPad Pro (M1, 2021)
- iPad Pro (M2, 2022)

Supported devices (ARHeadsetKit 1)
- Anything that can run ARKit and iOS 14
- Apple A9 processor or higher

ARHeadsetKit 1 was higher level, had tutorials, LiDAR had barely penetrated the market...

ARHeadsetKit 2 is intrinsically lower level, but more flexible and power efficient. It makes the underlying algorithms easier to modify for custom use cases.
