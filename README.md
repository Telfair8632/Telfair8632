# Hi, I'm Haonan Sun 👋

*a.k.a.* **Telfair** — high-school student in **Beijing, China**, building things that move and things that learn.

I'm the **programmer & driver — and team captain — of VEX team 8632X** (formerly 86X & 86Y). Outside of competition I keep building: training robot arms with **imitation learning**, and taking a twin-engine RC aircraft from parametric CAD to flight-test firmware. What pulls me in is the space where mechanical, electrical, and software engineering meet — all of my projects live exactly there.

---

## 🤖 Featured projects

### [lerobot-project — teaching a robot arm to pick & place](https://github.com/Telfair8632/lerobot-project)

End-to-end imitation learning on the **SO-ARM101** robot arm: teleoperated data collection (49 demonstrations, 12.6k frames) → ACT policy training (loss 6.79 → 0.11, ~52M parameters on a cloud RTX 4090) → real-world deployment. When the trained model kept reaching for a *memorized* position instead of the actual object, I didn't stop at the symptom: the repo documents the full pipeline, an 18-entry engineering journal, and a root-cause analysis of behavior-cloning overfitting, closed out with a controlled V2 experiment plan.

`Python` · `PyTorch` · `LeRobot` · `ACT` · `Computer Vision`

### [sr71-600 — a twin-engine 600 mm RC Blackbird](https://github.com/Telfair8632/sr71-600)

A fully independent aircraft engineering project: parametric FreeCAD CAD, 1:1 manufacturing templates, a costed procurement plan, circuit design, and a **14-level staged verification ladder** for the Raspberry Pi Pico 2 flight controller — with automated QA evidence recorded at every step. Firmware level 3 (watchdog + 30-min endurance soak) and level 4 (200 Hz IMU logging, zero dropped samples) have passed; the airframe is now being built toward a supervised first flight.

`FreeCAD` · `CAD` · `RP2350 / C SDK` · `Circuit Design` · `MPU-6050`

### [RCFOverride2027 — VEX V5 competition robot code](https://github.com/Telfair8632/RCFOverride2027)

C++ code for **team 8632X's** robot in the 2026–27 **RCF Override** season, built on the PROS kernel: a shared PID controller, tank-drive chassis, gear-position lift, pneumatics, and **9 competition autonomous routines** selectable from the driver controller at the field.

`C++` · `PROS` · `PID Control` · `Embedded Systems`

---

## 🛠️ What I work with

| | |
|---|---|
| **Languages** | C++, Python |
| **Robotics** | VEX V5 / PROS, SO-ARM101, sensor fusion (IMU), PID & motion control |
| **ML / Data** | PyTorch, imitation learning (ACT), dataset pipeline design, model debugging |
| **Mechanical / Electrical** | Parametric CAD (FreeCAD), laser-cut & 3D-print part design, circuit & wiring design, RC aircraft |
| **Hardware** | Actuators & pneumatics, motor control, wiring & port-level debugging |

---

## 📍 Currently

- 🔴 Competing in the **2026–27 VEX season** (RCF Override) as **captain of 8632X**
- ✈️ Building the **SR-71 600** airframe — climbing the 14-level firmware ladder toward a supervised first flight
- 🧪 Designing controlled experiments for **V2** of the imitation-learning pipeline
- 🎓 Applying to undergraduate programs in **Robotics, Mechanical & Electrical Engineering, and CS**

> Every repo here is built to be read, not just run — full engineering journals, root-cause analyses, and reproduction instructions included.
