# CCBA
SHA:390e36bfba4ae54b43d53bdff7513c70be8225ac This repository contains the experimental data and source code for the paper "CCBA: Dynamic Scheduling Algorithm for 
Jammer Resources in Strong Electromagnetic Interference Environment".

File Structure & Core Content
The compressed file includes three key experimental result sections:

4.1 Parameter setting of the simulation scenario.
4.2 Comparison results and analysis of system operation duration.
4.3 Results and analysis of communication party's disturbed state

Environment Requirements
Python IDE: PyCharm 2023.2.1 (Professional Edition)
Runtime version: 17.0.8+7-b1000.8 amd64
Dependencies:
anaconda_depends_2023.09
PyTorch 1.13.1

Quick Start
1. Core Simulation Scripts
Script Name	Function Description
generate_nodes.py	Simulates the initial power configuration of communication nodes.
modify_communication_nodes.py	Implements dynamic power adjustment for communication nodes.
jammer_first_run.py	Jammer decision-making script (first decision based on TLOA strategy).
jammer_run.py	Jammer decision-making script (non-first decisions based on TLOA strategy).
test.py	Detects jamming effectiveness in simulation scenarios.
main.py enables one-click execution of simulation results for a specific antenna in a specific scenario.
2. Data Statistics
Run the "Data Statistics" and "Power Statistics (Including Standard Deviation)" programs to calculate and output the comparative experimental data presented in the paper.
