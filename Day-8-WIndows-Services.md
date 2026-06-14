# Class 8: Windows Services — The Hidden Workers

## Learning Objectives

By the end of this class, you should understand:

- What Windows Services are
- Why services run in the background
- How services support Windows features
- How to view services safely
- Why disabling services can cause problems

---

# What is a Windows Service?

A **Windows Service** is a program that runs in the background, usually without a visible window.

Services help Windows perform important tasks automatically.

Examples:

- Windows Update
- Windows Defender
- Print Spooler
- Network Services

Unlike normal applications, services often start automatically when Windows boots.

---

# Real-Life Analogy

```text
Restaurant
│
├── Customers = Applications
│
└── Kitchen Staff = Services
```

Customers see the food, but the kitchen staff do most of the work behind the scenes.

Similarly, users see applications, while services keep Windows running properly.

---

# Why Are Services Important?

Services provide critical functions such as:

- Internet connectivity
- Security protection
- Device communication
- Printing
- Windows updates
- User authentication

Without these services, many Windows features would stop working.

---

# Examples of Common Services

## Windows Update

Purpose:

- Downloads Windows updates
- Installs security patches

If stopped:

- Updates may fail

---

## Windows Defender

Purpose:

- Protects the computer from malware
- Provides real-time security

If stopped:

- Security protection may be reduced

---

## Print Spooler

Purpose:

- Manages print jobs

If stopped:

- Printing may stop working

---

# How to View Services

## Method 1: Task Manager

1. Press:

```text
Ctrl + Shift + Esc
```

2. Open **Task Manager**
3. Click **Services**

You will see:

- Service Name
- Status
  - Running
  - Stopped

---

# Service Status

## Running

```text
Service is active and working.
```

Example:

```text
Windows Update = Running
```

---

## Stopped

```text
Service is not currently running.
```

Example:

```text
Print Spooler = Stopped
```

Printing may not work until the service starts again.

---

# Practical Exercise

## Your Results

```text
Running Services: Approximately 100–110
```

---

# Analysis

This is normal.

Windows uses many services for:

- Networking
- Security
- Hardware support
- Updates
- User management
- Background system operations

Having around 100–110 services does not indicate a problem.

---

# Professor's Gold Rule #9

> Never disable a Windows service unless you understand what it does.

---

# Quiz

## Q1

A Windows Service usually:

A. Runs in the background

B. Is a hardware component

C. Is a monitor

### Answer

**A. Runs in the background**

### Explanation

Services work behind the scenes without requiring a visible window.

---

## Q2

Which is an example of a service?

A. Windows Update

B. Keyboard

C. Screen

### Answer

**A. Windows Update**

### Explanation

Windows Update is a background service responsible for downloading and installing updates.

---

## Q3

Where can you see services?

A. Calculator

B. Task Manager

C. Paint

### Answer

**B. Task Manager**

### Explanation

Task Manager contains a Services tab that displays running and stopped services.

---

## Q4

Should you disable random Windows services?

A. Yes

B. No

### Answer

**B. No**

### Explanation

Disabling important services can break Windows features and cause system problems.

---

# Challenge Question

## Scenario

```text
Windows Update Service = Stopped
```

User reports:

```text
Windows updates are not downloading.
```

What is the most likely cause?

A. Monitor is broken

B. Windows Update service is not running

C. Mouse is disconnected

### Answer

**B. Windows Update service is not running**

### Explanation

If the Windows Update service is stopped, Windows cannot properly download or install updates.

---

# Key Takeaways

- Windows Services run in the background.
- Services support important Windows functions.
- Many services start automatically with Windows.
- Task Manager can be used to view services.
- Running 100+ services is normal.
- Never disable services unless you understand their purpose.

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

---

# Class 8 Status

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
