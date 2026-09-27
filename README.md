# Computer structure

## Introduction

A computer is an electronic device that processes data according to instructions. It consists of hardware components that work together to input, process, store, and output information.

This document describes the main parts of a computer and how they interact.

---

## 1. Main Components

A typical desktop computer contains:

- **CPU** — Central Processing Unit
- **RAM** — Random Access Memory
- **Motherboard** — connects all components
- **Storage** — HDD, SSD, or NVMe
- **GPU** — Graphics Processing Unit
- **PSU** — Power Supply Unit
- **Cooling system** — fans, heatsinks, liquid cooling
- **Case** — holds and protects components
- **Peripherals** — keyboard, mouse, monitor, printer, etc.

---

## 2. CPU (Central Processing Unit)

The CPU is the "brain" of the computer. It executes instructions and performs calculations.

### Parts of a CPU

- **ALU (Arithmetic Logic Unit)** — performs math and logic operations.
- **Control Unit** — directs the flow of instructions and data.
- **Registers** — very fast, small storage inside the CPU.
- **Cache** — small, fast memory (L1, L2, L3) that stores frequently used data.

### Instruction Cycle

1. **Fetch** — get an instruction from memory.
2. **Decode** — translate the instruction.
3. **Execute** — perform the operation.
4. **Store** — write the result back.

### Cores and Threads

Modern CPUs have multiple cores. Each core can run instructions independently. Threads allow a core to handle multiple tasks at once.

---

## 3. Memory (RAM)

RAM is temporary, fast storage used by running programs.

- Data in RAM is lost when the computer is turned off.
- More RAM allows more programs to run at the same time.
- RAM is much faster than disk storage but slower than CPU cache.

### Memory Hierarchy

| Level    | Speed       | Size          |
|----------|-------------|---------------|
| Registers| Fastest     | Bytes         |
| Cache    | Very fast   | KB to MB      |
| RAM      | Fast        | GB            |
| SSD/HDD  | Slow        | TB            |

---

## 4. Storage

Storage keeps data permanently, even when the power is off.

### Types of Storage

- **HDD (Hard Disk Drive)** — magnetic disks, slower, cheaper per GB.
- **SSD (Solid State Drive)** — flash memory, faster, no moving parts.
- **NVMe SSD** — very fast, connects directly to PCIe.

### What Is Stored

- Operating system
- Applications
- User files (documents, photos, videos)
- Configuration data

---

## 5. Motherboard

The motherboard is the main circuit board. It connects all components.

### What It Provides

- Sockets for CPU
- Slots for RAM
- Connectors for storage (SATA, M.2)
- Expansion slots (PCIe) for GPU, sound cards, network cards
- Ports for peripherals (USB, HDMI, Ethernet, audio)
- Chipset that manages communication between components

---

## 6. GPU (Graphics Processing Unit)

The GPU handles graphics and parallel calculations.

- **Integrated GPU** — built into the CPU, good for basic tasks.
- **Discrete GPU** — separate card, used for gaming, 3D rendering, AI, and video editing.

GPUs have many small cores designed for parallel processing.

---

## 7. Power Supply Unit (PSU)

The PSU converts AC power from the wall outlet into DC power used by computer components.

- Provides different voltages: +3.3V, +5V, +12V
- Power rating measured in watts (W)
- Efficiency rating: 80 Plus Bronze, Silver, Gold, Platinum, Titanium

---

## 8. Cooling

Components generate heat. Cooling keeps them within safe temperatures.

- **Air cooling** — fans and heatsinks
- **Liquid cooling** — water or coolant loop
- **Thermal paste** — improves heat transfer between CPU and heatsink

Overheating can cause slowdowns, crashes, or permanent damage.

---

## 9. Input and Output Devices

### Input

- Keyboard
- Mouse
- Microphone
- Webcam
- Scanner
- Touchscreen

### Output

- Monitor
- Speakers
- Printer
- Projector

### Input/Output

- USB flash drive
- External hard drive
- Network adapter
- Touchscreen

---

## 10. Buses and Communication

A bus is a communication path between components.

- **Front Side Bus** — CPU to memory (older systems)
- **PCIe** — high-speed expansion cards
- **SATA** — storage devices
- **USB** — peripherals
- **Memory bus** — CPU to RAM

### DMA (Direct Memory Access)

DMA allows devices to transfer data directly to/from RAM without constant CPU involvement. This improves performance.

---

## 11. Boot Process

When you press the power button:

1. **PSU** supplies power.
2. **BIOS/UEFI** starts and runs a self-test (POST).
3. **Boot device** is selected (SSD, HDD, USB).
4. **Bootloader** loads the operating system.
5. **OS kernel** initializes hardware and starts services.
6. **User session** begins.

---

## 12. How It All Works Together

1. You type on the keyboard (input).
2. The CPU receives the signal and processes it.
3. Data is stored in RAM temporarily.
4. The GPU renders the result on the monitor.
5. Files are saved to SSD or HDD (storage).
6. The PSU provides power to all components.
7. The motherboard connects everything.

---

## 13. Summary

- **CPU** executes instructions.
- **RAM** stores data temporarily.
- **Storage** keeps data permanently.
- **Motherboard** connects all parts.
- **GPU** handles graphics and parallel tasks.
- **PSU** provides power.
- **Cooling** prevents overheating.
- **Peripherals** allow input and output.
- **Buses** move data between components.

A computer is a system where all parts depend on each other. Understanding each component helps you understand how software runs on hardware.

---

## Further Reading

- [How Computers Work](https://computer.howstuffworks.com/pc.htm)
- [Computer Hardware Basics](https://www.geeksforgeeks.org/computer-hardware/)
- [Inside a Computer](https://www.explainthatstuff.com/howcomputerswork.html)