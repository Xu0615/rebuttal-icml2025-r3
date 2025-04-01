# rebuttal-icml2025-r3

## Table 1: Faithfulness of the Union Circuit across different percentage values of total edges
| Top Edges Used | 1%   | 2%   | 3%   | 4%   | 5%   | 6%   | 8%   | 10%  |
| -------------- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |
| Faithfulness   | 67.4 | 79.4 | 83.7 | 87.2 | 89.2 | 89.4 | 89.6 | 89.7 |

## Table 2: Comparison of the accuracy of the two methods on five tasks
| Method                          | Param Ratio | Add/Sub(300) | Mul/Div   | Sequence  | LCM       | Function   |
| ------------------------------- | ----------- | ------------ | --------- | --------- | --------- | ---------- |
| AdaLoRA                         | 1.7481%     | 76.70        | 92.75     | 90.10     | 89.80     | 98.20      |
| **CircuitLoRA (rₒ=16, r_c=64)** | 1.4248%     | **83.10**    | **97.00** | **94.60** | **93.00** | 99.50      |

## Table 3: Top-5 Critical Layers in five tasks
| Task             | Top-5 Critical Layers |
| ---------------- | --------------------- |
| Add/Sub(100–500) | 0, 4, 6, 5, 2         |
| Mul/Div          | 0, 3, 4, 11, 13       |
| Sequence         | 0, 7, 9, 10, 11       |
| Function         | 0, 3, 4, 13, 14       |
| LCM              | 0, 3, 4, 11, 13       |
