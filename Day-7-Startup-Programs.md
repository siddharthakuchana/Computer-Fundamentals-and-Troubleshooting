# Class 7: Startup Programs and Why Windows Becomes Slow After Login

## Learning Objectives

By the end of this class, you should understand:

- What startup programs are
- Why too many startup programs can slow down a computer
- How to check startup applications
- How to identify startup-related bottlenecks
- How to use Task Manager to manage startup apps

---

# What Are Startup Programs?

Startup programs are applications that automatically launch when Windows starts.

### Examples

- Microsoft Teams
- Discord
- Spotify
- Steam
- OneDrive
- Antivirus software

These programs start in the background after you log in.

---

# Why Can Startup Programs Slow Down a PC?

Imagine 20 people trying to enter a room through one door at the same time.

Everything becomes slower.

The same thing happens when many programs start together.

### Effects

- Increased CPU usage
- Increased RAM usage
- Increased Disk usage
- Slower login experience
- Windows takes longer to become responsive

---

# Startup Process Example

```text
Windows Starts
↓
Discord Starts
↓
Spotify Starts
↓
Steam Starts
↓
OneDrive Starts
↓
Antivirus Starts
↓
PC Feels Slow
```

---

# Startup Impact

Windows estimates how much each startup program affects boot performance.

## Low Impact

- Small effect on startup speed

## Medium Impact

- Moderate effect on startup speed

## High Impact

- Significant effect on startup speed

---

# How to Check Startup Programs

## Method

1. Press:

```text
Ctrl + Shift + Esc
```

2. Open **Task Manager**
3. Click **Startup Apps** (or **Startup**)
4. Review the list

You will see:

- Application Name
- Status (Enabled/Disabled)
- Startup Impact

---

# Practical Exercise

## Your Results

```text
Enabled Startup Apps: 3
High Impact Apps: None
Startup Impact: Not Measured
```

---

# Analysis

### Good Findings

- Only 3 startup applications are enabled
- No High Impact applications detected
- Startup configuration is relatively light

### Conclusion

Startup programs are unlikely to be a major cause of slow performance on your laptop.

---

# Professor's Gold Rule #8

> The fewer unnecessary startup programs you have, the faster Windows usually becomes ready after login.

---

# Quiz

## Q1

What is a startup program?

A. A program that starts automatically with Windows

B. A program that only runs at shutdown

C. A hardware device

### Answer

**A**

### Explanation

Startup programs launch automatically when Windows starts.

---

## Q2

Too many startup programs can increase:

A. CPU usage

B. RAM usage

C. Boot time

D. All of the above

### Answer

**D**

### Explanation

Too many startup programs can affect CPU, RAM, Disk activity, and overall boot time.

---

## Q3

Where can you view startup applications?

A. Paint

B. Task Manager

C. Calculator

### Answer

**B**

### Explanation

Task Manager contains a Startup Apps section for managing startup programs.

---

## Q4

Which startup impact is the largest?

A. Low

B. Medium

C. High

### Answer

**C**

### Explanation

High Impact applications have the greatest effect on startup performance.

---

# Challenge Question

## Scenario

```text
15 Startup Apps Enabled
CPU = 90%
RAM = 85%
```

What is the most likely cause?

A. Too many startup programs

B. Bad monitor

C. Keyboard problem

### Answer

**A. Too many startup programs**

### Explanation

A large number of startup programs can heavily increase CPU and RAM usage immediately after login.

---

# Key Takeaways

- Startup programs launch automatically when Windows starts.
- Too many startup programs can slow down login and startup.
- Startup applications consume CPU, RAM, and Disk resources.
- Task Manager can be used to view and manage startup apps.
- Fewer unnecessary startup programs generally improve startup performance.
- Startup Impact helps identify applications that affect boot speed.

---

# Professor's Rules Learned So Far

1. What was the last thing that worked?
2. Check Task Manager before guessing.
3. The component closest to 100% is often the bottleneck.
4. Check which process uses resources before closing apps.
5. Slow storage can make a good PC feel slow.
6. RAM above 90% often causes slowdowns.
7. If CPU usage stays near 100%, find the responsible process first.
8. The fewer unnecessary startup programs you have, the faster Windows becomes ready after login.

---

# Class 7 Status

✅ Passed

## Quiz Score

```text
4 / 4
```

## Challenge Question

```text
Correct
```

## Practical Exercise

```text
Completed
```

## Final Result

🏆 Passed with Full Marks
