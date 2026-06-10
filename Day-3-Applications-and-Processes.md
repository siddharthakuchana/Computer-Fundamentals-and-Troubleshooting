# Day 3: Applications and Processes

## Introduction

When using a computer, we interact with applications such as Google Chrome, Microsoft Word, Spotify, and Visual Studio Code. However, behind the scenes, the operating system manages these applications through processes.

Understanding the difference between applications and processes is essential for troubleshooting system performance and diagnosing software issues.

---

## What is an Application?

An application is a software program installed on a computer.

Examples:

- Google Chrome
- Microsoft Word
- Spotify
- VLC Media Player
- Visual Studio Code

Applications are stored on a storage device such as an HDD or SSD until they are launched.

### Characteristics of Applications

- Stored permanently on disk.
- Can be installed or uninstalled.
- Do not consume CPU or RAM when not running.
- Become active only when launched.

---

## What is a Process?

A process is a running instance of an application.

Example:

```text
Chrome Installed
       ↓
User Opens Chrome
       ↓
Chrome Process Starts
```

The operating system allocates resources to each process:

- CPU Time
- RAM
- Storage Access
- Network Access

Without processes, applications cannot execute.

---

## Application vs Process

| Application | Process |
|------------|----------|
| Stored on disk | Running in memory |
| Passive | Active |
| Installed software | Executing software |
| Does not consume resources when closed | Consumes CPU and RAM while running |

### Example

Google Chrome installed on your computer is an application.

When Chrome is opened:

- Chrome.exe starts
- Memory is allocated
- CPU resources are assigned

At this point, Chrome becomes a process.

---

## Why Chrome Uses Multiple Processes

Many users are surprised to see multiple Chrome processes in Task Manager.

This is intentional.

Chrome creates separate processes for:

- Browser tabs
- Extensions
- GPU acceleration
- Background services

### Advantages

#### Stability

If one tab crashes, the entire browser usually remains functional.

#### Security

Each process is isolated, reducing security risks.

#### Performance

Multiple processes can utilize multiple CPU cores efficiently.

---

## Understanding Task Manager

Task Manager is a built-in Windows utility that displays information about running processes and system performance.

### Opening Task Manager

Method 1:

```text
Ctrl + Shift + Esc
```

Method 2:

```text
Ctrl + Alt + Delete
→ Task Manager
```

Method 3:

```text
Right Click Taskbar
→ Task Manager
```

---

## Important Task Manager Tabs

### Processes

Displays:

- Running applications
- Background processes
- Resource consumption

### Performance

Displays:

- CPU usage
- Memory usage
- Disk usage
- Network usage
- GPU usage

### Startup

Displays programs that automatically start when Windows boots.

Examples:

- Discord
- Steam
- Spotify

Too many startup applications can increase boot time.

### Users

Displays resource usage by logged-in users.

---

## Understanding Resource Usage

### CPU Usage

Represents processor workload.

Example:

```text
CPU Usage = 95%
```

Indicates:

- Heavy calculations
- Multiple active programs
- Possible performance bottleneck

---

### Memory Usage

Represents RAM consumption.

Example:

```text
Memory Usage = 92%
```

Indicates:

- Insufficient available RAM
- Too many applications running

---

### Disk Usage

Represents storage activity.

Example:

```text
Disk Usage = 100%
```

Indicates:

- Storage bottleneck
- Slow file access
- Slow application loading

---

## What is explorer.exe?

Explorer.exe is one of the most important Windows processes.

Responsibilities:

- Desktop
- Taskbar
- Start Menu
- File Explorer

Without explorer.exe, Windows becomes difficult to use.

---

## Symptoms of Explorer Failure

If explorer.exe crashes:

- Taskbar disappears
- Desktop icons disappear
- Start Menu stops working
- File Explorer may close

---

## Restarting explorer.exe

Task Manager allows Explorer to be restarted.

Steps:

1. Open Task Manager
2. Locate Windows Explorer
3. Right-click
4. Select Restart

This often fixes:

- Frozen taskbar
- Missing desktop icons
- Unresponsive Start Menu

---

## Troubleshooting Example

Scenario:

```text
Chrome = 3.5 GB RAM
Spotify = 150 MB RAM
```

Question:

Which application should be investigated first?

Answer:

Chrome

Reason:

Chrome is consuming significantly more memory.

---

## Troubleshooting Rule

> Before closing applications, identify which process is consuming resources.

Never guess.

Always verify using Task Manager.

---

## Key Takeaways

- Applications are installed software.
- Processes are running instances of applications.
- Every running application creates one or more processes.
- Task Manager is essential for troubleshooting.
- Explorer.exe controls the desktop, taskbar, and Start Menu.
- Resource-heavy processes should be identified before taking action.
