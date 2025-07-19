
# Smart Assistance System for Maritime Border Security and Fishermen Navigation

A final-year engineering project focused on building a smart, low-cost, and efficient system to assist fishermen near international maritime borders. The system uses **Arduino UNO**, **GPS**, and **LoRa (Long Range)** communication to provide **real-time tracking**, **zone-based alerts**, and **motor control**—enhancing both **maritime safety** and **national security**.

---

## Team Contribution and Collaboration

This project is the result of strong **teamwork**, **collaborative engineering**, and **leadership**. Each member took ownership of different components—hardware interfacing, embedded programming, communication protocols, testing, and documentation—to complete the system within the deadline.

**Team Members:**
- Anbarasu S — Hardware & GPS Integration
- Mohanraj R — Embedded Systems & Motor Control
- Selvanagarajan M — LoRa Communication & Project Coordination

---

## Project Objectives

- Prevent accidental maritime border crossings by fishermen.
- Provide real-time GPS tracking and zone-based alerts.
- Use LoRa for long-distance, low-power data transmission.
- Alert users with LEDs and buzzers based on zone proximity (safe, warning, restricted).
- Automatically reduce boat speed near restricted zones for enhanced safety.

---

## Key Technologies

| Technology   | Purpose                                |
|--------------|-----------------------------------------|
| Arduino UNO  | Core microcontroller                    |
| GPS Module   | Real-time boat location tracking        |
| LoRa Module  | Long-range communication to shore       |
| Motor Driver | Boat control based on zone              |
| LCD Display  | Display location and zone info          |
| Buzzer & LEDs| Visual and audio alerts for zones       |

---

## System Overview

- **Transmitter (Boat):**  
  - GPS constantly sends coordinates to Arduino.  
  - LoRa module sends location to receiver.  
  - Arduino evaluates zone status and alerts fishermen using LED and buzzer.  
  - In restricted zone, motor control logic reduces speed.

- **Receiver (Shore):**  
  - Receives GPS coordinates via LoRa.  
  - Matches location with geofenced zones.  
  - Sends feedback to boat (optional).  
  - Logs data for real-time monitoring and authority records.

---

## Features

- Real-time GPS tracking of fishing boats
- Visual (Green, Yellow, Red LEDs) and audio (Buzzer) zone alerts
- Automatic motor control in restricted zones
- Long-range, low-power wireless communication via LoRa
- Affordable and scalable solution for fishing communities

---

## Block Diagram

Transmitter (Boat) → [GPS] → [Arduino UNO] → [LoRa TX] → → → [LoRa RX] → [Arduino UNO] → Zone Evaluation → Alerts & Motor Control

---

## Leadership and Soft Skills Demonstrated

- Project Coordination: Organized task distribution, integration, and weekly milestones.
- Problem Solving: Resolved GPS inaccuracies and LoRa communication issues during testing.
- Communication: Collaborated effectively with faculty and team for progress reporting.
- Documentation: Created structured and detailed project reports, simulation diagrams, and source code.

---

## Project Report

The full report contains detailed circuit diagrams, simulations, literature reviews, and testing results.

[View Project Report (PDF)](./MARINE_final_end_one.pdf)

---

## Repository Structure

```
/marine-navigation-system
│
├── /code                        # Arduino code files
├── /hardware                   # Block diagrams, component images
├── /docs                       # Final year report and simulation diagrams
├── README.md                   # Project overview
```

---

## Acknowledgements

Special thanks to:
- Dr. M. Newlin Rajkumar, Project Guide
- Anna University Regional Campus, Coimbatore
- All EEE Department staff for their support and mentoring

---

## License

This project is developed for academic and non-commercial purposes. Free to use, share, and modify with credit to the authors.

---

## Contact

For inquiries or project demos:
- Selvanagarajan M — selvanagarajan.email@example.com
- GitHub: [github.com/selvarajan-m](https://github.com/selvarajan-m)
