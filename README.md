# Vietnamese Medicine and Biology Text Summarization

In this study, we collected a medicine and biolgy dataset from existing datasets called VMB. We experiment several baselines and compare them with our proposed methods (Prompt techniques: APP, POS prompts and sentence extracting methods: Kmeans, Herding algorithm)

All processing data and training notebooks are in folder src.

As presented in the report, APP achieves the highest performance on the test dataset of VMB. The checkpoint of VMB is stored on huggingface. For demo section, please run all cells in notebook demo.ipynb to get gradio public link of the web application. Once you access the web, you can paste your document and get the summary by clicking on the summit button.

**HuggingFace**: https://huggingface.co/OpenHust
## Framework versions

Transformers 4.18.0

Pytorch 1.9.0+cu111

Datasets 2.13.0

Tokenizers 0.12.1
