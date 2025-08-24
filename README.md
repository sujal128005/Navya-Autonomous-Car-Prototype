# **Navya – Autonomous Car Prototype (Phase-1 Plan)**

# 🚗 Project Aim:
Navya is a student-led project at IIITDM Kurnool to build a **working prototype of an autonomous car** in 3 months.
This version focuses on:
* Lane detection & following
* Obstacle detection & avoidance
* Real-time control using Raspberry Pi + Camera + RC car platform
The long-term goal is to advance toward **Level 3 Automation**, but this first phase delivers a **proof-of-concept prototype**.
---

## 📅 Roadmap (12 Sub-Phases for Phase-1)
| Sub-Phases | Milestone                                    | Status |
| ---- | -------------------------------------------- | ------ |
| 1    | Finalize scope, recruit team, order hardware | ☐      |
| 2    | Hardware setup (RC car + Pi + Camera)        | ☐      |
| 3    | Lane detection (offline video)               | ☐      |
| 4    | Lane detection (real-time)                   | ☐      |
| 5    | PID controller for steering                  | ☐      |
| 6    | Integration: Lane + PID control              | ☐      |
| 7    | Obstacle detection (offline)                 | ☐      |
| 8    | Obstacle avoidance (real-time)               | ☐      |
| 9    | ML experiments (YOLO-lite / MobileNet)       | ☐      |
| 10   | System integration & indoor testing          | ☐      |
| 11   | Tuning & improvements                        | ☐      |
| 12   | Final demo + documentation                   | ☐      |
(☐ = Pending, ✅ = Done)
---

## 📂 Repository Structure
```
Navya/
│
├── docs/                # Documentation, research notes, setup guides
│   ├── research/
│   ├── setup/
│   ├── vision/
│   ├── control/
│   ├── system_integration.md
│   └── final_demo.md
│
├── vision/              # Computer vision code
│   ├── lane_detection.py
│   ├── obstacle_detection.py
│   └── ml_experiments/
│
├── control/             # Control algorithms
│   └── pid_controller.py
│
├── hardware/            # Hardware wiring diagrams, configs
│   └── motor_driver_test.py
│
├── results/             # Test videos, FPS logs, demo outputs
│
└── README.md            # Project overview
```
---

## 👥 Team Structure
* **Perception Team** → Lane & obstacle detection (OpenCV, ML)
* **Control Team** → PID steering & vehicle dynamics
* **Hardware Team** → RC car, Pi, wiring, sensors
* **Integration Team** → Merge perception + control + hardware
* **Documentation Team** → Maintain research logs, write guides
---

## 🛠️ Tech Stack
* **Hardware:** Raspberry Pi, Pi Camera, RC Car chassis, Motor Driver, Batteries
* **Software:** Python, OpenCV, TensorFlow Lite, GitHub Projects
* **Control:** PID Controller, GPIO-based motor control
* **Testing:** Indoor tracks with lanes + obstacles
---

## 🤝 Contributing
We welcome contributions from all students. Since this is a **knowledge-based, non-paid project**, commitment and curiosity are the only requirements.
* Fork this repo, work on assigned issues, and make pull requests
* Attend weekly team syncs for task updates
* Document everything in `/docs/` so future teams can build on it
---

## 📌 Next Steps
1. [ ] Publish weekly progress reports in `/results/`

---
🔥 This repo is the foundation of Navya’s journey toward building a self-driving car.


Thanks,


With ❤️ **"Navya"**

