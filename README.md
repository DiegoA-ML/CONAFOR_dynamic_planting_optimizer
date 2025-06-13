# CONAFOR Reforestation MILP + Heuristic Model

This repository contains a hybrid optimization approach for dynamic reforestation planning under operational constraints, developed in collaboration with CONAFOR.

The model integrates:
- A **Mixed Integer Linear Program (MILP)** to schedule purchases, inventory, and planting activities over a 28-day horizon.
- A **heuristic layer (NSGA-II + Greedy VRP)** for scalable and multiobjective decision-making under field-level complexities.

### Key Features
- Daily planning of plant acquisitions from multiple suppliers.
- Inventory flow with acclimation periods and capacity constraints.
- Assignment of species to polygons based on demand and suitability.
- Internal logistics modeled via simplified transport trips.
- Cost minimization and feasibility trade-offs via heuristics.

### Motivation
This tool supports data-driven reforestation operations by generating feasible, cost-effective schedules under real-world field constraints.

---

*Developed by [Your Name] as part of the Reforestation Optimization Project with CONAFOR.*
