# Hi there 👋

I'm **Michele Baggi**, and I hold an MSc in Mathematical Engineering from **Politecnico di Milano** 🇮🇹, graduated **110/110**. My work centers on numerical methods, scientific machine learning, and the mathematical modeling of complex systems — turning rigorous theory into tools for real, meaningful problems.

> To me, mathematics is the language of nature, and my passion is putting its power to work on problems that matter, without ever losing the rigour they demand.

🎓 **Just graduated** — MSc thesis at **INRAE (Paris-Saclay)** 🇫🇷 on a *patient-specific digital twin of the human gut*.

🌍 **Open to opportunities** — I want to work on something useful and impactful for the world, where scientific computing and modeling make a real difference.

## 🎓 Education

- **MSc in Mathematical Engineering** (Computational Science and Computational Learning) at **Politecnico di Milano** 🇮🇹 — **110/110**, October 2026
- **BSc in Mathematical Engineering** at **Politecnico di Milano** 🇮🇹
- Erasmus exchange at the **National Technical University of Athens (NTUA)** 🇬🇷
- MSc thesis in collaboration with **INRAE Paris-Saclay** 🇫🇷 — *Data Integration, Sensitivity Analysis and Inverse Problem Formulation for a Compartmental Colon Model*. Advisor: Prof. Paola F. Antonietti (MOX, Politecnico di Milano); co-advisors: Béatrice Laroche and Lorenzo Sala (MaIAGE, INRAE)

## 🔬 MSc Thesis — Gut Digital Twin @ INRAE

**[Repository](https://github.com/MicheleBaggi/MSc-Thesis)** · [Full thesis](https://github.com/MicheleBaggi/MSc-Thesis/blob/main/docs/Baggi_MSc_Thesis.pdf) · [Executive summary](https://github.com/MicheleBaggi/MSc-Thesis/blob/main/docs/Baggi_MSc_Thesis_Executive_Summary.pdf) · [Defence slides](https://github.com/MicheleBaggi/MSc-Thesis/blob/main/docs/Baggi_MSc_Thesis_Presentation.pdf)

The same diet can trigger very different metabolic responses from one person to another, and the inside of the colon cannot be observed directly. I connected a mechanistic model of the colon with real patient data, tuning it to each individual: a first step towards a patient-specific **gut digital twin**.

- ⚡ Re-implemented the **compartmental colon model** (106 nonlinear ODEs) from Matlab/Simulink in Python, compiled with Numba (~7× faster)
- 🧪 Linked the model to **real patient data** (3613 metagenomic samples), comparing microbial compositions with the Aitchison distance
- 🎯 **Global sensitivity analysis** (Morris, then Sobol'), narrowing 30 candidate parameters down to the 4 that matter most
- 🧠 Trained a **neural-network surrogate** of the model (R² > 0.998)
- 🔁 Solved the **Bayesian inverse problem** (MCMC with PyMC) for every patient sample in the cohort, with no failures
- 📉 The model reproduces each sample **an order of magnitude more closely** than subjects differ from each other

## 📌 Featured projects

- **[MSc Thesis — Gut Digital Twin](https://github.com/MicheleBaggi/MSc-Thesis)** — data integration, sensitivity analysis and Bayesian inverse problem for a compartmental colon model, applied to 3613 metagenomes. Thesis, executive summary and slides 📄
- **[Numerical Analysis for PDEs](https://github.com/MicheleBaggi/polydg)** — Discontinuous Galerkin (DG) implementation of the non-homogeneous Laplace operator in the `lymph` library for multiphysics simulations. Report + presentation 📄
- **Advanced Programming for Scientific Computing** — [Challenge 1](https://github.com/MicheleBaggi/Pacs_Challenge_1) & [Challenge 2](https://github.com/MicheleBaggi/Pacs_Challenge_2): high-performance scientific computing in C++.
- **Algorithms and Parallel Computing** — functions and algorithms in C++ and MPI for parallel architectures.
- **Fluids Labs** — several Fluid Dynamics laboratory problems solved with computational tools.
- **Artificial Neural Networks & Deep Learning** — Deep Learning challenges in Python: [image classification](https://github.com/MicheleBaggi/DeepL-1) and [semantic segmentation](https://github.com/MicheleBaggi/DeepL-2).
- **[Climate Impact Statistical Modeling](https://github.com/MicheleBaggi/global_temperature_prediction)** — modeled sea surface temperature rise as a function of natural and anthropogenic factors (linear regression + ANOVA, in R).
- **[Crop Yield Challenge](https://github.com/MicheleBaggi/Yield-Prediction-Models-CSI)** — ML models (LSTM, LightGBM, CNN) to predict wheat and maize yields under a high-emissions climate scenario, using daily radiation, temperature and precipitation data. Best results with LSTM. *(Kaggle: The Future Crop Challenge.)*
- **[Geothermal energy + lithium co-production](https://github.com/MicheleBaggi/geothermal-lithium-extraction)** — a reveal.js presentation explaining a published paper on fracture networks, for the course *Numerical Methods for the Geosciences*.

## 🚀 Skills

![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=for-the-badge&logo=mathworks&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=for-the-badge&logo=latex&logoColor=white)

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Numba](https://img.shields.io/badge/Numba-00A3E0?style=for-the-badge&logo=numba&logoColor=white)
![Simulink](https://img.shields.io/badge/Simulink-FF6F00?style=for-the-badge&logo=mathworks&logoColor=white)
![MPI](https://img.shields.io/badge/MPI-1F6FEB?style=for-the-badge&logo=openmpi&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![FEniCS](https://img.shields.io/badge/FEniCS-FF6F00?style=for-the-badge&logo=python&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white)
![PyMC](https://img.shields.io/badge/PyMC-1F4E79?style=for-the-badge&logo=python&logoColor=white)
![SALib](https://img.shields.io/badge/SALib-2E7D32?style=for-the-badge&logo=python&logoColor=white)

**Areas:** Numerical Analysis · PDEs · FEM / DG methods · Scientific Machine Learning · Deep Learning · PINNs · Sensitivity & Uncertainty Quantification · Statistical Inference · Bayesian Inference / MCMC · Inverse Problems · Parallel Computing · Computational Fluid Dynamics · Computational Systems Biology

## 💻 Get in touch

- [LinkedIn](https://www.linkedin.com/in/michele-baggi/)
- michelebaggi.baggi@gmail.com

## ⭐ About me

- 🏊 13+ years of competitive swimming at national level, with podiums at regional and international meets — water is my element
- 🎸 I love music, blues and rock above all, and I play guitar in my band *Syntonic*, gigging live together
- 🤝 A sociable person — always keen to meet new people and explore new places
- 🌱 Passionate about everything from health and wellbeing to sustainability
- 🌍 Clear-eyed about the challenges the world faces, but hopeful — and personally committed to doing my part for a better one
- 🌅 Happiest under a good sunrise, a sunset, or a sky full of stars
- 📚 Favourite book: *The Three-Body Problem* by Cixin Liu

*My motto: "Head in the clouds, feet on the ground."*

Enjoy my repositories! 🚀
