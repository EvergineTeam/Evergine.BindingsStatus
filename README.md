# Evergine Bindings Status

This repository contains low-level bindings for various graphics libraries and frameworks used in Evergine, including Vulkan, OpenXR, WebGL (WebGPU), OpenGL, RenderDoc, and ImGui.

## Current Bindings

The following bindings are currently available in this repository:

### [Vulkan.NET](https://github.com/EvergineTeam/Vulkan.NET)
* Binding for the Vulkan API
* Auto-generated from vk.xml file included in the KhronosRegistry folder

[![CI](https://github.com/EvergineTeam/Vulkan.NET/actions/workflows/CI.yml/badge.svg)](https://github.com/EvergineTeam/Vulkan.NET/actions/workflows/CI.yml)
[![Monthly update check](https://github.com/EvergineTeam/Vulkan.NET/actions/workflows/monthly_update.yml/badge.svg)](https://github.com/EvergineTeam/Vulkan.NET/actions/workflows/monthly_update.yml)
[![Nuget](https://img.shields.io/nuget/v/Evergine.Bindings.Vulkan?logo=nuget)](https://www.nuget.org/packages/Evergine.Bindings.Vulkan)

### [OpenXR.NET](https://github.com/EvergineTeam/OpenXR.NET)
* Binding for the OpenXR API
* Auto-generated from xr.xml file included in the KhronosRegistry folder

[![CI](https://github.com/EvergineTeam/OpenXR.NET/actions/workflows/CI.yml/badge.svg)](https://github.com/EvergineTeam/OpenXR.NET/actions/workflows/CI.yml)
[![Monthly update check](https://github.com/EvergineTeam/OpenXR.NET/actions/workflows/monthly_update.yml/badge.svg)](https://github.com/EvergineTeam/OpenXR.NET/actions/workflows/monthly_update.yml)
[![Nuget](https://img.shields.io/nuget/v/Evergine.Bindings.OpenXR?logo=nuget)](https://www.nuget.org/packages/Evergine.Bindings.OpenXR)

### [WebGPU.NET](https://github.com/EvergineTeam/WebGPU.NET)
* Lightweight, low-level wrapper built on top of the `wgpu-native` library from Firefox
* Facilitates swift development of an adapter for Evergine, allowing for rapid testing across Windows, Linux, and Mac platforms using DirectX, Vulkan, and Metal

[![CI](https://github.com/EvergineTeam/WebGPU.NET/actions/workflows/CI.yml/badge.svg)](https://github.com/EvergineTeam/WebGPU.NET/actions/workflows/CI.yml)
[![CD WebGPU](https://github.com/EvergineTeam/WebGPU.NET/actions/workflows/cd.yml/badge.svg)](https://github.com/EvergineTeam/WebGPU.NET/actions/workflows/cd.yml)
[![Nuget](https://img.shields.io/nuget/v/Evergine.Bindings.WebGPU?logo=nuget)](https://www.nuget.org/packages/Evergine.Bindings.WebGPU)

### [OpenGL.NET](https://github.com/EvergineTeam/OpenGL.NET)
* Binding for the OpenGL API
* Auto-generated from gl.xml file included in the KhronosRegistry folder

[![CI](https://github.com/EvergineTeam/OpenGL.NET/actions/workflows/CI.yml/badge.svg)](https://github.com/EvergineTeam/OpenGL.NET/actions/workflows/CI.yml)
[![CD](https://github.com/EvergineTeam/OpenGL.NET/actions/workflows/CD.yml/badge.svg)](https://github.com/EvergineTeam/OpenGL.NET/actions/workflows/CD.yml)
[![Nuget](https://img.shields.io/nuget/v/Evergine.Bindings.OpenGL?logo=nuget)](https://www.nuget.org/packages/Evergine.Bindings.OpenGL)

### [RenderDoc.NET](https://github.com/EvergineTeam/RenderDoc.NET)
* Binding for OpenGL (ES1-3.0, ES2.0, GL 1.x-4.6) and OpenGL ES
* Auto-generated from [renderdoc_api_header](https://github.com/baldurk/renderdoc/blob/v1.x/renderdoc/api/app/renderdoc_app.h "RenderDoc API Header")

[![CI](https://github.com/EvergineTeam/RenderDoc.NET/actions/workflows/CI.yml/badge.svg)](https://github.com/EvergineTeam/RenderDoc.NET/actions/workflows/CI.yml)
[![CD](https://github.com/EvergineTeam/RenderDoc.NET/actions/workflows/CD.yml/badge.svg)](https://github.com/EvergineTeam/RenderDoc.NET/actions/workflows/CD.yml)
[![Nuget](https://img.shields.io/nuget/v/Evergine.Bindings.RenderDoc?logo=nuget)](https://www.nuget.org/packages/Evergine.Bindings.RenderDoc)

### [TinyUSD.NET](https://github.com/EvergineTeam/TinyUSD.NET)
* This repository contains a thin low-level autogenerated C# binding for tinyusdz used by Evergine.
* tinyusdz is a lightweight, single-header C++ library for handling USD (Universal Scene Description) files.

[![CI](https://github.com/EvergineTeam/TinyUSD.NET/actions/workflows/CI.yml/badge.svg)](https://github.com/EvergineTeam/TinyUSD.NET/actions/workflows/CI.yml)
[![CD](https://github.com/EvergineTeam/TinyUSD.NET/actions/workflows/CD.yml/badge.svg)](https://github.com/EvergineTeam/TinyUSD.NET/actions/workflows/CD.yml)
[![Nuget](https://img.shields.io/nuget/v/Evergine.Bindings.TinyUSD?logo=nuget)](https://www.nuget.org/packages/Evergine.Bindings.TinyUSD)

### [ImGui.Net](https://github.com/EvergineTeam/ImGui.Net)
* Thin low-level autogenerated bindings for Imgui in C#
* Includes c# bindings of the most popular imgui libraries as well, Imguizmo, Implot and Imnodes

[![CI Imgui](https://github.com/EvergineTeam/ImGui.Net/actions/workflows/ci-imgui.yml/badge.svg)](https://github.com/EvergineTeam/ImGui.Net/actions/workflows/ci-imgui.yml)
[![CD Imgui](https://github.com/EvergineTeam/ImGui.Net/actions/workflows/cd-imgui.yml/badge.svg)](https://github.com/EvergineTeam/ImGui.Net/actions/workflows/cd-imgui.yml)

| Project | Nuget |
| :-- | :-- |
| Imgui  | [![Nuget](https://img.shields.io/nuget/v/Evergine.Bindings.Imgui?logo=nuget)](https://www.nuget.org/packages/Evergine.Bindings.Imgui) |
| Imguizmo | [![Nuget](https://img.shields.io/nuget/v/Evergine.Bindings.Imguizmo?logo=nuget)](https://www.nuget.org/packages/Evergine.Bindings.Imguizmo) |
| Implot | [![Nuget](https://img.shields.io/nuget/v/Evergine.Bindings.Implot?logo=nuget)](https://www.nuget.org/packages/Evergine.Bindings.Implot) |
| Imnodes | [![Nuget](https://img.shields.io/nuget/v/Evergine.Bindings.Imnodes?logo=nuget)](https://www.nuget.org/packages/Evergine.Bindings.Imnodes) |

This README serves as a centralized hub for all the bindings available in this repository. You can find more information about each binding by clicking on the links above.
