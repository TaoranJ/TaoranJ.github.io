---
title: "Patent Citation Dynamics Modeling via Multi-Attention Recurrent Networks"
collection: publications
author: "Taoran Ji, Zhiqian Chen, Nathan Self, Kaiqun Fu, Chang-Tien Lu and Naren Ramakrishnan"
permalink: /publication/2019_ijcai
date: 2019-08-28
venue: 'International Joint Conference on Artificial Intelligence (IJCAI)'
paperurl: 'http://taoranj.github.io/files/ijcai2019.pdf'
---

Abstract-Modeling and forecasting forward citations to a patent is a central task for the discovery of emerging technologies and for measuring the pulse of inventive progress. Conventional methods for forecasting these forward citations cast the problem as analysis of temporal point processes which rely on the conditional intensity of previously received citations. Recent approaches model the conditional intensity as a chain of recurrent neural networks to capture memory dependency in hopes of reducing the restrictions of the parametric form of the intensity function. For the problem of patent citations, we observe that forecasting a patent’s chain of citations benefits from not only the patent's history itself but also from the historical citations of assignees and inventors associated with that patent. In this paper, we propose a sequence-to-sequence model which employs an attention-of-attention mechanism to capture the dependencies of these multiple time sequences. Furthermore, the proposed model is able to forecast both the timestamp and the category of a patent’s next citation. Extensive experiments on a large patent citation dataset collected from USPTO demonstrate that the proposed model outperforms state-of-the-art models at forward citation forecasting.


[Download paper here](http://taoranj.github.io/files/ijcai2019.pdf)


Recommended citation:
```json
@inproceedings{ji2019patent,
    title={Feature Driven Learning Framework for Cybersecurity Event Detection},
    author={Ji, Taoran and Chen, Zhiqian and Nathan, Self and Fu, Kaiqun and Lu, Chang-Tien and Ramakrishnan, Naren},
    booktitle={IJCAI},
    year={2019},
}
```
