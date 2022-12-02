# pytail
PyTAIL - Interactive and Incremental Learning of NLP Models with Human in the Loop for Online Data


[![Dataset DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.7236430.svg)](https://doi.org/10.5281/zenodo.7236430) [![arXiv](https://img.shields.io/badge/arXiv-2210.08129-b31b1b.svg)](https://arxiv.org/abs/2211.13786) [![Poster](https://img.shields.io/badge/Poster-Neurips2022-b31b1b.svg)](./PyTAIL-Neurips-Poster.pdf) [![Slides](https://img.shields.io/badge/Slides-Neurips2022-b31b1b.svg)](./PyTAIL-Neurips-Slides.pdf) [![YouTube Video Views](https://img.shields.io/youtube/views/AwDu64gN8t4?style=social)](https://www.youtube.com/watch?v=AwDu64gN8t4)



* ArXiv: https://arxiv.org/abs/2211.13786 
* Dataset: https://doi.org/10.5281/zenodo.7236430 
* Code: https://github.com/socialmediaie/pytail 
* Video: https://www.youtube.com/watch?v=AwDu64gN8t4 
* Slides: [PyTAIL-Neurips-Slides.pdf](./PyTAIL-Neurips-Slides.pdf)
* Slides: [PyTAIL-Neurips-Poster.pdf](./PyTAIL-Neurips-Poster.pdf)

## Abstract

> Online data streams make training machine learning models hard because of distribution shift and new patterns emerging over time. For natural language processing (NLP) tasks that utilize a collection of features based on lexicons and rules, it is important to adapt these features to the changing data. To address this challenge we introduce PyTAIL, a python library, which allows a human in the loop approach to actively train NLP models. PyTAIL enhances generic active learning, which only suggests new instances to label by also suggesting new features like rules and lexicons to label. Furthermore, PyTAIL is flexible enough for users to accept, reject, or update rules and lexicons as the model is being trained. Finally, we simulate the performance of PyTAIL on existing social media benchmark datasets for text classification. We compare various active learning strategies on these benchmarks. The model closes the gap with as few as 10% of the training data. Finally, we also highlight the importance of tracking evaluation metric on remaining data (which is not yet merged with active learning) alongside the test dataset. This highlights the effectiveness of the model in accurately annotating the remaining dataset, which is especially suitable for batch processing of large unlabeled corpora.