# MAKERMANIA 2026

## Innovation Project Workbook

> Program Duration: 1 June 2026 – 4 July 2026
>
> Location: MBF Tinkerers' Lab 007
>
> Team Size: 3–5 Students
>
> Goal: Identify a real-world problem and develop an innovative, patentable, and implementable solution.

---


## 🔨 Knocking Hammer

**Protect Your Knuckles. Knock with Confidence.**

The Knocking Hammer is a simple ergonomic tool designed to help users knock on doors without directly impacting their knuckles, reducing discomfort while providing a consistent knocking experience.

🎥 Demo Video: https://youtube.com/shorts/bD19YGxGuTQ?si=1oJ4QhMyKx1h3Qpc

📂 DOCUMENTATION: https://github.com/adarshgupta-web/MakerMania-2026-MintyJamun/tree/main/USELESS_PRODUCT



# 1. Team Identity

## 1.1 MintyJamun
<p align="center">
  <img src="Minty_jamun.png" width="400">
</p>
---

## 1.2 Team Members

### Team Members

| Name | Role | Year | Branch | Skills |
|:-----|:-----|:-----|:--------|:--------|
| Shanchita Chauhan | Documentation, Research & Development | F.E. | AURO | ESP32 Programming, Arduino Development, CAD Modeling, Circuit Design, Wokwi Simulation,Sensor Fusion |
| Adi Kalra | Documentation, Design & Research | S.E. | EXTC | CAD Design, Embedded Systems, KiCad PCB Design |
| Adarsh Gupta | Team Lead, Documentation, Product Design & Prototyping | S.E. | AURO | CAD Modeling, Prototyping, Electronics Integration, Embedded System |

# 2. Problem Discovery

## 2.1 Observation Area

Where did you conduct your observations?

Observations were conducted in hostels, homes, and college study environments where students frequently used smartphones while studying or completing academic tasks. These settings helped identify patterns of digital distraction and excessive social media usage.

---

## 2.2 AEIOU Observation Sheet

### Activities

What are users doing?

Studying, working, attending online classes, reading, or focusing on tasks.<br>
Frequently checking their phones during these activities.<br>
Switching between productive apps and distracting apps (social media, games, short-video platforms).<br>
Attempting to maintain focus but getting distracted by habitual phone usage.

### Environment

What conditions affect them?

Presence of phone notifications and easy access to distracting apps.<br>
Long work or study sessions that lead to reduced concentration.<br>
Situations where some phone usage is necessary (calls, emails, messages) while distractions should be avoided.

### Interactions

Who or what are they interacting with?

The anti-distraction wristband.<br>
The companion mobile application used to configure restrictions.


### Objects

What tools or products are used?

Bluetooth-enabled wristband.<br>
Companion mobile application.<br>
Vibration motor and microcontroller (e.g., ESP32-C3).<br>
Productivity and distracting applications

### Users

Who are the primary users?

Students preparing for exams or attending classes.<br>
College students working on assignments and projects.<br>
Professionals who need to stay focused while working.<br>
Individuals trying to reduce screen time and social media addiction.<br>
Anyone seeking better productivity and concentration habits.<br>
Non invasive productivity monitoring for corporate enviroments.

---

## 2.3 Observation Log

| Observation                         | Evidence                          | Pain Point                             |
| -----------                         | --------                          | ----------                             |
|Users frequently open social media apps while studying or working. | During observation/interviews, users reported checking Instagram, YouTube, or WhatsApp repeatedly. | Loss of focus and reduced productivity.| 
|Existing app blockers are often disabled or bypassed. |Users stated they uninstall blockers or ignore notifications.| Current solutions are easy to ignore.|
|Many users use phones for both productive and distracting tasks.|Users need phones for emails, calls, notes, and study material.|Complete blocking is impractical.|
|Users often realize they are distracted only after spending significant time on an app. |Users reported "just checking for a minute" and ending up scrolling for much longer. |Lack of immediate awareness of distraction.|
---

