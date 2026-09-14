Hi, I'm Erik (hardcoreerik)

I build firmware, custom device drivers, embedded systems software, software-defined radio tools, mapping systems, mesh-networking software, and local AI infrastructure — usually with the goal of pushing consumer hardware well beyond what it was originally designed to do.

Much of my embedded work focuses on the software layer closest to the hardware: ESP32 firmware, USB host drivers, hardware integration, RF and DSP pipelines, device interfaces, embedded graphics, and reusable libraries for constrained systems.

A growing part of that work lives inside the Orc Ecosystem — a collection of open-source projects spanning ESP32-P4, SDR, custom hardware drivers, offline mapping, LoRa and Meshtastic, RF visualization, distributed systems, and local-first AI tooling.

## The Orc Ecosystem

### [OrcSDR](https://github.com/hardcoreerik/OrcSDR)

An embedded **software-defined radio platform** exploring how far SDR can be pushed on **ESP32-class hardware**, particularly the **ESP32-P4**.

OrcSDR combines RF visualization, signal analysis, broadcast radio, protocol experimentation, offline reference data, and direct control of USB SDR hardware in a portable embedded interface.

A major part of the project is direct support for the **RTL-SDR Blog V4** through a custom ESP32-P4 USB host driver, allowing devices such as the **M5Stack Tab5** to communicate with an SDR without requiring a traditional PC.

The larger goal is to turn inexpensive embedded hardware into a capable, portable RF exploration platform.

**Repository:**
https://github.com/hardcoreerik/OrcSDR

---

### [esp-rtl-sdr](https://github.com/hardcoreerik/esp-rtl-sdr)

A clean-room **ESP-IDF USB host SDR driver** for RTL2832U-class hardware, developed with **RTL-SDR Blog V4** support first.

It gives ESP32 systems a native path to communicate directly with SDR hardware without depending on a PC-side RTL-SDR stack.

The driver began as part of OrcSDR but has grown into a reusable project of its own, designed to make embedded RTL-SDR development possible across **ESP32-P4 hardware platforms**.

**Repository:**
https://github.com/hardcoreerik/esp-rtl-sdr

---

### [OrcMaps](https://github.com/hardcoreerik/OrcMaps)

A reusable **embedded mapping and geospatial platform** designed for constrained hardware such as the ESP32-P4 and **M5Stack Tab5**.

OrcMaps focuses on bringing fast, practical **offline mapping** to embedded applications while providing reusable rendering and integration components for projects across the Orc Ecosystem.

The project is being built around technologies such as **M5GFX and M5Unified**, with the goal of making maps, geographic overlays, RF data, routes, stations, nodes, and other spatial information available without depending on a permanent internet connection.

**Repository:**
https://github.com/hardcoreerik/OrcMaps

---

### [TheOrc](https://github.com/hardcoreerik/TheOrc)

TheOrc is built around a simple idea: **your models should run on your hardware, your context should stay yours, and the system should be able to show how it got there.**

The long-term vision is **OrcEngine**: a native local runtime for downloading models, running them directly, coordinating agents, and moving work across the computers you already own.

The **TheOrc HIVE** is being developed to pool compute, memory, and graphics resources across multiple computers, allowing smaller systems to cooperate and making model choice less dependent on the VRAM available in a single machine.

That direction means moving away from required dependence on Ollama, llama.cpp, LM Studio, OpenRouter, or mandatory cloud infrastructure.

At the center is **Context Fabric**, a structured layer for documents, code, memory, citations, and decisions. It gives local AI systems continuity and provenance so their work can be traced, inspected, and understood.

**Repository:**
https://github.com/hardcoreerik/TheOrc

#### [TheOrcCompanion](https://github.com/hardcoreerik/TheOrcCompanion)

Android companion and mobile field node for TheOrc's HIVE MIND.

**Repository:**
https://github.com/hardcoreerik/TheOrcCompanion

---

### [OrcMesh](https://github.com/hardcoreerik/OrcMesh)

The mesh-networking side of the Orc Ecosystem, focused on **LoRa, Meshtastic, MeshCore, embedded communications, RF visualization, and distributed wireless nodes**.

The larger goal is to let Orc devices communicate with each other, observe their RF environment, exchange data, and operate together as parts of a distributed hardware and software system.

OrcMesh explores how small embedded devices can become cooperative nodes rather than isolated pieces of hardware.

**Repository:**
https://github.com/hardcoreerik/OrcMesh

---

## Wireless & Security Tools

### [NEONDRIVE](https://github.com/hardcoreerik/NEONDRIVE)

Multi-target **ESP32 firmware** for wireless experimentation, wardriving, RF exploration, and authorized wireless security assessment labs.

It focuses on portable wireless discovery and data collection while supporting multiple ESP32 hardware targets and field-use workflows.

**Repository:**
https://github.com/hardcoreerik/NEONDRIVE

#### [Wardrive Analyzer](https://github.com/hardcoreerik/Wardrive-Analyzer)

Desktop analysis platform for turning captures from NEONDRIVE and other wireless assessment tools into searchable datasets, visualizations, evidence, and exported reports.

**Repository:**
https://github.com/hardcoreerik/Wardrive-Analyzer

---

I like building systems that blur the line between **AI, software, radio, networking, and hardware** — especially when it means making hardware do something it wasn't supposed to be able to do.
