# Map Editor

To edit a map, run `python3 editor.py`

- Use WASD keys to move the camera.
- Use the mouse scroll wheel to select specific terrain.
- Use the mouse to place tiles, right-click to undo.
- Press 'g' to place one tile at a time.
- Press 't' for auto-tile function.
- Press 'o' to save the map.

## Play Game!

Run `python3 game.py`

- Use WASD to move.
- Explore your map!

## Progress and Notes

### Scene
- Background image and player loaded.
- Clouds animation looped, done! (these clouds were references, adjust art accordingly).

### Player Movement
- Done!
- Loaded reference images for idle, run, and jump.
- Camera offset implementation according to player movement.

### Animation Class
- Done!
- Idle, run, and jump images are looped.
- Camera offsets are set accordingly.
- Animation images are flipped when player faces a certain direction (left or right).

### Level Editor
- Done!
- Primitive approaches (0 and 1 to represent air/ground).
- Using JSON (although JSON has no support for tuples).
- Save and load functions done! Able to load into the created map.
