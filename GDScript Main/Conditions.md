Conditions are one of the most important part of coding. As the name implies, they are used to run code only under certain specific conditions. Most commonly variables are used in conditions, to see if they are at a certain value, within a range of values, etc.

[[Operators]] are very important to learn and remember when using conditions. Its the symbols you add between the two values in the condition to represent what the condition needs to meet in order to be true.

**A basic if statement:**
```
if variable == value:
	print("run code")
```

**An if statement with several conditions needing to be met:**
```
if variable == value && variable2 == value:
	print("run code")
```
The "&&" operator is used in the case of several conditions needing to be met. Its what separates the conditions from each other and can be used an unlimited amount of times in a single condition.

**An if statement with several conditions, with only one needing to be met:**
```
if variable == value || variable2 == value:
	print("run code")
```
The "||" operator, also known as the "or" operator is used in case you only want one of the several conditions to be needed to be met in order for the if statement to run.