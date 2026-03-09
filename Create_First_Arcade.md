# Create First Arcade

You can create an arcade machine by using the prefab located at:

IronStudio/Arcade/Prefab/Empty

Drag the prefab into your scene.

The arcade machine uses several materials:

1. Base Body (Color)
2. Side Panels (Texture)
3. Logo (Texture)
4. Control Pad (Color)

The remaining materials are only used for borders and decorative parts.

---

## Important Components

### ArcadeBehaviour
This component controls the main arcade functionality such as starting the game, restarting, and exiting the arcade.

### ArcadeRef
This component only stores references used by the arcade system.

### ArcadeInputs
This is one of the most important components. It manages the arcade input system and connects buttons and joysticks.

### JoystickBehaviour and ButtonBehaviour
These components handle interaction with the arcade joystick and buttons.

More details about these components will be explained later.

---

[Next: Create First Game](Create_First_Game.md)