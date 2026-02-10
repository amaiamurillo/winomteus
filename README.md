# WinoMTeus
[![Hugging Face Dataset](https://img.shields.io/badge/🤗%20Hugging%20Face-Dataset-yellow)](https://huggingface.co/datasets/amaiaimurillo/winomteus)


WinoMTeus is the Basque version of [WinoMT](https://github.com/gabrielStanovsky/mt_gender) that consists of 1,827 sentences. The aim of this adaptation is to evaluate how gender is assigned when translating gender-neutral occupations in Basque into gendered languages such as Spanish or French.


## Uses
This dataset can be used to analyse whether translation from Basque into a gendered language reinforces gender stereotypes or reflects the actual labour distribution in the Basque Country.
The evaluation procedure involves:
1. Automatically translating the dataset into a gendered language.
2. Extracting the mentions of occupations in the translations and labelling their gender.
3. Comparing the distribution of translated occupations to real-world labour statistics.

## Citation
If you use WinoMTeus in your work, please make sure to also cite the original WinoMT paper:

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

## Dataset Card Contact
amaia.murillo@ehu.eus
