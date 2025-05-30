
## 📄 Description
This repository contains supplementary material for the paper:

> **"Multi-Objective Cooperative Multi-Fitness Evolutionary Algorithm for Workflow Scheduling in Cloud Computing"**  
> (Submitted to **Natural Computing (NACO)**)  
> Authors: Pablo Barredo, Jorge Puente  
>
> DOI: [Pending Assignment]  
> URI: [Pending Assignment]

The efficient scheduling of scientific workflows in cloud environments involves balancing multiple conflicting objectives, primarily makespan and energy consumption. This paper proposes a novel extension of the Cooperative Multi-Fitness (CMF) paradigm to multi-objective evolutionary algorithms (MOEAs), where each objective is supported by a dedicated set of domain-specific heuristics.

The proposed method, termed **MOCMF**, embeds cooperative decoding and Lamarckian recoding into a standard MOEA (e.g., NSGA-II, SPEA2, IBEA), producing multiple objective-specific phenotypes from a shared genotype. This approach enables each heuristic to guide the search independently while preserving improvements across the population. The method is tested on data-intensive scientific workflows under the Disk–Network–Computing (DNC) model, demonstrating substantial improvements in convergence and robustness without sacrificing generality.

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
git clone https://github.com/iScOp-uniovi/Paper_NACO_MOCMF_2025
cd Paper_NACO_MOCMF_2025
```

Follow the instructions in the `code/` folder to configure and run experiments using your chosen algorithm and workflow configuration.

---

## 🔍 Cite this Work

If you use this material in your research, please cite our paper as follows:

```
@article{Barredo2025MOCMF,
  author    = {Pablo Barredo and Jorge Puente},
  title     = {Multi-Objective Cooperative Multi-Fitness Evolutionary Algorithm for Workflow Scheduling in Cloud Computing},
  journal   = {Submitted to Natural Computing (NACO)},
  year      = {2025},
  doi       = {Pending Assignment}
}
```

---

## 📧 Contact
For questions or inquiries about this work, please contact:  
✉️ **[puente@uniovi.es](mailto:puente@uniovi.es)**
