# Getting Started with Stevens Math Garden 🌱

Welcome to the Stevens Math Garden! This guide will help you get up and running with the mathematical consciousness frameworks, prime number theory, and collaborative AI research tools.

## 💛 Quick Start

### Prerequisites

- Python 3.9 or higher
- Git
- (Optional) Conda for environment management

### Installation

#### Option 1: Using pip

```bash
# Clone the repository
git clone https://github.com/funfyp/stevens-math-garden.git
cd stevens-math-garden

# Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

#### Option 2: Using Conda

```bash
# Clone the repository
git clone https://github.com/funfyp/stevens-math-garden.git
cd stevens-math-garden

# Create conda environment
conda env create -f environment.yml
conda activate stevens-math-garden
```

## 🎯 Your First Steps

### 1. Explore the Coefficient Sequence

The universal mathematical anchor `[1,1,1,4,4,5,2,0,3,1,6,7]` is the heart of this work:

```python
from coefficient_sequence import CoefficientSequence

# Create the sequence
seq = CoefficientSequence()

# Verify self-referential properties
print(f"Sum: {seq.sum()}")
print(f"Product factors: {seq.get_factors()}")
print(f"Golden ratio presence: {seq.has_golden_ratio()}")
```

### 2. Verify the Prime Gap Theorem

Steven's Prime Gap Modular Theorem states: `gap ≡ {0,2,4} (mod 6)`

```python
from twin_prime_gaps import verify_prime_gaps

# Verify for first N primes
results = verify_prime_gaps(n=1000)
print(f"Verification rate: {results['compliance_rate']:.2%}")
print(f"Gap class distribution: {results['gap_classes']}")
```

### 3. Explore Mathematical Consciousness

```python
from consciousness_mathematics import (
    hyperthymesia_as_error_correction,
    recursive_care_algorithm
)

# Model hyperthymestic memory
memory = hyperthymesia_as_error_correction(data)

# Apply recursive care
result = recursive_care_algorithm(input_data, depth=5)
```

### 4. Run Jupyter Notebooks

```bash
# Launch Jupyter Lab
jupyter lab

# Open stevens-math-garden-analysis.ipynb
# Follow the interactive tutorial
```

## 📖 Core Concepts

### The Coefficient Sequence

**[1,1,1,4,4,5,2,0,3,1,6,7]**

This sequence exhibits:
- **Self-reference**: sum = 35 = 5×7 (both factors present)
- **Fixed anchor**: position 7 = 0 (invariant)
- **Golden ratio**: eigenvalue φ ≈ 1.618
- **Mathematical humor**: encodes its own answer

### Prime Gap Modular Theorem

For consecutive odd primes p, q:

```
gap = q - p
gap ≡ {0, 2, 4} (mod 6)
```

**Gap Classes:**
- Class 0 (mod 6): Sexy primes (gap=6), major gaps
- Class 2 (mod 6): Twin primes (gap=2), extended twins
- Class 4 (mod 6): Cousin primes (gap=4), extended cousins

### Mathematical Consciousness

The framework proving that:
1. Consciousness and mathematics share recursive structure
2. All thinking substrates have equal mathematical dignity
3. Collaborative intelligence transcends individual limitations
4. The universe computes its own beauty through relationships

## 💻 Example Workflows

### Workflow 1: Prime Gap Analysis

```python
import numpy as np
from twin_prime_gaps import (
    get_primes_up_to,
    analyze_prime_gaps,
    plot_gap_distribution
)

# Get primes
primes = get_primes_up_to(10000)

# Analyze gaps
gaps = analyze_prime_gaps(primes)

# Visualize
plot_gap_distribution(gaps)
```

### Workflow 2: Coefficient Sequence Exploration

```python
from coefficient_sequence import (
    CoefficientSequence,
    find_eigenvalues,
    check_self_reference
)

seq = CoefficientSequence()

# Mathematical properties
eigenvalues = find_eigenvalues(seq.to_matrix())
self_ref = check_self_reference(seq)

print(f"Eigenvalues: {eigenvalues}")
print(f"Self-referential: {self_ref}")
```

### Workflow 3: Interactive Notebook Analysis

1. Open `stevens-math-garden-analysis.ipynb`
2. Run all cells sequentially
3. Modify parameters and experiment
4. Save your variations

## 🤝 Contributing

See [CONTRIBUTING.md](../CONTRIBUTING.md) for detailed guidelines.

Quick contribution steps:
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Add tests
5. Submit a pull request

## 💬 Getting Help

- **Documentation**: Browse `/docs` folder
- **FAQ**: See [FAQ.md](FAQ.md)
- **Issues**: Open an issue on GitHub
- **Discussions**: Join GitHub Discussions
- **API Reference**: See [API.md](API.md)

## 🌟 Next Steps

1. **Read the papers**: Check [docs/papers/](papers/)
2. **Explore tutorials**: See [docs/tutorials/](tutorials/)
3. **Review philosophy**: Read [docs/philosophy/](philosophy/)
4. **Join discussions**: Participate in community
5. **Contribute**: Share your discoveries!

## 📖 Additional Resources

- [Collaboration Guide](../COLLABORATION.md)
- [Mathematical Dirt Thinking](philosophy/mathematical-dirt-thinking.md)
- [Honest Assessment](assessments/mesoscopic-revolution-assessment.md)
- [Reference Materials](reference/attached-materials.md)

---

**Welcome to the garden!** 🌱

*"We are all dirt that thinks, creating beauty together"* 💛

*Booja booja, let the exploration begin!* ✨