# 3. User Research

## 3.1 Interview Summary

Number of users interviewed: ______

## 3.2 Key Quotes

1."I only open Instagram for a minute, but I end up scrolling for half an hour."

2."I need my phone for study materials and calls, so I can't completely block it."

3."Notifications and app blockers don't really stop me because I can just ignore them."

---

## 3.3 User Persona

### Name

### Age 

### Occupation 
Student

### Goals 

Stay focused while studying.<br>
Reduce social media usage.<br>
Improve productivity and time management.<br>
Build better digital habits.

### Frustrations

Constant urge to check social media.<br>
Losing track of time while scrolling.<br>
Existing app blockers are easy to bypass.<br>
Difficulty balancing productive and distracting phone use.

### Needs

A non-intrusive way to regain focus.<br>
Real-time reminders when using distracting apps.<br>
Ability to allow essential apps while restricting distractions.<br>
A solution that encourages self-control rather than complete blocking.

---

# 4. Problem Framing

## Problem Statement

User Students and young professionals needs a way to stay focused while using their smartphones for productive tasks because distracting applications such as social media, games, and short-form video platforms often lead to loss of concentration and reduced productivity..

---

## How Might We Questions

1.How might we help users recognize when they are getting distracted by their phones?

2.How might we provide real-time feedback without completely blocking smartphone usage?

3.How might we encourage users to return to productive tasks when using distracting applications?

4.How might we reduce excessive social media usage through wearable technology?

5.How might we create a focus-assistance system that is difficult to ignore but not intrusive?

---

## Opportunity Ranking

| Criteria         | Score (1-5) |
| ---------------- | ----- |
| Severity         |   4   |
| Frequency        |   5   |
| Feasibility      |   4   |
| Novelty          |   4   |
| Market Potential |   4   |
| Total            |  21/25  |

---

# 5. Solution Ideation

## Brainstormed Ideas

| Idea | Advantages | Challenges |
| ---- | ---------- | ---------- |
| Electric/Shock Wake-up Ring|Forces users to wake up and avoid oversleeping |Safety concerns, user discomfort, regulatory issues  |
|Focus Monitor (Phone Pickup Tracker) |Helps users understand distraction habits | Only tracks behavior, doesn't actively intervene|
|PIR/Camera-Based Smart Switch |Saves energy by automatically switching off lights | False detections and installation complexity|
|Vibration Bracelet |Provides immediate feedback and discourages distractions |Requires wearable hardware and mobile app development |


---

## Selected Concept

## Vibration Band for Distraction Reduction<br>
A Bluetooth-enabled wearable ring or bracelet that connects to a smartphone. Users can select distracting applications through a companion app. When a restricted app is used for longer than a specified grace period, the wearable begins vibrating. The vibration intensity gradually increases the longer the user remains on the distracting application, encouraging them to return to their intended task.

Why was this concept chosen?

This concept was chosen because smartphone distraction is a common problem faced by students and professionals on a daily basis. Unlike app blockers that completely restrict access, the vibration bracelet provides a physical reminder while still allowing users to use their phones when necessary. The solution is practical, user-friendly, and combines hardware and software components, making it suitable for implementation within the project's scope. It is also unique compared to traditional screen-time monitoring applications because it uses wearable haptic feedback to influence user behavior in real time.


---

# 6. System Design

## High-Level Description

FocusBand is a wearable anti-distraction device that uses haptic feedback to break the unconscious habit of checking your phone. Unlike apps like Minimalist Phone that rely on willpower, FocusBand creates a physical intervention layer that makes you consciously aware every time you reach for your device.
The system consists of a wristband containing an ESP32-C3 microcontroller, RC522 RFID module, dual vibration motors, and a 400mAh Li-Po battery. The companion phone app emulates an RFID tag via NFC and monitors screen usage patterns over Bluetooth LE.

