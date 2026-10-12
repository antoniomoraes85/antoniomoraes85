# José Antônio Coutinho de Moraes Filho

**Computer Science MSc researcher at UFRGS**  
**Career focus:** AI Research Engineering · ML Systems Engineering  
**Specialization:** Numerical Optimization · Reinforcement Learning · Computational Performance

I work at the intersection of **control, learning, and efficient computation**. My current focus is on building reproducible experiments that explain not just *whether* an algorithm works, but **what drives its computational cost**.

## Research focus

My MSc research at the Federal University of Rio Grande do Sul (UFRGS) investigates the relationship between **control-problem structure** and the computational costs of **Model Predictive Control (MPC)** and **Reinforcement Learning (RL)**.

- **MPC:** study online optimization cost using quadratic-program structure, including Hessian dimensions, KKT-system dimensions, constraints, and solver effort.
- **RL:** study offline training cost, environment transitions, updates, and evaluation at comparable control quality.
- **Dynamics:** investigate whether properties of the system matrix (including spectral radius and norm) help explain the observed costs.
- **Research question:** do structural and dynamical descriptors explain computational difficulty better than state dimension alone?

This is an ongoing empirical research program, **not a claim of general equivalence or superiority between MPC and RL**.

## Selected work

| Project | What it demonstrates | Status |
| --- | --- | --- |
| [Reinforcement Learning Experiments](https://github.com/antoniomoraes85/reinforcement-learning-projects) | MountainCar-v0: Q-learning, SARSA(λ), and Dyna-Q; 108 screening runs and 60 final training runs, with saved checkpoints, common evaluation seeds, statistical reports, and reproducibility artifacts | Documented experimental study |
| [Inverted Pendulum Control](https://github.com/antoniomoraes85/projeto_pendulo_invertido) | Linearization, LQR, MPC, PPO, robustness simulation, and a C implementation of an LQR feedback kernel | Exploratory control/optimization prototype |
| [Atratora Forge](https://github.com/antoniomoraes85/atratora-forge) | Local-first technical tooling with React, TypeScript, automated tests, and a modular application architecture | Software engineering project |
| [ORAL LAB](https://github.com/antoniomoraes85/oral-lab) | Browser-based speech-assisted rehearsal platform, with text alignment, scoring, offline support, and tests | Applied software project |

For the RL study, the conclusions are **specific to the published experimental protocol**. The inverted-pendulum repository is a prototype; its performance and real-time properties should not be interpreted as independently certified production benchmarks.

## Technical interests and current development

- **Research & methods:** numerical optimization, RL, control systems, experimental design, statistical computing.
- **Tools in active use:** Python, NumPy, scientific notebooks, Git, reproducible experiment pipelines, performance measurement.
- **Systems direction:** C/C++, Linux, profiling, efficient inference, hardware/software co-design.
- **Longer-term learning roadmap:** GPU/CUDA programming and distributed ML systems.

**Career direction:** bridge rigorous algorithm evaluation with practical **ML systems performance engineering**.

## Connect

- [LinkedIn](https://www.linkedin.com/in/joseantoniomoraes/)
- [Email](mailto:antoniomoraes.ti@gmail.com)
- [Research Instagram](https://instagram.com/jose.antonio.moraes.research)
