# Class 9: Event Viewer — Windows' Black Box Recorder

## Learning Objectives

By the end of this class, you should understand:

- What Event Viewer is
- Why Windows records events
- The different types of events
- How to find errors and warnings
- How Event Viewer helps troubleshoot problems

---

# What is Event Viewer?

**Event Viewer** is a built-in Windows tool that records important system events.

Think of it as a **black box recorder** for your computer.

It keeps logs of:

- System events
- Application events
- Driver issues
- Service failures
- Warnings
- Errors
- Startup and shutdown events

---

# Real-Life Analogy

```text
Airplane
↓
Black Box Recorder
↓
Stores important events

Computer
↓
Event Viewer
↓
Stores important events
```

When an airplane has a problem, investigators check the black box.

When Windows has a problem, technicians check Event Viewer.

---

# Why Does Windows Record Events?

Windows records events so that problems can be diagnosed later.

Example:

```text
3:00 PM
↓
Laptop Crashes
↓
Event Viewer Shows:
Driver Error at 2:59 PM
```

This gives clues about the cause of the problem.

---

# Event Types

## Information

Represents normal activity.

Examples:

- Windows started successfully
- Service started successfully

Example:

```text
Information
Windows boot completed successfully
```

---

## Warning

Indicates a potential issue.

Examples:

- Low disk space
- Device responding slowly

Example:

```text
Warning
Disk space running low
```

---

## Error

Indicates that something failed.

Examples:

- Application crash
- Driver failure
- Service failure

Example:

```text
Error
Application crashed unexpectedly
```

---

# Important Event Viewer Logs

## Application Log

Records:

- Program crashes
- Software errors
- Application warnings

Examples:

- Chrome crash
- Word crash
- Software installation issues

---

## System Log

Records:

- Driver problems
- Hardware issues
- Windows component failures
- Startup issues

Examples:

- Network driver failure
- Disk errors
- Service failures

---

# How to Open Event Viewer

## Method 1

Press:

```text
Windows + R
```

Type:

```text
eventvwr
```

Press:

```text
Enter
```

---

# How to View System Events

1. Open Event Viewer
2. Expand:

```text
Windows Logs
```

3. Click:

```text
System
```

You will see:

- Information events
- Warning events
- Error events

---

# Practical Exercise

## Your Results

```text
Total Events: Approximately 34,942
Errors: Approximately 100
```

---

# Analysis

This is normal.

Windows records events continuously.

Therefore:

```text
Thousands of Events
```

is expected.

Similarly:

```text
~100 Errors
```

does not automatically mean something is wrong.

Many errors are:

- Old
- Minor
- Automatically corrected by Windows

A troubleshooter becomes interested when:

```text
Problem Occurs
↓
Error Appears at Same Time
```

---

# Can Event Viewer Show Everything You Do?

## What It Can Show

- Application crashes
- Windows updates
- Driver problems
- Service activity
- Startup and shutdown events
- Some application-related events

## What It Usually Cannot Show

- Every app you opened
- Every website visited
- Every file viewed
- A complete activity history

Event Viewer is a troubleshooting tool, not a full activity tracker.

---

# Professor's Gold Rule #10

> When a problem repeats, check the logs instead of guessing.

---

# Quiz

## Q1

Event Viewer is used to:

A. Play games

B. View system events and errors

C. Edit photos

### Answer

**B. View system events and errors**

### Explanation

Event Viewer stores logs that help diagnose Windows problems.

---

## Q2

Which event type usually indicates a failure?

A. Information

B. Error

C. Success

### Answer

**B. Error**

### Explanation

Errors indicate that something failed or did not work correctly.

---

## Q3

Which log commonly records driver issues?

A. System

B. Calculator

C. Paint

### Answer

**A. System**

### Explanation

The System log contains driver, hardware, and Windows component events.

---

## Q4

What command opens Event Viewer?

A. notepad

B. eventvwr

C. calc

### Answer

**B. eventvwr**

### Explanation

Typing `eventvwr` in the Run dialog opens Event Viewer.

---

# Challenge Question

## Scenario

```text
Laptop crashes every day at 4:15 PM
```

What should you check first?

A. Reinstall Windows immediately

B. Event Viewer logs around 4:15 PM

C. Buy a new monitor

### Answer

**B. Event Viewer logs around 4:15 PM**

### Explanation

The logs may reveal the exact error or warning that occurred before the crash.

---

# Key Takeaways

- Event Viewer is Windows' troubleshooting log system.
- It records Information, Warning, and Error events.
- The Application log records software-related events.
- The System log records driver and hardware-related events.
- Thousands of logged events are normal.
- Errors are not always serious.
- Look for events that occur at the same time as the problem.
- Use logs to investigate recurring issues.

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

---

# Class 9 Status

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
