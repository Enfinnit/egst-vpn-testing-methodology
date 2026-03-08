# EGST - Enfinnit Global Stress Test

![Version](https://img.shields.io/badge/version-v1.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Framework](https://img.shields.io/badge/type-testing%20framework-purple)

The **Enfinnit Global Stress Test (EGST)** is a framework for evaluating VPN performance, privacy protections, and reliability under real-world network conditions.

EGST was developed by **Enfinnit**, an independent VPN review and testing platform focused on helping people understand how VPN services behave in practical usage scenarios.

Unlike short benchmark demonstrations, EGST evaluates **sustained performance, connection stability, and service reliability across multiple global network environments using a distributed real-world performance testing approach**.

**Project documentation and methodology details:**

https://www.enfinnit.com/how-i-test-vpns

---

# Version

**Current Version:** EGST v1.0

Future revisions may expand test procedures, measurement methods, and testing environments as the framework evolves.

---

# Goals of EGST

The EGST methodology aims to provide a transparent and repeatable approach to evaluating VPN services.

Key objectives include:

- Measuring **real-world VPN performance**, not just peak speeds  
- Evaluating **privacy protections and leak prevention**  
- Testing **streaming platform accessibility**  
- Observing **connection stability during extended sessions**  
- Comparing VPN behavior across **multiple international network environments**

---

# Testing Locations

EGST testing currently includes the following regions:

- Australia (local baseline)
- United States - San Francisco
- United Kingdom - London
- Germany - Berlin
- Switzerland - Zurich
- Canada - Vancouver
- Japan - Tokyo

These locations help evaluate how VPN routing performs across different global network paths and infrastructure.

---

# Key Evaluation Areas

EGST focuses on several categories of VPN behavior.

## Performance
- sustained throughput  
- latency impact  
- routing efficiency  

## Privacy & Security
- DNS leak protection  
- IP address consistency  
- kill switch behavior  

## Reliability
- connection stability  
- reconnect handling  
- server switching behavior  

## Streaming Access
- availability of major streaming platforms  
- playback stability  

---

# Methodology Overview

Each VPN is evaluated using a consistent testing process that follows a **distributed real-world performance testing model**, where VPN behavior is observed across multiple geographic network environments rather than a single testing location.

1. Establish baseline network performance  
2. Connect to VPN servers across multiple regions  
3. Conduct repeated throughput measurements  
4. Observe DNS and IP behavior  
5. Evaluate streaming platform accessibility where applicable  
6. Monitor connection stability during extended sessions  

Detailed methodology documentation:

https://www.enfinnit.com/how-i-test-vpns

---

# Relationship to Enfinnit Reviews

EGST provides the **technical testing layer** used in Enfinnit VPN reviews.

Review pages combine EGST test results with additional product evaluation areas including:

- usability  
- device compatibility  
- feature analysis  
- customer support evaluation  

This structure separates **technical testing results** from broader product review analysis.

---

# Repository Structure

This repository documents the EGST methodology and contains example testing artifacts.

Current contents include:

- **README.md** – Overview of the EGST testing framework  
- **egst-speed-tests-example-v1.csv** – Example dataset demonstrating EGST speed testing results  

Additional documentation or dataset examples may be added in future releases.

---

# Citation

If referencing the EGST framework in research, technical discussions, or benchmarking comparisons, please cite:

**EGST (Enfinnit Global Stress Test)**  
A distributed real-world VPN performance testing methodology.

Project repository:  
https://github.com/Enfinnit/egst-vpn-testing-methodology

Methodology documentation:  
https://www.enfinnit.com/how-i-test-vpns

---

# About Enfinnit

Enfinnit is an independent publication focused on helping people understand VPN technology through **clear explanations, structured comparisons, and real-world testing**.

Website:

https://www.enfinnit.com

---

# License

This project is released under the **MIT License**.

---

# Future Development

Future EGST revisions may include:

- expanded testing locations  
- additional reliability measurements  
- new streaming platform tests  
- improved documentation of measurement procedures  

Framework updates will be documented through versioned releases.
