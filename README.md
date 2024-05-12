# awesome-memorization
**Still Under Constructed**
Focusing on everything on the memorization of foundation models with the interaction of following topics from both empirical and theoretical view(esp. statistical view):
- Memorization, Generalization and Optimization
- Memorization, Forgetting and Machine Unlearning
- Memorization in Diffusion Models
- Memorization in Security&Privacy, including differential privacy, privacy attacks, etc
- Memorization and noisy learning
- Memorization and data distribution/model architecture

## Papers
### Definition of Memorization and Evolution
- Understanding deep learning requires rethinking generalization(ICLR 2017) [\[paper\]](https://openreview.net/pdf?id=Sy8gdB9xx)
- A Closer Look at Memorization in Deep Networks(ICML 2017) [\[paper\]](https://proceedings.mlr.press/v70/arpit17a/arpit17a.pdf)
- What Neural Networks Memorize and Why: Discovering the Long Tail via Influence Estimation(NIPS 2020) [\[paper\]](https://arxiv.org/pdf/2008.03703)
- Does Learning Require Memorization? A Short Tale about a Long Tail(STOC 2020) [\[paper\]](https://arxiv.org/pdf/1906.05271)
- When is memorization of irrelevant training data necessary for high-accuracy learning?(STOC 2021) [\[paper\]](https://arxiv.org/pdf/2012.06421)
- On Memorization in Probabilistic Deep Generative Models(NIPS 2021) [\[paper\]](https://proceedings.neurips.cc/paper_files/paper/2021/file/eae15aabaa768ae4a5993a8a4f4fa6e4-Paper.pdf)
- The Privacy Onion Effect: Memorization is Relative(NIPS 2022) [\[paper\]](https://proceedings.neurips.cc/paper_files/paper/2022/file/564b5f8289ba846ebc498417e834c253-Paper-Conference.pdf)
- Can Neural Network Memorization Be Localized?(ICML 2023) [\[paper\]](https://proceedings.mlr.press/v202/maini23a/maini23a.pdf)
- Quantifying Memorization Across Neural Language Models(ICLR 2023) [\[paper\]](https://arxiv.org/pdf/2202.07646)


### Membership Inference Attack
#### Membership Inference Attack, Improvements and Interpretations
- Membership Inference Attacks on Machine Learning: A Survey(ACM Computing Surveys 2022) [\[paper\]](https://dl.acm.org/doi/10.1145/3523273)
- Membership Inference Attacks against Machine Learning Models(IEEE S&P 2017) [\[paper\]](http://arxiv.org/abs/1610.05820)
- Privacy Risk in Machine Learning: Analyzing the Connection to Overfitting(IEEE CSF 2018) [\[paper\]](https://arxiv.org/abs/1709.01604)
- Enhanced Membership Inference Attacks against Machine Learning Models(CCS 2022) [\[paper\]](https://dl.acm.org/doi/10.1145/3548606.3560675)
- Membership Inference Attacks From First Principles(IEEE S&P 2022) [\[paper\]](https://arxiv.org/abs/2112.03570v2)
- On the Importance of Difficulty Calibration in Membership Inference Attacks(ICLR 2022) [\[paper\]](https://arxiv.org/pdf/2111.08440)
- A Blessing of Dimensionality in Membership Inference through Regularization(AISTATS 2023) [\[paper\]](https://proceedings.mlr.press/v206/tan23b/tan23b.pdf)
- Canary in a Coalmine: Better Membership Inference with Ensembled Adversarial Queries(ICLR 2023) [\[paper\]](https://arxiv.org/pdf/2210.10750)
- Scalable membership inference attacks via quantile regression（NeurIPS 2023) [\[paper\]](https://openreview.net/pdf?id=t3WCiGjHqd)
- Investigating Membership Inference Attacks under Data Dependencies(IEEE CSF 2023) [\[paper\]](https://arxiv.org/pdf/2010.12112)
- Why Does Differential Privacy with Large Epsilon Defend Against Practical Membership Inference Attacks?(AAAI 2023) [\[paper\]](https://arxiv.org/pdf/2402.09540)
- Privacy Backdoors: Enhancing Membership Inference through Poisoning Pre-trained Models.(arXiv 2024) [\[paper\]](https://arxiv.org/pdf/2404.01231)
- Leave-one-out Distinguishability in Machine Learning(ICLR 2024) [\[paper\]](https://openreview.net/pdf?id=9RNfX0ah0K)
- Mitigating Privacy Risk in Membership Inference by Convex-Concave Loss(ICML 2024) [\[paper\]](https://arxiv.org/pdf/2402.05453)
- Low-Cost High-Power Membership Inference by Boosting Relativity(ICML 2024) [\[paper\]](https://openreview.net/pdf?id=dRel8fuUK4)


#### Membership Inference Attack in Specific Scenarios
##### Diffusion Models
- Membership Inference Attacks against Diffusion Models(IEEE S&P Workshops 2023) [\[paper\]](https://arxiv.org/pdf/2302.03262)
- Are Diffusion Models Vulnerable to Membership Inference Attacks?(ICML 2023) [\[paper\]](https://arxiv.org/pdf/2302.01316)
- White-box Membership Inference Attacks against Diffusion Models(arXiv 2023) [\[paper\]](https://arxiv.org/pdf/2308.06405)
- Towards More Realistic Membership Inference Attacks on Large Diffusion Models(WACV 2024) [\[paper\]](https://openaccess.thecvf.com/content/WACV2024/papers/Dubinski_Towards_More_Realistic_Membership_Inference_Attacks_on_Large_Diffusion_Models_WACV_2024_paper.pdf)
- An Efficient Membership Inference Attack for the Diffusion Model by Proximal Initialization(ICLR 2024) [\[paper\]](https://openreview.net/pdf?id=rpH9FcCEV6)
- Membership Inference Attacks on Diffusion Models via Quantile Regression(ICML 2024) [\[paper\]](https://arxiv.org/pdf/2312.05140)


##### Large Language Models
- Membership Inference Attacks against Language Models via Neighbourhood Comparison(ACL 2023) [\[paper\]](https://arxiv.org/pdf/2305.18462)
- Do Membership Inference Attacks Work on Large Language Models?(arXiv 2023) [\[paper\]](https://arxiv.org/pdf/2402.07841)
- 

- Semi-Leak: Membership Inference Attacks Against Semi-supervised Learning(ECCV 2022) [\[paper\]](https://arxiv.org/pdf/2207.12535)
- Membership Inference Attacks against Synthetic Data through Overfitting Detection(AISTATS 2023) [\[paper\]](https://arxiv.org/pdf/2302.12580)
- Students Parrot Their Teachers: Membership Inference on Model Distillation(NeurIPS 2023) [\[paper\]](https://openreview.net/pdf?id=a2Yg9Za6Rb)

### Differential Privacy




### Neural Collapse
- Neural Collapse meets Differential Privacy: Curious behaviors of NoisyGD with Near-Perfect Representation Learning(ICML 2024) [\[paper\]](https://openreview.net/pdf?id=ZVi81SH1Ob)

### Data Pruning/Data Condensation/Data Selection
- Ameliorate Spurious Correlations in Dataset Condensation(ICML 2024) [\[paper\]]

### Noisy Learning
#### Privilage Information
- Learning Using Privileged Information: Similarity Control and Knowledge Transfer(NN 2009) [\[paper\]](https://www.jmlr.org/papers/volume16/vapnik15b/vapnik15b.pdf)
- Mind the Nuisance: Gaussian Process Classification using Privileged Noise(NIPS 2014) [\[paper\]](https://proceedings.neurips.cc/paper_files/paper/2014/file/6e2713a6efee97bacb63e52c54f0ada0-Paper.pdf)
- Unifying distillation and privileged information(ICLR 2016) [\[paper\]](https://arxiv.org/pdf/1511.03643)
- Transfer and Marginalize: Explaining Away Label Noise with Privileged Information(ICML 2022) [\[paper\]](https://arxiv.org/pdf/2202.09244)
- When does Privileged Information Explain Away Label Noise?(ICML 2023) [\[paper\]](https://proceedings.mlr.press/v202/ortiz-jimenez23a/ortiz-jimenez23a.pdf)
- Pi-DUAL: Using privileged information to distinguish clean from noisy labels(ICML 2024) [\[paper\]](https://arxiv.org/pdf/2310.06600)

### Memorization, Generalization and Optimization
- Information Complexity of Stochastic Convex Optimization: Applications to Generalization and Memorization(ICML 2024) [\[paper\]](https://arxiv.org/pdf/2402.09327)

