- [My Projects](#my-projects)
  - [Own repositories](#own-repositories)
    - [1. BinLTools](#1-binltools)
    - [2. CPU Organization and Design](#2-cpu-organization-and-design)
    - [3. Thread scheduler](#3-thread-scheduler)
    - [4. One Death Clear](#4-one-death-clear)
  - [Open Source projects contributions](#open-source-projects-contributions)
    - [1. Kueue](#1-kueue)


# My Projects

## Own repositories

### 1. BinLTools

Gin Framework-based project.
Used for small features and articles created by the author.

To see the repository, please click [this link](https://github.com/BinL233/BinLTools_Gin).

Website: http://binltools.fun

1. Tech
    - Framework: Gin
    - Frontend: HTML + CSS + JavaScript
    - Backend: Go
    - Database: Mysql

2. Features
    - Login/Registation
        - Password encryption
        - JWT web tokens for users
        - Prevent duplicate logins/registrations
        - Error handlers
    - Reaction Test
        - Automatic upload of scores
        - Ranking System
    - Live2D Widgit
        - Developed based on [l2d](https://github.com/UsernameFull/l2d)
        - Model adaptation
        - Website adaptation
        - Window mousemove tracking
        - Thanks for the L2D model made by [拉莫斯的壳](https://space.bilibili.com/6769942/?spm_id_from=333.999.0.0) !
    - Digit Converter
        - Fast conversion of digits
        - Support Binary, Octal, Decimal and Hexadecimal conversions.
    - Download handler

### 2. CPU Organization and Design
This project implements 5 stages: 
Instruction Fetch, Instruction Decode, Instruction Execute, Memory of the pipelined CPU 
using the Xilinx design package for FPGAs.

To see the repository, please click [this link](https://github.com/BinL233/Computer-Organization-and-Design)

1. Tech
   - Software: Vivado
   - Language: Verilog
2. Features:
   - Pipelining
   - Circuits of the Instruction Fetch Stage
   - Circuits of the Instruction Decode Stage
   - Circuits of the Execution Stage
   - Circuits of the Memory Access Stage
   - Circuits of the Write Back Stage


### 3. Thread scheduler

This repository contains code for emulation of a single CPU with 
the Shortest Remaining Time First scheduling policy 
and two IO Devices based thread scheduler.

To see the repository, please click [this link](https://github.com/BinL233/Thread-scheduler).

1. Languages
   - C language
   - Makefile

2. Features
   - Implemented and parsed various mechanisms for virtual memory to 
   physical memory to page mapping and page scheduling algorithms (FIFO, LRU, CLOCK).
   - Implemented multi-process, CPU/IO multi-threading 
   (spin locks, mutex locks, and thread scheduling algorithms (FCFS, SRJF)).
   - implemented TLB mechanism to determine the 
   physical address of the memory request at the time of the TLB hit.

### 4. One Death Clear

This is a 2D RPG game. 
Control the character to fight against monsters 
and defeat the boss at the end to clear the game.
The most important thing is that if you die you need to start over!

To download this game, please click [this link](/download/No_Death_Clear_0.8.3.exe).

To download the repository, please click [this link](/download/No_Death_Clear_0.8.3_Project.zip)

1. Tech
   - Game Engine: Godot
   - UI and Object Painting: Aseprite & PhotoShop

2. Features
   - Character movement acceleration system
   - Physical collision
   - Health system
   - Buff mechanism

## Open Source projects contributions

### 1. Kueue

Kueue is a kubernetes-native system that manages quotas and how jobs consume them. 
Kueue decides when a job should wait, when a job should be admitted to start (as in pods can be created) 
and when a job should be preempted (as in active pods should be deleted).

To see the repository, please click [this link](https://github.com/kubernetes-sigs/kueue).

**My contributions:**
   - Pull requests: 8
   - Code: 132 lines
   - Issues: 1
