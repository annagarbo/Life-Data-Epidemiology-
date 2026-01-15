# Life Data Epidemiology
Final Delivery Course project held by Prof. Chiara Poletto at University of Padova

This peoject is inspired by the paper:

> **R. Pastor-Satorras, C. Castellano, P. Van Mieghem, A. Vespignani**  
> *Epidemic processes in complex networks* (Physics Reports, 2015)

The project explores epidemic spreading on networks from a computational and data-driven perspective, connecting theoretical concepts from network epidemiology with numerical simulations and visual analysis.

---

## Project overview

Starting from the theoretical framework presented in the reference paper, we implemented and explored simplified epidemic dynamics on complex networks, with particular attention to the interplay between disease spreading and information dynamics.

In particular, the project includes the implementation of a **multi-layer network structure**, where:
- one layer represents physical or contact interactions relevant for epidemic spreading,
- an additional layer encodes the **information state of individuals** (informed vs. non-informed),
allowing us to investigate how awareness can influence infection risk.

The epidemic process is modeled through **SIS-like dynamics**, while the information layer modulates the effective susceptibility of nodes.  
At the end of the project, we produced **heatmaps describing infection risk** as a function of the information state and network position of nodes.

A detailed description of the theoretical assumptions can be found in the reference paper, while a schematic and intuitive overview of the implemented model is provided in the presentation prepared for the course.

Although some aspects of the model require further refinement — in particular, the temporal evolution of the information layer tends to converge to a fully non-informed population — the project proved to be a valuable exercise to identify **critical challenges** in the construction of coupled, multi-layer epidemic–information networks.

Overall, the work focuses on conceptual understanding, exploratory modeling, and visualization, highlighting both the potential and the limitations of such complex network-based approaches.


---

## Repository structure

```
├── LDE_project_29ottobre.ipynb # Main notebook with simulations and analysis
├── LDE_presentation.pptx # Project presentation slides
├── network_evolution.mp4 # Animation of the network evolution
├── network_evolution_example.mp4 # Another example visualization of dynamics
├── paper/
│ └── 1408.2701v2.pdf # Reference paper
```

---

## Methods and tools

- **Python** for simulations and data analysis  
- **Network-based models** inspired by SIS epidemic dynamics  
- **Jupyter Notebook** as the main development environment  
- **Network visualizations and animations** to inspect temporal evolution  

The simulations are intended to provide qualitative insight into epidemic dynamics on networks and to link theoretical results from the literature to observable behaviors.

---

## Notes and limitations

- Some components of the theoretical model are implemented in a simplified form.
- Certain features discussed in the reference paper are only partially explored.
- The focus is on conceptual understanding, experimentation, and visualization.

Despite these limitations, the project offers a coherent and reproducible exploration of epidemic processes on networks.

---

## Authors

This project was developed as  PoD master student collaboratively with Erica Brisigotti.

---

## Reference

- Pastor-Satorras, R., Castellano, C., Van Mieghem, P., Vespignani, A.  
  *Epidemic processes in complex networks*, Physics Reports (2015).


