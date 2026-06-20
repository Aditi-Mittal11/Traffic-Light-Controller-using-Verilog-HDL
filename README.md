# Traffic-Light-Controller-using-Verilog
 
## 📌 Project Overview
 
This project implements a **Traffic Light Controller** using **Verilog HDL** based on a **Finite State Machine (FSM)**. The controller manages traffic signals for two roads:
 
 
- **North-South (NS)**
 
- **East-West (EW)**
 

 
The design cycles through four states to ensure safe and organized traffic flow.
  
## 🎯 Objectives
 
 
- Design a traffic light controller using FSM concepts.
 
- Implement the design in Verilog HDL.
 
- Verify functionality using a testbench.
 
- Simulate and analyze waveforms using EDA Playground.
 

  
## ⚙️ State Description
 
  
 
State
 
North-South
 
East-West
 
   
 
**S0**
 
Green
 
Red
 
 
 
**S1**
 
Yellow
 
Red
 
 
 
**S2**
 
Red
 
Green
 
 
 
**S3**
 
Red
 
Yellow
 
  
 
### **State Transition**
 `S0 → S1 → S2 → S3 → S0 `  
## 🛠️ Tools Used
 
 
- **Verilog HDL**
 
- **EDA Playground**
 
- **EPWave Viewer**
 
- **GitHub**
 

  
## 📂 Project Structure
 `Traffic-Light-Controller/ 
 
 ├── design.sv 
 ├── testbench.sv 
 ├── waveform.png
 └── README.md 
## 📜 Design Features
 
 
- FSM-based traffic signal control
 
- Synchronous operation using clock signal
 
- Reset functionality
 
- Timer-based state transitions
 
- Simulation waveform verification
 

  
## ▶️ Simulation
 
The testbench performs:
 
 
- Clock generation
 
- Reset initialization
 
- State transition verification
 
- Waveform dumping for analysis
 

 
Simulation confirms proper transitions through all traffic light states.
  
## 📊 Waveform Output
 
The waveform verifies:
 
 
- Clock operation
 
- Reset behavior
 
- State transitions
 
- Timer increments
 
- Correct NS and EW signal outputs
 

 
### **Example Sequence**
 `State 0 → State 1 → State 2 → State 3 → State 0 ` 
 
Add your waveform image here:
 
 `![Simulation Waveform](waveform.png) `  
## 🚦 Output Encoding
 
### **North-South Signals**
 
  
 
Value
 
Signal
 
   
 
**001**
 
Green
 
 
 
**010**
 
Yellow
 
 
 
**100**
 
Red
 
  
 
### **East-West Signals**
 
  
 
Value
 
Signal
 
   
 
**001**
 
Green
 
 
 
**010**
 
Yellow
 
 
 
**100**
 
Red
 
  
  
## ✅ Results
 
The Traffic Light Controller was successfully designed and simulated. The waveform output confirms correct FSM operation and traffic signal sequencing.
  
## 🔮 Future Enhancements
 
 
- Pedestrian crossing signal
 
- Emergency vehicle priority
 
- Traffic density sensors
 
- Adaptive traffic light timing
 

  
## 👩‍💻 Author
 
**Aditi Mittal**
 
*B.Tech Student | VLSI Design & Digital Systems Enthusiast*
  
## 📄 License
 
This project is developed for **educational and academic purposes**.
