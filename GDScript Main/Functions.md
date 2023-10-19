A function is a string of code you can rerun as many times as you want without rewriting any of the code. You are even able to add arguments and return values to modify the functions results. Each time you call a function it creates a new instance of it every single time, so you do not have to worry about calling too many at once.

**Defining a function:**
```
func functionName():
	print("function has been callled")
```

**Calling a function:**
```
functionName()
```

Function arguments let you input a value to alter the function when calling it, thus making it act different.

**Defining a function with arguments:**
```
func functionName(boolArgument = bool):
	if boolArgument == true:
		print("true")
	if boolArgument == false:
		print("false")
```

**Calling a function with arguments:**
```
functionName(true)
```

Functions with arguments are also able to have return variables. You can get and use these returned variables by setting a variable to a function call. When setting the  function you add a "->" after the brackets followed by a variable, defining what variable you want to return.

**Defining a function with a return type:**
```
func functionName(inputNumber = int) -> int:
	return inputNumber * 3
```

**Calling a function with a return type and setting it to a variable:**
```
var returnedVariable = functionName(10)
print(returnedVariable)
```

**Console result**
```
30
```