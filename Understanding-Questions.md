# Understanding Questions:
1. What are the steps of execution from the pressing of the 1 button to the rendering of our updated value? List what part of the code excutes for each step.
* The user presses the 1 button.
* 
...
-UI interaction (button click) causes event handler to go off
-event handler dispatches action
-action gets to reducer and proper state manipulation occurs
-reducer renders new state and updates to UI

* TotalDisplay shows the total plus 1.
