# sim-ml

Working notes and code from my self-study path from FEA and DEM analysis into machine learning for engineering simulation.

## About

I'm an Analysis Engineer working on FEA and DEM simulation of mining and heavy machinery equipment (ANSYS Workbench, Altair EDEM, Ansys Rocky). This repo records my path toward ML for simulation: surrogate models, reduced-order models and physics-informed methods, with a focus on aerospace and energy applications.

Everything here uses my own or publicly available data. No client or employer data is included.

## Roadmap

| Phase | Focus | Status |
|---|---|---|
| 1. Maths refresh | Linear algebra, calculus, statistics, PCA | In progress |
| 2. Core ML | Regression, neural networks, PyTorch, first FEA surrogate | Not started |
| 3. ML for simulation | POD/SVD, Gaussian processes, PINNs, graph neural networks | Not started |
| 4. Project | CFD surrogate for a J-shaped VAWT blade (separate repo) | Not started |

## Highlights

- _Add links to your 2–3 best notebooks here as you finish them._

## Contents

| Folder | What's in it | Status |
|---|---|---|
| `01-linear-algebra/` | Matrix transforms, spring–mass eigenmodes, truss stiffness assembly, SVD | In progress |
| `02-calculus/` | Gradients, backpropagation, a NumPy neural network, curve fitting | Not started |
| `03-statistics/` | Distribution fitting (PSD), bootstrapping, PCA | Not started |
| `04-core-ml/` | Coursework labs and engineering-data exercises | Not started |
| `05-pytorch/` | PyTorch fundamentals and surrogate models | Not started |
| `06-bracket-surrogate/` | FEA surrogate for a parametric bracket (Ansys Student) | Not started |
| `07-sim-ml/` | POD, DMD/SINDy, GPs, PINNs, GNNs | Not started |

## Getting started

```bash
git clone https://github.com/<your-username>/sim-ml.git
cd sim-ml
conda env create -f environment.yml
conda activate sim-ml
jupyter lab
```

## Learning resources

- 3Blue1Brown, *Essence of Linear Algebra* (YouTube)
- Imperial College London, *Mathematics for Machine Learning* (Coursera)
- StatQuest (YouTube)
- Andrew Ng, *Machine Learning Specialization* (Coursera)
- PyTorch official tutorials
- Brunton & Kutz, *Data-Driven Science and Engineering*, 2nd ed.

## Contact

Hrishikesh (Rishi) Mohan · [LinkedIn](https://www.linkedin.com/in/<your-profile>)

## Licence

MIT
