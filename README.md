# CoTERM
## A Consistency-Oriented Term  Metric for MT System Evaluation

Proper treatment of terms is an important and critical aspect in machine translation. It is therefore necessary to use appropriate metrics to evaluate MT system outputs from terminology perspective. However, despite the great improvements witnessed in the recent NMT and LLM models, MT system evaluation metrics that shed light on specific aspects of term translations are yet to be fully explored. 

In this paper, we propose CoTERM, a new metric for automatic evaluation of term translations based on the Herfindahl-Hirshman Index (HHI).
CoTERM  measures target term closeness to one or more reference translations, taking into account the fundamental criteria for translating terms, i.e. (i) accuracy; (ii) consistency at document or corpus levels; and (iii) appropriateness to the domain conventions with regard to term variations. 
The proposed metric correlates strongly with human raters, and empirical evaluations of a wide range of NMTs and LLMs show that the best MT systems in standard metrics are not necessarily the best at treating terms. CoTERM is thus shown to be highly useful for diagnosing MT systems' term translation performance and conveniently seen  as complementary to generic measures for MT system evaluations.

The **paper** can be found [here](coming soon)

The **poster** can be found [here](./Poster_LREC_2026.pdf)

When citing **CoTERM** in academic papers and theses, please use the following BibTeX entry:
```
@InProceedings{coterm,
  author = {Amir Hazem and kyo Kageura},
  title = "{CoTERM: A Consistency-Oriented Term  Metric for MT System Evaluation}",
  booktitle = {Proceedings of The Fifteenth International Conference on Language Resources and Evaluation (LREC 2026)},
  year = {2026},
  month = {May 13-15},
  address = {Palma, Mallorca (Spain).}
  }
```

## Requirements
### Sentence-level measures
- BLEU, chrF (sacrebleu): [source](https://github.com/mjpost/sacrebleu), [paper](https://aclanthology.org/W18-6319.pdf)

- BertScore: [source](), [paper]()

- COMET: [source](https://huggingface.co/Unbabel/wmt22-comet-da), [paper]()

### Consistency measures:

- EM, WO2: [source](https://github.com/mahfuzibnalam/terminology_evaluation), [paper](https://arxiv.org/pdf/2106.11891)
- F1, TC: [source](https://github.com/ufal/wmt22-term-based-metric), [paper1](https://aclanthology.org/2022.wmt-1.41.pdf), [paper2](https://aclanthology.org/2023.wmt-1.54.pdf)

## CoTERM




