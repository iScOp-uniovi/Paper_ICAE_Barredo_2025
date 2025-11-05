
## 📄 Description
This repository contains supplementary material for the paper:

> **"Multiobjective Cooperative Multi-Fitness in Workflow Scheduling problem"**  
> Published in **Integrated Computer-Aided Engineering (ICAE)**
>
> Authors: Pablo Barredo, Jorge Puente  
>
> DOI: [10.1177/10692509251363797](https://doi.org/10.1177/10692509251363797)  
> URI: [https://hdl.handle.net/10651/80828](https://hdl.handle.net/10651/80828)

The optimisation of scientific workflows in cloud environments presents considerable challenges, primarily due to the inherent trade-offs between makespan and energy consumption. To address this, we propose Multi-Objective Cooperative Multi-Fitness (MOCMF), a novel mechanism that significantly enhances multi-objective evolutionary algorithms through a unique cooperative evaluation and recoding strategy. Diverging from existing multi-decoder approaches, MOCMF's core innovation lies in its collaborative framework: heuristic decoders work in tandem to support a baseline decoding function, providing expert solutions that guide the Lamarckian recoding of chromosomes. Furthermore, MOCMF extends this cooperative evaluation to a multi-objective setting, where each heuristic decoder focuses on optimising a specific objective, leading to the generation of multiple distinct solutions per chromosome. 
Experimental results on data-intensive workflow benchmarks show that MOCMF improves the average Hypervolume by 32% and Inverted Generational Distance by 42% compared to a standard NSGA-II implementation, and by 7% and 6% respectively compared to its mono-objective cooperative variants. The proposed mechanism is also generalisable and potentially applicable to other multi-objective problems beyond workflow scheduling.

---

## 📂 Repository Content

- `data/` → Workflow datasets and infrastructure configurations used in the experiments, formatted for DNC-based evaluation.
- `code/` → Implementation of MOCMF using the JMetal v6 framework, including NSGA-II, SPEA2, and IBEA variants.
- `results/` → Output of experimental evaluations, including Pareto fronts, metric comparisons, and statistical rankings.
- `README.md` → This file.

---

## 📊 Datasets and Code

The datasets consist of real scientific workflows adapted to the Disk–Network–Computing (DNC) model to simulate realistic I/O and communication delays. The codebase extends the JMetal v6 library and includes modular components for standard, heuristic, and cooperative decoders.

For detailed usage instructions, refer to the README files within each subdirectory.

---

## 📥 Using the Material

To access and utilize the supplementary material, clone this repository and navigate to the appropriate directories:

```bash
git clone https://github.com/iScOp-uniovi/Paper_ICAE_Barredo_2025
cd Paper_ICAE_Barredo_2025
```

Follow the instructions in the `code/` folder to configure and run experiments using your chosen algorithm and workflow configuration.

---

## 🔍 Cite this Work

If you use this material in your research, please cite our paper as follows:

```
@article{Barredo2025ICAE,
author = {Pablo Barredo and Jorge Puente},
title ={Multiobjective cooperative multi-fitness in workflow scheduling problem},
journal = {Integrated Computer-Aided Engineering},
volume = {32},
number = {4},
pages = {443-464},
year = {2025},
doi = {10.1177/10692509251363797}
}
```

---

## 📧 Contact
For questions or inquiries about this work, please contact:  
✉️ **[puente@uniovi.es](mailto:puente@uniovi.es)**
