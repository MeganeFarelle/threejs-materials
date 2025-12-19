# Three.js Materials Playground

This project explores the main built-in materials available in Three.js, following the **Three.js Journey** course by Bruno Simon.

## 🚀 What’s covered

- MeshBasicMaterial
- MeshNormalMaterial
- MeshMatcapMaterial
- MeshDepthMaterial
- MeshLambertMaterial
- MeshPhongMaterial
- MeshToonMaterial
- MeshStandardMaterial
- MeshPhysicalMaterial

## 🧱 Features

- Shared material across multiple meshes (sphere, plane, torus)
- Texture loading and color space management (sRGB)
- Lighting vs non-lighting materials
- Environment maps using HDR (RGBELoader)
- PBR workflow (metalness, roughness, normal maps, AO maps)
- Debug controls with lil-gui
- Advanced physical effects:
  - Clearcoat
  - Sheen
  - Iridescence
  - Transmission

## 🛠️ Tech Stack

- Three.js
- Vite
- lil-gui

## ▶️ Run locally

```bash
npm install
npm run dev
