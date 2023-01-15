# DAD-FPGA-exam 2022

## 3 State machiens 

### 3.1 Mealy vs Moore machine 
- Mealy machine use fewer state , because we can possibly merge more states, due to the input dependancy that allows several output values to be specified for the same state.
- Mealy machine respond faster - whenever the input changes for the same state , the output will follow (we do not have to wait for the state to update)
- Mealy machine may be transparent to glitches on inputs, ie. they will pass glitches from input to outputs directly.
insert flip-flop to input and output can prevent this .
- Moore machines are safer because they used registered values of the state.

## timing analysis 

https://www.youtube.com/watch?v=6D-w8mOttnE&t=247s

![image](https://user-images.githubusercontent.com/121833181/211170484-9b3c0a32-aa80-4012-bc60-713b10ccde04.png)
