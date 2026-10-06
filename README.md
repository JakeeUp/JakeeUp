<div align="center">

# Jacob Fernandez

Gameplay and systems programmer · C++ · C# · Python

San Antonio, TX · Graduating December 2026

[![Portfolio](https://img.shields.io/badge/Portfolio-111111?style=flat&logo=vercel&logoColor=white)](https://www.jacobfernandez.dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jacobfernandezprogrammer/)
[![Email](https://img.shields.io/badge/Email-444444?style=flat&logo=gmail&logoColor=white)](mailto:jacob@jacobfernandez.dev)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=flat&logo=leetcode&logoColor=black)](https://leetcode.com/u/JakeUp/)

</div>

I'm finishing an accelerated B.F.A./M.F.A. in Game Programming at UIW. Most of what I build is combat systems and renderers, plus some backend services. I'm looking for gameplay or software engineering roles.

## Projects

### [Hack & Slash Combat System](https://github.com/JakeeUp/HackAndSlash-Combat-System)
`UE5` `C++`

DMC-style action combat in Unreal. Inputs pressed before the combo window opens are buffered and fire as soon as it does, so hitting a button a frame early still chains the combo. The windows themselves are set by animation notifies. There are [GIFs in the repo](https://github.com/JakeeUp/HackAndSlash-Combat-System#showcase).

### [OpenGL Rendering Engine](https://github.com/JakeeUp/Engine_OpenGLProject)
`C++17` `GLSL` `Lua` `ImGui`

A renderer and scene editor I wrote from scratch. Scenes are written in Lua, so changing one doesn't need a recompile. I measure frame cost with double-buffered `GL_TIME_ELAPSED` queries that close before ImGui draws, which keeps the editor UI out of the number. [Demos here](https://github.com/JakeeUp/Engine_OpenGLProject#features).

### [PlayGraph](https://github.com/JakeeUp/playgraph)
`Python` `FastAPI` `Redis` `arq`

A game log that saves your Steam playtime with a review at the moment you write it. A Locust load test took the public read path from 49 s p95 down to 41 ms. It has 116 tests, and `pip-audit` and `bandit` run on every commit.

[![Tests and security](https://github.com/JakeeUp/playgraph/actions/workflows/security.yml/badge.svg)](https://github.com/JakeeUp/playgraph/actions/workflows/security.yml)

### [TopDown Mechanics](https://github.com/JakeeUp/TopDown_Mechanics)
`Unity 6` `C#` `URP` `HLSL`

A shooter where you can switch between top-down and first person in the middle of a fight. A single raymarched fog volume works in both views, and two flashlight cones cut through it: a projected one for top-down and a true 3D one for first person.

### [Metal Gear Mechanics](https://github.com/JakeeUp/MetalGearMechanics_Unity)
`Unity` `C#` `NavMesh`

A rebuild of MGS1's stealth systems. Guards spot you with a vision cone checked by raycast, warn the guards around them, and go through scanning and searching when they lose you. It started as a class project in 2023, and I came back to it later to split the guard AI into separate state classes.

## Experience

- M.F.A. prototyping, University of the Incarnate Word (2024 to present). I work on gameplay systems and technical design for a turn-based horror game in Unreal, and our cross-functional team has shipped two prototypes and a final build.
- Teaching assistant, UIW Game Programming (Aug 2025 to May 2026). I taught C++ and Unreal to students coming from C# and Unity, wrote the labs and specs, and ran code review.
- UPGRADE Program representative, UIW (Nov 2022 to Nov 2025). I represented the Animation and Game Design department to prospective students and walked incoming high schoolers through the programming track and what the coursework actually involves.
- Triple A Programmer Award (2024)

<div align="center">

![C++17](https://img.shields.io/badge/C%2B%2B17-00599C?style=flat&logo=cplusplus&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=flat&logo=csharp&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Lua](https://img.shields.io/badge/Lua-2C2D72?style=flat&logo=lua&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Unreal Engine 5](https://img.shields.io/badge/UE5-0E1128?style=flat&logo=unrealengine&logoColor=white)
![Unity](https://img.shields.io/badge/Unity-222222?style=flat&logo=unity&logoColor=white)
![OpenGL](https://img.shields.io/badge/OpenGL-5586A4?style=flat&logo=opengl&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Perforce](https://img.shields.io/badge/Perforce-404040?style=flat&logo=perforce&logoColor=white)

[![Activity](https://github-readme-activity-graph-psi-gray.vercel.app/graph?username=JakeeUp&bg_color=00000000&color=0F69A6&line=0F69A6&point=0F69A6&area=true&hide_border=true&height=300)](https://github.com/JakeeUp)

</div>
