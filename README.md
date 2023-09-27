# awesome-human-label-variation
## The "Problem" of Human Label Variation: On Ground Truth in Data, Modeling and Evaluation

[![MIT License](https://img.shields.io/badge/license-MIT-green.svg)](https://opensource.org/licenses/MIT) [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome datasets with human label variation (un-aggregated labels) in Natural Language Processing and Computer Vision, including links to related initiatives and key references. The key focus of the table provided below is to collect datasets that contain multiple annotations per instance, to enable learning with human label variation/disagreement. The starting point of Table 1 was the table in the appendix of [our paper](https://arxiv.org/abs/2211.02570). 

### :jigsaw: Something not listed? 

If you know of resources or papers or links that are not yet listed, please help grow this resource. You can contribute by creating a pull request as outlined in [contributing.md](contributing.md).

### :mortar_board: Citing 

Please cite our paper [Plank, 2022 EMNLP](https://arxiv.org/abs/2211.02570) if you find this repository useful:

```
@inproceedings{plank-2022-emnlp,
    title = "The ``Problem'' of Human Label Variation: On Ground Truth in Data, Modeling and Evaluation",
    author = "Plank, Barbara",
    booktitle = "Proceedings of the 2022 Conference on Empirical Methods in Natural Language Processing ",
    month = December,
    year = "2022",
    address = "Abu Dhabi",
    publisher = "Association for Computational Linguistics",
}
```

## Human Label Variation - Related Initiatives and further reading 

### Initiatives, Evaluation Campaigns and Workshops

Icons refer to the following:

* :thumbsup: :thumbsdown: [SemEval 2023 Shared Task 11 on Learning with Disagreement (Le-Wi-Di)](https://le-wi-di.github.io/): 2nd Shared task on subjective NLP tasks :high_brightness: on-going! 
* :shrug: [SemEval 2021 Shared Task 11 on Learning with Disagreement](https://sites.google.com/view/semeval2021-task12/home): 1st Shared task, which included core NLP and computer vision tasks
* :pie: [Perspectivist Data Manifesto (PDAI)](https://pdai.info/): Website that contains key references and a first list of non-aggregated datasets 
* :speaking_head: NLPerspectives 2022, [Workshop on Perspectivist Approaches to NLP](https://nlperspectives.di.unito.it/) held at LREC 2022; 2nd edition [2023 Workshop on Perspectivist Approaches to NLP co-located with ECAI 2023](https://nlperspectives.di.unito.it/w/2nd-workshop-on-perspectivist-approaches-to-nlp/)

### Survey and Key Selected References

* :mag: Uma et al., 2021: [Learning from Disagreement: A Survey](https://www.jair.org/index.php/jair/article/view/12752). Broad overview across NLP and computer vision tasks.
* Plank et al., 2014. [Learning part-of-speech taggers with inter-annotator agreement loss](https://aclanthology.org/E14-1078/). Proposed to leverage small samples of un-aggregated data to improve performance on morphosyntactic NLP tasks. Inspired follow-up work such as [Linguistically debatable or just plain wrong?](https://aclanthology.org/P14-2083/) ACL 2014. Analysis of systematicity of annotator agreement on objective linguistic annotation tasks (POS tagging). 
* Aroyo & Welty, 2015. [Truth is a lie: Crowd truth and the seven myths of human annotation](https://ojs.aaai.org/index.php/aimagazine/article/view/2564). AI Magazine. Proposes the crowd truth framework, which included a large body of work on medical relation extraction, frame disambiguation and other semantic processing tasks.
* Pavlick & Kwiatkowski, 2019. [Inherent Disagreements in Human Textual Inferences](http://aclanthology.lst.uni-saarland.de/Q19-1043.pdf). TACL. Seminal work that illustrates plausible disagreement in entailment datasets. Inspired follow-up work such as dataset re-annotation studies like [ChaosNLI](https://github.com/easonnie/ChaosNLI) by Nie et al., 2020 and follow-up work such as embracing the collective human opinion for NLI.
* Alm, 2011. [Subjective Natural Language Problems: Motivations, Applications, Characterizations, and Implications](https://aclanthology.org/P11-2019/). Early paper discussing annotator agreement on subjective linguistic annotation tasks.
* Basile et al., 2021. [Toward a Perspectivist Turn in Ground Truthing for Predictive Computing](https://arxiv.org/abs/2109.04270). Conference of the Italian Chapter of the Association for Intelligent Systems (ItAIS 2021). Putting forward data perspectivism to embrace human perspectives. Inspired a lot of follow-up work on subjective tasks (see e.g. the Le-Wi-Di 2023 shared task)
* Gordon et al., 2021. [The Disagreement Deconvolution: Bringing Machine Learning Performance Metrics In Line With Reality](https://dl.acm.org/doi/abs/10.1145/3411764.3445423). Seminal paper in the Human-Computer-Interaction (CHI) conference. 
* :eyeglasses: Davani et al., 2022. [Dealing with Disagreements: Looking Beyond the Majority Vote in Subjective Annotations](https://aclanthology.org/2022.tacl-1.6/) TACL. Examines, a.o., whether the uncertainty in predictions is correlated with whether the
multi-task model was able to correctly predict the majority label.
* Jiang & de Marneffe, 2022. [Investigating Reasons for Disagreement in Natural Language Inference](https://github.com/njjiang/NLI_disagreement_taxonomy). TACL. Provides a novel linguistic taxonomy to characterize disagreements in natural language inference datasets.
* :small_orange_diamond: Wan et al., 2023. [Everyone’s Voice Matters: Quantifying Annotation Disagreement Using Demographic Information](https://github.com/minnesotanlp/Quantifying-Annotation-Disagreement). AAAI. Predict human label variation on five subjective tasks, examine demographic information.  

This list above are selected key references. Please see our EMNLP 2022 theme paper (Plank, 2022) for further references related to annotator culture/backgrounds, different terms proposed in the literature and more. If you know of relevant related work (not datasets), please leave an Issue. For more datasets, please see contributing.md

### :bar_chart: Datasets

#### NLP datasets

| Reference | Name or Description | URL | Used in/Listed on |
|:----- |:----- |:----- |:----- |
| Passonneau et al., 2010 | Word sense disambiguation (WSD)  | https://anc.org/ | |
| Plank et al., 2014  | Part-of-Speech (POS) tagging, 500 tweets from Lowlands and Gimpel POS | https://bitbucket.org/lowlands/costsensitive-data/ or https://zenodo.org/record/5130737  | :mag:, :shrug:  |
| Derczynski et al., 2016 | Broad Named Entity Recognition (NER) Twitter dataset | https://github.com/GateNLP/broad_twitter_corpus | :pie: | 
| Rodrigues et al., 2018 | NER dataset, re-annoted sample of CoNLL 2003 | http://fprodrigues.com//publications/deep-crowds/ | |
| Martinez Alonso et al., 2016 | Supersense tagging | https://github.com/coastalcph/semdax | |
| Berzak et al., 2016 | Dependency Parsing, WSJ-23, 4 annotators | https://people.csail.mit.edu/berzak/agreement/ | |
| Peng et al., 2022 | GCDT, Mandarin Chinese discourse treebank, small subsection with double annotations | https://github.com/logan-siyao-peng/GCDT/tree/main/data | |
| Bryant and Ng, 2015   | Grammatical error correction | http://www.comp.nus.edu.sg/~nlp/sw/10gec_annotations.zip | |
| Poesio et al. 2019 | PD (Phrase Detectives dataset): Anaphora and Information Status Classification | https://github.com/dali-ambiguity/Phrase-Detectives-Corpus-2.1.4 | :mag:, :shrug:  |
| Dumitrache et al. 2018 | Medical Relation Extraction (MRE) | https://github.com/CrowdTruth/Open-Domain-Relation-Extraction | :mag: |
| Bassignana and Plank, 2022 | CrossRE, relation extraction, small doubly-annotated subset | https://github.com/mainlp/CrossRE |
| Dumitrache et al. 2018 | Frame Disambiguation | https://github.com/CrowdTruth/FrameDisambiguation | | 
| Snow et al. 2008 | RTE (recognizing textual entailment; 800 hypothesis-premise pairs) collected by Dagan et al. 2005, re-annotated; includes further datasets on temporal ordering, WSD, word similarity and affective text  | https://sites.google.com/site/nlpannotations/ | :mag: |
| Pavlick and Kwiatkowski 2019 | NLI (natural language inference) inherent disagreement dataset, approx. 500 RTE instances from Dagan et al. 2005 re-annotated by 50 annotators | https://github.com/epavlick/NLI-variation-data | |
| Nie et al., 2020 | ChaosNLI, large NLI dataset re-annotated by 100 annotators | https://github.com/easonnie/ChaosNLI | |
| Demszky et al., 2020 | GoEmotions: reddit comments annotated for 27 emotion categories or neutral | https://github.com/google-research/google-research/tree/master/goemotions | :eyeglasses: |
| Ferracane et al., 2021 |  Subjective discourse: conversation acts and intents | https://github.com/elisaF/subjective_discourse | |
| Damgaard et al., 2021 |  Understanding indirect answers to polar questions |  https://github.com/friendsQIA/Friends_QIA | |
| de Marneffe et al., 2019 | CommitmentBank:  8 annotations indicating the extent to which the speakers are committed to the truth of the embedded clause | https://github.com/mcdm/CommitmentBank | |
| Kennedy et al., 2020 | Hate speech detection | https://huggingface.co/datasets/ucberkeley-dlab/measuring-hate-speech | :pie:, :eyeglasses: |
| Dinu et al., 2021 | Pejorative words dataset | https://nlp.unibuc.ro/resources or http://pdai.info/ | :pie: |
| Leonardelli et al., 2021 | MultiDomain Agreement, Offensive language detection on Twitter, 5 offensive/non-offensive labels; also part of Le-Wi-Di SemEval23  | https://github.com/dhfbk/annotators-agreement-dataset/ | :thumbsup: :thumbsdown:, :pie: |
| Cercas Curry et al., 2021 |  ConvAbuse, abusive language towards three conversational AI systems; also part of Le-Wi-Di SemEval23  | https://github.com/amandacurry/convabuse | :thumbsup: :thumbsdown:, :pie: | 
| Liu et al., 2019 |  Work and Well-being Job-related Tweets, 5 annotators | https://github.com/Homan-Lab/pldl_data | :pie: |
| Simpson et al., 2019 | Humour: pairwise funniness judgements | https://zenodo.org/record/5130737 | :shrug:  |
| Akhtar et al., 2019 | HS-brexit; Abusive Language on Brexit and annotated for hate speech (HS), aggressiveness and offensiveness, 6 annotators, extended and new parts part of Le-Wi-Di SemEval23  | https://le-wi-di.github.io/ | :thumbsup: :thumbsdown: |
| Almanea and Poesio 2022 | ArMIS; New Le-Wi-Di SemEval23 dataset on Arabic tweets annotated for misogyny detection | https://le-wi-di.github.io/ | :thumbsup: :thumbsdown: |
| Sap et al., 2022 |  Annotators with Attitudes: How Annotator Beliefs And Identities Bias Toxic Language Detection | http://maartensap.com/racial-bias-hatespeech/ | |
| Kumar et al., 2021 |  Designing Toxic Content Classification for a Diversity of Perspectives |  https://data.esrg.stanford.edu/study/toxicity-perspectives (contact author for password) | |
| [Nguyen et al., 2017](https://aclanthology.org/P17-1028/) | Biomedical Infomation Retrieval, each doc is annotated by roughly 5 Amazon Mechanical Turk workers |  https://github.com/yinfeiy/PICO-data | |
| [Zhang et al., 2022](https://aclanthology.org/2022.acl-long.200/) | Chinese Sentiment Words Identification, each sentence is annotated by 3 ~ 5 workers |  https://github.com/izhx/crowd-OEI | |
| [Grubenmann et al., 2018](https://aclanthology.org/L18-1372/) | Sentiment annotations for Swiss German sentences | https://github.com/spinningbytes/SB-CH | |
| [Ji et al., 2022](https://arxiv.org/pdf/2211.16492.pdf)| KiloGram tangram dataset, 10 annotations per tangram (EMNLP 2022 best long paper award)| https://github.com/lil-lab/kilogram | |
| [Kennedy et al., 2020](https://psyarxiv.com/hqjxn/)|  The gab hate corpus: A collection of 27k posts annotated for hate speech. [#Labels: 2, #Unique Raters: 18, Atleast 3 annotations per instance]| https://osf.io/edua3/ | |
| [Haber et al., 2023](https://aclanthology.org/2023.acl-long.711.pdf) |  SOA: Singapore online attacks, multilingual toxic data annotated with 3 annotators. | [https://github.com/rewire-online/singapore-online-attacks/tree/main](https://github.com/rewire-online/singapore-online-attacks/tree/main) | |
| [Liu et al., 2022](https://aclanthology.org/2022.aacl-main.9/) | Word Associations with 19K explanations and 725 relation labels from 5 annotators | [https://github.com/ChunhuaLiu596/WAX/](https://github.com/ChunhuaLiu596/WAX/) | |
| [Frermann et al., 2023](https://aclanthology.org/2023.acl-long.486/) | Multi-label frame annotations of 428 news articles, each labeled by 2-3 annotators | [https://github.com/phenixace/narrative-framing/tree/main/data](https://github.com/phenixace/narrative-framing/tree/main/data) | |
| [Sap et al., 2020](https://aclanthology.org/2020.acl-main.486.pdf) | Social Bias Frames: Reasoning about Social and Power Implications of Language (3 annotators) | https://maartensap.com/social-bias-frames/ | :small_orange_diamond: |
| [Fleisig et al., 2023](https://aclanthology.org/2023.acl-long.343.pdf) |  FairPrism: Evaluating Fairness-Related Harms in Generated Text (3 annotators) | https://github.com/microsoft/FairPrism | |
| [Forbes et al., 2020](https://arxiv.org/pdf/2011.00620.pdf) | Social Chemistry 101: Learning to Reason about Social and Moral Norms (up to 5 crowd annotations) | https://github.com/mbforbes/social-chemistry-101 | :small_orange_diamond: | 
| [Lourie et al., 2021](https://arxiv.org/abs/2008.09094) |  Scruples-dilemmas: A Corpus of Community Ethical Judgments (with 5 crowd annotations per instance) | https://github.com/allenai/scruples | :small_orange_diamond: | 
| [Potts et al., 2021](https://arxiv.org/abs/2012.15349) | Dyna-Sentiment (5 crowd annotations) | https://github.com/cgpotts/dynasent | :small_orange_diamond: |
| [Danescu-Niculescu-Mizil et al. 2013](https://arxiv.org/abs/1306.6078) | Wikipedia Politeness (with up to 5 crowd annotations) | https://convokit.cornell.edu/documentation/wiki_politeness.html or https://github.com/minnesotanlp/Quantifying-Annotation-Disagreement | :small_orange_diamond: |


     
####  Computer Vision (CV) datasets

| Reference | Name or Description | URL | 
|:----- |:----- |:----- |    
| Rodrigues et al. 2018 | LabelMe: Image classification dataset with 8 categories, re-annotated   | http://fprodrigues.com//publications/deep-crowds/ | :mag:, :shrug:  | 
| Peterson et al., 2019 | Cifar10H: Image classification with 10 categories, re-annotated | http://github.com/jcpeterson/cifar-10h | :mag:, :shrug: |
| Cheplygina et al. 2018 | Medical lesion classification challenge, 6 annotators each | https://figshare.com/s/5cbbce14647b66286544 | |
| Wei, Zhu et al., 2022 | CIFAR-100N | http://noisylabels.com/ | | 

