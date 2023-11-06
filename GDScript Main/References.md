References are one of the most important things to learn when coding in any game engine. "Getting a reference" simply means getting access to the other nodes and [[variables]] in your scene within your script. There are very many ways to get references, below are some of the most common.

**Using the $ operator:**
```
var objectReference = $nodeName
```
The $ operator is a type of directory getter, so if you drag the node you want to get a reference to into your script it will automatically create a directory to it from your current script. This directory is what you want to set your variable to in order to get a reference to that node. If you wanna define the variable at the top of your script, within your class and as soon as the script is ready, remember to add the @onready annotation right before declaring the variable.