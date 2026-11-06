### Vladimir Shakirov

Machine learning engineer with a background in computational neuroscience. I work on GPU performance, on evaluating models and agents, and on ML for biology.

**GPU and performance**
- [esm2-inference-optimization](https://github.com/Schakirov/esm2-inference-optimization): profiling and speeding up the ESM2 protein language model on an NVIDIA L4. Length-sorted batching gives 1.7× throughput; also `torch.compile` and a custom Triton kernel, all checked for correctness.
- [nano-transformers](https://github.com/Schakirov/nano-transformers): a transformer built from scratch (own autograd, NumPy only), plus hand-written CUDA kernels traced down to PTX and SASS.

**Evaluating models and agents**
- [llm-regression-observability](https://github.com/Schakirov/llm-regression-observability): detects when a model, prompt or tool change makes an LLM app worse. Caught 18 of 18 planted regressions with 0 false alarms.
- [code-agent-runtime](https://github.com/Schakirov/code-agent-runtime): runs, sandboxes, traces, replays and scores coding agents.

**Biology**
- [bioscientist-os](https://github.com/Schakirov/bioscientist-os): turns biomedical papers into evidence tables, where every claim links back to its source sentence.

**Research**

MSc thesis in computational neuroscience on cerebellar learning ([code](https://github.com/Schakirov/cerebellum)), published as:
- Shakirov V. et al. *Cerebellar plasticity-based equalization of total input to inferior olive cells.* Neurosci Behav Physi 53, 739–751 (2023). [doi](https://doi.org/10.1007/s11055-023-01422-8)
- Shakirov V., Dorofeev V., Dunin-Barkowski W. *Cerebellar plasticity-based equalization of total input to inferior olive cells: properties of the model dynamics.* Neurosci Behav Physi 53, 729–738 (2023). [doi](https://doi.org/10.1007/s11055-023-01423-7)
- Shakirov V. et al. *Dynamic chaos in cerebellum and electrical synapses between climbing fiber cells of inferior olives.* Neurosci Behav Physi 53, 717–728 (2023). [doi](https://doi.org/10.1007/s11055-023-01420-w)

Earlier: deep-transition RNN language models in Torch7 ([2017](https://github.com/Schakirov/deep-transition-RNN)), multi-agent reinforcement learning with PPO (2019).

**Contact:** [LinkedIn](https://www.linkedin.com/in/vladimir-shakirov/)
