# session1(adder,encoder,mux)
## 1] FULL ADDER

#### This project implements a Full Adder on an FPGA using Verilog HDL. A Full Adder is a fundamental combinational circuit that computes the sum of three binary inputs: A, B, and Carry-In (Cin), producing a Sum and a Carry-Out (Cout). It is a critical building block in digital arithmetic circuits like adders, ALUs, and processors.

The design module was verified through simulation and synthesized using Xilinx Vivado, ensuring accurate logic synthesis and hardware mapping. This project serves as a foundational step toward more complex digital systems.

The image shown below is the schematic representation of Full adder in Xilinx Vivado tool.

![Screenshot 2025-05-24 234550](https://github.com/user-attachments/assets/2e02f42a-7f1a-4166-a7b3-33de47cfd95d)

## 2] PRIORITY ENCODER

#### This project implements a priority encoder using Verilog HDL, designed and simulated in Xilinx Vivado. A priority encoder is a combinational logic circuit that outputs the binary representation of the highest-priority active input. It plays a key role in applications such as interrupt controllers, input selection systems, and resource arbitration where prioritization is required.

The Verilog module was created to detect the highest-order '1' among the input bits and generate the corresponding encoded output. The design was thoroughly verified using Vivado’s simulation environment to ensure correct behavior under all possible input combinations.

The image shown below is the schematic representation of priority encoder in Xilinx Vivado tool.

![encoder](https://github.com/user-attachments/assets/bfc68017-5a26-47e3-bff8-c76ba8e1434b)

## 3] 2x1 MUX
#### This project demonstrates the implementation of a 2x1 multiplexer (MUX) using Verilog HDL, simulated using Xilinx Vivado. A 2x1 multiplexer is a basic digital component that selects one of two input signals based on a single select line and routes it to the output. It serves as a fundamental building block in data routing, control logic, and processor architectures.

The design was written in Verilog and verified through behavioral simulation in Vivado

The image shown below is the schematic representation of 2x1 MUX in Xilinx Vivado tool.

![mux](https://github.com/user-attachments/assets/ca35339a-4eef-442f-b89d-7ed416b7ae60)

