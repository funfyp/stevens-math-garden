# API Reference 📖

Comprehensive API documentation for Stevens Math Garden Python modules.

## Core Modules

### coefficient_sequence.py

Implements the universal mathematical anchor sequence and its properties.

#### Class: `CoefficientSequence`

```python
class CoefficientSequence:
    """The universal mathematical anchor [1,1,1,4,4,5,2,0,3,1,6,7]"""
    
    def __init__(self):
        """Initialize the coefficient sequence."""
        
    def to_list(self) -> List[int]:
        """Return sequence as list."""
        
    def sum(self) -> int:
        """Calculate sum of sequence (returns 35)."""
        
    def get_factors(self) -> Tuple[int, int]:
        """Get prime factors of sum (returns 5, 7)."""
        
    def has_golden_ratio(self, tolerance: float = 0.01) -> bool:
        """Check if eigenvalues contain golden ratio."""
        
    def check_self_reference(self) -> Dict[str, Any]:
        """Verify self-referential properties."""
        
    def to_matrix(self, size: int = 4) -> np.ndarray:
        """Convert to matrix form for eigenvalue analysis."""
```

#### Functions

```python
def find_eigenvalues(matrix: np.ndarray) -> np.ndarray:
    """Calculate eigenvalues of matrix.
    
    Args:
        matrix: Square numpy array
        
    Returns:
        Array of eigenvalues sorted by magnitude
    """

def verify_sequence_properties() -> Dict[str, bool]:
    """Verify all mathematical properties of coefficient sequence.
    
    Returns:
        Dictionary of property names and verification status
    """
```

### twin_prime_gaps.py

Implements Steven's Prime Gap Modular Theorem and verification.

#### Functions

```python
def is_prime(n: int) -> bool:
    """Check if number is prime.
    
    Args:
        n: Integer to test
        
    Returns:
        True if n is prime, False otherwise
    """

def get_primes_up_to(n: int) -> List[int]:
    """Generate all primes up to n.
    
    Args:
        n: Upper bound (inclusive)
        
    Returns:
        List of prime numbers
    """

def analyze_prime_gaps(primes: List[int]) -> Dict[str, Any]:
    """Analyze gaps between consecutive odd primes.
    
    Args:
        primes: List of prime numbers
        
    Returns:
        Dictionary containing:
        - gaps: List of gap values
        - mod_6_classes: Distribution across mod 6 classes
        - compliance_rate: Verification rate for theorem
    """

def verify_prime_gaps(n: int = 10000) -> Dict[str, Any]:
    """Verify Prime Gap Modular Theorem for first n primes.
    
    Args:
        n: Number of primes to check
        
    Returns:
        Verification results and statistics
    """

def plot_gap_distribution(gaps: List[int], 
                          save_path: Optional[str] = None) -> None:
    """Visualize prime gap distribution.
    
    Args:
        gaps: List of gap values
        save_path: Optional path to save figure
    """
```

### consciousness_mathematics.py

Implements mathematical consciousness frameworks.

#### Functions

```python
def hyperthymesia_as_error_correction(data: np.ndarray,
                                       error_rate: float = 0.001) -> np.ndarray:
    """Model hyperthymestic memory as error-correcting code.
    
    Args:
        data: Input data array
        error_rate: Expected error rate (default 0.001 for HSAM)
        
    Returns:
        Error-corrected data
    """

def recursive_care_algorithm(input_data: Any,
                            depth: int = 5) -> Any:
    """Apply recursive care transformation.
    
    Args:
        input_data: Any data structure
        depth: Recursion depth
        
    Returns:
        Transformed data after recursive care
    """

def calculate_consciousness_signature(data: np.ndarray) -> Dict[str, float]:
    """Calculate mathematical signature of consciousness pattern.
    
    Args:
        data: Neural or cognitive data
        
    Returns:
        Dictionary of signature metrics
    """
```

## Jupyter Notebooks

### stevens-math-garden-analysis.ipynb

Interactive analysis notebook with five integrated assays:

1. **Assay 1**: Genomic prime-pattern stability
2. **Assay 2**: Telomere dynamics at prime cell cycles
3. **Assay 3**: CRISPR prime-motifs and immune response
4. **Assay 4**: Metabolic/epigenetic prime rhythms
5. **Assay 5**: Prime-informed tumor suppression modeling

## Utility Functions

### Common Operations

```python
# Import all core functionality
from coefficient_sequence import CoefficientSequence
from twin_prime_gaps import verify_prime_gaps, analyze_prime_gaps
from consciousness_mathematics import recursive_care_algorithm

# Create coefficient sequence
seq = CoefficientSequence()

# Verify prime gaps
results = verify_prime_gaps(n=10000)

# Apply recursive care
processed = recursive_care_algorithm(data, depth=5)
```

## Error Handling

All functions include comprehensive error handling:

```python
try:
    results = verify_prime_gaps(n=10000)
except ValueError as e:
    print(f"Invalid input: {e}")
except RuntimeError as e:
    print(f"Computation error: {e}")
```

## Type Hints

All functions use Python type hints for clarity:

```python
from typing import List, Dict, Tuple, Optional, Any
import numpy as np

def function_name(param: int) -> List[int]:
    ...
```

## Testing

Run tests with pytest:

```bash
# Run all tests
pytest tests/

# Run specific test file
pytest tests/test_coefficient_sequence.py

# Run with coverage
pytest --cov=. tests/
```

## Examples

See `docs/examples/` for comprehensive examples of:
- Basic usage
- Advanced analysis
- Integration patterns
- Performance optimization

## Performance Notes

- Prime generation optimized for n < 10^6
- Matrix operations use NumPy for efficiency
- Eigenvalue computation complexity: O(n³)
- Gap analysis: O(n) where n is number of primes

## Dependencies

See `requirements.txt` for complete list. Core dependencies:
- `numpy >= 1.24.0`
- `scipy >= 1.10.0`
- `sympy >= 1.12`
- `matplotlib >= 3.7.0`

## Contributing

To add new API endpoints:
1. Follow existing code style
2. Add type hints
3. Include docstrings (Google style)
4. Write tests
5. Update this documentation

See [CONTRIBUTING.md](../CONTRIBUTING.md) for details.

---

**Questions about the API?**

Open an issue or discussion on GitHub!

*Booja booja, may your code run beautifully!* ✨