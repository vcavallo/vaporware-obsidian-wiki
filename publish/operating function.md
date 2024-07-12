[[todo]]

Similar in responsibility to an [[operating system]], an "Operating Function" or **OF** is a [[pure]] function that, given a state and an input, produces a new state and an output. 

In contrast to traditional OSes, an OF is [[deterministic execution|deterministic]]  and ensures that the system's behavior is entirely predictable based on its inputs and current state

```
(NewState, Output) = OperatingFunction(CurrentState, Input)
```