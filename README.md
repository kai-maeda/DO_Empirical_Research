# Federated Optimization and Privacy-Preserving Distributed Learning

Below are the final results for torch.manual_seed(42), np.random.seed(42). In order to reproduce the same results, in Google Colab select Runtime --> Change runtime type --> A100 GPU --> Save and run all cells.

# Federated Learning Communication Efficiency Research
## Testing Different Communication Rounds (τ)

**Research Question:** How does the number of communication rounds (τ) affect FL efficiency?

**Variables:**
- Independent: τ ∈ {1, 5, 10, 20, 50}
- Dependent: Communication cost (bits), Accuracy (90% threshold), Convergence round, Training time

---

# Federated Learning: Quantization & Sparsification for Communication Efficiency
## Reducing Communication Cost via Compression

**Research Question:** How do quantization and sparsification affect FL communication efficiency?

**Independent Variables:**
- Quantization: {8, 16, 32} bits (deterministic)
- Sparsification (Top-K): {10%, 20%, 50%, 100%} of gradients

**Dependent Variables:**
- Communication cost (bits)
- Model accuracy (90% threshold)
- Convergence round
- Training time

---

# Federated Learning: Worker Selection Strategies for Communication Efficiency
## Reducing Communication by Selecting Fewer Workers

**Research Question:** How do different numbers of workers and selection strategies affect FL efficiency?

**Independent Variables:**
1. **Number of Workers (Total Pool):** {10, 20, 50, 100}
2. **Worker Selection Strategies:**
   - Random Selection
   - Cyclic Selection (round-robin)
   - Adaptive Selection (LAG - Least Recently Selected)

**Dependent Variables:**
- Communication cost (bits)
- Model accuracy (90% threshold)
- Convergence round
- Training time

---

# Appendix

## Reducing Communication Cost via Different Communication Rounds ($\tau$)

![Alt text](results/tau/Exp_pt1.png)
![Alt text](results/tau/Exp_pt2.png)
![Alt text](results/tau/Acc_Time.png)
![Alt text](results/tau/Cost_Time.png)
![Alt text](results/tau/Summary.png)

## Reducing Communication Cost via Compression

![Alt text](results/quant_sparse/Exp_pt1.png)
![Alt text](results/quant_sparse/Exp_pt2.png)
![Alt text](results/quant_sparse/Exp_pt3.png)
![Alt text](results/quant_sparse/Acc_Time_Quant.png)
![Alt text](results/quant_sparse/Acc_Time_Sparse.png)
![Alt text](results/quant_sparse/Summary.png)

## Reducing Communication cost via Selecting Fewer Workers

![Alt text](results/worker_selection/Exp_pt1.png)
![Alt text](results/worker_selection/Exp_pt2.png)
![Alt text](results/worker_selection/Exp_pt3.png)
![Alt text](results/worker_selection/Exp_pt4.png)
![Alt text](results/worker_selection/Acc_Time_N.png)
![Alt text](results/worker_selection/Acc_Time_Strategy.png)
![Alt text](results/worker_selection/Worker_Participation.png)
![Alt text](results/worker_selection/Summary_N.png)
![Alt text](results/worker_selection/Summary_Strategy.png)
