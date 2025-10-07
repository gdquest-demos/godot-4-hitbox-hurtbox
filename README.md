# Hit and hurt boxes

This demo shows how to work with what we call hit and hurt boxes.

To detect interactions in games, we generally use simple geometry: boxes, capsules, circles, polygons. In godot, we achieve that with area nodes.

You can use area nodes for many tasks like interacting with a door, a chest, collecting a pick-up, or dealing and receiving damage.

The role of a hit box is to deal damage to something that has one or more hurt boxes. The hit box represents the part of a weapon that deals damage while the hurt box represents the part of a character that can receive damage.

<!-- TODO: For a detailed guide to get you started with saving and loading in Godot, check out the GDQuest Library: [Interactions with hit and hurt boxes](https://gdquest.com/library/hitbox_hurtbox_godot4/) -->

## Controls

- <kbd>W</kbd><kbd>A</kbd><kbd>S</kbd><kbd>D</kbd>: move the sword.
- <kbd>Space</kbd>: attack.
