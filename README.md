# 🪶 Feather Atlas — 3D Living Field Guide

An interactive 3D WebGL bird specimen field guide curated by **Ajay Saini** ([ajaynxt.com](https://ajaynxt.com/)).

🌐 **Live Experience:** [ajaynxtbirds.com](https://ajaynxtbirds.com/)  
📦 **Repository:** [github.com/ajaynxt/ajaynxt-birds](https://github.com/ajaynxt/ajaynxt-birds)

---

## ✨ Features

- **Full 18 Bird Species in True 3D:**
  - Every single bird species features an authentic, volumetric 3D model (`.glb`) generated via Blender from high-resolution field artwork.
  - Interactive 360° rotation with inertia physics and touch/drag controls.
  - Smooth camera zooming, double-click to reset, and directional step buttons.
- **Dynamic Lighting Modes:**
  - Day / Dusk ambient lighting toggle with material specular highlights and shadows.
- **Museum Focus Mode:**
  - Distraction-free full-stage inspection view with high-magnification close-up lens detail.
- **Instant Search & Category Filtering:**
  - Real-time search across species names, scientific names, families, diets, and habitats.
  - Quick taxonomy category filters: *Featured, Songbirds, Kingfishers, Owls, Hummingbirds, Raptors, Waders*.

---

## 🦅 Included Species

1. **Kingfisher** (*Alcedo atthis*)
2. **Hoopoe** (*Upupa epops*)
3. **Indian Peafowl** (*Pavo cristatus*)
4. **Greater Flamingo** (*Phoenicopterus roseus*)
5. **Great Hornbill** (*Buceros bicornis*)
6. **Barn Owl** (*Tyto alba*)
7. **Golden Eagle** (*Aquila chrysaetos*)
8. **Scarlet Macaw** (*Ara macao*)
9. **Keel-billed Toucan** (*Ramphastos sulfuratus*)
10. **Ruby-throated Hummingbird** (*Archilochus colubris*)
11. **Emperor Penguin** (*Aptenodytes forsteri*)
12. **Sarus Crane** (*Antigone antigone*)
13. **European Robin** (*Erithacus rubecula*)
14. **Painted Stork** (*Mycteria leucocephala*)
15. **Peregrine Falcon** (*Falco peregrinus*)
16. **Grey Heron** (*Ardea cinerea*)
17. **Superb Lyrebird** (*Menura novaehollandiae*)
18. **Scarlet Ibis** (*Eudocimus ruber*)

---

## 🛠️ Tech Stack

- **Three.js** (v0.170.0) + WebGL 2.0
- **GLTFLoader**, **DRACOLoader**, **MeshoptDecoder**
- **Blender 5.2 Python Pipeline** (Automated volumetric 3D mesh & GLB generation)
- Vanilla CSS Design System with responsive mobile layouts

---

## 🚀 Running Locally

```bash
# Clone the repository
git clone https://github.com/ajaynxt/ajaynxt-birds.git
cd ajaynxt-birds

# Start any local HTTP server
python3 -m http.server 8000
# Open http://localhost:8000 in your browser
```

---

*Curated with precision by Ajay Saini — Creative developer, UI/UX designer & video editor.*
