
# Neural Differential Models


## Motivation
Differential equations provide a natural framework for modeling continuous dynamics. Neural ODEs and their extensions (e.g., flows, social ODEs, neural operators) unify deep learning with dynamical systems and offer new approaches for tasks such as:
- Modeling time series and trajectories  
- Multi-agent forecasting  
- Learning mappings between function spaces (PDEs)  
- Efficient continuous-time alternatives to traditional deep nets  

This repo collects experiments inspired by seminal works such as:
1. *Neural Ordinary Differential Equations*  
2. *Understanding Neural ODEs*  
3. *Neural Flows: Efficient Alternatives to Neural ODEs*  
4. *Social ODE: Multi-Agent Trajectory Forecasting*  
5. *Neural Operator: Learning Maps Between Function Spaces with Applications to PDEs*  

---

## 📂 Repository Structure
```

neural-differential-models/
│── notebooks/        # Interactive Jupyter notebooks with experiments
│── src/              # Core implementations (ODE solvers, models, utils)
│── experiments/      # Scripts for reproducing results
│── data/             # Datasets (or links/instructions to download)
│── README.md         # Project documentation

````

---

## 🚀 Getting Started

### Prerequisites
- Python 3.9+  
- PyTorch >= 1.12  
- Other dependencies listed in `requirements.txt`  

### Installation
```bash
git clone https://github.com/<your-username>/neural-differential-models.git
cd neural-differential-models
pip install -r requirements.txt
````

---

## 📖 References

1. [An Introduction to Neural Ordinary Differential Equations (TFG Thesis)](https://diposit.ub.edu/dspace/bitstream/2445/208621/2/tfg_baldillou_salse_pau.pdf)  
2. [Understanding Neural ODEs (Blog)](https://jontysinai.github.io/jekyll/update/2019/01/18/understanding-neural-odes.html)  
3. [Neural Ordinary Differential Equations (NeurIPS 2018)](https://proceedings.neurips.cc/paper_files/paper/2018/file/69386f6bb1dfed68692a24c8686939b9-Paper.pdf)  
4. [Neural Operator: Learning Maps Between Function Spaces (NeurIPS 2020)](https://proceedings.neurips.cc/paper_files/paper/2020/file/293835c2cc75b585649498ee74b395f5-Paper.pdf)  
5. [Social ODE: Multi-Agent Trajectory Forecasting (AAAI 2021)](https://proceedings.neurips.cc/paper_files/paper/2021/file/b21f9f98829dea9a48fd8aaddc1f159d-Paper.pdf)  
6. [Modeling Trajectories with Neural Ordinary Differential Equations (ECCV 2022)](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136820211.pdf)  
7. [Neural Flows: Efficient Alternative to Neural ODEs (IJCAI 2021)](https://www.ijcai.org/proceedings/2021/0207.pdf)  
8. [Neural Controlled Differential Equations (JMLR 2023)](https://www.jmlr.org/papers/volume24/21-1524/21-1524.pdf)  
9. [Neural Ordinary Differential Equations — Rethinking Architecture (Medium)](https://medium.com/@justygwen/neural-ordinary-differential-equations-neural-odes-rethinking-architecture-272a72100ebc)  
10. [Hybrid Models: Combining Neural ODEs with Discrete Layers (Medium)](https://medium.com/@justygwen/hybrid-models-combining-neural-odes-with-discrete-layers-319d4ac05430)  

---

## ✨ Contributing

Contributions are welcome! If you have suggestions, bug fixes, or new experiments, feel free to open an issue or submit a pull request.

---

## 📜 License

This project is released under the MIT License.

