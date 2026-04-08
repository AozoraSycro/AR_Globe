# 🌍 3D AR Globe for Education
> **An immersive Augmented Reality (AR) educational application visualizing the Earth's anatomical structure in 3D.**
> แอปพลิเคชันสื่อการเรียนการสอนรูปแบบโลกเสมือน (AR) สำหรับจำลองและสำรวจโครงสร้างชั้นเปลือกโลกแบบสามมิติ

---

## 🌐 Demo

<p align="center">
  <img src="https://github.com/user-attachments/assets/67c3b74d-addd-44ef-8f8c-9b14304ad6d9" width="700">
</p>

---

## ✨ Key Features

- 🌍 **Interactive 3D Spatial Globe:** View the Earth from multiple perspectives using robust marker-based AR tracking.
- 🧭 **Internal Structural Visualization:** Intuitively explore the anatomical layers of the Earth through a dynamic UI, including:
  - Crust (เปลือกโลก)
  - Mantle (เนื้อโลก)
  - Outer Core (แก่นโลกชั้นนอก)
  - Inner Core (แก่นโลกชั้นใน)
- 📷 **High-Fidelity AR Tracking:** Delivers a stable, low-latency, and seamless AR experience powered by **Vuforia Engine**.
- 🎓 **EdTech Focused:** Purposely designed to bridge the gap between theoretical geography and interactive visual learning for students.

---

## 🛠️ Tech Stack

- **Game Engine:** Unity 3D
- **Core Logic:** C#
- **AR Framework:** Vuforia Engine SDK
- **Deployment Platform:** Android (APK)

---

## 📁 Architecture & Structure

```text
3D-AR-Globe/
├── Unity Project Files/
├── Assets/
│   ├── 3D Models/         # Earth and structural layer meshes
│   ├── Textures/          # High-resolution geographic maps & materials
│   └── Scripts/           # C# logic for AR tracking and UI interactions
└── Build/
    └── ARGlobe.apk        # Compiled Android executable file
