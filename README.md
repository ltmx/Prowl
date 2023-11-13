# Prowl, An Open Source Unity-like C# Game Engine!

<a id="readme-top"></a>

  <ol>
    <li> <a href="#about-the-project">About The Project</a> </li>
    <li> <a href="#about-the-project">Features</a> </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    # <li><a href="#acknowledgments">Acknowledgments</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#dependencies">Dependencies</a></li>
    <li><a href="#screenshots">Screenshots</a></li>
  </ol>

# About The Project
Prowl is an open-source, **MIT-licensed** game engine developed in **pure C# in .NET 8**, (which suprisingly has **no runtime fees** believe it or not!). It aims to provide a seamless transition for developers familiar with Unity by maintaining a similar API while also following KISS and staying as small and customizable as possible. This engine is intended to be customized to your needs, everything is written to be a "Minimal" Production-Ready Implementation. Ideally their will be plenty of Modules/Packages to expand on functionality for those who dont want (or unable) to expand the base engine.

### [Join our Discord server!](https://discord.gg/BqnJ9Rn4sn)

**Note:** The Engine is very young and far from production ready, being developed mainly by a single developer in his spare time. **And has only been tested and compiled for windows!**

**Note:** Currently, the engine is using Raylib as a temporary base to speed up development, with plans to implement a custom-built API Agnostic backend later.

