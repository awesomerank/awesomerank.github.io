---
layout: default
title: Awesome Rank for vinjn/awesome-vulkan
---

<p align="center">
	This list is a copy of <a href="https://github.com/vinjn/awesome-vulkan">vinjn/awesome-vulkan</a> with ranks
</p>
---
# Awesome Vulkan [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★63835](https://github.com/sindresorhus/awesome)

<img src="https://raw.githubusercontent.com/SaschaWillems/Vulkan/master/images/vulkanlogoscene.png" alt="Vulkan demo scene" height="256px">

A curated list of awesome Vulkan libraries, debuggers and resources. Inspired by [awesome-opengl ★583](https://github.com/eug/awesome-opengl) and other awesome-... stuff.

* **[Hardware Support](#hardware-support)**
* **[SDK](#sdk)**
* **[IHV Document](#document)**
* **[Tutorial](#tutorial)**
* **[Apps](#apps)**
* **[Samples](#samples)**
* **[Libraries](#libraries)**
* **[Bindings](#bindings)**
* **[Tools](#tools)**
* **[Books](#books)**
* **[Community](#community)**

## Hardware Support
*  [gpuinfo](http://vulkan.gpuinfo.org/) - Vulkan Hardware Database by Sascha Willems
*  [Khronos](https://www.khronos.org/vulkan)
*  [NVIDIA](https://developer.nvidia.com/Vulkan)
    *  [Driver for Desktop](https://developer.nvidia.com/vulkan-driver)
    *  [Driver for Android](https://developer.nvidia.com/vulkan-android)
    *  [Driver for Linux for Tegra (L4T)](https://developer.nvidia.com/embedded/vulkan)
*  [AMD](http://www.amd.com/en-gb/innovations/software-technologies/technologies-gaming/vulkan)
*  [Imagination](https://imgtec.com/tools/powervr-early-access-program/)
*  Intel
    *  [Open-source Driver](https://01.org/linuxgraphics/blogs/jekstrand/2016/open-source-vulkan-drivers-intel-hardware/)
    *  [Driver for Windows](https://software.intel.com/en-us/blogs/2016/03/14/new-intel-vulkan-beta-1540204404-graphics-driver-for-windows-78110-1540)
*  [Qualcomm](https://developer.qualcomm.com/software/adreno-gpu-sdk/gpu)
*  [ARM](http://malideveloper.arm.com/resources/sdks/mali-vulkan-sdk/)

## SDK
*  [For Windows & Linux](https://vulkan.lunarg.com/signin)
*  [For Android](https://developer.android.com/ndk/guides/graphics/index.html)

## Document
*  [AMD](http://gpuopen.com/tag/vulkan/)
    *  [Vulkan barriers explained](http://gpuopen.com/vulkan-barriers-explained/)
    *  [Vulkan Fast Paths](http://32ipi028l5q82yhj72224m8j.wpengine.netdna-cdn.com/wp-content/uploads/2016/03/VulkanFastPaths.pdf)
    *  [Let Your Game Shine – Optimizing DirectX 12 and Vulkan Performance with AMD CodeXL	](http://32ipi028l5q82yhj72224m8j.wpengine.netdna-cdn.com/wp-content/uploads/2016/03/Let_your_game_shine_optimizing_DirectX-12_and_Vulkan-performance_with_AMD_CodeXL.pdf)
    *  [D3D12 & Vulkan: Lessons Learned	 ](http://32ipi028l5q82yhj72224m8j.wpengine.netdna-cdn.com/wp-content/uploads/2016/03/d3d12_vulkan_lessons_learned.pdf)
    *  [Say Hello to a New Rendering API in Town!](http://gpuopen.com/say-hello/)
    *  [Vulkan Renderpasses](http://gpuopen.com/vulkan-renderpasses/)
    *  [Performance tweets series: Barriers, fences, synchronization](http://gpuopen.com/performance-tweets-series-barriers-fences-synchronization/)
    *  [Using the Vulkan™ Validation Layers](http://gpuopen.com/using-the-vulkan-validation-layers/)
    *  [Most common mistakes in Vulkan apps](http://32ipi028l5q82yhj72224m8j.wpengine.netdna-cdn.com/wp-content/uploads/2016/05/Most-common-mistakes-in-Vulkan-apps.pdf)
	*  [Vulkan Device Memory](http://gpuopen.com/vulkan-device-memory/)
*  [NVIDIA](https://developer.nvidia.com/taxonomy/term/586)
    * [Vulkan Device-Generated Commands](https://developer.nvidia.com/device-generated-commands-vulkan)
    * [Getting Vulkan Ready For VR](https://developer.nvidia.com/getting-vulkan-ready-vr)
    * [GPU-Driven Rendering](http://on-demand.gputechconf.com/gtc/2016/presentation/s6138-christoph-kubisch-pierre-boudier-gpu-driven-rendering.pdf) 
    * [GDC 16 - High-performance, Low-Overhead Rendering with OpenGL and Vulkan](http://developer.download.nvidia.com/gameworks/events/GDC2016/mschott_lbishop_gl_vulkan.pdf)  
    * [GDC 16 - Vulkan and NVIDIA – The Essentials](http://developer.download.nvidia.com/gameworks/events/GDC2016/Vulkan_Essentials_GDC16_tlorach.pdf)
    * [Engaging the Voyage to Vulkan](https://developer.nvidia.com/engaging-voyage-vulkan)
    * [Vulkan Shader Resource Binding](https://developer.nvidia.com/vulkan-shader-resource-binding)
    * [Vulkan Memory Management](https://developer.nvidia.com/vulkan-memory-management)
    * [OpenGL like Vulkan](https://developer.nvidia.com/opengl-vulkan)
    * [Transitioning from OpenGL to Vulkan](https://developer.nvidia.com/transitioning-opengl-vulkan)
    * [Siggraph 15 talk - Vulkan on NVIDIA GPUs](http://on-demand.gputechconf.com/siggraph/2015/presentation/SIG1501-Piers-Daniell.pdf)
*  ARM
    * [Porting a Graphics Engine to the Vulkan API](https://community.arm.com/groups/arm-mali-graphics/blog/2016/02/16/porting-a-graphics-engine-to-the-vulkan-api)
    * [Multi-Threading in Vulkan](https://community.arm.com/groups/arm-mali-graphics/blog/2016/04/19/massively-multi-thread-for-vulkan)
    * [Vulkan's Key Features on ARM Architecture](https://developer.arm.com/-/media/Files/pdf/graphics-and-multimedia/Vulkan%20API%20key%20features%20on%20ARM%20architecture.pdf)
    * [Get Your Engine Ready for Vulkan on Mobile](http://malideveloper.arm.com/downloads/Presentations/GDC%202016/Theatre/Get%20Your%20Engine%20Ready%20for%20Vulkan%20on%20Mobile.pdf)
    * [Mali Vulkan Tutorials](http://malideveloper.arm.com/downloads/deved/tutorial/SDK/Vulkan/1.1/index.html) and [Slides](https://developer.arm.com/graphics/vulkan/vulkan-tutorials) Vulkan tutorials from the [Mali Vulkan SDK](http://malideveloper.arm.com/resources/sdks/mali-vulkan-sdk/)
* Intel
    * [API without Secrets: Introduction to Vulkan ★463](https://github.com/GameTechDev/IntroductionToVulkan) [[LICENSE](https://github.com/GameTechDev/IntroductionToVulkan/blob/master/license.txt)]
        * [Part 1: The Beginning](https://software.intel.com/en-us/api-without-secrets-introduction-to-vulkan-part-1)
        * [Part 2: Swap Chain](https://software.intel.com/en-us/api-without-secrets-introduction-to-vulkan-part-2)
        * [Part 3: First Triangle](https://software.intel.com/en-us/api-without-secrets-introduction-to-vulkan-part-3)
        * [Part 4: Vertex Attributes](https://software.intel.com/en-us/articles/api-without-secrets-introduction-to-vulkan-part-4)
* [Imagination](http://blog.imgtec.com/tag/vulkan)
    * [Efficient Rendering with Vulkan on PowerVR](https://imagination-technologies-cloudfront-assets.s3.amazonaws.com/idc-docs/gdc16/6_Efficient%20rendering%20with%20Vulkan%20on%20PowerVR.pdf)
    *  [Migrating to Vulkan with the New PowerVR Graphics Framework](https://imagination-technologies-cloudfront-assets.s3.amazonaws.com/idc-docs/gdc16/7_FrameworkIDC16.pdf)
* Samgsung
    * [Siggraph 2016 - Best Practices for Mobile](https://community.arm.com/servlet/JiveServlet/download/96891546-24708/6-mmg-siggraph2016-vulkan-smedis.pdf)
* Epic
    * [Efficient use of Vulkan on UE4 Mobile](https://community.arm.com/servlet/JiveServlet/download/96891546-24708/6-mmg-siggraph2016-vulkan-smedis.pdf)

## Tutorial
*  [jhenriques's tutorial](http://jhenriques.net/development.html)
*  [Khronos](https://www.khronos.org/registry/vulkan/)
    *  [Vulkan 1.0 Quick Reference](https://www.khronos.org/registry/vulkan/specs/1.0/refguide/Vulkan-1.0-web.pdf)
    *  [Vulkan 1.0 Specification](https://www.khronos.org/registry/vulkan/specs/1.0-wsi_extensions/pdf/vkspec.pdf)
    *  [GDC 2016 Presentations](https://www.khronos.org/developers/library/2016-gdc)
    *  [Moving to Vulkan Khronos UK May16](https://www.khronos.org/assets/uploads/developers/library/2016-uk-chapter-moving-to-vulkan/Moving-to-Vulkan_Khronos-UK_May16.pdf)
    *  [SIGGRPAH 2016 3D BOF](https://www.khronos.org/assets/uploads/developers/library/2016-siggraph/Khronos-3D-BOF-SIGGRAPH_Jul16.pdf)
*  [Lunarg's tutorial](https://vulkan.lunarg.com/doc/sdk/1.0.26.0/windows/tutorial.html)
* Siggraph
    * [An overview of next-generation graphics APIs](http://nextgenapis.realtimerendering.com/) - covers Vulkan, D3D12 etc.
*  [vulkan-sxs](https://github.com/philiptaylor/vulkan-sxs) - explain the Vulkan API step by step and [vulkan-sync ★9 ⏳1Y](https://github.com/philiptaylor/vulkan-sync) - rephrase Vulkan's requirements on execution dependencies in a more precise form. [MIT]
*  [Vulkan in 30 minutes](https://renderdoc.org/vulkan-in-30-minutes.html) - by baldurk.
*  [Tutorial by Overv](https://vulkan-tutorial.com/) and [its github repository ★524](https://github.com/Overv/VulkanTutorial). [CC BY-SA 4.0]
*  [Vulkan Demos and Tutorials ★36](https://github.com/Z80Fan/VulkanDemos) [MIT].
*  [Qualcomm Video Tutorial Series](https://developer.qualcomm.com/software/adreno-gpu-sdk/tutorial-videos) - Leans more towards Vulkan for mobile devices.
*  [Raw Vulkan](https://alain.xyz/blog/raw-vulkan) - Overview on how to program a Vulkan application from the ground up.
*  [I Am Graphics And So Can You](https://www.fasterthan.life/blog/2017/7/11/i-am-graphics-and-so-can-you-part-1) - Blog post style tutorial for those new to graphics learning Vulkan.

## Apps
*  [The Talos Principle](http://www.croteam.com/talos-principle-will-support-vulkan-first-screenshot-released/) - by Croteam.
*  [Dota2 ★39 ⏳1Y](https://github.com/ValveSoftware/Dota-2-Vulkan) - by Valve.
*  [Basemark](http://www.basemark.com/2015/11/10/basemark-extends-its-benchmarking-lead-with-a-vulkan-performance-test/) - by Basemark.
*  [GFXBench 5](https://kishonti.net/news_single.jsp?id=31133884) - by Kishonti.
*  [ProtoStar](https://www.unrealengine.com/blog/epic-games-unveils-protostar-at-samsung-galaxy-unpacked) - by Epic, built with Unreal Engine 4 technology.
*  [Doom](https://en.wikipedia.org/wiki/Doom_(2016_video_game)) - by id Software.
*  [vkQuake ★354](https://github.com/Novum/vkQuake) - Vulkan Quake port based on QuakeSpasm. [GPL]
*  [Linux port of SteamVR ★236](https://github.com/ValveSoftware/SteamVR-for-Linux) - SteamVR is built on top of the Vulkan API.
*  [3DMark](https://www.futuremark.com/pressreleases/compare-vulkan-and-directx-12-performance-with-3dmark) - 3DMark API Overhead test.

## Samples
*  Sascha Willems's [samples](https://github.com/SaschaWillems/Vulkan) and [Deferred rendering of  Sponza ★24](https://github.com/SaschaWillems/VulkanSponza) and his talk of [Khronos_meetup_munich](https://github.com/SaschaWillems/Vulkan/blob/master/documentation/Khronos_meetup_munich_fromGLtoVulkan.pdf).
*  McNopper's [examples ★193](https://github.com/McNopper/Vulkan)
*  [KhronosGroup](https://github.com/KhronosGroup)
    *  [Samples ★401](https://github.com/KhronosGroup/Vulkan-Samples)
    *  [Conformance Tests (CTS)](https://github.com/KhronosGroup/Vulkan-CTS)
*  Google
    *  [Android port of LunarG samples ★107](https://github.com/googlesamples/vulkan-basic-samples).
    *  [android tutorials ★260](https://github.com/googlesamples/android-vulkan-tutorials).
*  [nvpro-samples](https://github.com/nvpro-samples) - NVIDIA DesignWorks Samples. [[LICENSE](https://github.com/nvpro-samples/gl_vk_threaded_cadscene/blob/master/LICENSE)]
    *  [gl_vk_chopper ★112](https://github.com/nvpro-samples/gl_vk_chopper) - Simple vulkan rendering example.
    *  [gl_vk_threaded_cadscene ★66](https://github.com/nvpro-samples/gl_vk_threaded_cadscene) - OpenGL and Vulkan comparison on rendering a CAD scene using veraious techniques and [the blog](https://developer.nvidia.com/vulkan-opengl-threaded-cad-scene-sample) about it.
    *  [gl_vk_bk3dthreaded ★42](https://github.com/nvpro-samples/gl_vk_bk3dthreaded) - Vulkan sample rendering 3D with 'worker-threads'.
    *  [gl_vk_supersampled ★37 ⏳1Y](https://github.com/nvpro-samples/gl_vk_supersampled) - Vulkan sample showing a high quality super-sampled rendering.
*  [NVIDIA GameWorks Samples ★387](https://github.com/NVIDIAGameWorks/GraphicsSamples) - GameWorks cross-platform graphics API samples. [[LICENSE](https://github.com/NVIDIAGameWorks/GraphicsSamples/blob/master/license.txt)]
*  [LunarG's samples ★489](https://github.com/LunarG/VulkanSamples)
*  [vkcube ★34](https://github.com/krh/vkcube) - 'vkcube' sample from krh, works under X, wayland and VT console with
drm/kms.
*  [Stardust from Intel ★64](https://github.com/GameTechDev/stardust_vulkan) - The Stardust sample application uses the Vulkan graphics API to efficiently render a cloud of animated particles. [[LICENSE](https://github.com/GameTechDev/stardust_vulkan/blob/master/license.txt)]
*  [Vulkan Quake port based on QuakeSpasm ★354](https://github.com/Novum/vkQuake).
*  [C# Samples](https://github.com/FacticiusVir/SharpVk-Samples) - Port of Overv's tutorials to [SharpVk ★35](https://github.com/FacticiusVir/SharpVk) [MIT]
*  [Vulkan-Forward-Plus-Renderer ★276](https://github.com/WindyDarian/Vulkan-Forward-Plus-Renderer) - VFPR - a Vulkan Forward Plus Renderer. [MIT]
*  [Laugh Engine ★193](https://github.com/jian-ru/laugh_engine) - Vulkan implementation of real-time PBR renderer.
*  [tinyrenderers ★197](https://github.com/chaoticbob/tinyrenderers) - Single header implemenations of Vulkan and D3D12 renderers.
*  [TLVulkanRenderer ★16](https://github.com/trungtle/TLVulkanRenderer) - Simple Vulkan-based renderer for my master thesis on real-time transparency. [CC BY-SA 4.0]
*  [Vulkan-Hpp Samples ★91](https://github.com/jherico/Vulkan) - Fork of Sascha Willems excellent Vulkan examples that uses Vulkan-Hpp.
*  [SDF Font Demo ★94](https://github.com/kocsis1david/font-demo) - Text rendering in Vulkan by estimating signed distance. [MIT]
*  [vulkantoy ★13](https://github.com/jpystynen/vulkantoy) - Shadertoy image shader test app with Vulkan. [MIT]
*  [GL_vs_VK ★25](https://github.com/RippeR37/GL_vs_VK) - Comparison of OpenGL and Vulkan API in terms of performance. [MIT]

## Libraries
*  [Cinder ★3199](https://github.com/cinder/Cinder) and [the story](https://libcinder.org/notes/vulkan) [behind](https://forum.libcinder.org/#Topic/23286000002614007). [BSD]
*  [SDL](https://discourse.libsdl.org/t/sdl-2-0-6-prerelease/23024) - added cross-platform Vulkan graphics support in SDL_vulkan.h. [zlib]
*  [DemoFramework ★9](https://github.com/NXPmicro/gtec-demo-framework) - NXP GTEC C++11 cross-platform demo framework including lots of samples for Vulkan, OpenGL ES, OpenVX, OpenCL, OpenVG and OpenCV. [[BSD-3-clause](https://github.com/NXPmicro/gtec-demo-framework/blob/master/License.md)]
*  [openFrameworks ★36](https://github.com/openframeworks-vk/openFrameworks) - the most famouse C++ creative coding framework. [MIT]
*  [bgfx ★3332](https://github.com/bkaradzic/bgfx) - Cross-platform rendering library, bgfx backend is WIP. [[LICENSE](https://github.com/bkaradzic/bgfx/blob/master/LICENSE)]
*  [PowerVR SDK ★217](https://github.com/powervr-graphics/Native_SDK) - C++ cross-platform 3D graphics SDK to speed up development of Vulkan and GLES. [[LICENSE](https://github.com/powervr-graphics/Native_SDK/blob/4.1/LICENSE_POWERVR_SDK.txt)]
*  [glfw ★2906](https://github.com/glfw/glfw) and [the guide](http://www.glfw.org/docs/3.2/vulkan.html).  [[LICENSE](https://github.com/glfw/glfw/blob/master/COPYING.txt)]
*  [MoltenVK](https://moltengl.com/moltenvk/) - run Vulkan on iOS and macOS. [Non-free]
*  [imgui ★7651](https://github.com/ocornut/imgui) - Immediate Mode Graphical User interface. [MIT]
*  [libvc ★62 ⏳1Y](https://github.com/alexhultman/libvc) - Vulkan Compute for C++.  [[LICENSE](https://github.com/alexhultman/libvc/blob/master/LICENSE)]
*  [AMD's Anvil ★280](https://github.com/GPUOpen-LibrariesAndSDKs/Anvil) - cross-platform framework for Vulkan. [[LICENSE](https://github.com/GPUOpen-LibrariesAndSDKs/OutOfOrderRasterization/blob/master/LICENSE.txt)]
    * [Introductory Vulkan sample ★46](https://github.com/GPUOpen-LibrariesAndSDKs/HelloVulkan). [MIT]
*  [Vulkan Memory Allocator ★121](https://github.com/GPUOpen-LibrariesAndSDKs/VulkanMemoryAllocator) - Easy to integrate Vulkan memory allocation library from AMD [MIT]
*  [Google's vulkan-cpp-library ★157](https://github.com/google/vulkan-cpp-library) - Vulkan abstraction library using C++11 for memory, resource management, type and thread safety as well as system independency. [Apache]
*  [Vookoo ★54](https://github.com/andy-thomason/Vookoo) - Vookoo is a set of dependency-free utilities to assist in the construction and updating of Vulkan graphics data structres. [MIT]
*  [vpp ★60](https://github.com/nyorain/vpp) - Modern C++ Vulkan Abstraction focused on performance and a straightforward interface. [MIT]
*  [Intrinsic Engine](http://www.intrinsic-engine.com/) - Intrinsic is a Vulkan based cross-platform graphics and game engine. [Apache License 2.0]
*  [glo / OpenGL Overload ★208](https://github.com/g-truc/glo) - OpenGL implementation on top of Vulkan.
*  [Spectrum ★2](https://github.com/mwalczyk/spectrum_core) - Work-in-progress framework and abstraction layer around Vulkan. 
*  [VkHLF ★200](https://github.com/nvpro-pipeline/VkHLF) - Vulkan High Level Framework. [[LICENSE]](https://github.com/nvpro-pipeline/VkHLF/blob/master/LICENSE.txt)
*  [VulkanOnD3D12 ★3](https://github.com/Chabloom/VulkanOnD3D12) - Vulkan API for D3D12. [Apache License 2.0]
*  [visor ★10](https://github.com/baldurk/visor) - Vulkan Ignoble Software Rasterizer. [MIT]
*  [Lugdunum ★74](https://github.com/Lugdunum3D/Lugdunum) - Modern cross-platform 3D rendering engine built with Vulkan and modern C++14. [MIT]
*  [Vulkan-WSIWindow ★18](https://github.com/renelindsay/Vulkan-WSIWindow) - Multi-platform library to create a Vulkan window, and handle input events. [Apache License 2.0]
*  [Falcor ★99](https://github.com/NVIDIAGameWorks/Falcor) - Real-time rendering framework from NVIDIA, supporting DX12 and Vulkan. [BSD 3-clause]

## Bindings
*  [libvulkan.lua](https://github.com/CapsAdmin/ffibuild/blob/master/examples/vulkan/libvulkan.lua) - Lua bindings for Vulkan.
*  [dvulkan ★13](https://github.com/ColonelThirtyTwo/dvulkan) - Auto-generated D bindings for Vulkan.
*  [ErupteD ★21](https://github.com/ParticlePeter/ErupteD) - Another Auto-generated D bindings for Vulkan.
*  [Haskell bindings for Vulkan ★38 ⏳1Y](https://github.com/expipiplus1/vulkan) - [[LICENSE](https://github.com/expipiplus1/vulkan/blob/master/LICENSE)]
*  [Vulkan-hpp ★833](https://github.com/KhronosGroup/Vulkan-Hpp) Open-Source Vulkan C++ API originated from NVIDIA and [the blog](https://developer.nvidia.com/open-source-vulkan-c-api) about it.
*  [VulkanSharp ★177](https://github.com/mono/VulkanSharp) - C# bindings for Vulkan. [MIT]
*  [Vulkano ★1](https://github.com/tomaka/vulkano) - Safe and rich Rust wrapper around the Vulkan API. [MIT]
*  [LWJGL](https://www.lwjgl.org/) - Lightweight Java Game Library 3 has Vulkan bindings. [BSD]
*  [SharpVk ★35](https://github.com/FacticiusVir/SharpVk) - C# bindings for Vulkan with Linq-to-SPIR-V & [NuGet package](https://www.nuget.org/packages/SharpVk). [MIT]
*  [vulkan ★29](https://github.com/realitix/vulkan) - Ultimate Python bindings for Vulkan generated with CFFI. [Apache Licence 2.0]
  
## Tools
*  [Nsight™ Visual Studio Edition 5.2+](https://developer.nvidia.com/nvidia-nsight-visual-studio-edition).
*  [LoaderAndValidationLayers ★331](https://github.com/KhronosGroup/Vulkan-LoaderAndValidationLayers) - from KhronosGroup. [Apache Licence 2.0]
*  [renderdoc ★1918](https://github.com/baldurk/renderdoc) - by baldurk, a stand-alone graphics debugging tool. [MIT]
*  [VulkanTools ★187](https://github.com/LunarG/VulkanTools) - LunarG's tools including layers, `vktrace` and `vkreplay`. [Apache Licence 2.0]
*  [CodeXL ★588](https://github.com/GPUOpen-Tools/CodeXL) - CodeXL goes open source. [MIT]
*  [Qualcomm GPU Tools](https://developer.qualcomm.com/software/adreno-gpu-sdk/tools).
*  [Mali Graphics Debugger](http://malideveloper.arm.com/resources/tools/mali-graphics-debugger/).
*  [Open Capture and Analytics Tool (OCAT) ★64](https://github.com/GPUOpen-Tools/OCAT) - rovides an FPS overlay and performance measurement for D3D11, D3D12, and Vulkan. [MIT]
*  [gapid ★379](https://github.com/google/gapid) - Graphics API Debugger, can trace and replay Android OpenGL ES and Vulkan applications. [Apache License 2.0]

## Books
* [Learning Vulkan](https://www.amazon.com/Learning-Vulkan-Parminder-Singh/dp/1786469804) - by **Parminder Singh** - Get started with the Vulkan API and its programming techniques using the easy-to-follow examples.
  * [Book's Examples ★17](https://github.com/PacktPublishing/Learning-Vulkan)
* [Vulkan Cookbook](https://www.amazon.com/Vulkan-Cookbook-Pawel-Lapinski/dp/1786468158)- by **Pawel Lapinski** - Explores a wide range of graphics programming and GPU compute methods to make the best use of the Vulkan API.
  * [Book's Examples ★40](https://github.com/PacktPublishing/Vulkan-Cookbook)
* [Vulkan Programming Guide](https://www.amazon.com/Vulkan-Programming-Guide-Official-Learning/dp/0134464540) - by **Graham Sellers** and **John Kessenich** - Introduces powerful 3D development techniques for many fields. 

## Community
*  [Freenode IRC](http://webchat.freenode.net/?channels=Vulkan)
*  [Google Plus](https://plus.google.com/communities/108983304183191634377)
*  [Khronos Forum](https://forums.khronos.org/forumdisplay.php/114-Vulkan)
*  [Reddit](https://www.reddit.com/r/vulkan/)
*  [Stack Overflow](http://stackoverflow.com/questions/tagged/vulkan)

## Related lists
*  [awesome ★63835](https://github.com/sindresorhus/awesome) - Curated list of awesome lists.
*  [awesome-opengl ★583](https://github.com/eug/awesome-opengl) - Curated list of awesome OpenGL libraries, debuggers and resources.
*  [gamedev ★4095](https://github.com/ellisonleao/magictools) - Awesome list about game development.
*  [graphics-resources ★1026](https://github.com/mattdesl/graphics-resources) - List of graphic programming resources.
*  [awesome-d3d12 ★16](https://github.com/vinjn/awesome-d3d12) - Curated list of awesome D3D12 libraries, debuggers and resources.

## License

[![Creative Commons License](http://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)

This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).

## Contributing
Please see [CONTRIBUTING](https://github.com/vinjn/awesome-vulkan/blob/master/CONTRIBUTING.md) for details.
---
<p align="center">
	This list is a copy of <a href="https://github.com/vinjn/awesome-vulkan">vinjn/awesome-vulkan</a> with ranks
</p>
