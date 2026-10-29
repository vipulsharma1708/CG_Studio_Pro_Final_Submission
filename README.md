# CG Studio Pro — Interactive 3D Modeling & Computer Graphics Lab

## Final-submission version
This is a polished browser-based Computer Graphics project designed for a 7th-semester B.Tech CSE lab presentation.

### Highlights
- Professional dark "3D editor" UI
- Primitive library: Cube, Sphere, Cylinder, Cone, Torus, Plane
- Interactive X/Y/Z translation
- X/Y/Z rotation
- Uniform scaling
- Drag-to-move and Shift+drag-to-rotate
- Mouse wheel zoom/scale
- Wireframe rendering mode
- Lighting control
- Auto-rotation
- Isometric, front and top presets
- Object inspector with live values
- Scene statistics: vertices, faces, triangles
- JSON scene export
- CG Concepts modal for viva/presentation
- Responsive layout
- No npm, Maven, Java or external dependency required

## Run
### VS Code + Live Server
1. Extract the ZIP.
2. Open the folder in VS Code.
3. Right-click `index.html`.
4. Select **Open with Live Server**.

### Direct
You can also open `index.html` directly in Chrome/Edge.

## Presentation demo
1. Select Cube.
2. Move it on X/Y/Z.
3. Rotate X, Y and Z.
4. Scale it.
5. Turn on Wireframe.
6. Change lighting.
7. Try Sphere/Torus/Cylinder.
8. Demonstrate drag and Shift+drag.
9. Show the vertex/face/triangle statistics.
10. Open "CG Concepts" and explain the relationship between primitives, transformations and rendering.

## Viva points
- Translation changes position using coordinate displacement.
- Rotation changes orientation around an axis.
- Scaling changes size.
- Wireframe represents geometry using edges.
- Solid rendering represents filled surfaces.
- Lighting changes the perceived intensity of the rendered object.
- Perspective projection makes objects appear smaller with distance; this project uses a visual perspective-style viewport.
- The scene inspector exposes the parameters that drive the transformation pipeline.

## Note
The current build uses a dependency-free browser visualization so it is extremely easy to run. For a future research-level extension, the same UI can be connected to WebGL/Three.js with actual vertex buffers, transformation matrices, depth testing, normals, textures, camera orbit and OBJ/GLTF import.
