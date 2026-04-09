# RobustVisRAG: Causality-Aware Vision-Based Retrieval-Augmented Generation under Visual Degradations
Official repository for RobustVisRAG: Causality-Aware Vision-Based Retrieval-Augmented Generation under Visual Degradations

[Project Page](https://robustvisrag.github.io/) | [Paper](https://arxiv.org/abs/2602.22013) | [Dataset](https://huggingface.co/collections/robustvisrag/distortion-visrag) | [Code](https://github.com/robustvisrag/RobustVisRAG)

## Updates
- April 2026: ✨ DVisRAG dataset and weights was released publicly. 
- February 2026: ✨ RobustVisRAG was accepted into CVPR 2026!

## RobustVisRAG
RobustVisRAG enhances Vision-based Retrieval-Augmented Generation (VisRAG) under visual degradations through causality-guided semantic–degradation disentanglement. By explicitly separating degradation and semantic factors inside the vision encoder, our framework suppresses degradation-induced bias while preserving task-relevant representations — without introducing additional inference cost.

<img width="1096" alt="DVisRAG overview" src="asset/RobustVisRAG.png">

## Inference
Please follow the [VisRAG](https://github.com/openbmb/visrag) pipeline for the inference process.
* Replace the default model with our fine-tuned model [RobustVisRAG](https://huggingface.co/robustvisrag/RobustRAG/tree/main).
* Additionally, make sure to follow the dataset configuration (dataset) when preparing and running the data. 
* Dataset can be found [here](https://github.com/robustvisrag/RobustVisRAG/tree/main/dataset).

## Acknowledgements 
This work builds upon the following open-source projects: 
- VisRAG: Vision-based Retrieval-augmented Generation on Multi-modality Documents \[[GitHub](https://github.com/openbmb/visrag), [Paper](https://arxiv.org/abs/2410.10594)\], 
- RVL-CDIP: Evaluation of Deep Convolutional Nets for Document Image Classification and Retrieval \[[Data](https://huggingface.co/datasets/aharley/rvl_cdip), [Paper](https://arxiv.org/abs/1502.07058)\] 
- UniRestore: Unified Perceptual and Task-Oriented Image Restoration Model Using Diffusion Prior \[[Synthetic Function](https://github.com/unirestore/UniRestore/tree/main/src/data/corruption), [Paper](https://arxiv.org/abs/2501.13134)\] 

We sincerely thank the authors for their open-source contributions.

## Reference
If you find this work useful, please consider citing us!
```
@misc{chen2026robustvisragcausalityawarevisionbasedretrievalaugmented,
      title={RobustVisRAG: Causality-Aware Vision-Based Retrieval-Augmented Generation under Visual Degradations}, 
      author={I-Hsiang Chen and Yu-Wei Liu and Tse-Yu Wu and Yu-Chien Chiang and Jen-Chien Yang and Wei-Ting Chen},
      year={2026},
      eprint={2602.22013},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2602.22013}, 
}
```