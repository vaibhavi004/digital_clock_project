# 🕒 DigiTime: FPGA-Based 24-Hour Digital Clock using Verilog

An accurate, real-time 24-hour digital clock designed and implemented using Verilog HDL on the Spartan-3 FPGA board. This project demonstrates fundamental digital design principles and the application of HDL in building time-based systems for embedded applications.

## 🧠 Abstract
This project presents the design and implementation of a 6-digit digital clock that displays hours, minutes, and seconds in 24-hour format using Verilog. The clock operates on a 1 Hz time base generated using a clock divider module, and outputs the digits through a multiplexed seven-segment display interface. Synthesized and implemented on an FPGA, the system showcases practical usage of hardware description languages in real-world applications.

## 🌟 Features
- ⏱️ Real-time 24-hour digital clock  
- 🔄 Reset button to set time to 00:00:00  
- 🔁 Multiplexed 6-digit 7-segment display  
- 📉 Modular design with Verilog HDL  
- 💡 Easy integration with Spartan-3 FPGA  
- 🧠 Synchronous and Reset-aware logic  

## 🛠️ System Overview

| Component       | Function                                 |
|----------------|------------------------------------------|
| `clock_final`   | Main control logic for hours, minutes, seconds |
| `clk_divider`   | Divides base clock to generate 1 Hz and display clock |
| `get_segment()` | Converts digits into 7-segment encoding |
| `constraints.ucf` | Maps signals to FPGA I/O pins for Spartan-3 |

## 🛠️ Architecture
- Clock Divider: Generates slow clock (1 Hz and display clock)  
- Counter Logic: Increments seconds, minutes, hours  
- Display Logic: Multiplexed digit control using enable signals  
- Reset: Synchronously resets all digits to 00:00:00  

## 💻 Technologies Used
- Verilog HDL  
- Xilinx ISE  
- Spartan-3 FPGA  
- 7-Segment Displays  
- Constraint File (UCF)  


## 🚀 Applications
- Embedded timekeeping in FPGA-based systems  
- Real-time clocks in digital electronics labs  
- Educational demonstrations in HDL and FSMs  
- Foundation for stopwatch or timer-based designs  

## 🔮 Future Work
- Add alarm functionality with buzzer interface  
- Extend to 12-hour format with AM/PM indicator  
- Use push-button interface for time adjustment  
- Port to other FPGA boards (e.g., Basys, Nexys)  
- Add simulation testbenches for automated testing  

## 👩‍💻 Team Members
- Pallavi D. Lad  
- Patadayya G. Chikkmath  
- Vaibhavi M. Patil  

## 👨‍🏫 Guided By
- Prof. Suresh F. Murgod  
KLE Dr. M. S. Sheshgiri College of Engineering and Technology, Belagavi
