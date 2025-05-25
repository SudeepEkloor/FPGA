# SES_3

## 1] synthesis 8 i/p function & find number of slices

![8_ip_function](https://github.com/user-attachments/assets/f4707d74-1ef4-442f-9096-eedff69a0309)

![447239501-fca03a49-0845-48a5-ab75-9e0a0c726c83](https://github.com/user-attachments/assets/33222c1f-7bba-4f48-a1a7-85c239bbc5bb)

#### In above pictures we can see that when we implement a 8 input function we get 2 slices.

## 2] implement negative edge detector and positive edge detector and simulate
#### I implemented a positive edge detector on an FPGA to detect rising edges of a digital input signal. The design uses a simple synchronous logic approach where the current and previous states of the signal are compared on each clock cycle. When the current signal is high and the previous state is low, a rising edge is detected. This is indicated by a one-clock-cycle pulse on the output signal. The design was coded in Verilog and synthesized for the target FPGA device, ensuring compatibility with real-time hardware operation.

The primary application of a positive edge detector is in event detection, such as button presses, pulse counting, or triggering control logic only on transitions. Unlike a simple level detector, this edge detector responds only when a transition occurs, reducing unnecessary processing.

![n_edge](https://github.com/user-attachments/assets/cbe3d5f3-37da-4fbc-869f-bc2bce9a1e70)

![image](https://github.com/user-attachments/assets/c8d05cd7-a030-4855-896b-d7ac914422a6)

## 3] WRITE THE I/O VERILOG CODE FOR SPI CONTROLLER
module spi_contrller(pclk_i,prst_i,paddr_i,pwrite_i,pwdata_i,prdata_o,penable_i,pready_o,psel_i,sclk,sclk_in,mosi,miso,ssel_o); input pclk_i,prst_i,pwrite_i; input [7:0]paddr_i; input [7:0]pwdata_i; output reg [7:0]prdata_o; input penable_i,psel_i; output reg pready_o; output reg mosi,ssel_o; input sclk_in; output sclk; input miso;

endmodule


