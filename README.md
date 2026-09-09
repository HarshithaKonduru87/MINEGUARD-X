🛡️ MINEGUARD-x 

📌 About the Project

MINEGUARD-X is an autonomous AI-powered rover designed to explore hazardous underground mine zones, detect risks, map the environment, and provide real-time intelligence to rescue teams.

The system focuses on shifting mine rescue from human-first exploration to intelligence-first reconnaissance, helping teams understand hazardous areas before entering them.


🚨 Problem

Underground mining environments can involve:

- ☣️ Toxic gases
- 🌫️ Poor visibility
- ⚠️ Unstable conditions
- 🧱 Difficult terrain and obstacles
- 📡 Unstable underground communication

Direct exploration of hazardous areas can increase the risk to rescue personnel. Existing approaches may also lack mobile exploration and persistent risk mapping.


💡 Our Solution

MINEGUARD-X uses a multi-sensor autonomous rover to explore hazardous areas and provide useful information to rescue teams.

Key Capabilities

- ☣️ Hazardous gas and condition detection
- 🧱 Obstacle and unsafe-zone identification
- 🗺️ SLAM-based environment mapping
- 🚨 Real-time hazard alerts
- 📍 Rover location monitoring
- 🗺️ Risk-zone mapping
- 🧭 Safe-route guidance
- 🧠 Persistent risk memory


🔄 How MINEGUARD-X Works

SENSE → ANALYSE → MARK → MAP → REMEMBER → RECOMMEND

1. Sense
The rover collects environmental and positional information through multiple sensors.

2. Analyse
Edge processing and AI analyse the collected data.

3. Mark
Detected hazards and unsafe areas are identified.

4. Map
SLAM helps build an understanding of the underground environment.

5. Remember
Previously detected risks are retained through the Persistent Risk Memory concept.

6. Recommend
The collected intelligence supports rescue teams in making safer decisions.

The PPT identifies this six-stage workflow as the core operating concept of MINEGUARD-X.



🧠 Key Innovation — Persistent Risk Memory

From Detection to Decision Support

A central innovation of MINEGUARD-X is Persistent Risk Memory.

Instead of treating each hazard detection as an isolated event, the system connects detected risks with future rescue decisions.

SENSE
  ↓
ANALYSE
  ↓
MARK
  ↓
MAP
  ↓
REMEMBER
  ↓
RECOMMEND

This enables the rover's detected risk information to remain useful for subsequent rescue planning.



🧰 Technology Stack

Technology| Role
ESP32| Embedded hardware
Raspberry Pi| Edge processing
Python| Programming & AI processing
ROS 2| Robotics framework
OpenCV| Computer vision
AI / ML| Intelligent analysis
SLAM| Environment mapping
IoT Communication| Communication
Web Dashboard| Monitoring & control

The technology stack is based on the components and technologies specified in the project presentation.



📡 System Inputs & Outputs

Inputs

- Gas
- Temperature / Humidity
- RGB camera
- Thermal camera
- Distance / Obstacle sensing
- IMU
- Wheel movement

Outputs

- 🚨 Hazard alerts
- 🗺️ Live mine map
- ⚠️ Risk zones
- 📍 Rover location
- 🧭 Safe-route guidance
- 💻 Monitoring dashboard



🎥 Prototype Demo

The prototype demonstrates the complete workflow:

Sense → Analyse → Mark → Map → Remember → Recommend

▶️ Demo Video

"🎬 Watch the MINEGUARD-X Prototype Demo" (https://drive.google.com/file/d/1JbgHAj_KjXzTrLX4XfUJfCMKViINLMEI/view?usp=drivesdk)



📑 Project Presentation

MINEGUARD-X — SIH 2026

"📊 View the MINEGUARD-X Presentation" (https://drive.google.com/file/d/1zhkODaXfnse9VmJzb9CWTm7wqBSy902t/view?usp=drivesdk)


🎯 Target Users

MINEGUARD-X is intended for:

- 🚒 Mine Rescue Teams
- ⛏️ Mine Operators
- 🛡️ Safety Authorities
- 🚨 Emergency Responders
- 👷 Mining Engineers
- 🏛️ Government Agencies



✅ Feasibility

🔧 Technical Feasibility

- Available sensors and embedded hardware
- AI, computer vision and SLAM
- Modular design for future upgrades

💰 Economic Feasibility

- Low-cost commercial components
- Modular maintenance and replacement
- Scalable deployment

🏭 Operational Feasibility

- Remote operation reduces exposure
- Real-time dashboard supports decisions
- Designed for low-visibility environments



⚠️ Challenges & Mitigation

Challenge| Mitigation Strategy
Underground communication instability| Store-and-forward + breadcrumb network
Low visibility & dust| RGB + thermal vision
Difficult terrain / obstacles| SLAM + obstacle detection
Sensor errors & uncertainty| Multi-sensor data validation
Limited battery life| Power-aware navigation & monitoring



🌍 Impact

MINEGUARD-X aims to shift mine rescue from:

Human-First Exploration

↓

Intelligence-First Reconnaissance

The rover can explore hazardous areas and provide information about conditions and risks before rescue teams enter.

Impact Areas

Area| Expected Impact
🛡️ Safety| Reduced human exposure
🚨 Detection| Early hazard identification
🗺️ Mapping| Real-time risk understanding
💡 Decision Support| Faster, safer decisions



📈 Benefits

- 🛡️ Improved safety
- 🚨 Early hazard detection
- 🗺️ Real-time risk mapping
- 📍 Better understanding of hazardous zones
- 🧭 Support for safer rescue planning
- 👥 Reduced exposure to dangerous environments

📚 Research & References

The project references:

1. DGMS — Directorate General of Mines Safety
   Mine safety regulations, standards and emergency practices.

2. Ministry of Coal, Government of India
   Mining safety, technology and modernization initiatives.

3. CSIR-CIMFR
   Research in mine safety, monitoring and disaster management.

4. NIOSH
   Mine hazard monitoring, safety and rescue technologies.



👥 Team

TerraSentinels

Project Detail| Information
Project| MINEGUARD-X
Event| Smart India Hackathon 2026
Problem Statement ID| 26039
Category| Hardware
Theme| Smart Automation


⭐ Vision

«Sense the danger. Map the risk. Remember the hazard. Recommend the safer path.»

🛡️ MINEGUARD-X

Intelligence-first reconnaissance for safer underground mine rescue.

“MINEGUARD-X — Let technology face the danger first, so humans can return home safely.”


👤 Developer

Harshitha Konduru
CSE Student | AI & Robotics Enthusiast.