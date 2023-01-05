# DAD-FPGA-exam 2022

## 3 State machiens 

### 3.1 Mealy vs Moore machine 
- Mealy machine use fewer state , because we can possibly merge more states, due to the input dependancy that allows several output values to be specified for the same state.
- Mealy machine respond faster - whenever the input changes for the same state , the output will follow (we do not have to wait for the state to update)
- Mealy machine may be transparent to glitches on inputs, ie. they will pass glitches from input to outputs directly.
insert flip-flop to input and output can prevent this .
- Moore machines are safer because they used registered values of the state.


### 3.2 Explain what is one-hot state encoding, what are the benefits and why this type of encoding is well suited for FPGA implementation.

### 3.3 state machines use Flip-Flops to store the value of current state variables. Explain why?