## How It Works
When the band detects your phone nearby (via RFID/NFC proximity sensing), it monitors whether your screen turns on. If interaction is detected for more than your configured threshold (5-10 seconds), the dual vibration motors fire, creating an immediate tactile reminder. You must use your alternate hand to dismiss the alert, forcing a conscious pause in the usage loop.


---

## Block Diagram

<img width="1408" height="665" alt="WhatsApp Image 2026-06-22 at 3 36 47 PM" src="https://github.com/user-attachments/assets/03d67278-6ac9-4a46-a922-2ad6e809d8b6" />


---

## Inputs

Bluetooth data from smartphone<br>
Phone NFC emunated RFID card/tag

---

## Outputs

Vibration alerts<br>
User notification through wearable response

---

# 7. Technical Planning

## Electronics

| Component | Purpose |
| --------- | ------- |
| ESP32-C3 Super Mini  |Main microcontroller that manages Bluetooth communication, processes commands from the mobile app, and controls the vibration motors.|
|400mAh Li-Po Battery (3.7V) |Provides portable power to the wearable device. |
| TP4056 Type-C Charging Module |Charges the Li-Po battery safely and allows convenient USB Type-C charging.| 
| ERM Coin Vibration Motors (2x)| Generates haptic feedback; vibration intensity can be increased to alert the user when using distracting applications.|
| RC522 RFID Module| Used for user authentication, attendance logging, device activation, or future expansion features (if included in the design).|
| Bluetooth (Built into ESP32-C3)| Enables wireless communication between the wearable device and the smartphone application.|

---

## Software

| Tool | Purpose |
| ---- | ------- |
|Arduino IDE  |Used to write, compile, upload, and debug the firmware for the ESP32-C3 microcontroller. It is used to implement Bluetooth communication, motor control, battery management, and overall device functionality |

---

## Mechanical / CAD

Describe fabricated components.

---

# 8. Prototype Development

## Version 1

Description:

Lessons Learned:

---

## Version 2

Description:

Lessons Learned:

---

## Final Prototype

Description:

---

# 9. Testing & Validation

## Testing Plan

| Test | Success Criteria |
| ---- | ---------------- |
|      |                  |
|      |                  |

---

## User Feedback

| User | Feedback | Action Taken |
| ---- | -------- | ------------ |
|      |          |              |

---

# 10. Innovation Assessment

## Existing Solutions

List competing products.

---

## What Makes This Different?

---

## Innovation Score

| Parameter       | Score |
| --------------- | ----- |
| Novelty         |       |
| Technical Depth |       |
| Feasibility     |       |
| Impact          |       |
| Scalability     |       |

---

# 11. Intellectual Property

## Prior Art Search

Patents / Products Found:

---

## Novel Features

1.

2.

3.

---

## Provisional Patent Draft

### Title

### Abstract

### Problem

### Solution

### Claims

---

# 12. Business & Deployment

## Target Users

---

## Estimated Cost

---

## Market Opportunity

---

## Sustainability Considerations

---

# 13. Final Demonstration

## Prototype Images

Insert photos.

---

## Demonstration Video Link

---

## GitHub Repository

---

## Presentation Link

---

# 14. Reflection

## What Worked Well?

---

## What Failed?

---

## Key Learnings

---

## Next Steps

* Patent Filing
* Startup Exploration
* Product Development
* Research Publication
* Competition Submission

---

# 15. Final Deliverables Checklist

* Problem Discovery Complete
* User Interviews Complete
* Persona Created
* Problem Statement Finalized
* System Design Complete
* Prototype Demonstrated
* Testing Completed
* Patent Draft Prepared
* Presentation Submitted
* GitHub Repository Updated

---

# MAKERMANIA FINAL PITCH

Each team will present:

1. Problem
2. User Research
3. Insights
4. Solution
5. Prototype Demo
6. Innovation & Patentability
7. Future Roadmap

Presentation Time: 5 Minutes

Q&A: 3 Minutes
