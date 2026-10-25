CS521 HW3 — Jinwu Hu (jinwuhu2)

Public code: https://github.com/Pamyt/cs521-hw3-fall2026

The report is provided separately with the course submission.
Problem 1: Q1_From_Scratch.ipynb and Q1_From_Scratch_Code_and_Results.zip
Problem 2: Q2_SynCode_Phi2.ipynb
Problem 3: Q3_MultiNorm_Adversarial_Training.ipynb
Bonus: CS521_Bonus_Experiments.ipynb

Problem 1 now uses two newly initialized official Q3 make_model() instances,
trained for five epochs each. The fresh Q1 archive contains the protocol,
per-epoch history, per-example attack outcomes and source hashes from the
October 24 experiment. No Q3 base checkpoint is loaded by these runs.
The unfinished final attack evaluation was resumed from the saved five-epoch
models after a runtime restart; the execution event and original log are retained.
No partial outcomes from the interrupted pass enter the results.

HW3_Code_and_Results.zip preserves the original Q2, Q3 and bonus evidence,
along with the earlier Q1 experiment. Q1_PGD_Training_Reconstructed.ipynb
is retained as historical material; the current Q1 answer uses
Q1_From_Scratch.ipynb and its separate evidence archive.

Each notebook embeds its implementation and provides explicit rerun options.
Large model weights and CIFAR datasets are excluded from the compact package;
public asset downloads are documented in the notebooks. Training timings and
numerical results depend on hardware. All reported results are measured.
