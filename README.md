This is the repository for the paper [SEOE: A Scalable and Reliable Semantic Evaluation Framework for Open Domain Event Detection](https://arxiv.org/abs/2503.03303).

### Release of SEOE's Benchmarks

You can find all of the following data clearly named in [this huggingface repository](https://huggingface.co/datasets/Ralston/SEOE_benchmark).

As stated in the paper, we will release three full SEOE's benchmarks: 

- The version with a preference for **accuracy** (using threshold $p=0.3$ in nucleus sampling with 10 rounds).
- The version with a preference for **diversity** (using threshold $p=0.7$ in nucleus sampling with 10 rounds).
- The **balance** version used in the paper (using threshold $p=0.5$ in nucleus sampling with 10 rounds).

Besides, we provide a subset of the benchmarks. You can also get these subsets with sizes of 1/10, 1/4, 1/2 of three full benchmarks. We have already validated that these subsets maintain statistical representativeness in evaluation experiments, while they can significantly reduce evaluation costs.

The integrated ontology along with its fine-grained definitions for all event types is provided. Besides, the corresponding group information (with threshold=0.9), which is used to assist in semantic evaluation in the paper, is also provided.
