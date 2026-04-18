# Brent Young, Ph.D.

**Applied Mathematics | Data Science | Machine Learning Systems**

I am an applied mathematician and data scientist with a PhD in Mathematics from Rutgers University and an MS in Data Science from Fordham University and 10+ years of experience designing quantitative models, building machine learning systems, and working with distributed computing frameworks. My work connects mathematical theory with practical implementation — particularly in probabilistic modeling, machine learning, and scalable computational systems. I have published research in mathematical physics and machine learning, and I am actively seeking industry roles in applied mathematics, data science, and ML research.

<p align="center">
<img src="https://raw.githubusercontent.com/byoung77/GUI-Fractal-Project/main/images/Rainbow_Mand.png" width="600">
</p>
<p align="center">
Example output from fractal visualization tool (C/GTK project below)
</p>

---

## 📄 Publications

- Young, B. and Zhao, Y., "Change Point Detection via Hierarchical Dirichlet Process Hidden Markov Models with Topological Emissions," MS Thesis, Fordham University (2025). Submitted for publication.
- Young, B., "Landau Damping in Relativistic Plasmas," J. Math. Physics 57, 021502 (2016).
- Young, B., "On Linear Landau Damping for Relativistic Plasmas via Gevrey Regularity," J. Diff. Eqns. (2015), doi:10.1016/j.jde.2015.04.021.
- Young, B., "Existence of Spherical Initial Data with Unit Mass, Zero Energy, and Virial less than −1/2 for the Relativistic Vlasov–Poisson Equation with Attractive Coupling," J. Math. Phys. 52, 093707 (2011).
- Young, B., "Optimal L^β-Control for the Global Cauchy Problem of the Relativistic Vlasov–Poisson System," Transport Theory and Statistical Physics 40, 331–359 (2011).

---

## 🛠️ Technical Skills

**Programming:** Python, Julia, Go, C, Mathematica
**Machine Learning:** Bayesian modeling, HMMs, clustering, topological data analysis, neural networks, RAG systems  
**Data Science:** NumPy, pandas, scikit-learn, PyTorch, SQL
**Data & Distributed Systems:** Hadoop, Spark, MapReduce  
**Tools:** Git, Linux, LaTeX  

---

## 🔍 Current Focus

- Approximate Nearest Neighbor (ANN) algorithms  
- Retrieval-Augmented Generation (RAG) systems  
- Bayesian modeling and change point detection  
- Distributed computing (Hadoop, Spark)  
- From-scratch implementations of machine learning algorithms  

---

## 🚀 Featured Projects

### 📈 HDP-HMM with Topological Emissions (Julia)  
Bayesian nonparametric model for unsupervised change point detection in time-series data, combining Hierarchical Dirichlet Process Hidden Markov Models with topological data analysis.

- Hierarchical Dirichlet Process prior for automatic state inference — no need to specify number of states
- Vectorized persistence diagrams as emission features, capturing topological structure of windowed time-series data
- Full Gibbs sampling inference pipeline implemented from scratch in Julia
- Validated on synthetic datasets, human motion capture data (MSRC-12), and NASA Solar Dynamics Observatory imagery
- Outperforms generic change point detection methods across all experimental settings 

👉 https://github.com/byoung77/hdp-hmm-te  

---

### 🔗 Approximate Nearest Neighbor (ANN) System  
Graph-based approximate nearest neighbor index inspired by HNSW, built for clarity, experimentation, and tunable performance.

- Cosine and Euclidean similarity with tunable search accuracy vs. performance tradeoffs
- Batch construction and dynamic incremental insertion
- Graph connectivity maintained via MST-based reconnection
- Empirical evaluation of recall, inflation, and timing across varying dataset sizes and parameters

👉 https://github.com/byoung77/Approximate-Nearest-Neighbors-Project  

<p align="center">
  <img src="https://raw.githubusercontent.com/byoung77/Approximate-Nearest-Neighbors-Project/main/Images/Figure_BuildTimes_Cosine.png" width="600">
</p>
<p align="center">
Build Times vs. Dataset Size for ANN System
</p>

---

### 🧠 Neural Network (NumPy, From Scratch)  
Configurable feedforward neural network implemented from first principles.

- Implemented generic feedforward architecture with user-defined layers  
- Coded backpropagation and gradient updates manually  
- Designed modular training loop with support for classification and regression  
- Trained model exposed as a reusable callable class  

👉 https://github.com/byoung77/Neural-Net-Implementation 

