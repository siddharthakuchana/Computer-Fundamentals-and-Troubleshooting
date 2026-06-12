# Class 5: How Windows Uses RAM

## Learning Objectives

By the end of this class, you should understand:

- What RAM is
- What happens when RAM becomes full
- What Virtual Memory (Page File) is
- Why computers slow down when RAM is exhausted
- How to identify a RAM bottleneck

---

# What is RAM?

**RAM (Random Access Memory)** is the computer's temporary working memory.

## Analogy

| Real Life | Computer |
|------------|------------|
| Study Desk | RAM |
| Bookshelf | Storage (HDD/SSD) |

A larger desk lets you work with more books at once.

---

# What Uses RAM?

Examples:

- Brave Browser
- Chrome
- VS Code
- Spotify
- Windows itself

Every running application occupies some RAM.

---

# What Happens When RAM Gets Full?

When RAM reaches around **95–100%**, Windows needs extra space.

It starts using:

## Virtual Memory (Page File)

Windows moves less-used data from RAM to storage.

```text
RAM Full
↓
Windows moves data
↓
Page File (HDD/SSD)
↓
Computer slows down
```

This process is called **Paging**.

---

# Why Does This Cause Slowdowns?

RAM is very fast.

Storage is slower:

```text
RAM > SSD > HDD
```

When Windows constantly moves data between RAM and storage:

- Applications become slow
- Browser tabs reload
- Switching between apps becomes sluggish
- Temporary freezes may occur

---

# Professor's Gold Rule #6

> If RAM usage is above 90%, expect slowdowns.

---

# Practical Exercise

## Your Results

```text
Total RAM     : 8 GB
Used RAM      : 4.8 GB
Available RAM : 3.1 GB
```

## Analysis

```text
4.8 ÷ 8 × 100 ≈ 60%
```

Result:

- RAM is healthy
- Plenty of memory available
- No RAM bottleneck

---

# Quiz

## Q1

RAM is:

- A. Permanent Memory
- B. Temporary Memory

**Answer:** B

### Explanation

RAM only stores data while the computer is running. When power is removed, RAM is cleared.

---

## Q2

When RAM becomes full, Windows starts using:

- A. CPU
- B. Page File / Virtual Memory
- C. Monitor

**Answer:** B

### Explanation

Windows moves less-used data from RAM to the Page File stored on disk.

---

## Q3

Which is faster?

- A. RAM
- B. HDD

**Answer:** A

### Explanation

RAM is significantly faster than HDD storage.

---

## Q4

Scenario:

```text
RAM = 97%
CPU = 15%
Disk = 20%
```

Most likely bottleneck?

- A. CPU
- B. RAM
- C. Disk

**Answer:** B

### Explanation

RAM is nearly full while CPU and Disk still have plenty of capacity.

---

# Challenge Question

## Scenario

```text
RAM = 99%
CPU = 10%
Disk = 15%
```

Laptop is lagging badly.

### Answer

**B. RAM**

### Reason

- RAM is almost full
- CPU has plenty of capacity available
- Disk is not heavily used

Therefore, RAM is the bottleneck.

---

# Key Takeaways

- RAM is temporary memory.
- Running applications consume RAM.
- Windows uses Virtual Memory when RAM becomes full.
- Paging can slow down a computer.
- RAM is much faster than storage.
- High RAM usage causes slowdowns.
- Always check Task Manager before guessing.
- RAM above 90% deserves attention.

---

# Class 5 Status

**Passed**

**Score:** 5/5
