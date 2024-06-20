# Optimal Control for A Knee-Ankle Exoskeleton

This repository contains the implementation of optimal control algorithms for a knee-ankle exoskeleton designed to assist with walking along prescribed trajectories. The project compares Model Predictive Control (MPC) with Linear Quadratic Regulator (LQR) and its iterative variant (iLQR) to achieve superior trajectory tracking for both knee and ankle motions.

## Project Overview

Conventional exoskeleton controls like proportional-integral-derivative (PID) require extensive hyper-parameter tuning and do not guarantee global optimality. This project introduces a new exoskeleton control system using Model Predictive Control (MPC), which calculates motor torques for each degree of freedom by solving a Quadratic Programming (QP) problem. Simulation results show that MPC provides better trajectory tracking compared to LQR and iLQR.

## Folder Structure

- `control-algorithms/`: This folder contains the code implementations for MPC, LQR, and iL
