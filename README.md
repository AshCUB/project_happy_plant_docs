# 🌱 Project Happy Plant

---

## 📖 Table of Contents

- [About the Project](#about-the-project)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
  - [Materials](#materials)
  - [Tools](#tools)
- [Manufacturing](#manufacturing)
  - [Planter](#planter)
  - [Electronics](#electronics)
  - [Lid](#lid)
  - [Assembly](#assembly)
- [Uploading the Code](#uploading-the-code)
- [Usage](#usage)
- [Project Files](#project-files)
- [Acknowledgements](#acknowledgements)

---

## 📌 About the Project

Project Happy Plant is a mission to provide species-specific, hassle-free plant care while fostering a deeper connection to nature. The project has two parts:

- **Happy Planter** — a uniquely designed planter with a built-in bottom-up watering system for optimal root development
- **Happy Tracker** — a kit including stickers, log sheets, and a poster to help you track your plant's growth

Developed in collaboration with a local plant shop, Project Happy Plant makes keeping your plants healthy and happy easier than ever.

---

## ✨ Features

- 💧 **Automated Watering** — create a custom watering schedule to automate your plant care
- 🌿 **Developed with Local Plant Experts** — built in collaboration with a local plant shop to ensure the best care possible
- 📋 **Physical Growth Tracker** — connect with your plant's journey through the Happy Tracker
- 🏅 **Achievement Stickers** — celebrate milestones by checking off fun stickers as your plant grows
- 🌱 **Bottom-Up Watering** — delivers water directly to the roots for stronger, healthier development
- 🪟 **Labeled Planter Window** — easily monitor soil moisture and root growth at a glance
- ⚙️ **Customizable Watering Settings** — fine-tune your configuration to optimize growth for any plant
- 🌐 **Web App Integration** — unlock expanded features and insights through the Happy Plant web app
- 🖱️ **Quick Water Button** — manually trigger watering instantly with a single tap

---

## 🛠 Tech Stack

| Layer | Technology |
|-------|------------|
| Hardware | Arduino ESP32 Nano |
| Firmware | C++ via PlatformIO |
| Frontend | HTML / CSS |

---

## 🚀 Getting Started

### Materials

| Item | Purpose |
|------|---------|
| Rock PLA | 3D printing the planter body |
| Flex Seal | Waterproofing the electronics enclosure |
| Arduino ESP32 Nano | Microcontroller |
| 9V Relay | Pump switching |
| 9V Battery + attachment | Power supply |
| Wires | Electronics connections |
| Button | Quick water trigger |
| 4x4 Water Vat | Water reservoir |
| Protoboard | Circuit assembly |
| USB-C Cord | Power + code upload |
| Acrylic | Laser cut lid |
| Water Pump | Watering mechanism |
| Acrylic Tubing | Water delivery |

### Tools

| Tool | Purpose |
|------|---------|
| 3D Printer | Print planter body |
| Soldering Iron | Assemble electronics |
| Fume Hood | Safe Flex Seal application |
| Paintbrush | Apply Flex Seal |
| Laser Cutter | Cut acrylic lid |
| VS Code + PlatformIO | Upload firmware |

---

## 🏭 Manufacturing

### Planter

1. Load Rock PLA into the 3D printer and send the file to print with perimeters increased to 4
2. Remove supports and place the print in a fume hood
3. Coat the electronics enclosure with Flex Seal — wait 48 hours
4. Apply a second coat of Flex Seal — wait another 48 hours

### Electronics

1. Gather all electronic components and solder according to the wiring diagram

### Lid

1. Place acrylic sheet in the laser cutter
2. Send the laser cut file and run

### Assembly

1. String the water pump wire through the hole on the outside of the laser cut lid
2. Solder wires to electronics according to the wiring diagram
3. Insert the back of the button into the interior button hole and press the outer piece to the front
4. String the USB-C cord through the cord hole and plug into the planter
5. Gently press all electronic components into the enclosure and close with the lid

---

## 📤 Uploading the Code

### Prerequisites
- VS Code with the [PlatformIO extension](https://platformio.org/install/ide?install=vscode) installed
- A data-transfer USB-C cable connected to your ESP32 Nano

### Steps

1. Open the project in VS Code via `File > Open Folder` and select the `happy_plant` folder
2. Wait for PlatformIO to finish installing dependencies automatically
3. In the PlatformIO sidebar, go to `Project Tasks > Platform > Upload Filesystem Image`
4. Once complete, click the **→ Upload** button in the bottom toolbar to flash the firmware



---

## 🌿 Usage

Once running, open the web app to:
- Adjust how long the water pump is triggered
- Create and manage watering schedules
- Manually water your plant with the quick water button

---

## 📁 Project Files

### Wiring Diagram
> `![Wiring Diagram](docs/wiring-diagram.png)`

### Laser Cut File
> `![Laser Cut File](docs/laser-cut-file.png)`

### 3D Print File
> `![3D Print File](docs/3d-print-file.png)`

---
