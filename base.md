# CoreXY 600×600×600mm Over-Engineered 3D Printer Build (2024–2025)

> Designed for maximum stability, precision, and dual tool-changing with the latest Duet3D electronics and top-tier community toolchanger systems.

---

## 🟦 1. Frame & Structure

- **Aluminum Extrusions:**  
  - Heavy T-slot profiles (40×80mm or 45×90mm) – Misumi, Motedis, RatRig, or 80/20.
  - Calculate for:  
    - 4 verticals, 4 horizontals (main cube)
    - 6–8 cross braces for top, bottom, and middle stability
- **Corner Brackets & Gussets:**  
  - 6mm+ thick aluminum or steel
- **Base/Bed Plate:**  
  - 5–6mm machined MIC6 aluminum (or steel) plate ~650×650mm
  - High-temp insulation (silicone/cork) beneath
- **Leveling Feet:**  
  - Heavy-duty adjustable feet or castors

---

## 🟦 2. Motion System & Linear Rails

- **Linear Rails:**  
  - HiWin/THK/HRS rails (15mm square type, e.g., HGW15CC)
    - X axis: 2 × MGN15 (or 2 × MGN12 for lighter toolheads)
    - Y axis: 2 × MGN15 (or MGN12)
    - Z axis: 3–4 × MGN12/15 for bed support
- **Belts:**  
  - Gates GT2, steel- or carbon-reinforced, 6mm width
- **Pulleys & Idlers:**  
  - 20T hardened steel pulleys, high-precision bore
  - High-quality idlers (bearings or Igus bushings)
- **Motors:**  
  - NEMA17 high-torque (≥0.5Nm) for XY  
  - NEMA17/NEMA23 for Z (as load requires)
- **Couplers:**  
  - Zero-backlash (e.g. Reprap, FabRat)
- **Idler Blocks:**  
  - Self-aligning with shielded bearings

---

## 🟦 3. Z Axis (Bed Lift)

- **Leadscrews:**  
  - 3 or 4 × Tr8×8 (2mm pitch) or ballscrews (SFU1204)
  - Anti-backlash nuts/spring-loaded nuts
- **Synchronization:**  
  - Multiple leadscrews can be synchronized with belts/gears or independent motors (auto-squaring via firmware)
- **Guides:**  
  - Linear rails as above for anti-wobble
- **Bed Supports:**  
  - Kinematic mounts for precise leveling

---

## 🟦 4. Toolchanger System

- **Mechanics:**  
  - **Jubilee** toolchanger (open source, modular, proven)  
  - **RatRig V-Minion** toolchanger or similar open-source 2024+ projects  
  - (E3D ToolChanger is discontinued – use community designs)
- **Docking:**  
  - Precision machined or printed docks with kinematic locating features (magnets/dowels)
- **Parking:**  
  - Optional simple parking for just two heads (less complexity)

---

## 🟦 5. Extruders & Hotends

- **Extruders:**  
  - Bondtech LGX (latest version)  
  - E3D Roto (lightweight, high-torque, designed for toolchanging)
- **Hotends:**  
  - E3D Revo (standard or High-Temp/UHT for up to 400–500°C)
  - Slice Engineering Mosquito/Dragon (all-metal, 500°C capable)
  - Hardened or abrasive-resistant nozzles (E3D ObXidian, DiamondBack, etc.)
- **Quick Connect:**  
  - PTFE or custom couplers for rapid tool swap

---

## 🟦 6. Heated Bed & Surface

- **Bed Heater:**  
  - 600×600mm silicone AC pad (e.g., Keenovo), 1200W+, 230/240V  
  - Controlled via SSR (Solid State Relay)
- **Bed Plate:**  
  - 8–10mm MIC6 aluminum, precision ground for flatness
- **Build Surface:**  
  - PEI-coated spring steel flex plate (Energetic, WhamBam, Subtle Design)
  - High-temp adhesive magnetic sheet
- **Insulation:**  
  - Cork/silicone under bed

---

## 🟦 7. Electronics & Controls

- **Mainboard:**  
  - Duet 3 MB6HC (Trinamic TMC5160, CAN-FD support, 6 axes)
- **Expansion:**  
  - Duet 3 3HC Expansion Board (if more steppers needed)
- **Toolboards:**  
  - Duet 3 Tool Board 1LC (one per extruder/tool)
  - Duet 3 Roto Toolboard for E3D Roto (bundles hotend & extruder connections)
- **PanelDue Touchscreen:**  
  - Optional for direct printer control
- **Power Supply:**  
  - 24V Mean Well (RSP-750/1000), size as needed (750–1000W)
- **Wiring & Cable Management:**  
  - Heavy gauge (12–14AWG) for bed, 18–22AWG for signals
  - Cable chains, drag chains, ferrules, and braided sleeving

---

## 🟦 8. Cooling

- **Hotend Fans:**  
  - 40–50mm blower per tool
- **Part Cooling:**  
  - 50–80mm high-speed radial fan, PWM
- **Electronics Cooling:**  
  - Small case fan for board enclosure if needed

---

## 🟦 9. Sensors & Safety

- **Endstops:**  
  - Optical or Hall-effect (Honeywell, Omron)
- **Bed/Nozzle Probes:**  
  - Duet IR Z-probe, Euclid Probe, or quality inductive sensor (NPN/PNP)
  - BLTouch or CR-Touch as alternative
- **Filament Sensor:**  
  - Optical or mechanical runout sensor, wired to Duet
- **Thermal Protection:**  
  - Enable firmware safety, thermal fuses on AC bed
- **Grounding:**  
  - Bond frame and bed to earth ground

---

## 🟦 10. Enclosure & Extras

- **Enclosure:**  
  - Acrylic, polycarbonate, or aluminum composite panels
- **Lighting:**  
  - High-CRI LED strips
- **Camera:**  
  - Optional for remote monitoring
- **Power Entry:**  
  - IEC C14/C20 module with switch & fuse
- **Emergency Stop:**  
  - Panel mount E-stop, wired to Duet input

---

## 🟦 11. Software & Firmware

- **Firmware:**  
  - Duet RepRapFirmware (3.4+ recommended)
- **Web Interface:**  
  - Duet Web Control (DWC)
- **Slicer:**  
  - PrusaSlicer, SuperSlicer, OrcaSlicer, or Cura (Duet/G-code mode)
- **Input Shaping & Tuning:**  
  - Configure in RRF for best print quality

---

## 🟦 12. References / Open Designs

- [Jubilee Toolchanger (official)](https://jubilee3d.com/index.php?title=Main_Page)
- [RatRig V-Core 4](https://ratrig.com/)
- [Duet3D Official Documentation](https://docs.duet3d.com)
- [E3D Revo & Roto](https://e3d-online.com)
- [Bondtech LGX](https://www.bondtech.se/en/product/lgx-extruder/)

---

## Build Process (Summary)

1. **Design frame layout in CAD** (or adapt Jubilee/RatRig to 600mm size)
2. **Order/extrusions, brackets, plates**
3. **Assemble frame and linear rails**
4. **Install Z-lift and bed with heater**
5. **Mount gantry/toolchanger/toolheads**
6. **Wire all electronics, power, sensors**
7. **Configure firmware, calibrate, test**
8. **Test tool changing, dual extrusion**
9. **Fine-tune for best performance**

---

> 💡 **Tip:** For best results, join Discord or forums for Jubilee, RatRig, and Duet3D communities for advice and print profiles.
