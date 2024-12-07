# Lab 1: Fine-Tuning Project Topic, Hardware Resource Mapping, and Literature Survey

## 1. Refined Project Topic

### **Topic:**  
**Implementing Edge Computing in a Smart City Traffic Light System**

### **Objective:**  
Develop an edge-computing-based traffic light control system that uses real-time sensor data to dynamically adjust signal timings, thereby reducing traffic congestion and latency.

### **Scope:**  
- Design and implement a prototype using Raspberry Pi, IR sensors, ultrasonic sensors, and LEDs to simulate real-world traffic scenarios.  
- Evaluate the system’s performance in reducing latency and improving traffic flow efficiency.  
- Potential integration of AI algorithms for advanced traffic management and future scalability.  

---

## 2. Hardware Resource Mapping

### **Hardware Components**

| **Component**           | **Functionality**                                                                 | **Necessity**                                                                                                         |
|--------------------------|-----------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| **Raspberry Pi 4**       | Processes sensor data, makes real-time decisions for signal control.             | Provides sufficient computational power and flexibility for real-time edge computing tasks.                          |
| **IR Sensors**           | Detect vehicle presence at stop lines, count waiting vehicles.                   | Cost-effective method to monitor traffic density and adjust signals dynamically.                                      |
| **Ultrasonic Sensors**   | Measure vehicle distance to estimate traffic density and queue length.           | Enhances accuracy of traffic monitoring when combined with IR sensor data.                                           |
| **ESP32 Microcontroller**| Enables wireless communication between signals for synchronization.              | Ensures low-latency communication across intersections in the IoT architecture.                                      |
| **Individual LEDs**      | Simulate traffic lights for testing (red, yellow, green).                        | Serves as the primary output mechanism for system verification and functionality testing.                            |
| **Battery**              | Powers all components for uninterrupted operation.                               | Critical for ensuring reliability, especially in areas without consistent power supply.                              |
| **Cameras (Optional)**   | Capture images/videos for advanced traffic analysis using AI.                    | Optional for basic setups but essential for future AI-based upgrades.                                                |
| **Jumper Wires**         | Connect components for prototyping.                                              | Facilitate easy assembly, debugging, and changes during testing phases.                                              |
| **Breadboard/PCB**       | Breadboard for prototyping; PCB for the final design.                            | Breadboards allow temporary connections; PCBs ensure stable deployment-ready configurations.                          |

---

## 3. Literature Survey

### **Methodology:**  
Using the *Publish or Perish* tool, academic papers and studies related to edge computing, IoT in traffic management, and smart cities were reviewed.  

**Search terms:**  
- *"Edge computing in smart cities"*  
- *"Traffic light systems IoT"*  
- *"Latency reduction in IoT systems"*  
- *"Sensor integration in traffic management"*  

### **Summary of Findings:**

#### 1. Existing Solutions:  
- **Edge Computing for Traffic Systems:** Studies demonstrate the feasibility of using edge devices like Raspberry Pi for real-time traffic data processing, significantly reducing latency compared to cloud-based systems.  
- **Sensor Integration:** IR and ultrasonic sensors are widely used for traffic density monitoring, and combining multiple sensors improves detection accuracy.  
- **AI and Machine Learning:** Some implementations utilize AI for predicting traffic patterns and optimizing signal timings.  

#### 2. Research Gaps:  
- Limited studies focus on integrating edge computing with traffic light systems in smart cities.  
- Scalability remains a challenge when extending the system to cover multiple intersections.  
- Few practical demonstrations exist on integrating real-time data processing with IoT communication protocols (e.g., MQTT, CoAP).  

#### 3. Relevance of the Project:  
- Traffic congestion is a significant issue in urban areas, leading to economic losses and increased emissions.  
- Implementing edge computing in a smart city context addresses real-time latency issues, offering a more responsive traffic management solution.  
- The project can serve as a stepping stone for integrating AI-based traffic optimization in future iterations.  
