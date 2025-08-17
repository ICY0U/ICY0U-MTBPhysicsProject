# MTBPhysicsProject

A self-contained Godot 4.x mountain bike controller with manuals (by leaning back), bunny hops, suspension feel, WASD + controller support, and a simple test level.

## Controls

Keyboard:
- Pedal/accelerate: W or Up
- Brake/reverse: S or Down
- Steer: A/D or Left/Right
- Manual (lean back): Hold S
- Bunny Hop: Space (best after leaning back)
- Restart: R
- Toggle mouse capture: Esc

Controller (typical Xbox layout):
- Pedal: RT
- Brake: LT
- Steer: Left stick (X)
- Manual (lean back): Pull left stick down
- Bunny Hop: A
- Restart: Y
- Toggle mouse capture: Menu/Options

## How to run
- Open this folder in Godot 4.x
- Run main.tscn

Notes:
- This project uses only built-in meshes and collision shapes (no external assets), so it should import without warnings.
- You can tweak handling in scenes/BikePlayer.gd (accel, drag, lean strength, hop power, etc.).
