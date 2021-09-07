### Arabic Denormalization ###
Arabic is a morphologically rich language which can cause data sparsity issues for many NLP models. To overcome such, many popular toolkits such as MADAMIRA and FARASA have been proposed. However, many of the settings for these systems result in destructive normalization - or lack of ability to reconstruct the original data.

This is a tool for training a simple sequence-to-sequence model where tokenized data is fed into the model and proper Arabic is generated.

## Paper

Please cite this paper for reference:

```bibtex
@inproceedings{yarmohammadi-etal-2021-everything,
    title = "Everything Is All It Takes: A Multipronged Strategy for Zero-Shot Cross-Lingual Information Extraction",
    author = "Yarmohammadi, Mahsa  and
      Wu, Shijie  and
      Marone, Marc  and
      Xu, Haoran  and
      Ebner, Seth  and
      Qin, Guanghui  and
      Chen, Yunmo and
      Guo, Jialiang and
      Harman, Craig  and
      Murray, Kenton and
      White, Aaron Steven  and
      Dredze, Mark and
      Van Durme, Benjamin",
    booktitle = "Proceedings of the 2021 Conference on Empirical Methods in Natural Language Processing",
    year = "2021",
    
}
```
