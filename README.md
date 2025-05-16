<div align="center">


# SEOE: A Scalable and Reliable Semantic Evaluation Framework for Open Domain Event Detection

</div>

<h5 align=center>

[![arXiv](https://img.shields.io/badge/arXiv-2503.03303-b31b1b.svg)](https://arxiv.org/abs/2503.03303)
[![hf](https://img.shields.io/badge/🤗-Hugging%20Face-blue.svg)](https://huggingface.co/datasets/Ralston/SEOE_benchmark)
[![License](https://img.shields.io/badge/Code%20License-Apache%202.0-yellow)](https://github.com/Lyfralston/SEOE?tab=Apache-2.0-1-ov-file#readme)
[![GitHub stars](https://img.shields.io/github/stars/Lyfralston/SEOE.svg?colorA=orange&colorB=orange&logo=github)](https://github.com/Lyfralston/SEOE)

</h5>

This is the repository for the paper [SEOE: A Scalable and Reliable Semantic Evaluation Framework for Open Domain Event Detection](https://arxiv.org/abs/2503.03303).


## 🔥 News

- **2025 May 16:** Paper is accepted by [ACL 2025](https://2025.aclweb.org/) Main Conference.
- **2024 Mar 5:** Paper is available on [arXiv](https://arxiv.org/abs/2503.03303).

## 📊 Release of SEOE's Benchmarks

You can find all of the following data clearly named in [this huggingface repository](https://huggingface.co/datasets/Ralston/SEOE_benchmark).

As stated in the paper, we will release three full SEOE's benchmarks: 

- The version with a preference for **accuracy** (using threshold $p=0.3$ in nucleus sampling with 10 rounds).
- The version with a preference for **diversity** (using threshold $p=0.7$ in nucleus sampling with 10 rounds).
- The **balance** version used in the paper (using threshold $p=0.5$ in nucleus sampling with 10 rounds).

Besides, we provide a subset of the benchmarks. You can also get these subsets with sizes of 1/10, 1/4, 1/2 of three full benchmarks. We have already validated that these subsets maintain statistical representativeness in evaluation experiments, while they can significantly reduce evaluation costs.

You can also find the integrated ontology, along with fine-grained definitions for all event types, and the corresponding group information (with threshold=0.9), which is used to assist in semantic evaluation in the paper.

