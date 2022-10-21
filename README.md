# Code for HIPE-2022 Shared Task Submission
*Codebase of the Paper [Exploring Transformers for Historical Named Entity Recognition](http://ceur-ws.org/Vol-3180/paper-86.pdf)*

## Contents

**Models**: The code we used to train the different models for the different datasets.

**Ensembling**: The code we used to ensemble and clean the model's predictions.

**Post-Submission Experiments**: Code of the different Post submission experiments

**Error Analysis**: Scripts we used for error analysis

## Abstract

<p align='justify'> This paper explores the performance of out-of-the-box transformers language models for historical Named Entity Recognition (NER). Within the HIPE2022 (Identifying Historical People, Places, and other Entities) shared task, we participated in the NER-COARSE task of the Multilingual Newspaper Challenge (MNC). Three main approaches are experimented with: ensembling techniques on multiple fine-tuned models, using multilingual pretrained models, and relabeling the entity tags from the IOB-segmentation to a simplified version. By ensembling predictions from different system outputs, we outperformed the baseline model in the majority of cases. Moreover, through post-submission experiments, we found that using multilingual models did not yield better results compared to monolingual models. Furthermore, the relabeling experiment on the Newseye French dataset showed that merging entity labels and inferring the IOB segmentation in postprocessing increases precision but lowers recall. Last but not least, soft-label ensembling experiments on the same dataset enhanced precision, recall and thus F1-scores compared to hard-label ensembling by at least one percentage point. </p>