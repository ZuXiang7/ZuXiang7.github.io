---
layout: page
title: Red is The enemy
subtitle: 3rd year game project
cover-img:
  [
    "/assets/img/redistheenemy/redistheenemy_gif2.gif",
    "/assets/img/redistheenemy/redistheenemy_gif3.gif",
    "/assets/img/redistheenemy/redistheenemy_gif5.gif",
  ]
---

## Description

This is a 3D game project where we write a custom game engine primarily with `c++`, limited 3rd party libraries and rendering API. The project spans over 2 semester(6 months) and is completed in a group of 9.

## Role / What I worked on
For this project, I was the tech lead and I worked primarily on
 ### **Engine architecture** 
 - ECS
 - Templated
 - sparse sets
 - groups
 - delegates 
 - hierarchy
 - prefabs
 ### **Serialization** 
 - Binary serialization with [cereal](https://github.com/USCiLab/cereal)
 - Json serialization with [rapidjson](https://github.com/Tencent/rapidjson) 
 - reflection with [properties](https://gitlab.com/LIONant/properties)
 ### **Resource Management**
 - File manager
 - dds texture compression with [nvidia texture tools](https://developer.nvidia.com/nvidia-texture-tools-exporter) 
 - Fbx models with [assimp](https://github.com/assimp/assimp)
 ### **Renderer**
 - OpenGL
 - Deffered Shading
 - SMAA
 - PBR with IBL
 - Bloom
 - SSAO
 - Shadows
 - Instancing
 - Batching
 - Shader pipeline
 - particles
 ### **Embedding Scripting Language**
 - C#
 - [mono](https://www.mono-project.com/)
 ### **Editor**
 - [ImGui](https://github.com/ocornut/imgui)
 - Scene Graph
 - Inspector
 - Viewport
 - Profiler
 - File viewer


## What I learnt

For this project, I was responsible for developing multiple key features for the game engine, which helped me gained a lot more technical skills and knowledge compared to my other projects.

However, I believe the project could have done better if I did not need to develop this many key features.

In my opinion, the issue was that some of the programmer's programming efficiency was not on the same level, which in itself is not an issue as development teams often have programmers with different level of skill, but because we also did not conduct any code review or knowledge sharing, which led to a lot of issue such as bugs, code with poor performance, code that was hard to understand, or all of the above.

At that time, I felt the most efficient way of solving this issue was to either redo the code or take over the key feature completely.

In retrospect, I should have tried to convice my team the importance of code review and sharing our research so everyone had a better understanding of the codebase and have the ability to handle key features.

<p align = "center">
 <b>Screenshots of gameplay</b>
</p>
<p align = "center">
  <img src = "/assets/img/redistheenemy/redistheenemy_0.PNG" alt = "redistheenemy_png0" />
</p>
<p align = "center">
  <img src = "/assets/img/redistheenemy/redistheenemy_1.PNG" alt = "redistheenemy_png1" />
</p>
<p align = "center">
  <img src = "/assets/img/redistheenemy/redistheenemy_2.PNG" alt = "redistheenemy_png2" />
</p>
<p align = "center">
  <img src = "/assets/img/redistheenemy/redistheenemy_3.PNG" alt = "redistheenemy_png3" />
</p>
<p align = "center">
  <img src = "/assets/img/redistheenemy/redistheenemy_4.PNG" alt = "redistheenemy_png4" />
</p>
<p align = "center">
  <img src = "/assets/img/redistheenemy/redistheenemy_5.PNG" alt = "redistheenemy_png5" />
</p>

<p align = "center">
 <b>GIFs of gameplay</b>
</p>
<p align = "center">
 <b>! Image quality and framerate severely deteriorated due to limitations of GIFs !</b>
</p>
<p align = "center">
  <img src = "/assets/img/redistheenemy/redistheenemy_gif2.gif" alt = "redistheenemy_gif2" />
</p>
<p align = "center">
  <img src = "/assets/img/redistheenemy/redistheenemy_gif3.gif" alt = "redistheenemy_gif3" />
</p>
<p align = "center">
  <img src = "/assets/img/redistheenemy/redistheenemy_gif5.gif" alt = "redistheenemy_gif5" />
</p>

[Download](https://games.digipen.edu/games/red-is-the-enemy)
