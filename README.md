# Federated Optimization and Privacy-Preserving Distributed Learning

Below are the final results for torch.manual_seed(42), np.random.seed(42). In order to reproduce the same results, in Google Colab select Runtime --> Change runtime type --> A100 GPU --> Save and run all cells.

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
