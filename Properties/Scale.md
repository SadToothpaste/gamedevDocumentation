"Scale" is a [[Vector3]] variable with three values. These are "x", "y" and "z". They represent the size of your object relative to its parent. In 2D games however, you only have to worry about the first two values considering there is no third dimension for the z value to exist in.

**Getting the scale of an object:**
```
objectReference.scale
```

**Setting the scale of an object in 2D:**
```
objectReference.scale = Vector2(x, y)
```

**Setting the scale of an object in 3D:**
```
objectReference.scale = Vector3(x, y, z)
```