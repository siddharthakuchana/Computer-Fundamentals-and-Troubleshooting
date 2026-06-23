# Class 14: DISM — Repairing the Windows Image

## Learning Objectives

By the end of this class, you should understand:

- What DISM is
- What a Windows image is
- How DISM repairs Windows
- When to use DISM
- How DISM works with SFC

---

# What is DISM?

**DISM** stands for:

```text
Deployment Image Servicing and Management
```

It is a built-in Windows tool used to check and repair the Windows image.

---

# What is a Windows Image?

A Windows image contains the files and components that Windows uses to repair itself.

Think of it as:

```text
Master Copy of Windows Files
```

When Windows needs to repair damaged files, it often uses this image as the repair source.

---

# Why Do We Need DISM?

Sometimes system files become corrupted.

Normally:

```text
SFC
↓
Repairs System Files
```

However, if the Windows image itself is damaged:

```text
SFC
↓
Cannot Repair Files
```

In that case:

```text
Run DISM
↓
Repair Windows Image
↓
Run SFC Again
```

---

# Relationship Between SFC and DISM

## SFC

Checks:

```text
System Files
```

Repairs:

```text
Corrupted Windows Files
```

---

## DISM

Checks:

```text
Windows Image
```

Repairs:

```text
Windows Repair Source
```

---

# Real-Life Analogy

Imagine:

```text
Photocopy Machine
↓
Creates Copies
```

If a copy is damaged:

```text
Use Original Copy
↓
Create New Copy
```

But if the original copy is damaged:

```text
Repair Original First
```

DISM repairs the "original copy" used by Windows.

---

# How to Run DISM

## Step 1

Open:

```text
Command Prompt (Administrator)
```

---

## Step 2

Run:

```text
DISM /Online /Cleanup-Image /RestoreHealth
```

---

## Step 3

Wait for the process to finish.

This may take several minutes.

---

# Understanding the Command

```text
/Online
```

Works on the currently running Windows installation.

---

```text
/Cleanup-Image
```

Checks and services the Windows image.

---

```text
/RestoreHealth
```

Repairs corruption if found.

---

# Possible Results

## No Corruption Found

Example:

```text
No component store corruption detected.
```

Meaning:

```text
Windows Image Healthy
```

---

## Corruption Repaired

Example:

```text
The restore operation completed successfully.
```

Meaning:

```text
Corruption Found
↓
Successfully Repaired
```

---

# Your Practical Exercise

Result:

```text
Completed Successfully: Yes
Corruption Found: No
```

Meaning:

```text
Windows Image Healthy
```

Excellent result.

---

# When Should You Use DISM?

Use DISM when:

- SFC cannot repair files
- Windows behaves strangely
- System corruption is suspected
- Windows repair operations fail

---

# Professor's Gold Rule #15

> If SFC cannot repair Windows, run DISM before considering a reinstall.

---

# Quiz

## Q1

What does DISM repair?

A. Windows Image

B. Photos

C. RAM

### Answer

**A. Windows Image**

---

## Q2

What does DISM stand for?

A. Disk Manager

B. Deployment Image Servicing and Management

C. Driver Installation Service Manager

### Answer

**B. Deployment Image Servicing and Management**

---

## Q3

Which command repairs the Windows image?

A. chkdsk

B. taskmgr

C. DISM /Online /Cleanup-Image /RestoreHealth

### Answer

**C. DISM /Online /Cleanup-Image /RestoreHealth**

---

## Q4

If SFC cannot repair files, what should you try next?

A. DISM

B. Paint

C. Calculator

### Answer

**A. DISM**

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

- DISM repairs the Windows image.
- SFC repairs system files.
- If SFC fails, DISM is often the next step.
- DISM can repair the source used by SFC.
- A successful DISM scan with no corruption is a good sign.

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
15. If SFC cannot repair Windows, run DISM before considering a reinstall.

---

# Class 14 Status

✅ Quiz Passed

✅ Practical Exercise Completed

```text
Quiz Score: 4 / 4
```

```text
Practical Result:
Completed Successfully = Yes
Corruption Found = No
```

🏆 Passed with Full Marks