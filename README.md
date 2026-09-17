# EcoVerse VR — Sustainable Cities & Experiential Environmental Learning (UN SDG 11)

An immersive, gamified Virtual Reality (VR) simulation built to foster sustainable daily habits and environmental consciousness in urban environments. Designed around the United Nations' **Sustainable Development Goal 11 (Sustainable Cities and Communities)**, the application delivers hands-on experiential learning where users interact with urban living spaces to mitigate carbon footprint, conserve biodiversity, optimize household energy, and manage solid waste.

---

## 📌 Problem Statement & Context

Urban areas account for nearly **70% of global CO₂ emissions**, with household operations consuming approximately **30% of total energy** and cities generating over **2.2 billion tons of solid waste per year**. By 2050, 68% of the global population is projected to live in urban centers. 

Traditional pedagogical approaches struggle to build long-term sustainable habits. **EcoVerse VR** tackles this gap by placing the player inside a realistic virtual city ecosystem where domestic and community-level decisions yield visible, measurable ecological feedback.

---

## 🎮 Core Game Objectives & Mechanics

Players explore virtual indoor and city environments, completing mission briefings that directly correspond to ecological action pillars:

1. **Object Reuse (Circular Economy):** Identify domestic items and repurpose them into practical tools rather than discarding them.
2. **Energy Conservation:** Navigate the living space to locate and turn off idle lighting and appliances to cut carbon footprint.
3. **Urban Gardening & Reforestation:** Plant, water, and nurture seeds to stimulate green space recovery and terrestrial ecosystem awareness.
4. **Waste Classification & Recycling:** Categorize and deposit waste fractions into appropriate color-coded containers to alleviate municipal landfill burden.

### Gameplay Progression & Gamification
- **Mission Briefings & Interactive Quests:** Step-by-step guidance paired with voice-over cues and accessibility subtitles.
- **Scoring & Achievement System:** Dynamic scoring algorithms rewarding speed, precision, and adherence to circular economy rules.
- **Zone Progression:** Unlock new urban districts as environmental indicators improve across the neighborhood.
- **Cooperative Multiplayer Support:** Collaborative tasks allowing multiple users to clean and restore shared urban sectors simultaneously.

---

## 🎯 Target UN Sustainable Development Goals (SDG Alignment)

- **SDG 11 (Target 11.6 & 11.b):** Reducing the environmental impact of cities and implementing disaster resilience strategies.
- **SDG 4 (Target 4.7):** Education for sustainable development and sustainable lifestyles.
- **SDG 12 (Target 12.5):** Substantially reducing waste generation through prevention, reduction, recycling, and reuse.
- **SDG 15 (Target 15.1):** Terrestrial ecosystem conservation and urban green recovery.

---

## 🛠 Tech Stack & Hardware Compatibility

- **Game Engine & Frameworks:** Unity 3D / OpenXR Standard, XR Interaction Toolkit
- **Scripting & Logic:** C#
- **3D Modeling & Environment:** Blender (low-poly assets, modular procedural city kits)
- **Graphics & Optimization:** Universal Render Pipeline (URP), custom VR-optimized shaders, physics simulations
- **Target Hardware & Platforms:**
  - Meta Quest 2 / Meta Quest 3 (Standalone & PC Link)
  - PC VR (HTC Vive, Valve Index via OpenXR)
  - Mobile VR compatibility options

---

## 🏫 Institutional Details

- **Institution:** Instituto Politécnico Nacional (IPN) — Escuela Superior de Cómputo (ESCOM)
- **Academic Program:** Desarrollo Sustentable (Sustainable Development)
- **Project Initiative:** EcoVerse VR — *Aprende. Actúa. Salva tu ciudad.*
- ---

---

## 🥽 Installation & Deployment Guide for Meta Quest 2 / 3 (.apk)

EcoVerse VR is compiled as an Android package (`.apk`) optimized for standalone VR execution on Meta Quest 2 and Meta Quest 3 headsets via SideQuest or Meta Quest Developer Hub (MQDH)[cite: 3].

### Prerequisites
1. **Developer Mode Enabled on Meta Quest:**
   - Open the **Meta Quest** app on your smartphone.
   - Go to **Menu** > **Devices** > select your Meta Quest headset.
   - Navigate to **Headset Settings** > **Developer Mode** and toggle it **ON**.
2. **SideQuest installed on PC / Mac:** Download and install [SideQuest Advanced Installer](https://sidequestvr.com/setup-howto).
3. **USB-C Data Cable:** Connect your headset to your computer.

---

### Step 1: Download the VR Build
- Go to the **Releases** section on the right sidebar of this GitHub repository.
- Download the latest compiled VR build file: `EcoVerse_VR_vX.X.apk`.

---

### Step 2: Install via SideQuest (Recommended)
1. Launch **SideQuest** on your computer.
2. Connect your Meta Quest headset to the PC using the USB-C cable.
3. Put on the headset and accept the prompt: **"Allow USB Debugging"** (check *Always allow from this computer*).
4. Verify that the indicator dot in the top-left corner of SideQuest turns **Green** (Connected).
5. Click on the icon labeled **"Install APK file from folder on computer"** (an icon showing a box with a down arrow in the top header).
6. Select the downloaded `EcoVerse_VR_vX.X.apk` file.
7. Wait until the bottom status bar confirms: *"All tasks completed successfully"*.

---

### Step 3: Launch EcoVerse VR in Headset
1. Put on your Meta Quest headset.
2. Open the main **App Library** grid.
3. Click on the dropdown menu in the upper-right corner (currently set to *All* or *Installed*).
4. Scroll down and select **Unknown Sources** (`Fuentes Desconocidas`).
5. Tap on **EcoVerse VR** to launch the interactive serious game experience.
