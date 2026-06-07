# Papers 05 — Context, Position & Retrieval

Presentation 05 in the Key LLM Publications series indexes five publications that define how modern LLMs encode position and ground their answers in external knowledge. It covers **RoFormer / RoPE** (Su et al., 2021 — rotary position embedding, now the default in Llama, Mistral and Qwen), **RAG** (Lewis et al., 2020 — coupling a BART generator with a dense Wikipedia retriever for grounded, updatable generation), **DPR** (Karpukhin et al., 2020 — the dual-encoder, in-batch-negatives, inner-product retriever that backs RAG and every modern embedding stack), **Lost in the Middle** (Liu et al., 2023 — the U-shaped curve showing long context windows are not used uniformly), and **Self-RAG** (Asai et al., 2023 — reflection tokens that make retrieval and self-critique on-demand decisions). Each slide gives the problem, the contribution, why it matters to a practising LLM/agent engineer, an original inline diagram, and a key takeaway, building an arc from position encoding through grounding to agentic, self-correcting retrieval.

**Live site:** https://brendanjameslynskey.github.io/Papers_05_Retrieval_and_Long_Context/

Part of the [Key LLM Publications sub-hub](https://github.com/BrendanJamesLynskey/LLM_Hub_Key_Publications)
