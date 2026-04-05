# RobustVisRAG: Causality-Aware Vision-Based Retrieval-Augmented Generation under Visual Degradations
Official repository for RobustVisRAG: Causality-Aware Vision-Based Retrieval-Augmented Generation under Visual Degradations

[Project Page](https://robustvisrag.github.io/) | [Paper](https://arxiv.org/abs/2602.22013) | [Dataset](https://huggingface.co/collections/robustvisrag/distortion-visrag) | [Code](https://github.com/robustvisrag/RobustVisRAG)

## Updates
- April 2026: ✨ DVisRAG dataset was released publicly. 
- February 2026: ✨ RobustVisRAG was accepted into CVPR 2026!

## RobustVisRAG
RobustVisRAG enhances Vision-based Retrieval-Augmented Generation (VisRAG) under visual degradations through causality-guided semantic–degradation disentanglement. By explicitly separating degradation and semantic factors inside the vision encoder, our framework suppresses degradation-induced bias while preserving task-relevant representations — without introducing additional inference cost.

<img width="1096" alt="DVisRAG overview" src="asset/RobustVisRAG.png">

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