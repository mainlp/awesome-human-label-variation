# awesome-human-label-variation
## The "Problem" of Human Label Variation: On Ground Truth in Data, Modeling and Evaluation

[![MIT License](https://img.shields.io/badge/license-MIT-green.svg)](https://opensource.org/licenses/MIT) [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome datasets with human label variation (un-aggregated labels) in Natural Language Processing and Computer Vision, including links to papers. The focus is on datasets that contain multiple annotations per instance, to enable learning with human label variation/disagreement. The starting point is Table 1 in the appendix of [our paper](). Feel free to contribute by creating a pull request as outlined in [contributing.md](contributing.md).

### :mortar_board: Citing 

Please cite our [paper (Plank, 2022 EMNLP)]() if you find this resource useful in your research:

```
@inproceedings{plank-2022-emnlp,
    title = "The ``Problem'' of Human Label Variation: On Ground Truth in Data, Modeling and Evaluation",
    author = "Plank, Barbara",
    booktitle = "Proceedings of the 2022 Conference on Empirical Methods in Natural Language Processing ",
    month = dec,
    year = "2022",
    address = "Abu Dhabi",
    publisher = "Association for Computational Linguistics",
}
```

### :bar_chart: Datasets

#### NLP datasets

| Reference | Name or Description | URL | 
|:----- |:----- |:----- |
| Passonneau et al., 2010 | Word sense disambiguation (WSD)  | https://anc.org/ | 
| Plank et al., 2014  | Part-of-Speech (POS) tagging, 500 tweets from Lowlands and Gimpel POS | https://bitbucket.org/lowlands/costsensitive-data/ or https://zenodo.org/record/5130737  |
| Derczynski et al., 2016 | Broad Named Entity Recognition (NER) Twitter dataset | https://github.com/GateNLP/broad_twitter_corpus | 
| Rodrigues et al., 2018 | NER dataset, re-annoted sample of CoNLL 2003 | http://fprodrigues.com//publications/deep-crowds/ | 
| Martinez Alonso et al., 2016 | Supersense tagging | https://github.com/coastalcph/semdax |
| Berzak et al., 2016 | Dependency Parsing, WSJ-23, 4 annotators | https://people.csail.mit.edu/berzak/agreement/ | 
| Peng et al., 2022 | GCDT, Mandarin Chinese discourse treebank, small subsection with double annotations | https://github.com/logan-siyao-peng/GCDT/tree/main/data | 
| Bryant and Ng, 2015   | Grammatical error correction | http://www.comp.nus.edu.sg/~nlp/sw/10gec_annotations.zip | 
| Poesio et al. 2019 & PD (Phrase Detectives dataset): Anaphora and Information Status Classification | https://github.com/dali-ambiguity/Phrase-Detectives-Corpus-2.1.4 |
 | Dumitrache et al. 2018 | Medical Relation Extraction (MRE) | https://github.com/CrowdTruth/Open-Domain-Relation-Extraction |
| Bassignana and Plank, 2022 & CrossRE, relation extraction, small doubly-annotated subset | https://github.com/mainlp/CrossRE |
| Dumitrache et al. 2018 | Frame Disambiguation | https://github.com/CrowdTruth/FrameDisambiguation | 
| Snow et al. 2008 | RTE (recognizing textual entailment; 800 hypothesis-premise pairs) collected by Dagan et al. 2005, re-annotated; includes further datasets on temporal ordering, WSD, word similarity and affective text  | https://sites.google.com/site/nlpannotations/ |
| Pavlick and Kwiatkowski 2019 | NLI (natural language inference) inherent disagreement dataset, approx. 500 RTE instances from Dagan et al. 2005 re-annotated by 50 annotators | https://github.com/epavlick/NLI-variation-data |
| Nie et al., 2020 | ChaosNLI, large NLI dataset re-annotated by 100 annotators | https://github.com/easonnie/ChaosNLI | 
| Demszky et al., 2020 | GoEmotions: reddit comments annotated for 27 emotion categories or neutral | https://github.com/google-research/google-research/tree/master/goemotions |

 ..
     
#### Computer Vision (CV) datasets

| Reference | Name or Description | URL | 
|:----- |:----- |:----- |    
| Rodrigues et al. 2018 | LabelMe: Image classification dataset with 8 categories, re-annotated   | http://fprodrigues.com//publications/deep-crowds/ |
| Peterson et al., 2019 | Cifar10H: Image classification with 10 categories, re-annotated | http://github.com/jcpeterson/cifar-10h | 
| Cheplygina et al. 2018 | Medical lesion classification challenge, 6 annotators each | https://figshare.com/s/5cbbce14647b66286544 |


