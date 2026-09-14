<img width="1280" height="640" alt="git (1)" src="https://github.com/user-attachments/assets/8920b256-2ba8-4988-b824-5351134eb4bd" />


# Viramam (വിരാമം) 🎯


## Basic Details
### Team Name: Viramam


### Team Members
- Team Lead: Mohammed Sinan K - College of Engineering Munnar
- Member 2: Akshay B Arjun - College of Engineering Munnar

### Project Description

Viramam is an AI-powered facial recognition system that detects registered users and prevents them from continuously working on a computer. After 10 seconds of recognition, it locks the setup using an ESP32-controlled SG90 servo and tells the user, **"GO TAKE SOME REST!"** 😴

### The Problem (that doesn't exist)

People keep working on computers without taking breaks.

So we created an AI that decides when you've worked enough. 😂

### The Solution (that nobody asked for)

Viramam recognizes registered users using AI-based facial recognition. If the user is continuously detected for 10 seconds, the ESP32 activates the servo and slowly locks the setup.

When the user leaves for 2 seconds, it automatically unlocks.

**Face detected → 10 seconds → LOCK 🔒 → GO TAKE SOME REST 😴**

## Technical Details
### Technologies/Components Used

For Software:
- Python 3.11
- OpenCV
- NumPy
- PySerial
- YuNet Face Detection
- SFace Face Recognition
- ONNX Models
- Arduino IDE

For Hardware:
- ESP32-WROOM-32
- SG90 Servo Motor
- Web Camera
- USB Cable
- Jumper Wires
- 5V Power Supply
- Servo signal connected to GPIO 18

### Implementation

For Software:

# Installation


cd C:\Users\aksha\useless3

py -3.11 -m venv venv

.\venv\Scripts\Activate.ps1

python -m pip install opencv-python numpy pyserial

### Project Documentation
For Software:

# Screenshots (Add at least 3)
![Screenshot1](Add screenshot 1 here with proper name)
*Add caption explaining what this shows*

![Screenshot2](Add screenshot 2 here with proper name)
*Add caption explaining what this shows*

![Screenshot3](Add screenshot 3 here with proper name)
*Add caption explaining what this shows*

# Diagrams
![Workflow](Add your workflow/architecture diagram here)
*Add caption explaining your workflow*

For Hardware:

# Schematic & Circuit
<img width="941" height="707" alt="Screenshot 2026-09-12 095646" src="https://github.com/user-attachments/assets/bf10ce7a-6e79-479d-a7d4-7c45c36aefff" />
<img width="960" height="737" alt="Screenshot 2026-09-12 084704" src="https://github.com/user-attachments/assets/a23598e1-abe1-47ed-bdd3-298df37dd8c6" />
# Build Photos
<img width="1080" height="1440" alt="WhatsApp Image 2026-09-12 at 9 52 18 AM (1)" src="https://github.com/user-attachments/assets/5faf4827-8968-48c0-aa58-69e75a9ae982" />*

<img width="1080" height="1440" alt="WhatsApp Image 2026-09-12 at 9 52 18 AM" src="https://github.com/user-attachments/assets/b92f543d-fa4e-46f7-bd3d-520e5dd9d156" /><img width="900" height="1600" alt="WhatsApp Image 2026-09-12 at 9 52 17 AM" src="https://github.com/user-attachments/assets/01335b33-4877-4585-bff8-bd7415786601" />


https://github.com/user-attachments/assets/6d70736c-3892-473f-8227-8c3250f203d3

### Project Demo


https://github.com/user-attachments/assets/d12e2e9f-c709-4db3-9fd6-b95fe74e4ed2








# Additional Demos


https://github.com/user-attachments/assets/4f42f9d6-bd79-45e5-9082-a84120abe39c



## Team Contributions
mohammed sinan k hardware configuration
akshay b arjun software configuration
---
Made with ❤️ at TinkerHub Useless Projects 

![Static Badge](https://img.shields.io/badge/TinkerHub-24?color=%23000000&link=https%3A%2F%2Fwww.tinkerhub.org%2F)
![Static Badge](https://img.shields.io/badge/UselessProjects--26-26?link=https%3A%2F%2Ftinkerhub.org%2Fevents%2F1M8ORET9A1%2Fuseless-projects-3.0)



