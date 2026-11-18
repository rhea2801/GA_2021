# Image Reconstruction using Genetic Algorithms
 
 > **Term Project — Evolutionary Computation**  
 > **Advisor:** Prof. Nirupam Chakraborti (IIT Kharagpur)  
 > **Timeline:** Jan 2021 – Apr 2021
 
 ## Overview
 This project implements a Genetic Algorithm (GA) framework from scratch to reconstruct a target input image starting from a randomly initialized population of pixel arrays. In addition to achieving visual and numerical convergence toward the target image, this study systematically compares the convergence behavior and interpretability of **real-valued encoding** versus **binary encoding** across multiple selection and evolutionary operator schemes.
 
 ## Key Features & Methodology
 
 - **Chromosome Representation & Population Initialization:**
   - Formulated 2D pixel arrays as 1D chromosomes under both **real-valued** (continuous pixel intensity) and **binary-encoded** (bit-string) representations.
   - Built configurable population generators and pixel-wise similarity fitness functions to guide evolutionary search.
 
 - **Evolutionary Operators (Real & Binary Encodings):**
   - Designed and implemented custom **crossover** and **mutation** operators tailored specifically to real-encoded and binary-encoded populations.
 
 - **Selection Strategies:**
   - Implemented and compared **Roulette Wheel Selection**, **Tournament Selection**, and **Elitism** to balance exploration vs. exploitation and prevent premature convergence.
 
 - **Convergence & Interpretability Analysis:**
   - Successfully reconstructed target images with clear generation-over-generation convergence.
   - Analyzed the trade-offs between real and binary chromosome encodings in terms of convergence speed, mutation sensitivity, and visual reconstruction fidelity.
