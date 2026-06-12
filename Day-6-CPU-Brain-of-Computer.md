# Class 6: CPU — The Brain of the Computer

## Learning Objectives

By the end of this class, you should understand:

- What a CPU is
- What CPU usage (%) means
- What happens when CPU usage reaches 100%
- How to identify a CPU bottleneck
- How to check CPU usage using Task Manager

---

# What is a CPU?

**CPU** stands for **Central Processing Unit**.

The CPU is often called the **brain of the computer** because it executes instructions and performs calculations.

Examples of tasks that require CPU usage:

- Opening applications
- Browsing the internet
- Watching videos
- Running code
- Playing games

---

# Real-Life Analogy

Imagine your brain while studying.

- Few tasks → Relaxed
- Many tasks → Busy
- Too many tasks → Overloaded

The CPU behaves the same way.

| Human | Computer |
|---------|---------|
| Brain | CPU |
| Thinking | Processing Instructions |

---

# Understanding CPU Usage

CPU usage is displayed as a percentage in Task Manager.

### CPU = 5%

```text
Mostly idle
```

### CPU = 50%

```text
Moderately busy
```

### CPU = 100%

```text
Fully occupied
```

At 100%, the CPU has no spare processing capacity available.

---

# What Happens When CPU Reaches 100%?

Common symptoms:

- Programs respond slowly
- Mouse movement may lag
- Applications may freeze temporarily
- Games stutter
- Fans may become louder
- Overall system feels sluggish

---

# CPU Bottleneck Example

Scenario:

```text
CPU = 100%
RAM = 45%
Disk = 10%
```

### Analysis

- CPU is fully occupied
- RAM is healthy
- Disk is healthy

### Conclusion

**CPU is the bottleneck.**

---

# How to Check CPU Usage

1. Press:

```text
Ctrl + Shift + Esc
```

2. Open **Task Manager**
3. Click **Performance**
4. Select **CPU**

You can view:

- Usage (%)
- Speed (GHz)
- Number of Cores
- Number of Logical Processors

---

# Practical Exercise Results

## Your Results

```text
CPU Usage = 8%
CPU Speed = 0.96 GHz
```

### Analysis

#### CPU Usage = 8%

- Very low usage
- Processor is mostly idle
- No CPU bottleneck

#### CPU Speed = 0.96 GHz

This is normal.

Modern processors reduce their speed when idle to save power and reduce heat.

When heavier tasks start, the CPU automatically increases its speed.

---

# Professor's Gold Rule #7

> If CPU usage stays near 100%, find the process causing it before doing anything else.

---

# Quiz

## Q1

CPU is the:

- A. Storage Device
- B. Brain of the Computer
- C. Monitor

### Answer

**B. Brain of the Computer**

### Explanation

The CPU executes instructions and controls processing.

---

## Q2

What does CPU = 100% mean?

- A. CPU is idle
- B. CPU is fully occupied
- C. RAM is full

### Answer

**B. CPU is fully occupied**

### Explanation

The processor is working at maximum capacity.

---

## Q3

Scenario:

```text
CPU = 100%
RAM = 50%
Disk = 15%
```

Most likely bottleneck?

- A. CPU
- B. RAM
- C. Disk

### Answer

**A. CPU**

### Explanation

CPU is fully utilized while RAM and Disk have plenty of available capacity.

---

## Q4

Where can you see CPU usage?

- A. Notepad
- B. Task Manager
- C. Calculator

### Answer

**B. Task Manager**

### Explanation

Task Manager displays CPU, RAM, Disk, and other performance metrics.

---

# Challenge Question

## Scenario

```text
CPU = 100%
RAM = 35%
Disk = 12%
```

Laptop feels slow.

### Answer

**A. CPU**

### Reason

- CPU is fully occupied
- RAM is healthy
- Disk is healthy

Therefore, the CPU is the bottleneck.

---

# Key Takeaways

- CPU is the brain of the computer.
- CPU executes instructions and calculations.
- CPU usage is measured as a percentage.
- CPU usage near 100% can cause slowdowns.
- Task Manager helps identify CPU bottlenecks.
- Always identify the process causing high CPU usage before taking action.

---

# Professor's Rules Learned So Far

1. What was the last thing that worked?
2. Check Task Manager before guessing.
3. The component closest to 100% is often the bottleneck.
4. Check which process uses resources before closing apps.
5. Slow storage can make a good PC feel slow.
6. RAM above 90% often causes slowdowns.
7. If CPU usage stays near 100%, find the responsible process first.

---

# Class 6 Status

✅ Passed

**Quiz Score:** 4/4

**Challenge Question:** Correct

**Overall Result:** Passed with Full Marks
