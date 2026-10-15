# Hi, I'm Haonan Sun 👋

*a.k.a.* **Telfair** — high-school student in **Beijing, China**, building things that move and things that learn.

I'm the **programmer & driver — and team captain — of VEX team 8632X** (formerly 86X & 86Y), and in my own time I train robot arms with **imitation learning**. What pulls me in is the space where mechanical, electrical, and software engineering meet — both of my projects live exactly there.

---

## 🤖 Featured projects

### [lerobot-project — teaching a robot arm to pick & place](https://github.com/Telfair8632/lerobot-project)

End-to-end imitation learning on the **SO-ARM101** robot arm: teleoperated data collection (49 demonstrations, 12.6k frames) → ACT policy training (loss 6.79 → 0.11, ~52M parameters on a cloud RTX 4090) → real-world deployment. When the trained model kept reaching for a *memorized* position instead of the actual object, I didn't stop at the symptom: the repo documents the full pipeline, an 18-entry engineering journal, and a root-cause analysis of behavior-cloning overfitting, closed out with a controlled V2 experiment plan.

`Python` · `PyTorch` · `LeRobot` · `ACT` · `Computer Vision`

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
| **Hardware** | Actuators & pneumatics, motor control, wiring & port-level debugging |

---

## 📍 Currently

- 🔴 Competing in the **2026–27 VEX season** (RCF Override) as **captain of 8632X**
- 🧪 Designing controlled experiments for **V2** of the imitation-learning pipeline
- 🎓 Applying to undergraduate programs in **Robotics, Mechanical & Electrical Engineering, and CS**

> Every repo here is built to be read, not just run — full engineering journals, root-cause analyses, and reproduction instructions included.
