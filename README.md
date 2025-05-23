## Seeed Grove Vision AI Module V2 — Overview

The **Grove Vision AI Module V2** is Seeed Studio’s latest compact, MCU-based vision AI module, designed for easy integration of advanced computer vision and machine learning into edge devices. It is built around the **Himax WiseEye2 HX6538** processor, featuring a dual-core Arm Cortex-M55 and an integrated Arm Ethos-U55 neural network unit for efficient, high-performance AI processing.

---

### **Key Features**

- **Processor:** Himax WiseEye2 HX6538  
  - Dual-core Arm Cortex-M55 (up to 400 MHz)
  - Integrated Arm Ethos-U55 microNPU (up to 400 MHz)
- **AI Model Support:**  
  - Supports TensorFlow and PyTorch frameworks
  - Compatible with SenseCraft AI for no-code/low-code model deployment
  - Out-of-the-box and custom models: Mobilenet V1/V2, EfficientNet-Lite, YOLO v5/v8, etc.[1][3][5]
- **Performance:**  
  - Inference time: 33 ms
  - Frame rate: 30.3 FPS
  - Power consumption: only 0.35 W — ideal for battery-powered applications[3][4][6]
- **Interfaces & Peripherals:**  
  - CSI interface (compatible with all Pi cameras)
  - PDM microphone (for audio/voice AI)
  - SD card slot (for data storage)
  - Type-C, Grove connector, I2C, UART, SPI
- **Memory:**  
  - 60 MB onboard flash
  - Configurable system memory up to 2432 KB
- **Compatibility:**  
  - Arduino IDE, Raspberry Pi, Seeed Studio XIAO, ESP-based boards, BeagleBoard, and more[1][2][3][4][5]
- **Open Source:**  
  - All codes, design files, and schematics are available for modification and use[1][3][7]

---

### **Use Cases**

- Object and face detection
- Classification and recognition tasks
- TinyML applications (vision and audio)
- Smart sensors and edge AI deployments

---

### **Summary Table**

| Feature             | Specification                                           |
|---------------------|--------------------------------------------------------|
| Processor           | Himax WiseEye2 HX6538 (Dual-core Cortex-M55 + Ethos-U55) |
| AI Model Support    | TensorFlow, PyTorch, SenseCraft AI, Mobilenet, YOLO, etc. |
| Inference Time      | 33 ms                                                  |
| Frame Rate          | 30.3 FPS                                               |
| Power Consumption   | 0.35 W                                                 |
| Interfaces          | CSI, I2C, UART, SPI, Type-C, Grove                     |
| Peripherals         | PDM mic, SD card slot                                  |
| Compatibility       | Arduino, Raspberry Pi, XIAO, ESP, BeagleBoard          |
| Open Source         | Yes                                                    |


