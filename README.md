Try it here: https://framer-3d-viewer.vercel.app/

# 3D GLB Viewer

Minimal static Three.js viewer — no framework. Fills viewport, loads a GLB model, OrbitControls, basic lighting.

## Files

- **index.html** — Full-viewport page and canvas
- **main.js** — Three.js scene, OrbitControls, GLTFLoader, lighting, resize
- **bag.glb** — Model (hardcoded path in `main.js`)

## Local dev

```bash
npm run dev
```

Opens at `http://localhost:3000` (or next port). Use `/bag.glb` for the model.

## Change the model

Edit `main.js`: set `GLB_PATH` to your path (e.g. `"/your-model.glb"`) and add the file to the project root (or adjust path).
