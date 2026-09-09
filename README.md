# AST 384C: Computational Astrophysics

Graduate-level course on computational methods for astrophysics. University of Texas at Austin, Fall 2026.

## Description

This course covers the essential computing skills and statistical methods used in modern astrophysical research. Students will learn version control and collaborative workflows, remote/HPC computing, and the statistical and machine learning tools that underpin contemporary data analysis and simulation in astrophysics — with an emphasis on Bayesian inference and simulation-based inference.

## Repository Structure

- `lectures/` — lecture notes and slides
- `pyproject.toml` — Python project/package configuration
- `environment.yml` — conda environment for course software

## Syllabus

Meets Mondays and Wednesdays, 2:00–3:30 PM. Fall 2026 term per the [UT Austin Registrar academic calendar](https://registrar.utexas.edu/calendars/26-27): classes begin **Monday, August 24, 2026** and the last class day is **Monday, December 7, 2026**. No class on Labor Day (Mon, Sep 7) or during Fall Break/Thanksgiving (Mon Nov 23 – Sat Nov 28). This yields 28 class meetings.


### Part I: Computing Foundations
| #          | Date        | Topic                       |
| ---------- | ----------- | --------------------------- |
| 1 | Mon, Aug 24 | Course introduction; Git    |
| 2 | Wed, Aug 26 | Scientific computing basics |

### Part II: Bayesian Inference
| #          | Date        | Topic                                                 |
| ---------- | ----------- | ----------------------------------------------------- |
| 3 | Wed, Aug 31 | Probability foundations and Bayes' theorem            |
| 4 | Wed, Sep 2  | Parameter estimation: priors, likelihoods, posteriors |
| 5 | Wed, Sep 9  | Optimization                                          |
| 6 | Mon, Sep 14 | MC methods, rejection sampling                        |
| 7 | Wed, Sep 16 | MCMC I: Metropolis-Hastings, `emcee`                  |
| 8 | Mon, Sep 21 | MCMC II: Hamiltonian Monte Carlo                      |
| 9 | Wed, Sep 23 | Hierarchical Bayesian modeling                        |
| 10| Mon, Sep 28 | Model comparison (guest lecture by Tanveer Karim)     |

### Part III: Machine Learning
| #   | Date        | Topic                           |
| --- | ----------- | ------------------------------- |
| 11  | Wed, Sep 30 | Gaussian processes              |
| 12  | Mon, Oct 5  | Neural Networks; pytorch primer |
| 13  | Wed, Oct 7  | Neural network architectures    |
| 14  | Mon, Oct 12 | Classification                  |
| 15  | Wed, Oct 14 | Regression                      |
| 16  | Mon, Oct 19 | Explainability                  |
| 17  | Wed, Oct 21 | Unsupervised ML                 |

### Part IV: Simulation-Based Inference
| #   | Date        | Topic                                             |
| --- | ----------- | ------------------------------------------------- |
| 18  | Mon, Oct 26 | Variational inference                             |
| 19  | Wed Oct 28  | Approximate Bayesian Computation (ABC)            |
| 20  | Mon, Nov 2  | SBI I: framework and introduction                 |
| 21  | Wed, Nov 4  | SBI II: neural density estimation                 |
| 22  | Mon, Nov 9  | SBI III: normalizing flows (MADE, MAF)            |
| 23  | Wed, Nov 11 | SBI for Bayesian inference / posterior estimation |
| 24  | Mon, Nov 16 | SBI validation and Bayesian neural networks       |

### Part V: You choose (e.g. diffusion models, coworking with LLMs, AI ethics)

| #   | Date        | Topic |
| --- | ----------- | ----- |
| 25  | Wed, Nov 18 |       |
| 26  | Mon, Nov 30 |       |

### Part VI: Synthesis
| # | Date | Topic |
|---|---|---|
| 27 | Wed, Dec 2 | Final project presentations I |
| 28 | Mon, Dec 7 | Final project presentations II (last class day) |


## Software Environment

This course uses Python 3. See `environment.yml` for the conda environment used in labs and homework, and `pyproject.toml` for the shared course package (installable with `pip install -e .`).

## License

Course materials are licensed under [CC BY 4.0](LICENSE) unless otherwise noted.
