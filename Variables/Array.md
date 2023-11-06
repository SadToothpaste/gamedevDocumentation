An array variable is a variable that contains lots of other [[variables]] withing it in order. Depending on the order the variable are added into the array, their id will change if you wanna get a specific  variable that is within an array. It increments by 1 from left to right, starting from 0.

**Defining an array:**
```
var arrayName = [floatValue, stringValue, boolValue]
```

**Getting a specific array variable:**
```
arrayName[id]
```

**Shuffling an array:**
```
arrayName.shuffle()
```
This will shuffle the order of all the variables within the array.

**Adding a variable to an array:**
```
arrayName.insert(position_id, variableToInsert)
```

**Clearing an array:**
```
arrayName.clear()
```

**Filling an array with a variable:**
```
arrayName.fill(variable)
```