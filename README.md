* Implemented fused CUDA kernels for Transformer attention (QK⊤, softmax, output projection) to reduce global
* Autotuned tiling and launch parameters; benchmarked against cuBLAS/CUTLASS with Nsight, showing significant latency reductions. 
