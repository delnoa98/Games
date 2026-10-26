# QuickScope Ops — credits

## 3D models
Sniper rifles, the M110/Dragunov/WA2000 base rifles, the enemy rifle, scope and bipod come from
**Quaternius — Ultimate Guns Pack**, released under **CC0 1.0** (public domain).
https://quaternius.com/packs/ultimategun.html · https://poly.pizza/bundle/Ultimate-Guns-Pack-cpgUfI4t2F

| File | Original model |
| --- | --- |
| models/intervention.glb | Sniper Rifle (variant 5) |
| models/m40.glb | Sniper Rifle (variant 1) |
| models/l115.glb | Sniper Rifle (variant 3) |
| models/barrett.glb | Sniper Rifle (variant 4) |
| models/m110.glb | Assault Rifle (variant 2) |
| models/svd.glb | Assault Rifle |
| models/wa2000.glb | Bullpup |
| models/enemy_rifle.glb | Assault Rifle (variant 4) |
| models/scope.glb, models/bipod.glb | Scope, Bipod |

## Sound
- Gunshots are built from two free sniper rifle recordings supplied by the game's owner, reshaped
  per rifle (pitch, EQ, layering, saturation, tail length) with suppressed variants.
- The initial muzzle-blast crack and the supersonic "crack" are generated with **PyGunShot**
  (Hüseyin Hacıhabiboğlu, MIT License) — https://github.com/metu-sparg/pygunshot
- Bolt, magazine, casing, dry-fire and impact sounds are synthesized.

## Code
- **three.js r128** and **GLTFLoader** (MIT License, © three.js authors) — `lib/`, see `lib/THREE-LICENSE.txt`.

Everything else (game code, maps, camos, UI) was made for this game.
