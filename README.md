# Dynamic Range-Optimized DUORAM

This repository contains the report and presentation slides for my undergraduate research project titled **"Dynamic Range-Optimized DUORAM: Balancing Computational Efficiency and Privacy in Distributed ORAM"**.

## Overview

As secure access to outsourced data becomes increasingly important, traditional ORAM techniques provide strong privacy but often at high computational cost. This project explores how *range-limited Distributed Point Functions (DPFs)* can be used to reduce the offline computation in DUORAM, while still maintaining a quantifiable and bounded privacy leakage.

The key idea is to allow the client to generate DPF keys over dynamically selected subranges instead of the entire database. We formalize the trade-off between computation time and information leakage, propose a binary tree structure for efficient range selection, and provide strategies to satisfy user-defined privacy and performance constraints.

## Contents

- `Report_UGP.pdf` – Full technical report of the project  
- `Presentation.pdf` – Slide deck used for the final UGP presentation  

## Technologies and Concepts

- Distributed Point Functions (DPFs)
- Secure Multi-Party Computation (MPC)
- Oblivious RAM (ORAM) and DUORAM
- Differential Privacy (conceptual application)
- Binary Tree Range Structures
- Formal Privacy-Performance Analysis (ε, δ, s)

## Related Papers

- [DUORAM: A Bandwidth-Efficient Distributed ORAM for 2- and 3-Party Computation (Vadapalli et al., USENIX Security 2023)](https://www.usenix.org/system/files/usenixsecurity23-vadapalli.pdf)
- [Differentially Private Oblivious RAM (Wagh et al., PoPETs 2018)](https://petsymposium.org/popets/2018/popets-2018-0032.pdf)

## Supervision

This project was carried out under the guidance of **Prof. Adithya Vadapalli**, Department of Computer Science and Engineering, IIT Kanpur.

## Acknowledgements

Special thanks to my mentor for valuable insights and guidance throughout the project.
