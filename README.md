# zero-shot hate speech detection for text-embedded images

This repository is set to be made public soon. It contains the solution for the Multimodal Hate Speech Event Detection 2024 shared task at the 7th Workshop on Challenges and Applications of Automated Extraction of Socio-political Events from Text (CASE @ EACL 2024). Our approach leverages the LLaVA 1.5 vision-language model to perform zero-shot detection of hate speech in text-embedded images.

## Key Features

- Utilizes the LLaVA 1.5 vision-language model for zero-shot hate speech detection.
- Capable of detecting hate speech in images that contain embedded text.

## Implementation
The repository includes a Jupyter notebook (`notebooks/llava_hate_detection.ipynb`) that demonstrates the implementation of our approach. The notebook covers:

- Loading and preparation of the LLaVA 1.5 model
- Processing of text-embedded images
- Zero-shot inference for hate speech detection

## Citation

If you find our work useful, please consider citing our paper:

```bibtex
@inproceedings{yamagishi-2024-yyama,
    title = "{YY}ama@Multimodal Hate Speech Event Detection 2024: Simpler Prompts, Better Results - Enhancing Zero-shot Detection with a Large Multimodal Model",
    author = "Yamagishi, Yosuke",
    booktitle = "Proceedings of the 7th Workshop on Challenges and Applications of Automated Extraction of Socio-political Events from Text (CASE 2024)",
    month = mar,
    year = "2024",
    address = "St. Julians, Malta",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2024.case-1.7",
    pages = "60--66",
}
