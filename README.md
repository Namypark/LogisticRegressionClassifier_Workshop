# Logistic Regression Classifier Workshop — Log-Loss Activity

My solution to the in-class activity for the **Statistical Classification and Logistic Regression** workshop.

In [`My_LogLoss_Activity.ipynb`](My_LogLoss_Activity.ipynb) I implement the log-loss (cross-entropy) function from scratch in NumPy, using the *hours studied → pass/fail* example. I then use it to train a logistic regression model with gradient descent. I check each part against scikit-learn and a numerical gradient estimate.

| Result | Value |
| --- | --- |
| Log-loss after training | 0.2321 (baseline: 0.6918) |
| Decision boundary | 2.875 hours |
| Accuracy | 89.47% (17 of 19 students) |

The notebook also contains my discussion of the results, the limitations, and my three talking points.

## Setup with pip

You need **Python 3.13** (I tested with 3.13).

### 1. Clone the repository

```bash
git clone https://github.com/Namypark/LogisticRegressionClassifier_Workshop.git
cd LogisticRegressionClassifier_Workshop
```

### 2. Create and activate a virtual environment

macOS / Linux:

```bash
python3 -m venv .venv
source .venv/bin/activate
```

Windows (PowerShell):

```powershell
python -m venv .venv
.venv\Scripts\Activate.ps1
```

### 3. Install the dependencies

```bash
pip install -r requirements.txt
```

### 4. Open the notebook

- **VS Code:** open `My_LogLoss_Activity.ipynb`, click *Select Kernel* (top right), and choose the `.venv` environment.
- **Jupyter in the browser:** install it with `pip install notebook`, then run `jupyter notebook My_LogLoss_Activity.ipynb`.

Run all cells from top to bottom (*Run All*). Every check should print ✅.

## Files

| File | Description |
| --- | --- |
| `My_LogLoss_Activity.ipynb` | My implementation, results, discussion, and talking points |
| `requirements.txt` | Pinned package versions for `pip install` |

## Author

Your name
