[[todo]]

**The below came mostly from an LLM and should be edited**

(SSI) A computational model that emphasizes [[deterministic execution]], state-based execution. In the context of [[pallas]], the SSI is designed to ensure that every action taken by the system is predictable and reproducible.

1. **Deterministic Execution**: In an SSI, the output and the new state are entirely determined by the current state and the input. This means that given the same input and initial state, the system will always produce the same output and end state. This predictability is crucial for reliability and debugging.

2. **State Management**: The state of the system is a snapshot of all relevant information at a given point in time. In an SSI, the state is updated only through defined functions, ensuring that state transitions are controlled and traceable.

3. **Persistence**: The system's state is persistent, meaning that it is saved and can be restored across different sessions or executions. This persistence is managed automatically by the SSI ([[orthogonal persistence]]), which means developers do not need to handle state-saving manually.

4. **Function-Based**: The core of an SSI is the [[operating function]], which takes the current state and an input, processes them, and returns a new state and an output. This function is deterministic and [[stateless]] in the sense that it relies solely on its inputs to produce outputs.