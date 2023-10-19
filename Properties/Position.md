"Position" is a [[Vector3]] variable with three values. These are "x", "y" and "z". They represent the exact coordinates your object is in the world. In 2D games however, you only have to worry about the first two values considering there is no third dimension for the z value to exist in.

**Getting the position of an object:**
```
objectReference.position
```

**Setting the position of an object in 2D:**
```
objectReference.position = Vector2(x, y)
```

**Setting the position of an object in 3D:**
```
objectReference.position = Vector3(x, y, z)
```