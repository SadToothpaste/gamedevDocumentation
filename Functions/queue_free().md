queue_free() is used to remove objects from the scene. Simply typing queue_free() will remove the object the script is attached to, but you can connect another object reference to it in which case it will delete that object instead.

Using queue_free() to delete self:
```
queue_free()
```

Using queue_free() to delete another object in the scene:
```
objectReference.queue_free()
```