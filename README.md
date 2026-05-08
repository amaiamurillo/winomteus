# WinoMTeus
[![Hugging Face Dataset](https://img.shields.io/badge/🤗%20Hugging%20Face-Dataset-yellow)](https://huggingface.co/datasets/HiTZ/winomteus)


WinoMTeus is the Basque version of [WinoMT](https://github.com/gabrielStanovsky/mt_gender) that consists of 1,827 sentences. The aim of this adaptation is to evaluate how gender is assigned when translating gender-neutral occupations in Basque into gendered languages such as Spanish or French.


## Uses
This dataset can be used to analyse whether translation from Basque into a gendered language reinforces gender stereotypes or reflects the actual labour distribution in the Basque Country.
The evaluation procedure involves:
1. Automatically translating the dataset into a gendered language.
2. Extracting the mentions of occupations in the translations and labelling their gender.
3. Comparing the distribution of translated occupations to real-world labour statistics.

## Citation
If you use **WinoMTeus** in your work, please cite both the original **WinoMT** paper and our paper introducing the Basque benchmark:

```bibtex
@misc{stanovsky2019evaluatinggenderbiasmachine,
      title={Evaluating Gender Bias in Machine Translation}, 
      author={Gabriel Stanovsky and Noah A. Smith and Luke Zettlemoyer},
      year={2019},
      eprint={1906.00591},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/1906.00591}, 
}
```

```bibtex
@inproceedings{murillo-etal-2026-gender,
  title = {Gender Bias in MT for a Genderless Language: New Benchmarks for Basque},
  author = {Murillo, Amaia and Perez-de-Viñaspre, Olatz and Perez, Naiara},
  booktitle = {Proceedings of the Fifteenth Language Resources and Evaluation Conference (LREC 2026)},
  month = {May},
  year = {2026},
  pages = {8971--8984},
  address = {Palma, Mallorca, Spain},
  publisher = {European Language Resources Association (ELRA)},
  doi = {10.63317/352cdsej8fcp},
  abstract = {Large language models (LLMs) and machine translation (MT) systems are increasingly used in our daily lives, but their outputs can reproduce gender bias present in the training data. Most resources for evaluating such biases are designed for English and reflect its sociocultural context, which limits their applicability to other languages. This work addresses this gap by introducing two new datasets to evaluate gender bias in translations involving Basque, a low-resource and genderless language. WinoMTeus adapts the WinoMT benchmark to examine how gender-neutral Basque occupations are translated into gendered languages such as Spanish and French. FLORES+Gender, in turn, extends the FLORES+ benchmark to assess whether translation quality varies when translating from gendered languages (Spanish and English) into Basque depending on the gender of the referent. We evaluate several general-purpose LLMs and open and proprietary MT systems. The results reveal a systematic preference for masculine forms and, in some models, a slightly higher quality for masculine referents. Overall, these findings show that gender bias is still deeply rooted in these models, and highlight the need to develop evaluation methods that consider both linguistic features and cultural context.}
}
```

## Dataset Card Contact
amaia.murillo@ehu.eus
