Variables are a way to store data. This could be player statistics, the amount of levels passed, the main characters name or even just if an object has been touched or not. There are several different types of variables, all with their different uses.

Depending on where you define your variable, that is where it would be accessible. If you define a variable right under the "extends" line at the top of the script, the variable will be accessible everywhere in the script. But if you were to define it within a function, it would only be accessible within that function.

If you want to get a variable from another script you can use the object that the variable is attached to followed by the get() function and then the variable name. Example is below:
```
objectReference.get("variableName")
```

**[[Array]]**
-Contains several other variables in a list/order.

**[[Bool]]**
-Contains a value that is either "true" or "false".

**[[Float]]**
-Contains a number with optionally a decimal.

**[[Int]]**
-Contains a whole number, is unable to handle decimals.

**[[String]]**
-Contains a string of text

**[[Vector2]]**
-Contains two variables

**[[Vector3]]**
-Contains three variables