# mcq-gen
Leveraging T5 and GloVe models for automated generation of Multiple Choice Questions (MCQs) including question generation (QG) and distractor generation.


## Running

Open `T5_QG_refined_implementation.ipynb` in Google Colab (CPU or GPU) and run the cells in order.
The notebook installs current `transformers`, downloads the `valhalla/t5-base-qa-qg-hl` model and
GloVe vectors (about 376 MB) automatically, and falls back to a built-in sample paragraph if the
optional Google Drive text files are missing.
