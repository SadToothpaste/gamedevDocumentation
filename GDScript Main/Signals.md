Signals are a very useful built in feature that makes it easier for different nodes to communicate between each other. Every node type has different signal outputs. But in general, a signal is something that will activate a function in another script when it is triggered. What triggers the function is completely dependant on the node type and signal that you use.

Attached below is an example on how signal works. There are two nodes in the scene. A button and a Sprite2D.

![[SignalExample1.png]]

The "button" node has several built in signals, I am using pressed() which activates whenever the button is pressed. When creating a signal you can choose which object you want to attach it to. The object must have a script.

![[SignalExample2.png]]

When turning on a signal and selecting where you want its output to be, there will be a new function created in that script. Inside you can place whatever code you would like, in my case I just made the sprite turn red.

![[SignalExample3.png]]

Here's an example of the final result:

![[SignalExample4.png]]
![[SignalExample5.png]]