<p align="center">
  <img src="https://raw.githubusercontent.com/byoung77/Neural-Net-Implementation/main/Images/test_moons_large_plot.png" width="45%">
  <img src="https://raw.githubusercontent.com/byoung77/Neural-Net-Implementation/main/Images/test_moons_large_loss.png" width="45%">
</p>
<p align="center">
  Neural Net Training Loss for Two Moons Dataset
</p>

---

### 🖧 Simulated CRAQ Server
Go-based distributed systems simulation of Chain Replication with Asynchronous Queries (CRAQ), emphasizing message-passing concurrency, observability, and interactive exploration.

- Message-passing architecture using goroutines and channels
- Chain replication with versioning, commit propagation, and dirty-state tracking
- Deferred-read design for dirty entries (waitlist-based instead of tail forwarding)
- Interactive REPL with real-time monitoring via per-node log files

👉 https://github.com/byoung77/Simulated-CRAQ-Server

<p align="center">
  <img src="https://raw.githubusercontent.com/byoung77/Simulated-CRAQ-Server/main/images/Simple_CRAQ_Simulation.png" width="45%">
</p>
<p align="center">
  CRAQ Simulation Architecture
</p>

---

### 📚 Doctor Who Oracle (RAG System)  
End-to-end retrieval-augmented generation system for question answering over unstructured text, built on Wikipedia data.

- FAISS vector database for semantic similarity search
- Cross-encoder reranking for improved document relevance
- Citation-aware LLM responses for verifiable outputs
- Interactive desktop GUI built with Tkinter 

👉 https://github.com/byoung77/Doctor-Who-Oracle  

<p align="center">
  <img src="https://raw.githubusercontent.com/byoung77/Doctor-Who-Oracle/main/Images/Oracle_Tab.png" width="60%">
</p>
<p align="center">
  Dr. Who Oracle Interface
</p>

---

### 💡 Lights Out

An interactive Python implementation of the classic *Lights Out* puzzle, extended with multiple algebraic state spaces and nontrivial topological grids.

- Variable grid sizes from 2×2 to 15×15
- Multiple state spaces over Z_p for p ∈ {2, 3, 5, 7}
- Nontrivial board topologies: cylinder, Möbius strip, torus, Klein bottle, projective plane
- Built-in solver using linear algebra over finite fields
- Guaranteed solvability via construction from valid press vectors

<p align="center">
  <img src="https://raw.githubusercontent.com/byoung77/lights-out/main/images/launch_window.png" width="25%" />
  <img src="https://raw.githubusercontent.com/byoung77/lights-out/main/images/sample_game_grid.png" width="25%" />
</p>

👉 https://github.com/byoung77/lights-out

---

### 💾 Committee Appeals Database 

Built a Python/MySQL/LaTeX system to replace fragmented committee records stored across multiple documents, enabling searchable history and automated generation of professional PDF reports.

- Designed and built a relational database system to replace fragmented committee records stored across disconnected Google Docs, enabling centralized search and retrieval for the first time
- Developed Tkinter GUI supporting record creation, editing, deletion, date-range queries, and student-specific lookup
- Automated generation of professional PDF reports using LaTeX, including statistical summaries of approval rates, repeat cases, and outcome breakdowns
- Database design was subsequently adopted into a larger institutional student management system at Wilkes University

👉 https://github.com/byoung77/committee-appeals-db  

---

### 🌀 Fractal Explorer (C / GTK)  
Interactive fractal visualization tool built in C using GTK, for exploring complex dynamical systems in real time.

- Mandelbrot and Julia sets with real-time zoom and navigation
- User-defined complex function exploration
- Iterative numerical algorithms for orbit computation and escape-time analysis
- Optimized for performance in C, enabling high-resolution real-time renderin 

👉 https://github.com/byoung77/GUI-Fractal-Project  

---

## 🎓 Background

- **Ph.D., Mathematics** — Rutgers University (2011)
- **M.S., Data Science** — Fordham University (2025)
- **M.S., Mathematics** — University of North Carolina – Wilmington (2005)
- **B.S., Physics** — University of North Carolina – Chapel Hill (1999)
- **Associate Professor of Mathematics**, Wilkes University (2015–Present)
- **Postdoctoral Researcher** — Universität zu Köln (2012–2014)


---

## 🎯 Approach

I build things from first principles to understand core mechanics, bridge mathematical theory and practical implementation, and evaluate tradeoffs through experimentation. I am particularly interested in problems that require both rigorous mathematical thinking and careful engineering judgment.

---

## 📫 Contact

- Email: [bojy77@gmail.com](mailto:bojy77@gmail.com) 
- GitHub: https://github.com/byoung77  

---

## 📄 License

All projects are released under the MIT License unless otherwise noted.
