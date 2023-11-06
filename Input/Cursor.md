There are many properties and functions you can apply to the players cursor in GDScript, below are some of the most important and most used ones.

**Changing the cursor position:**
```
Input.warp_mouse(Vector2(x, y))
```

**Getting the cursors position on the screen:**
```
get_global_mouse_position()
```

**Bool for mouse button presses**
```
Input.is_mouse_button_pressed(MOUSE_BUTTON_LEFT)
```
In this case, the left mouse button is an example and can be replaced with whatever you'd like.