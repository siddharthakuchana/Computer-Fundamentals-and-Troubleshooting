# Class 13: CHKDSK — Checking Disk Health

## Learning Objectives

By the end of this class, you should understand:

- What CHKDSK is
- What disk errors are
- How Windows checks a drive for problems
- How to run CHKDSK
- When to use CHKDSK during troubleshooting

---

# What is CHKDSK?

**CHKDSK (Check Disk)** is a built-in Windows tool that scans storage drives for problems.

It checks:

- File system errors
- Disk structure issues
- Bad sectors
- Storage-related problems

---

# Real-Life Analogy

```text
Mechanic
↓
Inspects Car
↓
Finds Problems

CHKDSK
↓
Inspects Drive
↓
Finds Problems
```

---

# Why Is CHKDSK Important?

A storage drive can develop problems over time.

Possible symptoms:

- Files disappearing
- Corrupted files
- Slow file access
- Unexpected errors
- Problems opening folders

CHKDSK helps detect and sometimes repair these issues.

---

# What Does CHKDSK Check?

## File System Errors

Examples:

```text
Broken File References
Directory Problems
Storage Structure Errors
```

---

## Bad Sectors

A bad sector is a damaged area of a storage drive.

Examples:

```text
Unreadable Data
Corrupted Files
Disk Errors
```

---

# How to Run CHKDSK

## Basic Scan

Open Command Prompt and run:

```text
chkdsk
```

This checks the drive and reports problems.

---

## Scan and Repair

Run:

```text
chkdsk C: /f
```

Where:

```text
C:
```

is the drive being checked.

---

# What Does /f Mean?

```text
/f
```

tells Windows to:

```text
Find Errors
↓
Attempt Repairs
```

---

# Possible Results

## No Errors Found

Example:

```text
Windows has scanned the file system
and found no problems.
```

Meaning:

```text
Drive Appears Healthy
```

---

## Errors Found

Example:

```text
Errors detected
```

Meaning:

```text
File System Problems Found
```

Further repairs may be required.

---

# Your Practical Exercise

Result:

```text
No Errors Found
```

✅ Good result.

This indicates CHKDSK did not find obvious file system issues on the drive checked.

---

# When Should You Use CHKDSK?

Use CHKDSK when:

- Files behave strangely
- Folder access becomes unreliable
- Disk-related errors appear
- Windows reports storage issues

---

# Professor's Gold Rule #14

> If files or folders behave strangely, check the disk before blaming Windows.

---

# Quiz

## Q1

What does CHKDSK check?

A. Disk health and file system errors

B. Photos

C. RAM

### Answer

**A. Disk health and file system errors**

---

## Q2

What does CHKDSK stand for?

A. Check Driver

B. Check Disk

C. Check Desktop

### Answer

**B. Check Disk**

---

## Q3

Which command runs CHKDSK?

A. sfc /scannow

B. taskmgr

C. chkdsk

### Answer

**C. chkdsk**

---

## Q4

What does `/f` do?

A. Fixes file system errors

B. Formats the disk

C. Finds photos

### Answer

**A. Fixes file system errors**

---

# Your Quiz Results

```text
Q1 = A ✅
Q2 = B ✅
Q3 = C ✅
Q4 = A ✅
```

Score:

```text
4 / 4
```

---

# Key Takeaways

- CHKDSK stands for Check Disk.
- It scans storage drives for errors.
- It can detect file system problems.
- The `/f` option attempts repairs.
- CHKDSK is useful when files or folders behave unexpectedly.
- A clean CHKDSK result is a good sign of drive health.

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
12. Use Reliability Monitor to find recurring problems.
13. When Windows acts strangely, check system files before reinstalling Windows.
14. If files or folders behave strangely, check the disk before blaming Windows.

---

# Class 13 Status

✅ Quiz Passed

✅ Practical Exercise Completed

```text
Quiz Score: 4 / 4
```

```text
Practical Result: No Errors Found
```

🏆 Passed with Full Marks
