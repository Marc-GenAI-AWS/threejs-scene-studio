# Three.js Scene Studio

Procedural real-time worlds where each layer — sky, ground, camera, vegetation, fauna, effects — is
written by a small model fine-tuned on that one layer, and a render harness decides what ships.

**[Playable scenes and results →](https://marc-genai-aws.github.io/threejs-scene-studio/specialist-scenes/)**

This repository hosts the demo site only. The full recipe — golden scenes, contract generator, harness
and training pipeline — lives in
[Recipes/recipes/model-customization/procedural-scene-specialists](https://github.com/Marc-GenAI-AWS/Recipes/tree/main/recipes/model-customization/procedural-scene-specialists).

Sibling project: [the same recipe applied to Godot 4](https://marc-genai-aws.github.io/godot-game/specialist-scenes/).

## What is here

```
docs/                        GitHub Pages root (served from main /docs)
  index.html                 landing page
  specialist-scenes/
    index.html               the write-up + gallery
    worlds/*.cdn.html        seven hand-built reference worlds, each a single self-contained file
    scenes/*.html            four scenes composed by the specialist loop
    shots/                   stills used on the page
```

Every `.cdn.html` is self-contained — three.js comes from a CDN, there are no other assets, and you can
open one straight from disk.
