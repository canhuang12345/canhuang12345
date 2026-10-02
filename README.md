## Hi, I'm Can Huang

M.S. student in **Computational & Mathematical Engineering (ICME) at Stanford**. B.S. in Mathematics from Renmin University of China.

I work on **LLM systems**: retrieval and reranking, agents, and fast inference. I've also done research on **neural network compression with symbolic regression**, and I have a background in **quantitative research**.

- **Recently:** SWE Intern at **Google** (Summer 2026). Fine-tuned a Gemma cross-encoder reranker in JAX/FSDP on TPU (Recall@5 0.80 → 0.94, 1.2 s latency vs. >30 s for LLM rerankers)
- **Research:** replacing NN / ViT layers with explicit symbolic & PDE expressions found by genetic programming
- **Reach me:** canhuang@stanford.edu · [LinkedIn](https://www.linkedin.com/in/canhuang123)

---

### Featured Projects

| Project | What it is | Stack |
|---|---|---|
| [**llm-inference-cuda-mpi**](https://github.com/canhuang12345/llm-inference-cuda-mpi) | Llama-3.2-3B inference engine with FlashAttention, PagedAttention, fused kernels, and MPI tensor parallelism. **+14.6%** single-GPU throughput, **1.84×** on 4 GPUs | C++ · CUDA · MPI · Nsight |
| [**tech-equity-stat-arb**](https://github.com/canhuang12345/tech-equity-stat-arb) | PCA-hedged AMD residual spread (**+15.9%** held-out PnL) and cross-sectional ML ranking of 49 tech stocks (Ridge/LightGBM vs. LSTM/GRU/Transformer, walk-forward 2017–2022) | Python · scikit-learn · LightGBM · PyTorch |

<!-- Add more rows as you publish more repos, e.g. the Research Q&A Agent Platform -->

---

### Publications

- **SymRefine: A Symbolic Regression Approach for Refining and Compressing Neural Networks**<br>
  Wei Wei, Qiang Lu, **Can Huang**, David Lee, Jake Luo<br>
  *Neurocomputing*, 2026 · [DOI](https://doi.org/10.1016/j.neucom.2026.132719)
- **Refining Neural Network with Symbolic Regression**<br>
  Wei Wei, Qiang Lu, **Can Huang**, Jake Luo<br>
  *GECCO '25 Companion*, pp. 923–926 · [DOI](https://doi.org/10.1145/3712255.3726565)

**Under review**

- *Refining Vision Transformer with PDE Discovered by Symbolic Regression* (TPAMI)
- *ResPDE-SR: Evolving Residual PDE Symbolic Regression for Refining CNN* (AAAI 2027)

<!-- Optional: add your Google Scholar link here once your profile is public -->
<!-- [Google Scholar](https://scholar.google.com/citations?user=XXXX) -->

---

### Toolbox

**Languages:** Python · C++ · CUDA<br>
**ML / LLM:** PyTorch · JAX · Transformers · scikit-learn · LightGBM / XGBoost<br>
**LLM training:** SFT · DPO · GRPO · LoRA / QLoRA · FSDP<br>
**Agents & retrieval:** Google ADK · LangGraph · MCP · RAG · Milvus / Chroma · reranking<br>
**HPC:** CUDA kernels · MPI · OpenMP · Nsight Systems

<!--
Optional stats card. Remove if you prefer a cleaner look:
![](https://github-readme-stats.vercel.app/api?username=canhuang12345&show_icons=true&hide_border=true)
-->
