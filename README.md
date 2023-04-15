# :oil_drum: feul 
:notebook: Notebooks on ***Fe***derated ~~Learning~~ <ins>***U***n***l***earning</ins>

My Final Year Project ([COMP4801](https://www.cs.hku.hk/programmes/beng-compsc/course-descriptions#COMP4801)) of :mortar_board: [BEng(CompSc)](https://www.cs.hku.hk/programmes/beng-compsc/programme-structure "Bachelor of Engineering in Computer Science") at :school: [HKU](https://hku.hk/ "The University of Hong Kong"). 

**FYP22002: A Repository of Jupyter Notebooks on Unlearning in Federated Learning**

:point_right: Check out the :globe_with_meridians: [project website](https://vicw0ng-hk.github.io/feul/) (or visit the [backup](https://i.cs.hku.hk/~shuang/fyp/) on [HKU CS](https://www.cs.hku.hk/ "Dept. of Comp. Sci., Fac. of Engr., Univ. of H.K.") server in case GitHub [goes down](https://www.githubstatus.com/ "GitHub Status")) 

## :memo: Description

This repo aims to provide materials, in the form of Jupyter Notebooks, for studying machine unlearning in federated learning (FL), both of which are new research areas that are developing rapidly. 

> **Note**
> The data collection ended in early April 2023 and I have done my best to scrape the internet on this topic. 
> If you are checking out this repo in the future, you may find it incomplete. 
> However, it is helpful that we have this snapshot, so that future researchers can see how this new area grew and take inspirations from earlier research. 

The contents of the notebooks consist of
1. general introduction to the area and it's background (0-2);
2. research progress in 2021 (3-5);
3. research progress in 2022 (6-15);
4. research progress in 2023 (until early April) (16-19).

The notebooks, except those in the 1st part, are ordered according to the publication dates (or conference dates, or last edit date of preprints) of the papers.

:book:-marked notebooks are summaries of the paper with key concepts, figures and tables presented. <br /> 
:computer:-marked notebooks are instructions on how to run the code for the design algorithms, with tweaks made to get rid of bugs that usually exist in the original code. 

### Recommended prerequisites

Machine Learning **AND** Computer Security **AND** Operating Systems

**Optional**: Cryptography, Distributed Systems

## :card_index_dividers: Contents

| # | Topics | Contents | References |
| ---: | :--- | :--- | :--- |
| 0 | :wave: Intro to unlearning and FL | :book: [intro-unlearning.ipynb](/notebooks/00-intro-ul-fl/intro-unlearning.ipynb) <br /> :book: [intro-fl.ipynb](/notebooks/00-intro-ul-fl/intro-fl.ipynb) <br /> :computer: [code-amnesiac-ml.ipynb](/notebooks/00-intro-ul-fl/code-amnesiac-ml.ipynb) <br /> :computer: [code-flwr.ipynb](/notebooks/00-intro-ul-fl/code-flwr.ipynb) | [^ngu+22][^dan21][^pit+19][^st17][^cy15][^bou+21][^zha+21][^mcm+17][^gng21] |
| 1 | :mag: More on unlearning | :book: [unlearning-definition.ipynb](/notebooks/01-ul-more/unlearning-definition.ipynb) <br /> :book: [unlearning-framework.ipynb](/notebooks/01-ul-more/unlearning-framework.ipynb)  | [^ngu+22] |
| 2 | :bridge_at_night: Unlearning in FL | :book: [ul-in-fl.ipynb](/notebooks/02-un-in-fl/ul-in-fl.ipynb) | [^ngu+22][^mcm+17] |
| 3 | :tada: FedEraser: 1st attempt | :book: [federaser.ipynb](/notebooks/03-liu+21a/federaser.ipynb) <br /> :computer: [code-federaser.ipynb](/notebooks/03-liu+21a/code-federaser.ipynb) | [^liu+21a] |
| 4 | :deciduous_tree: RevFRF: federated unlearning in RF | :book: [revfrf.ipynb](/notebooks/04-liu+21b/revfrf.ipynb) | [^liu+21b] |
| 5 | :coin: Bayesian variational FL and unlearning | :book: [bayesian-variational.ipynb](notebooks/05-gsk21/bayesian-variational.ipynb) | [^gsk21] |
| 6 | :test_tube: Federated unlearing with distillation | :book: [distillation.ipynb](/notebooks/06-wzm22/distillation.ipynb) | [^wzm22] |
| 7 | :scissors: Federated unlearning with class-discriminative pruning | :book: [channel-prune.ipynb](notebooks/07-wan+22/channel-prune.ipynb) | [^wan+22] |
| 8 | :weight_lifting: Federated unlearing with rapid retraining | :book: [rapid-retrain.ipynb](/notebooks/08-liu+22/rapid-retrain.ipynb) <br /> :computer: [code-rapid-retrain.ipynb](/notebooks/08-liu+22/code-rapid-retrain.ipynb) | [^liu+22] |
| 9 | :dizzy: Forget-SVGD: particle-based Bayesian federated unlearning | :book: [forget-svgd.ipynb](/notebooks/09-gon+22/forget-svgd.ipynb) | [^gon+22] |
| 10 | :heavy_check_mark: VeriFi: Verifiable federated unlearning | :book: [verifi.ipynb](/notebooks/10-gao+22/verifi.ipynb) | [^gao+22] |
| 11 | :no_good: Client opt-out | :book: [opt-out-unlearning.ipynb](/notebooks/11-hal+22/opt-out-unlearning.ipynb) | [^hal+22] |
| 12 | :pill: FedRecover: recover from poison | :book: [fedrecover.ipynb](/notebooks/12-cao+22/fedrecover.ipynb) | [^cao+22] |
| 13 | :busts_in_silhouette: Unlearning of federated clusters | :book: [unlearning-cluster.ipynb](/notebooks/13-pan+22/unlearning-cluster.ipynb) | [^pan+22] |
| 14 | :rocket: Unlearning in federated optimization | :book: [sequential-informed.ipynb](/notebooks/14-fra+22/sequential-informed.ipynb) | [^fra+22] |
| 15 | :balance_scale: Compare class, client, sample unlearning | :book: [federated-unlearning.ipynb](/notebooks/15-wu+22/federated-unlearning.ipynb) | [^wu+22] |
| 16 | :milky_way: Subspace-based federated unlearning | :book: [subspace.ipynb](/notebooks/16-li+23/subspace.ipynb) | [^li+23] |
| 17 | :bar_chart: Federated knowledge graph embedding learning and unlearning | :book: [heterogeneous-kg-embedding.ipynb](/notebooks/17-zlh23/heterogeneous-kg-embedding.ipynb) | [^zlh23] |
| 18 | :+1: Federated unlearning for on-device recommendation | :book: [on-device-recommend.ipynb](/notebooks/18-yua+23/on-device-recommend.ipynb) | [^yua+23] |
| 19 | :link: Knot: asynchronous federated unlearning | :book: [knot.ipynb](/notebooks/19-zl23/knot.ipynb) <br /> :computer: [code-knot.ipynb](/notebooks/19-zl23/code-knot.ipynb) | [^zl23] |

[^ngu+22]: T. T. Nguyen, T. T. Huynh, P. L. Nguyen, A. W.-C. Liew, H. Yin, and Q. V. H. Nguyen, A Survey of Machine Unlearning. arXiv, 2022. [[Paper](https://arxiv.org/abs/2209.02299)]
[^dan21]: Q.-V. Dang, “Right to Be Forgotten in the Age of Machine Learning,” in Advances in Digital Science, 2021, pp. 403–411. [[Paper](https://link.springer.com/chapter/10.1007/978-3-030-71782-7_35)]
[^pit+19]: N. Pitropakis, E. Panaousis, T. Giannetsos, E. Anastasiadis, and G. Loukas, “A taxonomy and survey of attacks against machine learning,” Computer Science Review, vol. 34, p. 100199, 2019. [[Paper](https://www.sciencedirect.com/science/article/abs/pii/S1574013718303289)]
[^st17]: R. Shwartz-Ziv and N. Tishby, Opening the Black Box of Deep Neural Networks via Information. arXiv, 2017. [[Paper](https://arxiv.org/abs/1703.00810)]
[^cy15]: Y. Cao and J. Yang, “Towards Making Systems Forget with Machine Unlearning,” in 2015 IEEE Symposium on Security and Privacy, 2015, pp. 463–480. [[Paper](https://ieeexplore.ieee.org/document/7163042)] [[Video](https://www.youtube.com/watch?v=sUgIS6a665k)]
[^bou+21]: L. Bourtoule et al., “Machine Unlearning,” in 2021 IEEE Symposium on Security and Privacy (SP), 2021, pp. 141–159. [[Paper](https://ieeexplore.ieee.org/document/9519428)] [[Video](https://www.youtube.com/watch?v=xUnMkCB0Gns)]
[^zha+21]: C. Zhang, Y. Xie, H. Bai, B. Yu, W. Li, and Y. Gao, “A survey on federated learning,” Knowledge-Based Systems, vol. 216, p. 106775, 2021. [[Paper](https://www.sciencedirect.com/science/article/abs/pii/S0950705121000381)]
[^mcm+17]: B. McMahan, E. Moore, D. Ramage, S. Hampson, and B. A. y Arcas, “Communication-Efficient Learning of Deep Networks from Decentralized Data,” in Proceedings of the 20th International Conference on Artificial Intelligence and Statistics, Apr. 2017, vol. 54, pp. 1273–1282. [[Paper](https://proceedings.mlr.press/v54/mcmahan17a.html)]
[^gng21]: Graves, L., Nagisetty, V., & Ganesh, V. (2021). Amnesiac Machine Learning. Proceedings of the AAAI Conference on Artificial Intelligence, 35(13), 11516-11524. [[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/17371)]
[^liu+21a]: G. Liu, X. Ma, Y. Yang, C. Wang, and J. Liu, “FedEraser: Enabling Efficient Client-Level Data Removal from Federated Learning Models,” in 2021 IEEE/ACM 29th International Symposium on Quality of Service (IWQOS), 2021, pp. 1–10. [[Paper](https://ieeexplore.ieee.org/abstract/document/9521274)]
[^liu+21b]: Y. Liu, Z. Ma, Y. Yang, X. Liu, J. Ma, and K. Ren, “RevFRF: Enabling Cross-Domain Random Forest Training With Revocable Federated Learning,” IEEE Transactions on Dependable and Secure Computing, vol. 19, no. 6, pp. 3671–3685, 2022. [[Paper](https://ieeexplore.ieee.org/abstract/document/9514457)]
[^gsk21]: J. Gong, O. Simeone, and J. Kang, “Bayesian Variational Federated Learning and Unlearning in Decentralized Networks,” in 2021 IEEE 22nd International Workshop on Signal Processing Advances in Wireless Communications (SPAWC), 2021, pp. 216–220. [[Paper](https://ieeexplore.ieee.org/abstract/document/9593225)]
[^wzm22]: C. Wu, S. Zhu, and P. Mitra, Federated Unlearning with Knowledge Distillation. arXiv, 2022. [[Paper](https://arxiv.org/abs/2201.09441)]
[^wan+22]: J. Wang, S. Guo, X. Xie, and H. Qi, “Federated Unlearning via Class-Discriminative Pruning,” in Proceedings of the ACM Web Conference 2022, 2022, pp. 622–632. [[Paper](https://dl.acm.org/doi/abs/10.1145/3485447.3512222)]
[^liu+22]: Y. Liu, L. Xu, X. Yuan, C. Wang, and B. Li, “The Right to be Forgotten in Federated Learning: An Efficient Realization with Rapid Retraining,” May 2022. doi: 10.1109/infocom48880.2022.9796721. [[Paper](https://ieeexplore.ieee.org/document/9796721)]
[^gon+22]: J. Gong, J. Kang, O. Simeone and R. Kassab, "Forget-SVGD: Particle-Based Bayesian Federated Unlearning," 2022 IEEE Data Science and Learning Workshop (DSLW), 2022, pp. 1-6, doi: 10.1109/DSLW53931.2022.9820602. [[Paper](https://ieeexplore.ieee.org/document/9820602)]
[^gao+22]: X. Gao et al., VeriFi: Towards Verifiable Federated Unlearning. arXiv, 2022. doi: 10.48550/ARXIV.2205.12709. [[Paper](https://arxiv.org/abs/2205.12709)]
[^hal+22]: A. Halimi, S. Kadhe, A. Rawat, and N. Baracaldo, Federated Unlearning: How to Efficiently Erase a Client in FL? arXiv, 2022. doi: 10.48550/ARXIV.2207.05521. [[Paper](https://arxiv.org/abs/2207.05521)]
[^cao+22]: X. Cao, J. Jia, Z. Zhang, and N. Z. Gong, FedRecover: Recovering from Poisoning Attacks in Federated Learning using Historical Information. arXiv, 2022. doi: 10.48550/ARXIV.2210.10936. [[Paper](https://arxiv.org/abs/2210.10936)]
[^pan+22]: C. Pan, J. Sima, S. Prakash, V. Rana, and O. Milenkovic, Machine Unlearning of Federated Clusters. arXiv, 2022. doi: 10.48550/ARXIV.2210.16424. [[Paper](https://arxiv.org/abs/2210.16424)]
[^fra+22]: Y. Fraboni, R. Vidal, L. Kameni, and M. Lorenzi, Sequential Informed Federated Unlearning: Efficient and Provable Client Unlearning in Federated Optimization. arXiv, 2022. doi: 10.48550/ARXIV.2211.11656. [[Paper](https://arxiv.org/abs/2211.11656)]
[^wu+22]: L. Wu, S. Guo, J. Wang, Z. Hong, J. Zhang, and Y. Ding, “Federated Unlearning: Guarantee the Right of Clients to Forget,” IEEE Network, vol. 36, no. 5, pp. 129–135, 2022, doi: 10.1109/MNET.001.2200198. [[Paper](https://ieeexplore.ieee.org/abstract/document/9964015)]
[^li+23]: G. Li, L. Shen, Y. Sun, Y. Hu, H. Hu, and D. Tao, Subspace based Federated Unlearning. arXiv, 2023. doi: 10.48550/ARXIV.2302.12448. [[Paper](https://arxiv.org/abs/2302.12448)]
[^zlh23]: X. Zhu, G. Li, and W. Hu, Heterogeneous Federated Knowledge Graph Embedding Learning and Unlearning. arXiv, 2023. doi: 10.48550/ARXIV.2302.02069 [[Paper](https://arxiv.org/abs/2302.02069)]
[^yua+23]: W. Yuan, H. Yin, F. Wu, S. Zhang, T. He, and H. Wang, “Federated Unlearning for On-Device Recommendation,” in Proceedings of the Sixteenth ACM International Conference on Web Search and Data Mining, 2023, pp. 393–401. doi: 10.1145/3539597.3570463. [[Paper](https://dl.acm.org/doi/abs/10.1145/3539597.3570463)]
[^zl23]: N. Su and B. Li, “Asynchronous Federated Unlearning,” Proceedings of International Conference on Computer Communications (INFOCOM), 2023. [[Paper](https://ningxinsu.github.io/projects/infocom23/)]
