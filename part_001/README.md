# Part 1: Introduction to Software and Operating Systems

## What is Software?

Software is a collection of data, programs, and instructions that tell a computer how to perform specific tasks. It serves as the logical interface allowing humans to interact with computer hardware, which would otherwise be unusable. Software is written in programming languages, compiled or interpreted into machine code that the computer's processor can execute.

### Types of Software

Software can be broadly categorized into two main types:

1. **System Software**: This type of software is responsible for managing and controlling computer hardware and providing a platform for other software to run. It serves as an interface between hardware and users.
   - **Examples**: Operating systems (Windows, macOS, Linux), device drivers, firmware, utility programs, compilers
   - **Purpose**: Manages hardware resources, provides services to applications, enables basic computer functionality

2. **Application Software**: This type of software is designed to help users perform specific tasks or activities, delivering functionality for practical user purposes.
   - **Examples**: Word processors (Microsoft Word, Google Docs), web browsers (Chrome, Firefox), media players (VLC), photo editors (Photoshop), games, mobile apps
   - **Purpose**: Enables users to perform specific tasks, solve problems, and enhance productivity

3. **Programming Software**: Tools that programmers use to create, debug, maintain, and support other programs and applications.
   - **Examples**: Integrated Development Environments (VSCode, IntelliJ), compilers, debuggers
   - **Purpose**: Provides tools and interfaces for software development

## What is an Operating System?

An operating system (OS) is system software that manages computer hardware, software resources, and provides common services for computer programs. It acts as an intermediary between users and the computer hardware, enabling users to interact with the system and run applications efficiently.

### Evolution of Operating Systems

- **1940s-1950s**: No operating systems; computers ran one program at a time
- **1960s**: First generation OS - simple batch systems
- **1970s**: Multiprogramming and time-sharing systems (UNIX)
- **1980s-1990s**: Personal computer OS (MS-DOS, early Windows, Mac OS)
- **2000s-Present**: Modern GUI-based, networked, mobile, and distributed OS

### Popular Operating Systems

- **Desktop/Laptop**: Windows, macOS, Linux distributions
- **Mobile**: Android, iOS
- **Server**: Linux, Windows Server
- **Embedded**: RTOS (Real-Time Operating Systems), embedded Linux

## Why Do We Need Operating Systems?

### Challenges Without an OS

1. **Complexity in Application Development**:
   - Applications would need to include all hardware interaction code
   - Each application would require its own device drivers
   - Programmers would need deep hardware knowledge for every app

2. **Resource Management Issues**:
   - No arbitration for hardware resource access
   - One application could monopolize all system resources
   - No memory protection between applications

3. **Security Concerns**:
   - No protection mechanisms between different programs
   - Malicious software would have direct hardware access
   - No user permission or access control systems

### Components of an Operating System

An operating system is made up of:

1. **Kernel**: The core component that manages CPU, memory, and devices
2. **Device Drivers**: Software interfaces for hardware devices
3. **System Libraries**: Common functions and services for applications
4. **User Interface**: Command-line interface (CLI) or graphical user interface (GUI)
5. **System Utilities**: Tools for system maintenance and configuration

## Operating System Functions

The OS provides several crucial functions:

- **Hardware Abstraction**: Hides the underlying complexity of hardware, providing simplified interfaces
- **Resource Management**: Allocates and manages system resources (CPU, memory, storage, I/O devices)
- **Process Management**: Creates, schedules, and terminates processes
- **Memory Management**: Allocates and deallocates memory space as needed
- **File System Management**: Organizes and maintains files and directories
- **Security and Protection**: Provides authentication, authorization, and isolation between users and processes
- **Error Detection and Handling**: Identifies and responds to hardware and software errors
- **Networking**: Enables communication between devices and access to network resources

## Layers of a Computer System

The computer system operates in distinct layers:

```
┌───────────────────┐
│       Users       │ ← Human users interacting with the system
├───────────────────┤
│    Applications   │ ← Software programs performing specific tasks
├───────────────────┤
│ Operating System  │ ← System software managing resources
├───────────────────┤
│ Computer Hardware │ ← Physical components (CPU, memory, devices)
└───────────────────┘
```

The operating system provides the critical middle layer that facilitates proper use of resources in the computer system, enabling applications to run efficiently while protecting hardware and ensuring fair resource allocation.


what is operating system?

An operating system (OS) is system software that manages computer hardware, software resources, and provides common services for computer programs. It acts as an intermediary between users and the computer hardware, enabling users to interact with the system and run applications efficiently. Examples of popular operating systems include Windows, macOS, Linux, and Android.


Why OS?
1. What if there is no OS?
a. Bulky and complex app. (Hardware interaction code must be in app’s
code base)
b. Resource exploitation by 1 App.
c. No memory protection.
2. What is an OS made up of?
a. Collection of system software.


An operating system function -
- Access to the computer hardware.
- interface between the user and the computer hardware
- Resource management (Aka, Arbitration) (memory, device, file, security, process etc)
- Hides the underlying complexity of the hardware. (Aka, Abstraction)
- facilitates execution of application programs by providing isolation and protection.

Levels of a computer system:

User
Application programs
Operating system
Computer hardware


The operating system provides the means for proper use of the resources in the operation of
the computer system.

