# 🚦 Randomized Route Optimization in Decentralized Traffic Networks

This project explores a **probabilistic routing framework** aimed at minimizing average travel time and alleviating congestion in decentralized traffic networks. It was developed as part of **CSE400: Fundamentals of Probability in Computing** under the guidance of **Prof. Dhaval Patel**, Ahmedabad University.

---

## 📌 Overview

We implement a **Randomized A\*** algorithm that introduces controlled randomness in path selection using a **Boltzmann probability distribution**. The cost function blends actual travel costs with heuristic estimates (Euclidean, Manhattan, Diagonal), promoting exploration of alternative routes.

---

## 📊 Key Features

- **Probabilistic Path Selection**  
  A Boltzmann-like Probability Mass Function (PMF) is used to assign probabilities to paths:

  ![PMF Equation](https://latex.codecogs.com/png.image?\dpi{120}P(P_i)=\frac{e^{-\beta%20f(P_i)}}{\sum_j%20e^{-\beta%20f(P_j)}})

  Where:
  - f(P_i) is the cost of path P_i
  - β controls randomness β = more exploration

- **Heuristics Used**
  - Euclidean Distance  
  - Manhattan Distance  
  - Diagonal Distance  

- **Algorithms Implemented**
  - Dijkstra’s Algorithm (Baseline)
  - Standard A\*
  - Randomized A\*

---

## 📂 Repository Contents

- `S1_ITS1_Project_Main.ipynb`: Main notebook with full simulation and results
- `Project_Report_ITS_S1_CSE400.pdf`: Final report with background, methods, and results
- `S1_ITS_1.pptx`: Project presentation slides
- `Mathematical_Analysis_(Handwritten)`: Scanned handwritten derivations

---

## 📚 Reference

Nguyen, H.T., Wiering, M.A., & van den Berg, J. (2015).  
**A randomized path routing algorithm for decentralized route allocation in transportation networks**.  
*ACM SIGSPATIAL CTScience 2015.*  
[🔗 Read the paper](https://dl.acm.org/doi/10.1145/2834882.2834886)

---


## 📃 License

This project is for academic use only.
