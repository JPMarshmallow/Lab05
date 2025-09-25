# Lab 05 - Combinatorial Logic

In this lab, you’ve learned real world applications of digital logic, as well
as how to assemble your own Verilog modules. In addition, you’ve learned how
the constraints file maps your inputs and outputs to real pins on the FPGA.

## Rubric

| Item | Description | Value |
| ---- | ----------- | ----- |
| Summary Answers | Your writings about what you learned in this lab. | 25% |
| Question 1 | Your answers to the question | 25% |
| Question 2 | Your answers to the question | 25% |
| Question 3 | Your answers to the question | 25% |

## Summary
  * We worked with combinaatorial logic where an output of one circuit (circuit_a) became an input for another circuit (circuit_b)
  * We learned how the constraints file maps the switches and leds so that we may use them in our modules and on the board when it is programmed.
  * We got more practice simplifying boolean equations with kmaps

## Lab Questions

### 1 - Explain the role of the Top Level file.
  * The top level instantiates the input switches and output LEDs then those switches and their input name are passed in to the other modules like circuit_a 
  * The top is the module that gets synthesized into the board.
### 2 - Explain the function of the Constraints file.
  * The constraints file matches the switches and leds to the pins on the FPGA so that we may be able to use the switches and leds in our design and modules.
### 3 - Was the selection of Minterm and Maxterm correct for each circuit? What would you have chosen?
  * Regardless of the selection of using minterms or Maxterms, a valid boolean equation will be generated for the circuit. Therefore both mnterms and Maxterms may be used and neither is explicitly correct.
