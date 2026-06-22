---
title: "Classes"
icon: "🍎"
created: 2024-12-08
updated: 2026-06-22
---

# Classes

s&box comes with a good amount of helper classes that simplifies working with various renderer features, such as lighting, decals, depth, envmaps, g-buffer, and many others. 

* 🌥️ [Ambient Light](/rendering/shaders/classes/ambientlight.md)
* * How to sample ambient light, DDGI/envprobe/lightmap probe/sky light priority
* 🔗 [Bindless API](/rendering/shaders/classes/bindless-api.md)
* * How bindless API works, how to assign a bindless texture or sampler from C# and read it from the shader
* 🎇 [Decals](/rendering/shaders/classes/decals.md)
* * Applying decals in your custom shaders, understanding the structure of decals structured buffer, and extra data byte address buffer, reading packed buffer data, helper functions
* 👀 [Depth](/rendering/shaders/classes/depth.md)
* * How to sample depth and get various data from it
* 🪩 [Dynamic Reflections](/rendering/shaders/classes/dynamic-reflections.md)
* * Adding support for dynamic reflections to your custom shader
* 🎨 [EnvMap](/rendering/shaders/classes/envmap.md)
* * How to sample environment map probe for your custom shader
* 🌁 [Fog](/rendering/shaders/classes/fog.md)
* * Applying fog and its separate effects, such as gradient fog, cubemap fog, and volumetric fog
* 🌍 [G-Buffer](/rendering/shaders/classes/g-buffer.md)
* * Everything you need to know about reading its contents, and writing to G-Buffer
* 💡 [Light](/rendering/shaders/classes/light.md)
* * Iterating all light sources in your custom shader, understanding light data, sampling shadows, light contribution types, and separatae directional light data   
* 🚝 [Motion](/rendering/shaders/classes/motion.md)
* 📉 [Procedural Effects](/rendering/shaders/classes/procedural-fx.md)
* * Optional library with procedural noises and patterns
* 🥢 [Screen Space Tracing](/rendering/shaders/classes/screen-space-tracing.md)
* 🕳️ [Screen Space Ambient Occlusion](/rendering/shaders/classes/ssao.md)
* ✂️ [Texture Sheets](/rendering/shaders/classes/texture-sheets.md)