# Awesome-3D-Character-Rigging-Animation
# Awesome-3D-Character-Rigging-Animation

# Top 3D Character Rigging & Animation Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Automated 3D Character Rigging, Skin Weighting, AI Motion Capture & Skeletal Animation Suites*  
**Last updated: November 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **3D Character Rigging & Animation**. These tools automate skeleton placement and skin weight painting for 3D character meshes, capture full-body and facial motion from video or sensors, synthesize animations from text prompts, and export rigged models for Blender, Unity, Unreal Engine, and Godot.

**Examples** include Mixamo, ActorCore, Plask, DeepMotion, Rokoko Studio, Kinetix, Move.ai, Cascadeur, Wonder Dynamics (Autodesk Flow Studio), AnyWorld, and mvschwarz/openrig (the category leaders). 

**Open-source emphasis**: This section is heavily expanded with every major active project for local autoregressive auto-rigging, browser-based skeletal binding, modular Maya/Blender rigging frameworks, markerless video-to-mocap, and text-to-motion generation — ideal for indie game developers, technical artists, 3D animators, and researchers building transparent character pipelines.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Adobe Mixamo](https://www.mixamo.com/)**  
  Cloud-based automatic 3D character rigging service and extensive library of downloadable motion-captured animations ready for games and film.

- **[Reallusion ActorCore](https://reallusion.com)**  
  Cloud motion library and AccuRIG browser/desktop platform providing automated humanoid bone placement, skin weighting, and AAA mocap animations.

- **[Plask](https://plask.ai)**  
  Browser-based AI motion capture and 3D keyframe animation editor for extracting, cleaning, and retargeting video motion directly onto rigged characters.

- **[DeepMotion](https://deepmotion.com)**  
  AI-powered cloud markerless motion capture suite converting 2D videos into physics-simulated full-body, hand, and facial 3D character animations.

- **[Rokoko Studio](https://rokoko.com)**  
  All-in-one motion capture software and Rokoko Vision cloud platform supporting inertial mocap suits, smartgloves, and AI webcam/video tracking.

- **[Kinetix](https://kinetix.tech)**  
  No-code cloud AI platform and SDK for generating, auto-rigging, and integrating user-generated 3D character emotes into games and virtual worlds.

- **[Move.ai](https://move.ai)**  
  Multi-camera and single-camera markerless AI motion capture platform delivering studio-grade skeletal character animations without physical suits.

- **[Cascadeur](https://cascadeur.com)**  
  Physics-assisted 3D keyframe animation software with cloud/AI-powered AutoPosing, center-of-mass trajectory editing, and secondary motion tools.

- **[Wonder Dynamics (Autodesk Flow Studio)](https://wonderdynamics.com)**  
  Cloud AI VFX studio that automatically detects actor performance from live-action video, tracks cameras, and replaces actors with rigged CG characters.

- **[AnyWorld](https://anyworld.ai)**  
  Cloud AI 3D world and interactive character animation platform enabling rapid character rigging, motion generation, and game asset deployment.


## Open-Source GitHub Projects

- **[UniRig (VAST-AI-Research)](https://github.com/VAST-AI-Research/UniRig)**  
  SIGGRAPH 2025 open-source unified auto-rigging framework using large autoregressive models to predict valid skeleton trees and per-vertex skinning weights for diverse 3D meshes.

- **[Mesh2Motion](https://github.com)**  
  Free, open-source browser-based Mixamo alternative enabling quick skeletal rigging, weight painting, and 40+ pre-built animations for bipeds, quadrupeds, and birds with GLB export.

- **[Roboticela/Animator](https://github.com/Roboticela/Animator)**  
  Cross-platform open-source (`AGPL-3.0`) 3D model animation studio built with Tauri, Rust, and Three.js for inspecting bones, authoring keyframe clips, applying procedural humanoid motions, and exporting GLB.

- **[Puppeteer (Seed3D)](https://github.com/Seed3D/Puppeteer)**  
  NeurIPS 2025 open-source framework for automatic 3D skeletal rigging, skinning weight generation, and video-guided differentiable animation exportable to FBX.

- **[mGear](https://github.com)**  
  Industry-proven open-source (`MIT`) modular rigging and animation framework for Autodesk Maya featuring Shifter guide-based biped/quadruped rigs, Synoptic pickers, and post-scripts.

- **[Blender (Rigify & Armature System)](https://github.com)**  
  Flagship open-source (`GPL-2.0+`) 3D creation suite featuring Rigify modular character rigging, Bendy Bones, automatic heat-map skinning, IK/FK snapping, and NLA animation blending.

- **[auto-rig-web](https://github.com/nff747/auto-rig-web)**  
  Zero-click autonomous 3D mesh rigging engine running a browser-local ONNX vision model with Web Workers for instant procedural character rigging.

- **[autorig-workbench](https://github.com)**  
  Standalone open-source (`GPL-3.0`) auto-rigger for generated 3D models combining headless Blender execution, JSON rig definitions, automated audits, and a 3D web results viewer.

- **[AutoTPose](https://github.com)**  
  Open-source Python and Blender add-on for automatically rigging humanoid GLB/FBX characters and converting them into clean, animation-ready T-poses.

- **[Poseforge](https://github.com/wolfgangjblack/poseforge)**  
  Local-first browser character studio for rigging 3D meshes, posing skeletons via interactive 3D gizmos or 2D stick-figure sketches, and exporting animated GLBs.

- **[vid2anim](https://github.com/mehulcode12/vid2anim)**  
  Open-source (`MIT`) AI motion capture and universal character retargeting studio with a Blender add-on supporting Mixamo, VRM, Rigify, Unreal Engine Mannequins, and raw unrigged meshes.

- **[HyMotion (Tencent Hunyuan)](https://github.com)**  
  Open-source Diffusion Transformer and flow-matching model generating natural 3D character skeletal animations from text prompts across sports, combat, and daily actions.

- **[FreeMoCap](https://github.com)**  
  Free, hardware-agnostic open-source (`AGPL-3.0`) multi-camera markerless motion capture system outputting rigged 3D skeletal animations for Blender and game engines.

- **[adamscript/Auto-Rigger](https://github.com/adamscript/Auto-Rigger)**  
  Open-source Autodesk Maya auto-rigging toolkit generating humanoid IK/FK rigs, reverse-foot controls, and dynamic custom controller picker GUIs from guide markers.

- **[mvschwarz/openrig](https://github.com/mvschwarz/openrig)**  
  Open-source (`Apache-2.0`) multi-agent CLI/YAML orchestration harness referenced alongside rigging ecosystems (note: specifically coordinates AI coding agent teams rather than 3D mesh rigging).

### Additional Strong Open-Source Options

- **[UniRigMCP](https://github.com)** and **[modly-skintokens-extension](https://github.com)** for local GPU auto-rigging via MCP servers and SkinTokens/TokenRig workflows.
- **[RigNet](https://github.com)** and **[Neural Blend Shapes](https://github.com)** for deep-learning skeleton prediction, skin weight estimation, and pose-space deformation.
- **[FACSvatar](https://github.com)** and **[OpenSeeFace](https://github.com)** for open-source FACS facial blendshape rigging and real-time webcam head/expression tracking.
- **[MakeHuman](https://github.com)** and **[MPFB2](https://github.com)** for parametric 3D character mesh creation pre-rigged with Game Engine, Mixamo, and Rigify skeletons.
- **[Godot Skeleton3D / IK](https://github.com)** and **[o3de EMotion FX](https://github.com)** for open-source runtime inverse kinematics, animation state machines, and skeletal blending.

**Frameworks for building custom systems**: Combine **UniRig** or **Mesh2Motion** with **Blender (Rigify)**, **Roboticela/Animator**, and **vid2anim** (or **HyMotion**) for end-to-end local 3D character rigging and animation pipelines.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Neural auto-rigging models (such as UniRig and Puppeteer) require compatible PyTorch/CUDA environments and may need manual weight cleanup around complex clothing or fingers.
- Verify weight and dataset licenses (e.g., `MIT`, `Apache-2.0`, `GPL-3.0`, or non-commercial research terms) before shipping rigged characters in commercial games.

---

**Made for 3D character artists, technical artists, riggers, and game developers.**  
Let's make 3D character rigging and animation more open, automated, and accessible.
