# ses_2(counter, multiplier, and_use_dff)

## 1]COUNTER USING D-FF
#### This project implements a binary counter using D flip-flops in Verilog HDL, designed and simulated in Xilinx Vivado. The counter increments its value on each rising edge of the clock signal and is capable of counting through a predefined sequence (e.g., 3-bit or 4-bit range). D flip-flops are used as the basic building blocks to store and propagate the binary count values synchronously.

The design was tested using Vivado’s simulation environment to verify correct counting behavior and proper reset functionality. Each flip-flop stage captures the output of a defined logic function, forming a ripple or synchronous counter depending on configuration.

Below is the image for schematic counter using D-ff in Xilinx Vivado.

![counter](https://github.com/user-attachments/assets/ce0500bc-182f-41af-8a39-f4c4642315df)

## 2] 3-BIT MULTIPLIER USING HALF ADDER
#### This project implements a 3-bit binary multiplier using Half Adders and basic logic gates, written in Verilog HDL and simulated in Xilinx Vivado. The multiplier takes two 3-bit binary inputs and produces a 6-bit product through a combination of partial product generation and binary addition using Half Adders.

The architecture mimics the traditional method of multiplication, where each bit of one operand is multiplied with the other operand to form partial products, which are then summed using Half Adders to generate the final result.This project demonstrates how basic arithmetic operations like multiplication can be built from the ground up using fundamental logic components.

Below is the image for schematic 3-bit binary multiplier using Half Adders in Xilinx Vivado.

![mult](https://github.com/user-attachments/assets/b70dcd9a-cc50-4cee-82ad-076523df4d22)

## 3] AND GATAE USING D-FF
#### This project implements a basic 2-input AND gate using D flip-flops on an FPGA. Instead of using simple combinational logic, the design leverages sequential elements (D flip-flops) to demonstrate how basic logic functions can be constructed using storage elements. This approach provides an educational insight into the flexibility of digital design, showcasing how flip-flops—typically used for memory—can also be repurposed for logic under certain conditions.

The design was synthesized and tested on an FPGA board to validate its functionality. It accepts two input signals and produces the ANDed result after a clock cycle delay, due to the inherent behavior of flip-flops.The design was tested using Vivado’s simulation environment to verify correct counting behavior.

Below is the image for schematic AND Gate using Half D-FF in Xilinx Vivado.

![and](https://github.com/user-attachments/assets/b996eb04-da35-4649-b416-14cb6280455e)

