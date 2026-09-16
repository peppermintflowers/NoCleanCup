# NoCleanCup

NoCleanCup is a hands-on project for learning and experimenting with online KV-cache compaction for multi-turn LLM inference.

The project is inspired by *Practical Online KV Cache Compaction for LLM Agents: An Empirical Study* by Yujian Liu, Jiabao Ji, Li An, Rohit Jain, Gungor Polatkan, Siyu Zhu, and Shiyu Chang (2026). I’m starting by recreating a small-scale version of the paper’s online KV-cache compaction setup to understand how the method works in practice. From there, I plan to experiment with adaptive cache-retention policies and study their behavior and performance on GPU.

**Reference:** Yujian Liu et al., *Practical Online KV Cache Compaction for LLM Agents: An Empirical Study*, arXiv:2608.00902, 2026.

## Why NoCleanCup?

The name comes from the Mad Hatter’s tea party, where nobody cleans the cups. They simply move down the table and keep going. A growing KV cache has a somewhat similar problem: eventually, we have to decide what to keep around and what to leave behind.
