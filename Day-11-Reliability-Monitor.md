# Class 11: Reliability Monitor — The Health Report of Windows

## Learning Objectives

By the end of this class, you should understand:

- What Reliability Monitor is
- How it tracks system stability
- How to identify crashes and failures
- Why it is useful for troubleshooting
- How to open and use Reliability Monitor

---

# What is Reliability Monitor?

**Reliability Monitor** is a built-in Windows tool that tracks the health and stability of your computer over time.

It records:

- Application crashes
- Windows failures
- Driver issues
- Hardware problems
- Software installations
- Windows updates

---

# Real-Life Analogy

```text
Student Report Card
↓
Shows Performance Over Time

Reliability Monitor
↓
Shows PC Stability Over Time
```

---

# Reliability Score

Windows assigns a stability score from:

```text
1 to 10
```

### Score 10

```text
Very Stable
```

### Score 1

```text
Many Problems
```

Higher scores indicate a healthier system.

---

# Why Reliability Monitor Is Useful

Example:

```text
Chrome crashes every day
```

Reliability Monitor may show:

```text
Day 1 → Chrome Crash
Day 2 → Chrome Crash
Day 3 → Chrome Crash
```

This helps identify patterns.

---

# Types of Events

## Critical Events

Examples:

- Application crashes
- Windows crashes
- Unexpected shutdowns

Shown with:

```text
Red X
```

---

## Warnings

Examples:

- Driver problems
- Minor system issues

---

## Information

Examples:

- Software installation
- Windows updates
- Successful operations

---

# How to Open Reliability Monitor

## Method 1

```text
Windows + R
↓
perfmon /rel
↓
Enter
```

---

# Reading the Timeline

Reliability Monitor displays:

```text
Date
↓
Events
↓
System Stability Score
```

You can click a day to view details.

---

# Why Technicians Use Reliability Monitor

Instead of searching through thousands of Event Viewer logs:

```text
Reliability Monitor
↓
Shows Problems Clearly
↓
By Date
```

This makes troubleshooting easier.

---

# Professor's Gold Rule #12

> When a user says "it crashes sometimes," check Reliability Monitor to find patterns.

---

# Quiz

## Q1

Reliability Monitor tracks:

A. Computer health and stability

B. Music files

C. Photos

### Answer

**A. Computer health and stability**

---

## Q2

What score is most stable?

A. 1

B. 5

C. 10

### Answer

**C. 10**

---

## Q3

Which command opens Reliability Monitor?

A. notepad

B. perfmon /rel

C. calc

### Answer

**B. perfmon /rel**

---

## Q4

Application crashes are usually shown as:

A. Critical Events

B. Wallpapers

C. Folders

### Answer

**A. Critical Events**

---

# Your Quiz Results

```text
Q1 = A ✅
Q2 = C ✅
Q3 = B ✅
Q4 = A ✅
```

Score:

```text
4 / 4
```

---

# Practical Exercise

Status:

```text
Pending
```

Tasks:

1. Open Reliability Monitor
2. Check Reliability Score
3. Count recent Red X (Critical Events)

---

# Key Takeaways

- Reliability Monitor tracks Windows stability.
- It provides a score from 1 to 10.
- Critical Events often indicate crashes.
- It helps identify recurring problems.
- It is often easier to read than Event Viewer.

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
12. When a problem happens occasionally, use Reliability Monitor to find patterns.

---

# Class 11 Status

✅ Theory Passed

```text
Quiz Score: 4 / 4
```

```text
Practical Exercise: Pending
```