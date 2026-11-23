# Zahrae Mourid — 3D journey (realistic build)

Run locally: `npx serve .` (or any static server), then open http://localhost:3000

## Drop in the real character
1. Export a rigged, realistic model as GLB with Mixamo-style bone names
   (Hips, Spine, LeftUpLeg, LeftLeg, LeftFoot, LeftArm, LeftForeArm, LeftHand, Head ...).
   Mixamo, Avaturn and Character Creator exports all work.
2. Save it as `assets/zahrae.glb`. The mannequin hides automatically and the model
   gets the skate pose (two-bone IK feet on the board, arms for balance, head turned to the road).
3. Optional, one model per outfit: fill `OUTFIT_MODELS` at the top of the script,
   e.g. `{ meknes:'assets/zahrae-djellaba.glb' }`.
   Without it, meshes whose name contains dress/kaftan/cloth/skirt are tinted to the outfit colour.
