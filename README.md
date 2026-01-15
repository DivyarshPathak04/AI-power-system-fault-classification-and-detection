# AI-Based Power System Fault Classification (MATLAB)

## Overview
This repository contains MATLAB code created as part of my **self-learning process** to understand how Artificial Intelligence (Machine Learning) can be applied to power system fault analysis.

The implementation is based on **guided learning, experimentation, and adaptation** for personal understanding.

## Objective
- To study voltage and current behavior during different power system faults
- To generate realistic synthetic fault data
- To apply a machine learning classifier for fault identification

## Fault Types Considered
- Normal Condition
- Line-to-Ground (LG)
- Line-to-Line (LL)
- Line-to-Line-to-Ground (LLG)
- Three-Phase Fault (LLL)

## Features Used
- RMS Phase Voltages (Va, Vb, Vc) in per-unit
- RMS Phase Currents (Ia, Ib, Ic) in per-unit

## Methodology
1. Realistic synthetic fault data is generated based on known power system behavior.
2. Noise is added to simulate real measurement conditions.
3. A Decision Tree classifier is trained using MATLAB.
4. Model performance is evaluated using accuracy and confusion matrix.

## Tools Used
- MATLAB
- Statistics and Machine Learning Toolbox

## Purpose of This Repository
This repository is intended **only for learning and skill development**.  
It is not claimed to be an industry-grade or research-level system.

## Future Improvements
- Random Forest classifier
- Fault location estimation
- Time-domain signal generation
- Simulink-based fault modeling

## Author
Electrical & Electronics Engineering student  
(Self-learning repository)
