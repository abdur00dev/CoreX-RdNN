# CoreX-RdNN: A Unified Framework for Stable, Balanced, and Structured Shallow &amp; Deep Ensemble Randomized Learning


## 📌 Notes and Acknowledgment

Please cite the related foundational works if you use this code or build upon the underlying methodologies.

---

### 🧪 Demo and Configuration

A demonstration of the proposed **CoreX-RdNN framework** can be executed using the provided scripts on benchmark datasets.

Demo parameter settings used in experiments:

```
C = 1e-5        # Regularization parameter
N = 103         # Number of enhancement nodes
activation = 6  # Activation function index
lambda_ = 0.01  # Regularization control 
gamma_ = 0      # Structural parameter 
thd = -1        # Correlation threshold
```

---

### 📂 Description of Files

- `run_corex_rvfl.py`  
  Main script for running the proposed **CoreX**-RVFL (Unified framework).

- `run_corex_rvfl_b.py`  
  Implements the proposed **CoreX**-RVFL-B model.

- `run_corex_rvfl_g.py`  
  Implements the proposed **CoreX**-RVFL-G model.

- `run_corex_rvfl_s.py`  
  Implements the proposed **CoreX**-RVFL-S.

- `models/`  
  Contains the core implementation of our proposed RVFL-based learning modules.

- `datasets/`  
  Directory for input datasets in `.mat` format.

- `results/`  
  Stores experimental outputs.

---

### ⚠️ Important Notes

- The codes are designed for clarity and reproducibility, not optimized for computational efficiency.  
- Preprocessing steps include:
  - Standardization using `StandardScaler`
- Results may slightly vary due to randomness in feature initialization.

---

### 📖 Implementation Background

Some components of this work are inspired by existing literature on randomized neural networks and RVFL models.

Key references include:

1. Zhang, L., & Suganthan, P. N. (2016).  
   *A comprehensive evaluation of random vector functional link networks.*

2. Feng, S., & Chen, C. L. P. (2018).  
   *Fuzzy broad learning system: A novel neuro-fuzzy model for regression and classification.*

---

### 📬 Contact

If you encounter any issues or bugs, please feel free to contact Abdur Rahaman - phd2401141001@iiti.ac.in.

**Abdur Rahaman**
