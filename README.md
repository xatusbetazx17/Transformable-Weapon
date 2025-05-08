[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Arduino](https://img.shields.io/badge/Platform-Arduino-red.svg)](https://www.arduino.cc/)
[![Repo Size](https://img.shields.io/github/repo-size/your-username/transformable-weapon.svg)](https://github.com/your-username/transformable-weapon)

# 🔱 Transformable Weapon

> A real-world prototype concept inspired by Mega Man Zero—seamlessly switching between **Sword**, **Shield**, and **Laser** modes using a single-button interface and modular hardware.

---

## 🚀 Features

- **Three Modes in One**  
  - 🗡️ **Sword**: Deployable folding/telescoping blade  
  - 🛡️ **Shield**: Magnetic pulse “shield” coil for defensive bursts  
  - 🔫 **Laser**: 5 mW diode laser module for directed-energy firing  

- **Unified Control**  
  - Single pushbutton cycles modes  
  - Hold to activate Laser or Shield in respective modes

- **Modular & Expandable**  
  - Swappable blade segments (3D-printed)  
  - Standard hobby servos and MOSFET-driven circuits  
  - Open-source firmware and simulation scripts

---

## 📁 Repository Structure

```
transformable-weapon/ ├── LICENSE ├── README.md ├── docs/ │ ├── concept.md │ ├── hardware_spec.md │ ├── software_spec.md │ └── safety_guidelines.md ├── hardware/ │ ├── BOM.csv │ ├── CAD/ │ │ ├── blade_segments.step │ │ └── servo_mounts.stl │ └── circuits/ │ ├── laser_module.sch │ ├── shield_coil.sch │ └── pcb_layout/ ├── power/ │ └── battery_specs.md └── software/ ├── arduino/ │ └── transformable_weapon.ino ├── host/ │ └── telemetry.py └── simulations/ ├── thermal_model.m └── animation.blend

```


---

## ⚙️ Getting Started

### Prerequisites

- **Hardware**  
  - Arduino Uno (or compatible)  
  - 2× micro servos (e.g., MG90S)  
  - KY-008 laser diode module  
  - Logic-level MOSFET (e.g., IRLZ44N)  
  - Blade segments (3D-printed)  
  - Copper coil & capacitor bank for shield  
  - 3.7 V Li-ion cells + BMS  

- **Software**  
  - Arduino IDE (version ≥1.8)  
  - Python 3.8+ (for telemetry scripts)  
  - MATLAB or compatible (for thermal model)  
  - Blender (for animation previews)

### Installation & Wiring

1. **Clone the repo**  
   ```bash
   git clone https://github.com/your-username/transformable-weapon.git
   cd transformable-weapon
