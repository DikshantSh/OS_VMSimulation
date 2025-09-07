# Virtual Memory Simulation via Pure Demand Paging  

**Operating Systems Project | May 2024**  

This project implements a **Virtual Memory Simulation** using **Pure Demand Paging**, modeled after core operating system principles. It is designed with four distinct modular components — **Master, Scheduler, Memory Management Unit (MMU), and Process** — to mimic real-world OS behavior.  


## Features  

- **Modular Design**:  
  - **Master**: Orchestrates execution and manages overall simulation.  
  - **Scheduler**: Controls process scheduling and CPU allocation.  
  - **Memory Management Unit (MMU)**: Handles virtual-to-physical address translation and manages page faults.  
  - **Process**: Simulates user-level processes that request memory pages.  

- **OS Data Structures Implemented**:  
  - Page Tables  
  - Free Frame List  
  - Ready Queue  

- **Page Fault Handling**:  
  - Robust page-fault handler for loading required pages on demand.  
  - Integrated with **LRU (Least Recently Used)** page-replacement algorithm.  

- **Algorithms**:  
  - Pure Demand Paging (no preloading of pages).  
  - Classic **LRU page replacement**.  
