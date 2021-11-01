# Understanding Questions:

1. What are the steps of execution from the pressing of the 1 button to the rendering of our updated value? List what part of the code excutes for each step.

- The user presses the 1 button.
- eventhandler fires
- dispatches the action addOne
- reducer accepts prev state and the action payload
- adds one to state
- TotalDisplay shows the total plus 1.
