# Learning with AI – CSC 494

## Overview
This repository documents my learning process using AI tools for my project, **Mold Risk Monitor**, in the AI-Driven IoT System Development course.

The goal is to use AI as a learning assistant to understand both hardware and software concepts while actively building a working IoT system.

---

## 1. Hardware Topic – I2C Communication

### What I Learned
- How I2C communication works between microcontrollers and sensors  
- How the ESP32 communicates with the AHT10 sensor using SDA and SCL  
- How to properly wire and power the sensor  
- How to scan for I2C devices and verify connections  
- How to read and interpret sensor data using libraries  

### How I Applied It
- Successfully connected the AHT10 sensor to the ESP32  
- Used an I2C scanner to detect the sensor (address 0x38)  
- Read real-time temperature and humidity data  
- Debugged wiring and connection issues when the sensor was not detected  

### Why This Is Important
I2C communication is essential for connecting sensors in IoT systems. Without it, the system would not be able to collect environmental data needed to assess mold risk.

### How I Used AI
- Asked AI to explain I2C communication in simple terms  
- Used AI to troubleshoot wiring and connection issues  
- Used AI to understand the difference between GPIO pins and labeled pins  
- Got help interpreting error messages when the sensor was not detected  

### Reflection
AI helped me move from having no experience with hardware communication to successfully building a working sensor system. It made debugging faster and helped me understand both the theory and practical setup.

---

## 2. Software Topic – Web Dashboard Development

### What I Learned
- How to create a web server using the ESP32  
- How to display real-time sensor data in a browser  
- How to structure HTML, CSS, and JavaScript within embedded systems  
- How to visualize data trends using a simple graph  
- How to design a user-friendly dashboard interface  

### How I Applied It
- Built a web dashboard accessible through the ESP32’s IP address  
- Displayed real-time temperature and humidity data  
- Implemented mold risk classification (Low, Moderate, High)  
- Added trend detection (Rising, Falling, Stable)  
- Stored recent readings and displayed them as history  
- Created a humidity trend graph using HTML canvas and JavaScript  
- Improved UI with a consistent color palette and layout  

### Why This Is Important
The goal of the project is not just to collect data, but to make it understandable. The web dashboard allows users to interpret environmental conditions and recognize patterns that contribute to mold risk.

### How I Used AI
- Asked AI how to create a web server on the ESP32  
- Used AI to generate and debug HTML/CSS/JavaScript code  
- Used AI to fix issues with styling and page rendering  
- Asked AI how to create a simple graph using JavaScript canvas  
- Used AI to improve UI design and layout  

### Reflection
AI helped me connect embedded systems with web development, which was new to me. It allowed me to build a complete system that goes from data collection to visualization. I learned how to structure a dashboard and make data more meaningful to users.

---

## Overall Reflection

Using AI helped me:
- Learn both hardware and software concepts faster  
- Debug issues more efficiently  
- Understand how different system components work together  
- Move from a basic idea to a fully working IoT system  

AI acted as a guide throughout the project, helping me overcome challenges and build confidence in problem-solving.

---

## Final Outcome

By the end of this project, I successfully used AI to:

- Build a working IoT system with an ESP32 and an AHT10 sensor  
- Collect and process real-time environmental data  
- Develop a web-based dashboard for visualization  
- Implement trend analysis and data interpretation  

---

## Next Steps

- Improve data visualization with advanced graphs
- Add long-term data storage  
- Improve mobile responsiveness  
- Explore alert systems for high humidity conditions  
