# Autonomous Package Sorting Machine Prototype 🤖  

An autonomous system designed to tackle logistics challenges on the planet **Calidi**. This project features a compact, efficient, and reliable solution for sorting diverse package types, showcasing advanced engineering concepts in automation and control systems.  

## 📖 Overview  
The **Autonomous Package Sorting Machine** is engineered to detect, sort, and manage three distinct package types with precision and efficiency. Key functionalities include error detection, real-time package tracking, and robust rejection subsystems, emphasizing scalability and durability for real-world applications.  

---

## 🎯 Features  
### Core Functionalities  
- **Autonomous Sorting System**: Utilizes sensors and control algorithms to identify and sort yellow and white table tennis balls and a plastic clothes peg.  
- **Error Detection & Indicators**: Built-in mechanisms to identify and indicate sorting errors for operational accuracy.  
- **Real-Time Monitoring**: LCD display to track sorted and rejected packages, enhancing transparency and control.  

### Advanced Engineering Concepts  
- **Finite State Machines (FSMs)**: Enables dynamic decision-making and adaptive behavior for sorting operations.  
- **Control Systems**: Implements advanced control strategies to ensure precision and efficiency.  
- **Scalable Design**: Built for adaptability, allowing future enhancements and applications.  

---

## 🛠️ Technical Details  
### System Architecture  
1. **Sensors**: Detect package type based on predefined characteristics.  
2. **Control Algorithms**: Direct sorting actions using FSM logic.  
3. **Sorting Mechanism**: Stepper motors push packages into designated bins.  
4. **Rejection Mechanism**: Handles unsortable or erroneous items with alerts.  
5. **Real-Time Display**: LCD shows the count of sorted and rejected packages.  

### Technologies Used  
- **STM32-F411RE Microcontroller**: Core processing unit for system control.  
- **Pixy Camera**: Object recognition and classification.  
- **LCD Display**: Tracks operational metrics.  
- **Servo Motors & Stepper Motors**: Enable package movement and sorting.  

---

## 🔧 Setup & Installation  
### Prerequisites  
- STM32CubeIDE for microcontroller programming.  
- Basic knowledge of embedded systems and motor control.  

### Steps to Build & Deploy  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/YourUsername/autonomous-sorting-machine.git  
   ```  
2. Connect components:  
   - Pixy Camera to STM32 for object detection.  
   - Servo motors for conveyor control.  
   - Stepper motors for sorting mechanism.  
3. Load the firmware onto the STM32 microcontroller using STM32CubeIDE.  
4. Power up the system and start sorting!  

### Folder Structure  
```
📂 AutonomousSortingMachine  
 ┣ 📂 Code  
 ┃ ┣ 📂 src  
 ┃ ┗ 📂 inc  
 ┣ 📂 Documentation  
 ┃ ┗ 📜 system_architecture.pdf  
 ┣ 📂 HardwareDesign  
 ┃ ┣ 📜 circuit_diagram.pdf  
 ┃ ┗ 📜 BOM.xlsx  
 ┣ 📜 README.md  
 ┗ 📜 LICENSE  
```  

---

## 📈 Future Improvements  
- Add machine learning for enhanced object recognition and sorting adaptability.  
- Incorporate a larger variety of package types.  
- Design a more compact and lightweight version for mass deployment.  

---

## 🛡️ License  
This project is licensed under the **MIT License**. See the `LICENSE` file for more information.  

---

## ✉️ Contact  
For inquiries, suggestions, or collaboration opportunities:  
- **Name:** Mohammed Rizwan 
- **Email:** mjrzwn@gmail.com  
- **LinkedIn:** https://www.linkedin.com/in/mjrzwan/

---