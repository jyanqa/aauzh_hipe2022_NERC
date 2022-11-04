## Paper
*Codebase of the HIPE-2022 Shared Task Paper [Exploring Transformers for Historical Named Entity Recognition](http://ceur-ws.org/Vol-3180/paper-86.pdf)* by Anja Ryser*, Quynh Anh Nguyen*, Niclas Bodenmann*, Shih-Yun Chen* at [CLEF 2022](https://clef2022.clef-initiative.eu).

To cite the paper, use the BibTex below:
```
@inproceedings{RyserEtAl:CLEF2022,
title = {Exploring Transformers for Multilingual Historical Named Entity Recognition},
author = {Anja Ryser* and Quynh Anh Nguyen* and Niclas Bodenmann* and Shih-Yun Chen*},
booktitle = "Proceedings of the Working Notes of CLEF 2022 - Conference and Labs of the Evaluation Forum",
    month = Sep,
    year = "2022",
    address = "Bologna, Italy",
    publisher = "CEUR-WS",
pages = {1090--1108},
url = {http://ceur-ws.org/Vol-3180/#paper-86},
crossref = {CLEF2022},
}
```
## Structure

**Models**: The code we used to train the different models for the different datasets.

**Ensembling**: The code we used to ensemble and clean the model's predictions.

**Post-Submission Experiments**: Code of the different Post submission experiments

**Error Analysis**: Scripts we used for error analysis

## Abstract

<p align='justify'> This paper explores the performance of out-of-the-box transformers language models for historical Named Entity Recognition (NER). Within the HIPE2022 (Identifying Historical People, Places, and other Entities) shared task, we participated in the NER-COARSE task of the Multilingual Newspaper Challenge (MNC). Three main approaches are experimented with: ensembling techniques on multiple fine-tuned models, using multilingual pretrained models, and relabeling the entity tags from the IOB-segmentation to a simplified version. By ensembling predictions from different system outputs, we outperformed the baseline model in the majority of cases. Moreover, through post-submission experiments, we found that using multilingual models did not yield better results compared to monolingual models. Furthermore, the relabeling experiment on the Newseye French dataset showed that merging entity labels and inferring the IOB segmentation in postprocessing increases precision but lowers recall. Last but not least, soft-label ensembling experiments on the same dataset enhanced precision, recall and thus F1-scores compared to hard-label ensembling by at least one percentage point. </p>
