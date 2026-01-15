# AI-Based Power System Fault Classification (MATLAB)

## Overview
This repository contains MATLAB code for generating realistic power system fault data and classifying different fault types using Artificial Intelligence (Machine Learning).

The work is intended for **personal learning and skill development** in:
- Power System Protection
- MATLAB
- AI applications in electrical engineering

## Fault Types Considered
- Normal Condition
- Line-to-Ground (LG)
- Line-to-Line (LL)
- Line-to-Line-to-Ground (LLG)
- Three-Phase Fault (LLL)

## Features Used
- RMS Phase Voltages: Va, Vb, Vc (per-unit)
- RMS Phase Currents: Ia, Ib, Ic (per-unit)

## AI Technique
- Decision Tree Classifier (`fitctree` in MATLAB)

## How the Data is Generated
Synthetic fault data is generated using realistic electrical behavior:
- Voltage drops during faults
- Current rises based on fault severity
- Gaussian noise added to simulate real measurements

## How to Run
1. Open MATLAB
2. Run `fault_data_generation.m`
3. Run `fault_classification_ai.m`
4. View accuracy, confusion matrix, and decision tree

## Learning Outcomes
- Understanding fault signatures in power systems
- Applying machine learning to classification problems
- Interpreting AI decisions using decision trees

## Future Improvements
- Random Forest classifier
- Fault location estimation
- Time-domain signal generation
- Simulink-based fault modeling

## Author
Personal learning project by an Electrical & Electronics Engineering student.
