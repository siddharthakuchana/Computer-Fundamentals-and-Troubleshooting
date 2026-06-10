# Day 2: CPU, RAM and Storage

## Introduction

Every computer relies on three major components:

1. CPU
2. RAM
3. Storage

Understanding their responsibilities is essential for troubleshooting and performance optimization.

---

## CPU (Central Processing Unit)

The CPU is often called the brain of the computer.

Its primary responsibility is executing instructions.

Examples of tasks handled by the CPU:

- Running applications
- Performing calculations
- Processing user input
- Managing operating system tasks

### Important CPU Characteristics

#### Clock Speed

Measured in GHz.

Example:

- 2.3 GHz

Higher clock speeds generally allow more instructions to be processed each second.

#### Cores

Modern CPUs contain multiple cores.

Examples:

- Dual Core
- Quad Core
- Six Core
- Eight Core

Multiple cores improve multitasking performance.

---

## RAM (Random Access Memory)

RAM is temporary memory used by running applications.

When a program starts:

1. Data is copied from storage.
2. Data is loaded into RAM.
3. CPU accesses RAM for processing.

### Characteristics

- Fast
- Temporary
- Volatile

When power is removed, RAM contents disappear.

---

## Storage

Storage permanently saves data.

Examples:

- Operating System
- Applications
- Documents
- Images
- Videos

Unlike RAM, data remains after shutdown.

---

## Computer Analogy

| Human Example | Computer Component |
|--------------|-------------------|
| Brain | CPU |
| Desk Workspace | RAM |
| Bookshelf | Storage |

---

## Performance Bottlenecks

A bottleneck occurs when one component limits overall performance.

### CPU Bottleneck

Symptoms:

- High CPU usage
- System lag
- Slow application response

### RAM Bottleneck

Symptoms:

- Frequent freezing
- Heavy disk activity
- Browser tab crashes

### Storage Bottleneck

Symptoms:

- Slow boot times
- Slow file access
- Slow application launching

---

## Using Task Manager

Open Task Manager:

```text
Ctrl + Shift + Esc
```

Monitor:

- CPU Usage
- Memory Usage
- Disk Usage
- Network Usage

---

## Example Analysis

```text
CPU = 2%
Memory = 63%
Disk = 7%
GPU = 0%
```

Interpretation:

- CPU healthy
- Memory healthy
- Disk healthy
- No major bottleneck

---

## Troubleshooting Principle

> The component closest to 100% usage is usually the bottleneck.

Always measure before making assumptions.

---

## Key Takeaways

- CPU performs calculations.
- RAM stores active data.
- Storage saves permanent data.
- Task Manager helps identify performance problems.
- High utilization often indicates a bottleneck.
