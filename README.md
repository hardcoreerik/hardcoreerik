# Hi, I'm Erik (`hardcoreerik`)

I build **local AI systems, embedded hardware, software-defined radio tools, mesh networking projects, and experimental software** focused on pushing consumer hardware further than it was originally designed to go.

A growing part of my work lives inside the **Orc Ecosystem** — a collection of projects combining **local AI, distributed computing, SDR, ESP32 hardware, LoRa, Meshtastic, MeshCore, RF visualization, and custom embedded tooling**.

## The Orc Ecosystem

### [TheOrc](https://github.com/hardcoreerik/TheOrc)

TheOrc is built around a simple idea: your models should run on your hardware, your context should stay yours, and the system should be able to show how it got there.

The long-term vision is **OrcEngine**: a native local runtime for downloading models, running them directly, coordinating agents, and moving work across the computers you already own.

The goal is to make model choice less dependent on a single machine's VRAM. The TheOrc HIVE pools compute, memory, and graphics resources across multiple computers so smaller systems can work together and get more out of less. OrcEngine is being developed toward running models that would otherwise be too large for one box.

That direction means moving away from required dependence on Ollama, llama.cpp, LM Studio, OpenRouter, or mandatory cloud infrastructure.

At the center is **Context Fabric**, a structured layer for documents, code, memory, citations, and decisions. It gives local systems continuity and provenance, so the work is grounded in information that can be traced and understood.

- **[TheOrcCompanion](https://github.com/hardcoreerik/TheOrcCompanion)** — Android companion and mobile field node for TheOrc's HIVE MIND.

### [OrcSDR](https://github.com/hardcoreerik/OrcSDR)

An embedded **software-defined radio (SDR)** platform exploring how far SDR can be pushed on **ESP32-class hardware**, including the **ESP32-P4**.

OrcSDR combines RF visualization, signal analysis, protocol experimentation, and direct communication with the **RTL-SDR Blog V4**.

A major part of the project is a **custom RTL-SDR V4 USB driver for ESP32 hardware**, developed to allow ESP32-P4 devices such as the **M5Stack Tab5** to communicate directly with an RTL-SDR V4 without requiring a traditional PC.

### [esp-rtl-sdr](https://github.com/hardcoreerik/esp-rtl-sdr)

A clean-room **ESP-IDF USB host driver** for RTL2832U-class SDR hardware, with RTL-SDR Blog V4 support first. It gives ESP32 systems a native path to communicate with the dongle without relying on a PC-side SDR stack.

## Wireless & Security Tools

### [NEONDRIVE](https://github.com/hardcoreerik/NEONDRIVE)

Multi-target **ESP32 firmware** for wireless experimentation, wardriving, RF exploration, and authorized wireless security assessment labs.

- **[Wardrive Analyzer](https://github.com/hardcoreerik/Wardrive-Analyzer)** — Desktop analysis platform for turning captures from NEONDRIVE and other wireless assessment tools into searchable datasets, visualizations, evidence, and exported reports.

### [OrcMesh](https://github.com/hardcoreerik/OrcMesh)

The mesh-networking side of the Orc Ecosystem, focused on **LoRa, Meshtastic, MeshCore, embedded communications, RF visualization, and distributed wireless nodes**.

The larger goal is to let Orc devices communicate with each other, observe their RF environment, exchange data, and operate together as parts of a distributed hardware and software system.

---

I like building systems that blur the line between **AI, software, radio, and hardware** — especially when it means making hardware do something it wasn't supposed to be able to do.
