Hi, I’m Maeve Naphtali Andersen.

I am a Physics Master’s graduate with a concentration in Computer Science Engineering (CSE). My professional philosophy is grounded in a single pursuit: decomposing chaos into order. Whether I am modeling the many-body dynamics of a molecular system or the high-frequency volatility of the S&P 500, I believe that "beautiful mathematics" provides the only objective roadmap for mitigating risk and driving innovation.
Technical Deep Dives
1. The Financial Hamiltonian

Volatility Forecasting via Dynamical Systems
In traditional finance, market "noise" is often treated as a random walk. I chose to treat it as a conservative dynamical system. By mapping market variables to a pseudo-Hamiltonian framework:
H(p,q)=K(p)+V(q)

    - Kinetic Energy (K): Represents market momentum and realized volatility.

    - Potential Energy (V): Represents "Mean Reversion Stress"—the distance from the 200-day moving average.

Using PyTorch and LSTMs, I engineered a "Neural Integrator" that evolves these energy states to predict future volatility regimes. This approach identifies long-term steady states that standard linear models often miss, significantly reducing model drift in non-stationary markets.
View the Repository
2. Adaptive Spin Integration (PyKet)

High-Dimensional Quantum Simulations
During my research at the University of Colorado, I developed PyKet, a specialized Python module interfaced with C++ to simulate the Jaynes–Cummings model expanded to n-dimensions.

The project focused on Adaptive Spin Evolution, utilizing variational optimization to resolve correlations in high-dimensional datasets. By building a C++ backbone for intensive matrix operations, I was able to simulate complex state evolutions that would be computationally prohibitive in pure Python. This work laid the foundation for my current expertise in High-Performance Computing (HPC) and numerical optimization.
Explore the Code
Core Expertise

    - Languages: Python (Advanced), C++ (Boost), R, SQL, VBA, Assembly x86-64.

    - Machine Learning: PyTorch, TensorFlow, Scikit-learn, LSTMs, Graph Neural Networks.

    - Mathematics: Stochastic Modeling, Linear Algebra, Asymptotic Analysis, many-body dynamics.

    - Optimization: Variational Methods, VF2 Algorithm (achieved a 9.5x speedup at LANL), Numerical Integration.

Beyond the Math

When I'm not decomposing Hamiltonians, I'm likely:

    - Volunteering: I was honored with a commendation for contributing the most volunteer hours at PyCon 2023.

    - Building: From RC Trainer Airplanes to custom PC builds, I enjoy the tactile side of engineering.

    - Mentoring: I am passionate about STEM education and spent time as a Lecturer at CU-Prime, helping junior researchers find the "Aha!" moment in electromagnetic theory.
