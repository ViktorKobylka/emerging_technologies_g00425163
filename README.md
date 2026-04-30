# Emerging Technologies - Assessment

**Module:** Emerging Technologies  
**Author:** Viktor Kobylka G00425163  
**Institution:** ATU

---

## About This Repository

This repository contains the solutions to the Emerging Technologies assessment.
The five problems explore the difference between classical and quantum algorithms,
focusing on the [Deutsch-Jozsa algorithm](https://quantum.cloud.ibm.com/learning/en/courses/fundamentals-of-quantum-algorithms/quantum-query-algorithms/deutsch-jozsa-algorithm) - one of the earliest demonstrations of
quantum computational advantage over any classical deterministic algorithm.

## Problems
1. Generating random Boolean functions
2. Classical algorithm to determine function type
3. Quantum oracles for Deutsch's single-input problem
4. Deutsch's algorithm implemented in Qiskit
5. Generalisation to the full Deutsch-Jozsa algorithm for four-bit inputs
---

## Setup Instructions

### Prerequisites

- Python 3.10 or higher
- `pip` (Python package manager)

### Clone the Repository

```bash
git clone https://github.com/ViktorKobylka/emerging_technologies_g00425163.git
cd emerging_technologies_g0042516
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

All required packages are listed in `requirements.txt`.


### Run the Notebook

```bash
jupyter notebook problems.ipynb
```

---

## Repository Structure

```
emerging-technologies/
├── problems.ipynb     # Main assessment notebook
├── requirements.txt   # Python dependencies
├── README.md          # This file
└── .gitignore         # Python gitignore
```

---

## Key References

- Deutsch, D. (1985). [Quantum Theory, the Church-Turing Principle and the Universal Quantum Computer](https://www.daviddeutsch.org.uk/wp-content/deutsch85.pdf).
- Deutsch, D., & Jozsa, R. (1992). [Rapid Solution of Problems by Quantum Computation](https://dl.acm.org/doi/10.5555/895843). 
- Nielsen, M. A., & Chuang, I. L. (2010). [Quantum Computation and Quantum Information](https://www.cambridge.org/highereducation/books/quantum-computation-and-quantum-information/01E10196D0A682A6AEFFEA52D53BE9AE). Cambridge University Press.
- [IBM Quantum Learning: Deutsch's Algorithm](https://quantum.cloud.ibm.com/learning/en/courses/fundamentals-of-quantum-algorithms/quantum-query-algorithms/deutsch-algorithm)
- [IBM Quantum Learning: Deutsch-Jozsa Algorithm](https://quantum.cloud.ibm.com/learning/en/courses/fundamentals-of-quantum-algorithms/quantum-query-algorithms/deutsch-jozsa-algorithm)
- [Qiskit Documentation](https://docs.quantum.ibm.com/)
- [Qiskit Aer Documentation](https://qiskit.github.io/qiskit-aer/)
