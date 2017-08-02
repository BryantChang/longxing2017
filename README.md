# 面向大数据处理的系统和内存系统

* Data-centric and Memory-centric


## Introduction

* High performance computing-> grid computing->cloud computing(space sharing)
* The biggest machine becomes even bigger
    - Scalibility
* The smallest machine becomes even smaller
* Pervasive Computing
    - Challanges:
        + Effective use of smart space
        + human center services
        + Invisibility
        + Masking Uneven Conditionning
        + Localized Scalability(更精确的服务)
* Multicore add another Dimendion
* Parallel I/O System
* Distributed I/O System

### Different views

* OS View  -> ISA
* Compiler  -> OS
* Application -> API

* Deep Memory hieracrchy

### Computing and Parallel Computing

* parallel computing --- 解决一个问题
* concurrent computing ---- 解决的是多个问题

* Performance comes from
    - Device
    - computer architecture
    - parallelism

* Multi-core
* Multi-thread


### Parallel Architecture


* SIMD (Vector computing)
* Shared address or Private address
* strong consistency  or eventually consistency
* programm 和 filesystem 相适应

## Memory

* memory wall(Memory 与 CPU速度不匹配)
* solution
    - memory hierarchy(locality)
        + Temporal(时间)
        + Spetial(空间)
    - concurrence


## Performance Evaluation

* CPI (每条指令执行的CPU周期数)
* Amdahl's law
* Golden Rule of PE
    - Ensure maasured results are deterministic
        + Dedicated runs, unloaded system
* CPI--type
    - Pipeline CPI 
    - Memory System CPI(Memory stall)
* C-AMAT
* Efficientcy
    - 用多少个processor达到额定的speedup
* Scalibility



## Memory Performance

* SRAM
* DRAM
* FLASH

* Cache miss
    - Compulsory
    - Cpacity
    - Conflict(Hash)
    - Coherence(for multi-core)

## Memory and Memory Hierarchy

* Markov Predict
    - 没有规律的，根据历史情况进行预测










