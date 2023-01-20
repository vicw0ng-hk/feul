---
title: "Introduction"
date: 2022-09-26T09:31:11+08:00
featured_image: "/images/mu.png"
---

## 👉 More details at [Project Plan](../docs/fyp-plan.pdf) 👈

## 👉 Update 🎈 [1st Presentation](../docs/fyp-1st-present.pdf) 👈

<div style="text-align:left;">

## What is Machine Unlearning?

<iframe src="https://www.youtube-nocookie.com/embed/xUnMkCB0Gns" class="video" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### Machine Unlearning for Dummies

Say machine learning is a machine learning from data, then machine unlearning is a machine forgetting the knowledge that it has learnt from data. 

To be more exact, we want to erase a machine's knowledge that it has learnt from certain data, making it look like that the machine has never seen that data. 

In a way, you can say we are rewriting history for the machine, or the machine has got [amnesia](https://en.wikipedia.org/wiki/Amnesia) that has caused permanent memory loss of certain data. 

If you like the analogy using the human brain, machine unlearning is like [memory erasure](https://en.wikipedia.org/wiki/Memory_erasure), which is very difficult. 

![MIB](../images/mib.jpg)

IRL, we don't have MIB's neuralyzer, so...

<iframe src="https://www.youtube-nocookie.com/embed/VuE_jqYNi3c" class="video" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### A Little Bit of History

There have been discussions of decremental learning early in the 00s, such as [Cauwenberghs and Poggio](https://proceedings.neurips.cc/paper/2000/hash/155fa09596c7e18e50b58eb7e0c6ccb4-Abstract.html "Incremental and Decremental Support Vector Machine Learning") in NeurIPS 2000. 

In 2015, [Cao and Yang](https://ieeexplore.ieee.org/document/7163042 "Towards Making Systems Forget with Machine Unlearning") ([Talk](https://www.youtube.com/watch?v=sUgIS6a665k)) first put together the term "machine unlearning". (Fun fact: HKUCS's [Dr. H. Cui](https://i.cs.hku.hk/~heming/) got his PhD under [Yang](http://www.cs.columbia.edu/~junfeng/)'s supervision at Columbia) The paper appeared in the 2015 IEEE Symposium on Security and Privacy ("Oakland"), a top conference in cybersecurity and privacy ([CORE A\* rank](http://portal.core.edu.au/conf-ranks/750/)). 

In 2019, [Bourtoule *et al.*](https://ieeexplore.ieee.org/document/9519428 "Machine Unlearning") proposed SISA training, a framework that expedites the machine unlearning process. The paper later appeared in IEEE S&P 2021. 

In 2022, [Nguyen *et al.*](https://arxiv.org/abs/2209.02299 "A Survey of Machine Unlearning") comprehensively surveyed recent developments of the machine unlearning field.  

## What is Federated Learning?

<iframe src="https://www.youtube-nocookie.com/embed/X8YYWunttOY" class="video" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### Federated Learning in Google's Own Words

> It works like this: your device downloads the current model, improves it by learning from data on your phone, and then summarizes the changes as a small focused update. Only this update to the model is sent to the cloud, using encrypted communication, where it is immediately averaged with other user updates to improve the shared model. All the training data remains on your device, and no individual updates are stored in the cloud.
> -- [McMahan *et al.*](https://ai.googleblog.com/2017/04/federated-learning-collaborative.html "Federated Learning: Collaborative Machine Learning without Centralized Training Data") ([Paper](https://proceedings.mlr.press/v54/mcmahan17a.html "Communication-Efficient Learning of Deep Networks from Decentralized Data"))

### Related FYP

[Quantitative Performance and Security Evaluation of Federated Learning on open-sourced platforms](https://wp.cs.hku.hk/2022/fyp22019/ "FYP22019") by C.T. Fong -- also supervised by [Prof. S.M. Yiu](https://www.cs.hku.hk/index.php/people/academic-staff/smyiu), an industry project with [ASTRI](https://www.astri.org/) (I [spent a summer](https://www.linkedin.com/feed/update/urn:li:activity:6966255953239306240/) there. ASTRI's CTO [Dr. Lucas C.K. Hui](https://www.astri.org/about/senior-management/senior-director-cctt/) was [with HKUCS](https://www.cs.hku.hk/people/academic-staff/hui)).

## About This Project

This project aims to investigate how machine unlearning can be applied in federated learning, to produce materials for non-specialists and experts in related areas for learning this topic, to explore possible improvements to the work done in the field and to deliver final year project results of outstanding quality and standard. 

## Related Resources

Related resources in security of ML and machine unlearning. 

- [Privacy and Security in ML Seminars - Privacy & Security in Machine Learning (PriSec-ML) Interest Group](https://prisec-ml.github.io/)
- [Virtual Seminar Series - Challenges and Opporunities for Security & Privacy in Machine Learning](https://vsehwag.github.io/SPML_seminar/)
- [IEEE Conference on Secure and Trustworthy Machine Learning (SaTML)](https://satml.org/)
- [the cleverhans blog - a blog by Ian Goodfellow and Nicolas Papernot about security and privacy in machine learning](http://www.cleverhans.io/)
- [ECE1784H/CSC2559H: Trustworthy Machine Learning Fall 2022 - University of Toronto](https://www.papernot.fr/teaching/f22-trustworthy-ml.html)
- [Awesome Machine Unlearning - GitHub Repo](https://github.com/tamlhp/awesome-machine-unlearning)

</div>
