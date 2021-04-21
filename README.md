
# Paper-2-Data (April 2021)

This repository contains the presentation, code and associated files used in the April 2021 Paper 2 Data AI presentation to the Jersey financial services community.

The PDF version of the presentation is in the root folder and the various Jupyter notebooks containing the Python code used to demonstrate various Natural Language Processing techniques on legal contracts are in the folder named 'Code'.

To install the various libraries to run the code, an environment can be created from the environment.yml file in the root directory. Use 'conda env create -f environment.yml' from the command line. The environment will be named 'p2d' and this can then be activated using 'conda activate p2d'.

All code, libraries and software used in the demonstration are open source and free to use. These include, but not limited to:
[Tesseract](https://github.com/tesseract-ocr/tesseract)
[Transformers](https://huggingface.co) (inc BERT, T5, DeBERTa and RoBERTa), [spaCy](https://spacy.io) and [Doccano](https://github.com/doccano/doccano).

Note that the demo notebook no.2 '2 DEMO_BERT legal predict' requires that the BERT-Large model be downloaded and available on the local machine.

Also, notebook no.5 '5 F5-P2D-NER-CUAD-v1-Inference' uses a fine-tuned model. This can be recreated using notebook no.4 '4 F3-P2D-NER-CUAD-v1-Fine-Tune-Transformer'. Unfortunately given the size of these models, they can not be pushed and made available on GitHub.

The PDF contracts used in the demonstration are primarily taken from the [Contract Understanding Atticus Dataset (CUAD) with attribution](https://www.atticusprojectai.org).

The authors of this repo make all original code, document annotations and data available under the GNU General Public License v3.0.
