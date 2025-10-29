# Applied Systems Lab – Kaspa Mining Infrastructure Overview

## Purpose

The **Applied Systems Lab** serves as a test environment for research, tuning, and reliability evaluation of **Kaspa (KAS) mining systems**.  
Its focus is on **hardware optimization**, **system performance**, and **operational resilience**, using open-source monitoring and structured experimental methodology.

---

## Objectives

1. **Optimize Mining Performance**
   - Analyze and tune **Iceriver KS5L** and **Bitmain KS5 Pro** miners for optimal hash-per-watt efficiency.  
   - Experiment with pool-side settings and network parameters to improve stability and throughput.

2. **Establish Reliability & Uptime Metrics**
   - Define and track **MTBF** (Mean Time Between Failures) and **MTTR** (Mean Time To Repair).  
   - Document recovery, restart, and diagnostic steps for faster maintenance cycles.

3. **Standardize Operational SOPs**
   - Maintain reproducible **startup, shutdown, and maintenance procedures**.  
   - Develop diagnostics and troubleshooting checklists for field consistency.

4. **Refine Cooling & Environmental Management**
   - Operate under an **air-based CRAC-inspired cooling layout** with defined **cold and hot aisles**.  
   - Target consistent thermal balance and airflow performance across rigs.

---

## Infrastructure Summary

| Component Type | Description | Notes |
|----------------|--------------|-------|
| **Mining Rigs** | Iceriver KS5L & Bitmain KS5 Pro | Dedicated Kaspa ASICs, currently offline for diagnostics |
| **Monitoring Stack** | Open-source tools + F2Pool dashboard | External telemetry only (no local log access) |
| **Power Systems** | 240V line with UPS + surge protection | *Not currently monitored; metering planned for Phase II* |
| **Cooling Setup** | Air-based CRAC-inspired system | Cold/hot aisle design with airflow zoning |
| **Networking** | Direct connection to F2Pool | Optimized for low latency and link reliability |

---

## Reliability & Maintenance Framework

The lab is developing a structured **reliability framework** to quantify performance and system resilience:

- **MTBF (Mean Time Between Failures):** Estimates average operational lifespan between outages.  
- **MTTR (Mean Time To Repair):** Tracks recovery duration after downtime.  
- **Uptime Tracking:** Based solely on F2Pool data and external monitoring outputs.  
- **Failure Mode Categorization:** Distinguishes between hardware, network, and environmental faults.
  
---

## Methodology

1. **Experimentation** – Controlled operational testing of cooling, configuration, and environmental variables.  
2. **Data Collection** – Aggregated from **F2Pool** and **open-source monitoring**.  
3. **Analysis** – Efficiency, stability, and reliability assessments from external data.  
4. **Documentation** – Version-controlled SOPs and findings maintained in this repository.

---



---

