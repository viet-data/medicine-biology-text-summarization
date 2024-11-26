# Vietnamese Medicine and Biology Text Summarization

In this study, we collected a medicine and biolgy dataset from existing datasets called VMB. We experiment several baselines and compare them with our proposed methods (Prompt techniques: APP, POS prompts and sentence extracting methods: Kmeans, Herding algorithm)

All processing data and training notebooks are in folder src.

**Process data** code for training BERT is in prepare-dataset.ipynb

**Train APP** code for the training APP is in bartpho-app.ipynb

**Train baseline** code for training baselines are in notebooks that have file names respective to their names.

**Extracting methods** Kmeans and Herding are in KMeans.ipynb and Herding.ipynb . Since extracting important sentences belongs to preprocessing step. We use these algorithms to prepare data in advance.

As presented in the report, APP achieves the highest performance on the test dataset of VMB. The checkpoint of VMB is stored on huggingface. For demo section, please run all cells in notebook demo.ipynb to get gradio public link of the web application. Once you access the web, you can paste your document and get the summary by clicking on the submit button.

**HuggingFace**: https://huggingface.co/OpenHust
## Framework versions

Transformers 4.18.0

Pytorch 1.9.0+cu111

Datasets 2.13.0

Tokenizers 0.12.1

## Contributors

This work was done as part of the course `Natural Language Processing Course - 	IT4772E` at Hanoi University of Science and Technology. Team members include:

- [Đỗ Tuấn Anh](https://github.com/AnhDt-dsai)
- [Trần Xuân Huy](https://github.com/TranXuanHuy267)
- [Phạm Vũ Huyền Trang](https://github.com/PhamVuHuyenTrang)
- [Đào Trọng Việt](https://github.com/viet-data)

