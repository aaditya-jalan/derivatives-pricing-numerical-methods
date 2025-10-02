📈 Derivatives Pricing – Numerical & Computational Finance

This repository contains implementations of derivatives pricing models and numerical methods commonly used in computational finance. The project covers both analytical models and numerical PDE/Monte Carlo methods for pricing options and related financial derivatives.

📂 Repository Contents

asian_option_crank_nicolson.ipynb

Pricing Asian options using the Crank–Nicolson finite difference scheme.

binomial_model_framework.ipynb

Generalized N-step Binomial Tree framework for European and American option pricing.

explicit_implict_crank_nicolson.ipynb

Comparison of explicit, implicit, and Crank–Nicolson finite difference schemes for option pricing PDEs.

finite_difference_cryers_algo.ipynb

Implementation of Cryer’s algorithm for solving finite difference discretizations of PDEs in finance.

jump_diffusion_stock_process.ipynb

Option pricing under Merton’s Jump-Diffusion model.

interpolation_and_quadratic_approximation.ipynb

Polynomial interpolation and quadratic approximation techniques applied to derivative pricing.

🚀 Features

Implements analytical models (Black-Scholes-Merton, Binomial trees).

Implements numerical PDE methods (Explicit, Implicit, Crank–Nicolson, Cryer’s algorithm).

Implements stochastic process models (Jump-diffusion).

Demonstrates approximation techniques (interpolation, quadratic fitting).

Written in Python (Jupyter Notebooks) for interactivity and visualization.

⚙️ Tech Stack

Python 3.x

Libraries:

numpy – numerical computation

pandas – data handling

matplotlib – visualization

scipy – numerical methods


📊 Example Methods Covered

Finite Difference Methods (FDM):

Explicit Scheme

Implicit Scheme

Crank–Nicolson Scheme

Lattice Models:

Binomial Tree Framework

Stochastic Processes:

Jump Diffusion (Merton Model)

Numerical Approximations:

Polynomial Interpolation

Quadratic Approximation

📖 References

J.C. Hull, Options, Futures, and Other Derivatives

Wilmott, Howison & Dewynne, The Mathematics of Financial Derivatives

Merton, R. (1976), Option Pricing When Underlying Stock Returns are Discontinuous
