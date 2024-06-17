# DeRa: Decoding-time Realignment of Language Models

DeRa is a simple method to explore and evaluate different regularization strengths in RLHF-aligned models without the need of retraining. 

Two main use cases of DeRa are:
- tailor language model alignment strength to specific user preferences or downstream applications
- identify promising regularization strengths to retrain a model, without expensive hyperparameter sweeps


In the colab notebook below, you'll find a reference implementation of DeRa with HuggingFace transformers. Specifically, we demonstrate how to apply DeRa to the [Zephyr-7b model](https://huggingface.co/HuggingFaceH4/zephyr-7b-beta), showing its ability adjust the alignment levels of language models at decoding time.


[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1s9hY3x3WtpCZMKSTCzm1xif0B2FTNnOt?usp=sharing)

Please find more details in our [paper](https://arxiv.org/abs/2402.02992), accepted to ICML 2024:

```bibtex
@inproceedings{Liu2024decoding,
 title = {Decoding-time Realignment of Language Models},
 author={Liu, Tianlin and Guo, Shangmin and Bianco, Leonardo and Calandriello, Daniele and Berthet, Quentin and Llinares, Felipe and Hoffmann, Jessica and Dixon, Lucas and Valko, Michal and Blondel, Mathieu},
 booktitle = {Proceedings of the International Conference on Machine Learning},
 year = {2024}
}
```

