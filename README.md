# Classical to Quantum Systems

This project demonstrates the transition from Classical Physical Systems to Quantum Systems through Python implementations. It explores the fundamental concepts and mathematical frameworks that bridge these domains, including classical mechanics, probabilistic systems, and quantum mechanics.

## Getting Started

These instructions will help you set up and run the project on your local machine for development and testing purposes.

### Prerequisites

You need to have Python 3.8 or higher installed, along with the following libraries:

```
numpy
matplotlib
jupyter
IPython
```

### Installing

1. Clone the repository:
```
git clone https://github.com/camilo-axm/Clasic-to-Quantum-CNYT.git
```

2. Install the required Python packages:
```
pip install numpy matplotlib jupyter
```

3. Launch Jupyter Notebook:
```
jupyter notebook
```

4. Open `TallerClasicToQuantum.ipynb` in the Jupyter interface

## Running the Systems

The notebook contains three main implementations:

### 1. Classical System

The classical system demonstrates deterministic evolution using a simple harmonic oscillator model. It shows how position and velocity evolve over time according to Newton's laws.

Example usage:
```python
initial_state = {'position': 1.0, 'velocity': 0.0}
classical_sys = ClassicalSystem(initial_state)
```

### 2. Probabilistic System

The probabilistic system introduces uncertainty through probability distributions and measurements. It implements a simple two-state system with transition probabilities.

Example usage:
```python
states = np.array([0, 1])
initial_probs = np.array([0.6, 0.4])
prob_sys = ProbabilisticSystem(states, initial_probs)
```

### 3. Quantum System

The quantum system implements basic quantum mechanics concepts including superposition and unitary evolution. It demonstrates the behavior of a single qubit under rotation.

Example usage:
```python
initial_state = np.array([1, 1]) / np.sqrt(2)  # |+⟩ state
quantum_sys = QuantumSystem(initial_state)
```

## Built With

* [Python](https://www.python.org/) - Programming language used
* [NumPy](https://numpy.org/) - Scientific computing library
* [Matplotlib](https://matplotlib.org/) - Plotting library
* [Jupyter](https://jupyter.org/) - Interactive computing platform

## Authors

* **Camilo Aguirre** - *Initial work* - [camilo-axm](https://github.com/camilo-axm)
## Acknowledgments

* Based on principles of classical mechanics, probability theory, and quantum mechanics
* Inspired by the need to understand the transition from classical to quantum systems
* Special thanks to the CNYT course for the theoretical foundations
