# Paper-2-Data (April 2021)
This repository contains the presentation, code and associated files used in the April 2021 Paper 2 Data AI presentation to the Jersey financial services community.

The presentation is in the root folder and the various Jupyter notebooks containing the Python code used to demonstrate various Natural Language Processing techniques on legal contracts is in the folder named 'Code'.

To install the various libraries to run the code, an environment can be created from the environment.yml file in the root directory. Use 'conda env create -f environment.yml' from the command line. The environment will be named 'p2d' and this can then be activated using 'conda activate p2d'. 

All code, libraries and software used in the demonstration are open source and free to use. These include, but not limited to:
Tesseract - https://github.com/tesseract-ocr/tesseract
Transformers (inc BERT, T5, DeBERTa and RoBERTa) - https://huggingface.co
spaCy - https://spacy.io
Doccano - https://github.com/doccano/doccano

The PDF contracts used in the demonstration are primarily taken from the Contract Understanding Atticus Dataset (CUAD) with attribution as follows: https://www.atticusprojectai.org
