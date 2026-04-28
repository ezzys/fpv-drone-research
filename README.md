# FPV Drone DIY & Engineering Research Repository

*A comprehensive open-source research collection on FPV drone engineering, DIY construction, mass production, and China supplier ecosystem.*

---

## 🎯 Repository Purpose

This repository consolidates research on building FPV (First-Person View) drones from scratch — covering component selection, manufacturing processes, cost optimization, and mass production. Emphasis on **China supplier ecosystem**, **open-source resources**, and **detailed DIY procedures**.

---

## 📚 Research Document

- **[FPV_DRONE_MASS_PRODUCTION_RESEARCH.md](FPV_DRONE_MASS_PRODUCTION_RESEARCH.md)** — Comprehensive engineering report covering:
  - Core component specifications (frame, FC, ESC, motors, batteries, VTX, RC)
  - Assembly sequences and production line layouts
  - Cost breakdowns and BOM for 5" racing/freestyle drones
  - Manufacturing challenges and solutions
  - Industry case studies (Ukraine's drone industry scaling)
  - Certification requirements (FCC, CE, SRRC, UN38.3)
  - Open-source software ecosystem

---

## 🔗 Essential DIY Build Guides

### English Language

| Resource | URL | Description |
|----------|-----|-------------|
| **Oscar Liang — How to Build an FPV Drone** | https://oscarliang.com/how-to-build-fpv-drone/ | Full step-by-step build guide with wiring diagrams, DJI O4 Pro integration, Betaflight config |
| **Oscar Liang — FPV Drone Guide** | https://oscarliang.com/ | Comprehensive FPV knowledge base (motors, ESCs, props, flight controllers) |
| **Instructables — Ultimate Drone Guide** | https://www.instructables.com/How-to-Build-the-Fastest-Quadcopter-in-3-Hours/ | 22-step illustrated drone build |
| **InsideFPV — Build an FPV Drone** | https://insidefpv.com/blogs/blogs/build-fpv-drone-components-guide | Component guide with cost breakdown |
| **DojoForDrones — DIY Guide** | https://dojofordrones.com/build-a-drone/ | Complete drone building guide, part selection math |
| **CADDxfpv — Beginner Build Guide** | https://www.caddxfpv.com/blogs/news/beginner-s-guide-how-to-build-your-first-fpv-drone | Walksnail/DJI HD system builds |
| **Robocraze — Drone Parts List** | https://robocraze.com/blogs/post/drone-part-list | Component breakdown with motor/ESC explanations |

---

## 🇨🇳 China Sources & Suppliers

### Major Chinese Drone Component Manufacturers

| Supplier | URL | Specialty |
|----------|-----|-----------|
| **T-Motor (SunnyXiao)** | https://uav-en.tmotor.com/ | Industrial UAV motors, ESCs, propulsion systems. Premium FPV motors (F80 Pro, F40 Pro, AT series). Official specsheets available. |
| **AliExpress Drone Parts** | https://www.aliexpress.com/w/wholesale-fpv-drone-parts.html | Wholesale portal for frames, motors, ESCs, cameras, VTX — direct from manufacturers |
| **Global Sources — DJI Parts** | https://www.globalsources.com/china-suppliers/dji-drone-parts.htm | China wholesale supplier directory for DJI-compatible parts |
| **Alibaba Drone Parts Sourcing Guide** | https://electronics.alibaba.com/buyingguides/drone-parts-in-china-a-practical-sourcing-guide | Practical guide to sourcing drone parts in China |
| **AliExpress DIY Wiki** | https://www.aliexpress.com/s/wiki-ssr/article/diy-drone-components-list | Comprehensive DIY drone component list with specs |

### Chinese FPV Racing/FPV YouTube Resources (with subtitles)

| Creator | Platform | Content |
|---------|----------|---------|
| **MoonshotFPV** | TikTok/YouTube | 組裝FPV穿越機結構與零件解析 — FPV assembly structure and parts analysis (Chinese) |
| **NewBeeDrone** | YouTube | 自組fpv穿越機，装机工具配件该如何去选 — Tools and accessories selection (Chinese) |
| **特里（视频大拍档）** | YouTube | 高清穿越机组装到起飞全流程教程 — HD FPV build to flight tutorial (Chinese) |
| **DRONEs** | YouTube | 史上最详穿越机拆解组件介绍 — Most detailed FPV component breakdown (Chinese) |

---

## 🛠️ Detailed DIY Procedures & Schematics

### Motor Construction & Testing

| Resource | URL | Description |
|----------|-----|-------------|
| **DIY 3D Printed Brushless Motor** | https://cadenkraft.com/creating-a-3d-printed-brushless-motor/ | Full design walkthrough, Delta vs Wye wiring, stator/rotor design |
| **3D Printed BLDC Motor — YouTube** | https://www.youtube.com/watch?v=XspvQhf_Gms | Complete build of 3D-printed BLDC motor from scratch |
| **DIY BLDC Motor — YouTube** | https://www.youtube.com/watch?v=OZarwftUh8w | 3D printed BLDC motor design and winding tutorial |
| **Brushless Motor Winding Machine** | https://hackaday.com/2025/06/17/making-a-brushless-dc-motor-winding-machine/ | Automated winding machine built from brushless motors |
| **DIY Thrust Stand — PCBWay** | https://www.pcbway.com/project/shareproject/Brushless_motor_thrust_stand_with_Arduino.html | Arduino-based thrust measurement stand for motor testing |
| **DIY Thrust Stand — RCGroups** | https://www.rcgroups.com/forums/showthread.php?2816516-DIY-Budget-Automated-Thrust-Stand-feat-Arduino%21%21%21 | Budget automated thrust stand with amp/voltage/watt readings |
| **Brushless Motor Thrust Stand — Instructables** | https://www.instructables.com/Brushless-Motor-Thrust-Stand/ | 7-step Arduino-based motor test stand |
| **Arduino Thrust Stand — YouTube** | https://www.youtube.com/watch?v=PfVJmci9IQQ | How-to video for Arduino motor test stand |
| **Motor Control Considerations (TI PDF)** | https://www.ti.com/lit/pdf/slyt692 | Texas Instruments: ESC motor control with FOC algorithm, cascaded speed/current control |

### ESC/Electronics

| Resource | URL | Description |
|----------|-----|-------------|
| **DJI Hardware Schematics (KiCad)** | https://github.com/o-gs/dji-hardware-schematics | Community reverse-engineered DJI drone schematics in KiCad format |
| **DJI ESC/Firmware Tools Wiki** | https://github.com/o-gs/dji-firmware-tools/wiki/P3X-ESC-center-board | DJI P3X ESC center board schematic documentation |
| **DIY ESC Build — DroneMesh/YouTube** | https://www.youtube.com/watch?v=K9toWUsjgkE | Complete ESC schematic walkthrough, 5.5V regulator, PCB design |
| **ESC Schematic Reddit Discussion** | https://www.reddit.com/r/diydrones/comments/1ggimbm/esc_schematic_anyone_got_one/ | Community ESC schematic sharing thread |
| **Infineon Drone ESC Application Note (PDF)** | https://www.researchgate.net/profile/Mohamed_Mourad_Lafifi/post/Quadcopter_BLDC_motors_modeling_electronics_mechanical_terms/attachment/5be06bf9cfe4a76455ffe0c2/AS%3A689639685910530%401541434322530/download/Infineon-Application-Motor_Control-Drone_Electronic_Speed_Controller_ESC-TR-v01_00-EN.pdf | Infineon ESC design with XMC microcontrollers, 3-phase inverter |

### Frame Design & 3D Printing

| Resource | URL | Description |
|----------|-----|-------------|
| **GrabCAD Drone Frame Library** | https://grabcad.com/library/tag/drone%20frame | Thousands of free CAD drone frame models |
| **PURIST DC 5/6 FPV Frame (GrabCAD)** | https://grabcad.com/library/fpv-drone-frame-purist-dc-5-6-1 | AstroX J5 / ImpulseRC Apex EVO inspired freestyle frame |
| **MakerWorld 5" Printable Frame** | https://makerworld.com/en/models/411258-3d-printable-5-inch-drone-frame | Free 3D printable 5" FPV frame for SLS/FDM |
| **Open-Source SRD-1 Arduino Drone** | https://www.reddit.com/r/3Dprinting/comments/1j19ldf/3d_printed_diy_opensource_arduino_drone_srd1_i/ | Fully 3D-printed Arduino-based drone, GitHub linked |
| **MDPI Open-Source 3D Printed Drone** | https://www.mdpi.com/2504-446X/9/11/797 | Academic paper: low-cost 3D-printed STEM education drone platform |
| **YouTube: Tubular Quad V6 FPV Frame CAD** | https://www.youtube.com/watch?v=2fe9Ta6geeY | Designing ultimate FPV frame, CAD walkthrough |

### Flight Controller & Firmware

| Resource | URL | Description |
|----------|-----|-------------|
| **Betaflight** | https://github.com/betaflight/betaflight | Open-source flight controller firmware (most popular FPV FC firmware) |
| **ExpressLRS** | https://expresslrs.org/ | Open-source RC link — 900MHz/2.4GHz, up to 1000Hz, 100km+ range |
| **BLHeli_32** | https://blheli32.com/ | Open-source ESC firmware for 32-bit ESCs |
| **ArduPilot** | https://ardupilot.org/ | Full autopilot stack for multirotor/fixed-wing/VTOL |
| **PX4 Autopilot** | https://github.com/px4/PX4-Autopilot | Industry-standard open-source autopilot (Linux Foundation/Dronecode) |
| **iNav** | https://github.com/iNavFlight/inav | Navigation-focused flight controller firmware |

---

## 🔬 Engineering Reference Papers

| Paper | URL | Description |
|-------|-----|-------------|
| **Quadcopter Flight Controller Design (UNTAN)** | https://jurnal.untan.ac.id/index.php/TELECTRICAL/article/download/73681/pdf | BLDC motor speed control for quadcopter stability |
| **Drone Design & Fabrication IIT Madras (PDF)** | https://eescholars.iitm.ac.in/sites/default/files/eethesis/ee19m004.pdf | PMSM IPM motor design, carbon fiber frame, gimbal design, telemetry |
| **Embedded Thrust Estimator (UTwente PDF)** | https://essay.utwente.nl/79850/1/Menezes_MA_EEMCS.pdf | Brushless DC motor thrust estimation for multi-rotor UAVs |
| **Awesome Drones (GitHub list)** | https://github.com/janesmae/awesome-drones/blob/master/README.md | Curated list of drone-related open-source projects |
| **Awesome FPV Flying (GitHub)** | https://github.com/Matthias84/awesome-flying-fpv | Comprehensive curated list: airframes, motor control, VTX, GPS, CV, simulators |

---

## 💰 Cost Optimization & Mass Production

| Resource | Description |
|----------|-------------|
| **Ukraine FPV Scaling** | 20,000 → 200,000/month (10x in 12 months). TAF Drones: 40,000/month across 6 cities |
| **Component Sourcing** | AliExpress wholesale, Alibaba bulk orders, Global Sources directories |
| **Carbon Fiber Frames** | CNC mold $1,500–$5,000 (amortized). Injection molded plastic $5–$30/unit at scale |
| **Bulk ESC Pricing** | STM32F405 based FC: $3–$6 bulk. 4-in-1 ESC: $30–$45 mid-range |
| **China Manufacturing** | T-Motor, iFlight, Speedybee, BetaFPV for ODM/OEM partnerships |

---

## 📋 Component Quick Reference

### Motor KV Ratings

| KV | Voltage | Prop Size | Application |
|----|---------|-----------|-------------|
| 800–1000 | 6S | 7–10" | Long Range / Cinewhoop |
| 1300–1500 | 6S | 6–7" | Long Duration FPV |
| 1800–2200 | 4S–6S | 5–6" | Freestyle |
| 2400–2800 | 4S | 5" | Racing |
| 3000–3500 | 3S–4S | 3–4" | Micro Racing |

### Battery Configurations

| Config | Nominal | Max Charge | Typical Capacity |
|--------|---------|-----------|-----------------|
| 3S | 11.1V | 12.6V | 1000–2200mAh |
| 4S | 14.8V | 16.8V | 1300–3000mAh |
| 6S | 22.2V | 25.2V | 1300–5000mAh |
| 6S HV (LiHV) | 22.8V | 25.35V | 1000–2500mAh |

### Flight Controller MCU Options

| MCU | Clock | FPU | RAM | Cost (Bulk) |
|-----|-------|-----|-----|-------------|
| STM32F405 | 168 MHz | Yes | 192 KB | $3–$6 |
| STM32F722 | 216 MHz | Yes | 256 KB | $5–$10 |
| STM32H743 | 480 MHz | Yes | 1 MB | $10–$20 |
| ESP32 | 240 MHz | No | 520 KB | $2–$5 |

---

## 🛒 Key Sourcing Links

### Frames
- **ImpulseRC Apex 5"** — Premium carbon fiber freestyle frame
- **iFlight** — Value carbon frames (Cinebee, Nazgul series)
- **TrueRC** — Canadian carbon frame manufacturer

### Motors
- **T-Motor F40 Pro / F80 Pro** — Industry standard
- **iFlight XING-E** — Budget-friendly alternative
- **BetaFPV** — Complete FPV ecosystem

### ESCs
- **Speedybee F45/F65 4-in-1** — Best value stack
- **T-Motor Alpha ESC** — Premium industrial grade
- **BLHeli_32 compatible** — Most firmware options

### VTX & Video
- **DJI O3 / O4 Pro** — Best digital HD system
- **Walksnail Avatar HD** — Budget HD alternative
- **HDZero** — Lowest latency (3–8ms)
- **Rush TinyBee** — Popular analog VTX

### RC Links
- **ExpressLRS** — Open-source, best value/performance
- **ELRS 900MHz** — Long range (100km+)
- **ELRS 2.4GHz** — General FPV, compact

---

## 🔧 Build Tools & Test Equipment

| Tool | Purpose | Budget Option |
|------|---------|---------------|
| **Soldering iron (60W+)** | Motor wire / ESC soldering | TS80/TS100 |
| **Multimeter** | Voltage/continuity check | BSIDE AD18 |
| **Oscilloscope** | Signal debugging | Hantek 6022BE |
| **Thrust stand** | Motor/prop performance testing | DIY Arduino ($30–50) |
| **LiPo charger** | Battery formation/balancing | ISDT / ToolkitRC |
| **Screwdrivers (Precision)** | Frame assembly | Wera / iFixit |
| **Threadlocker** | Motor screw retention | Loctite 243 (blue) |
| **Hot air station** | SMD rework / connector repair | Atten 858D |

---

## 📡 Communities & Forums

| Community | URL |
|-----------|-----|
| **RCGroups FPV Forum** | https://www.rcgroups.com/ |
| **FPV FC Forums** | https://fpvfc.org/ |
| **Oscar Liang Blog** | https://oscarliang.com/ |
| **DroneTroubleshooter** | YouTube channel |
| **Joshua Bardwell** | YouTube — FPV education |
| **UAV Futures** | YouTube — reviews and build guides |
| **r/fpv (Reddit)** | https://reddit.com/r/fpv |
| **r/diydrones (Reddit)** | https://reddit.com/r/diydrones |

---

## ⚠️ Legal Disclaimer

This repository is for **educational and engineering research purposes only**. Building and flying FPV drones may require licensing (e.g., FAA Part 107, EU CE marking, local RC aircraft regulations). Always comply with local laws regarding UAV operation, RF transmission (5.8GHz VTX, ELRS), and battery transport (UN38.3). Weaponization of drones is illegal in most jurisdictions.

---

*Compiled by Hermes Agent | Research conducted via web search and content extraction | April 2026*
