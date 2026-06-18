# Class 10: Device Manager — Windows Hardware Control Center

## Learning Objectives

By the end of this class, you should understand:

- What Device Manager is
- What hardware devices are
- What drivers do
- How to identify hardware problems
- How to use Device Manager for troubleshooting

---

# What is Device Manager?

**Device Manager** is a built-in Windows tool that displays all hardware connected to your computer.

Examples of hardware shown in Device Manager:

- Processor (CPU)
- Keyboard
- Mouse
- Display Adapter (GPU)
- Network Adapter (Wi-Fi/Ethernet)
- Disk Drives
- Audio Devices
- USB Devices

Device Manager helps you see whether Windows can properly detect and communicate with hardware.

---

# What is a Driver?

A **driver** is software that allows Windows to communicate with a hardware device.

Without a driver:

```text
Windows
✖
Hardware
```

With a driver:

```text
Windows
↓
Driver
↓
Hardware
```

Drivers act as translators between the operating system and the hardware.

---

# Real-Life Analogy

Imagine two people speaking different languages.

```text
English Speaker
↓
Translator
↓
Japanese Speaker
```

The translator helps both sides communicate.

A driver works the same way between Windows and hardware.

---

# Examples of Drivers

## Audio Driver

Allows Windows to communicate with speakers and headphones.

Without it:

```text
No Sound
```

---

## Network Driver

Allows Windows to communicate with Wi-Fi and Ethernet hardware.

Without it:

```text
No Internet Connection
```

---

## Graphics Driver

Allows Windows to communicate with the GPU.

Without it:

```text
Poor Graphics Performance
Low Resolution
Display Problems
```

---

# Signs of Driver Problems

Common symptoms include:

- No sound
- Wi-Fi missing
- Printer not working
- USB device not detected
- Display issues
- Slow graphics performance

---

# How to Open Device Manager

## Method 1

1. Press:

```text
Windows + X
```

2. Click:

```text
Device Manager
```

---

## Method 2

1. Press:

```text
Windows + R
```

2. Type:

```text
devmgmt.msc
```

3. Press Enter

---

# Device Categories

Common categories include:

- Disk Drives
- Display Adapters
- Keyboards
- Mice
- Network Adapters
- Processors
- Sound Devices
- USB Controllers

---

# Warning Icons

A yellow warning icon usually means:

```text
Driver Missing
or
Device Problem
```

Example:

```text
⚠ Network Adapter
```

This may indicate:

- Missing driver
- Corrupted driver
- Hardware issue

---

# Why Device Manager Is Important

Suppose:

```text
Wi-Fi disappears
```

Before replacing hardware, check Device Manager.

You might find:

```text
⚠ Network Adapter
```

This suggests a driver issue rather than a broken Wi-Fi card.

---

# Practical Exercise

## Status

Pending (to be completed later)

Tasks:

1. Open Device Manager
2. Check for yellow warning icons
3. Count the approximate number of categories displayed

---

# Professor's Gold Rule #11

> If hardware stops working, check Device Manager before replacing the hardware.

---

# Quiz

## Q1

What does Device Manager show?

A. Hardware devices

B. Photos

C. Documents

### Answer

**A. Hardware devices**

### Explanation

Device Manager displays all hardware detected by Windows.

---

## Q2

What does a driver do?

A. Stores files

B. Acts as a translator between Windows and hardware

C. Displays videos

### Answer

**B. Acts as a translator between Windows and hardware**

### Explanation

Drivers allow Windows and hardware devices to communicate.

---

## Q3

A yellow warning icon often indicates:

A. Device or driver problem

B. Everything is working perfectly

C. Low battery

### Answer

**A. Device or driver problem**

### Explanation

A warning icon usually means Windows has detected an issue.

---

## Q4

Where can you check hardware devices?

A. Calculator

B. Paint

C. Device Manager

### Answer

**C. Device Manager**

### Explanation

Device Manager is the primary Windows tool for viewing hardware devices.

---

# Key Takeaways

- Device Manager shows all hardware detected by Windows.
- Drivers act as translators between Windows and hardware.
- Missing or corrupted drivers can cause hardware problems.
- Yellow warning icons often indicate device or driver issues.
- Device Manager is one of the first tools used for hardware troubleshooting.
- Always check Device Manager before assuming hardware is defective.

---

# Professor's Rules Learned So Far

1. What was the last thing that worked?
2. Check Task Manager before guessing.
3. The component closest to 100% is often the bottleneck.
4. Check which process uses resources before closing apps.
5. Slow storage can make a good PC feel slow.
6. RAM above 90% often causes slowdowns.
7. If CPU usage stays near 100%, find the responsible process first.
8. Fewer unnecessary startup programs improve startup speed.
9. Never disable a Windows service unless you understand what it does.
10. When a problem repeats, check the logs instead of guessing.
11. If hardware stops working, check Device Manager before replacing the hardware.

---

# Class 10 Status

✅ Quiz Passed

## Quiz Score

```text
4 / 4
```

## Practical Exercise

```text
Pending
```

## Final Result

🎓 Theory Passed

⏳ Practical Exercise Pending