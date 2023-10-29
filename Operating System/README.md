# Operating System

## Application Software

- Performs specific task for the user.

## System Software

- operates and control the computer system and provide a platform to run application softwares.

## Operating System

- is a piece of software that manages all the resources of a computer system both hardware and software and provides an environment in which user can execute programs in a convinient and efficient manner by hiding underlying complexity  of the hardware and acting as a resource manager.

## Why OS ?

- **Resource Management** (ensures we have all the needed resources and making efficient use of resources such as cpu, gpu, memory and disk space.)
- Act as an **interface** between user and computer hardware.
- **Isolation** and **Protection.**

## If there is no OS ?

- Bulky and complex app. (hardware interaction code must be in app’s code base)
- Resource exploitation by 1 App (eat’s up all the resources).
- No memory protection.

## Operation System Functions

- Access to Computer Hardaware.
- Resource Management (arbitration).
- Act as Interface.
- Hides the underlying complexity of the hardware.
- Facilitates execution of application programs by providing isolation and protection.

## Goals of OS

- Maximum CPU Utilization.
- No Process Starvation.
- High Priority Execution.

## Types of OS

### Single Process OS

- Execute only one process at a time till it not executed completely.
- No max cpu utilization.
- process starvation will be there.
- No priority Execution.
- eg MSDOS

### Batch Processing OS

- Jobs loaded in form of punch cards, paper and  Magnet tapes.
- Operator convert these cards into batches.
- These batches are provided to CPU and sequentially executed.
- If any I/O operation is performed then cpu will become idle till the I/O process is not completed. Therefore process starvation, no max cpu utilization and no priority execution.
- eg ATLAS

### Multi Programming OS

- Single Cpu, ready queue contains various jobs ( which are ready to be executed).
- Whenever some process get to I/O then cpu will start executing the jobs from ready queue.
- It allows context-switching if some process went for I/O to achieve max cpu utilization with the help of PCB (process control block).
- eg THE

### Multi Taksing OS

- Single Cpu, Context-Switching is there and we can say its is enhanced version of MultiProgramming OS.
- It supports time sharing i.e a time quantam is associated with every process so that no process starvation is there.
- Therefore, Cpu witilization is maximum, less process starvation and context switching is allowed (so that high priority process can be executed first).
- eg CTSS

### Multi Processing OS

- Multiple Cpu.
- Context-Switching, Time Sharing.
- Maximum Cpu Utilization and less Process Starvation, better throughput.
- eg Windows

### Distrbuted OS

- Loosley coupled, autonomous interconnected computers work together.
- Collection of independent, networked, communication and physically seperate computaional nodes.
- So, there are many resouces and we can execute many  jobs, there may be many users.
- eg SOLARIS, LOCUS

### Real Time OS

- Realtime error free, computation within tight-time boundaries.
- Negligible Error chance.
- eg Medical Imagining Systems, Airline Traffic Control System.