![Sponza and Flight Helmet screenshot](https://i.imgur.com/abJgJv7.png)
<small>At the time of taking this screenshot, Materials could not be created nor modified in Editor so the PBR Textures are not correctly setup.</small>

# Features

-   **General:**
    - Unity-Like Editor & Scripting API
    - C# Scripting
    - Gameobject & Component structure
    - .NET 8
    - Dear ImGUI
    - Editor with support for Editor Scripts and Custom Editors
    - Less then 5k of Executable Code for both the Editor and Engine combined!
    - Unity-Like Coroutines
    - Json Serialization via Newtonsoft.Json
    - Play test directly in Editor
<p align="right">(<a href="#readme-top">back to top</a>)</p>

-   **Graphics Rendering:**
    -  PBR (Physically Based Rendering) using Cook-Torrance BRDF
        - Albedo Map
        - Normal Map
        - Roughness Map
        - Metallic Map
        - Ambient Occclusion Map
        - Emission Map
    -  Deferred Renderer
    -  Point, Spot and Directional Lights
    -  Shadow Mapping with PCF Filtering (Pcss Soft Shadows half implemented)
    -  HDR with Aces Tonemapping

-   **Asset Pipeline:**
    -  A Powerful Asset Pipeline with a very similiar structure to unity
    - Meta Files & Reference by GUID
    - Import Caching
    - Support for Custom Importers
    - Supports many major file formats via ImageMagick, Assimp, etc
<p align="right">(<a href="#readme-top">back to top</a>)</p>

# Getting Started

Getting Prowl up and running is super easy!

### Prerequisites

* [Visual Studio Version 17.8.0+](visualstudio.microsoft.com/vs/preview/) - Required to support .NET 8
* [.NET 8](https://dotnet.microsoft.com/en-us/download/dotnet/8.0)

### Installation

1. Clone the repo
2. Open `.sln` file with [Visual Studio Version 17.8.0+](visualstudio.microsoft.com/vs/preview/)
3. Thats it! :D
<p align="right">(<a href="#readme-top">back to top</a>)</p> 

# Roadmap

- [ ] Skinned Mesh Rendering & Animations
- [ ] API Agnostic Backends to expand to support Vulkan, Metal, WebGPU and more
- [ ] Procedural Skybox
    - [ ] Volumetric Clouds
- [ ] Package Manager (Packages partially implemented)
- [ ] Rendering Improvements
   - [ ] DOF, SSAO, SSR, TAA, Bloom, Screen-Space Decals, etc.
   - [ ] Transparency
   - [ ] Realtime GI
   - [ ] Lightmaps and Light Probes
   - [ ] Cascaded shadow mapping
- [ ] BepuPhysics v2
- [ ] Particle System
- [ ] Navmesh and AI Agents
- [ ] Terrain Engine
- [ ] Material Node Editor
- [ ] Visual Scripting
- [ ] Cross Platform
- [ ] Basic Networking Solution
- [ ] VR Support
- [ ] Basic 2D Support

See the [open issues](https://github.com/michaelsakharov/prowl/issues) for a full list of proposed features (and known issues).
<p align="right">(<a href="#readme-top">back to top</a>)</p>

# Contributing

🚀 **Welcome to the Prowl community! We're thrilled that you're interested in contributing.**

We're not too proud to admit it – we need your help. 🆘

Developing a game engine is a colossal task, and we can't do it alone. We need passionate developers, designers, testers, and documentation enthusiasts, people like you to help make Prowl the best it can be.

## How You Can Contribute

### Code Contributions

Whether you're a seasoned developer or just getting started, your code contributions are invaluable. We have a list of [open issues](https://github.com/michaelsakharov/prowl/issues) that you can tackle, or feel free to propose your own improvements.

### Bug Reports

Encountered a bug? We want to know! Submit detailed bug reports on our [issue tracker](https://github.com/michaelsakharov/prowl/issues) to help us squash those pesky bugs.

### Feature Requests

Have a fantastic idea for a new feature? Share it with us! Open a [feature request](https://github.com/michaelsakharov/prowl/issues) and let's discuss how we can make Prowl even better.

<!--Need a Documentation Site, Probably Hugo?-->
<!--
### Documentation

Documentation is crucial, and we could use your help to make ours more comprehensive and user-friendly. Contribute to the [docs](linktodocshere) and help fellow developers get the most out of Prowl.
-->

### Spread the Word

Not a developer? No problem! You can still contribute by spreading the word. Share your experiences with Prowl on social media, blogs, or forums. Let the world know about the exciting things happening here.

## Contributor Recognition

We're not just asking for contributors; we're asking for partners in this journey. Every small contribution is a step toward realizing Prowl.

All contributors will be acknowledged in our [Acknowledgments](#acknowledgments) section.

**Thank you for considering contributing to Prowl. Together, let's build something amazing!**
<p align="right">(<a href="#readme-top">back to top</a>)</p>

# Acknowledgments

- Hat tip to the creators of [Raylib](https://github.com/raysan5/raylib), It has shaved off hours of development time getting the engine to a useable state.
- Some ideas/code have been taken from the amazing 2D Engine [Duality](https://github.com/AdamsLair/duality).
- The great C++ [Arc Game Engine](https://github.com/MohitSethi99/ArcGameEngine), for some UI Inspiration
<p align="right">(<a href="#readme-top">back to top</a>)</p>
 
# License

Distributed under the MIT License. See `LICENSE.txt` for more information.
<p align="right">(<a href="#readme-top">back to top</a>)</p>

# Dependencies

### Runtime
- [Raylib](https://github.com/raysan5/raylib) via [Raylib-cs](https://github.com/ChrisDill/Raylib-cs) - Temporary
- [ImageMagick](http://www.imagemagick.org/) via [Magick.NET](https://github.com/dlemstra/Magick.NET)
- [ImGUI](https://github.com/ocornut/imgui) via [ImGUI.NET](https://github.com/ImGuiNET/ImGui.NET)
- [Newtonsoft](https://github.com/JamesNK/Newtonsoft.Json)
<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Editor

- [Assimp](https://github.com/assimp/assimp) via [Assimp.NET](https://bitbucket.org/Starnick/assimpnet)
<p align="right">(<a href="#readme-top">back to top</a>)</p>

# Screenshots
![Full Editor shot, Early in development, plenty of obvious bugs and issues :(](https://i.imgur.com/6Pbn7kU.png)

<p align="right">(<a href="#readme-top">back to top</a>)</p>