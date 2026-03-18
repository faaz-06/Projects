**Quantum Portfolio Optimization Using Variational Quantum Algorithms**  

Repo Link: https://github.com/KavinKrishnan2007/QC_Capstone_MarkowitzPortfolioOptimizer

A hybrid quantum–classical framework for optimizing financial portfolios using Variational Quantum Eigensolvers (VQE) implemented in PennyLane. The project compresses 256 assets into 8 qubits, producing normalized portfolio weights and balancing risk-return trade-offs in the NISQ era.  

**Key Principles**  
- Portfolio Optimization : Formulated as a combinatorial problem to balance expected return and risk.  
- VQE Implementation : Parameterized quantum circuits iteratively optimized with classical Adam optimizer to minimize portfolio risk.  
- Quantum Weight Encoding : Converts quantum probability outputs directly into continuous portfolio allocations.  
- Hardware Efficiency : 8-qubit compressed representation enables large-scale asset optimization.  

**Features**  
- Hybrid VQE workflow for continuous asset allocation  
- Normalized portfolio weights across 256 assets  
- Simulation and hardware execution (27-qubit processor)  
- Risk-return scatter and growth projection visualizations  

**Technologies Used**  

PennyLane, Python, NumPy, Matplotlib, Pandas  

**Author / Project Team**  
- Krishnam - Engineering Physics, Class of 2029, IIT Indore
- Anushri - Mathematics and Computing, Class of 2029, IIT Indore
- Kavin – Metallurgical Engineering & Material Sciences, Class of 2029, IIT Indore
