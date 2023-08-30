# iterative-nn-mqp
Author: Neil Kale

## RWKV
This project recreates the Receptance Weighted Key Value model. This model is less memory-intensive than attention-based transformers but still allows parallelization unlike RNNs. It also is much less prone to vanishing gradient, since it keeps a weighted sum of all previous inputs with no non-linearity applied.
