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
- (ICLR 2017) Understanding deep learning requires rethinking generalization [\[paper\]](https://openreview.net/pdf?id=Sy8gdB9xx)
- (ICML 2017) A Closer Look at Memorization in Deep Networks [\[paper\]](https://proceedings.mlr.press/v70/arpit17a/arpit17a.pdf)
- (NeurIPS 2020) What Neural Networks Memorize and Why: Discovering the Long Tail via Influence Estimation [\[paper\]](https://arxiv.org/pdf/2008.03703)
- (STOC 2020) Does Learning Require Memorization? A Short Tale about a Long Tail [\[paper\]](https://arxiv.org/pdf/1906.05271)
- (STOC 2021) When is memorization of irrelevant training data necessary for high-accuracy learning? [\[paper\]](https://arxiv.org/pdf/2012.06421)
- (NIPS 2021) On Memorization in Probabilistic Deep Generative Models [\[paper\]](https://proceedings.neurips.cc/paper_files/paper/2021/file/eae15aabaa768ae4a5993a8a4f4fa6e4-Paper.pdf)
- (NIPS 2022) The Privacy Onion Effect: Memorization is Relative [\[paper\]](https://proceedings.neurips.cc/paper_files/paper/2022/file/564b5f8289ba846ebc498417e834c253-Paper-Conference.pdf)
- (ICML 2023) Can Neural Network Memorization Be Localized? [\[paper\]](https://proceedings.mlr.press/v202/maini23a/maini23a.pdf)
- (ICLR 2023) Quantifying Memorization Across Neural Language Models [\[paper\]](https://arxiv.org/pdf/2202.07646)
- (arXiv 2024) Rethinking LLM Memorization through the Lens of Adversarial Compression [\[paper\]](https://arxiv.org/pdf/2404.15146)

#### Overparameterized Neural Networks


#### Forgetting and Machine Unlearning
- (PNAS 2017) Overcoming catastrophic forgetting in neural networks [\[paper\]](https://arxiv.org/pdf/1612.00796)
- (IJCNN 2020) On Catastrophic Forgetting and Mode Collapse in Generative Adversarial Networks [\[paper\]](https://arxiv.org/pdf/1807.04015)
- (ICLR 2019) An Empirical Study of Example Forgetting during Deep Neural Network Learning [\[paper\]](https://openreview.net/pdf?id=BJlxm30cKm)
- (NIPS 2022) Characterizing Datapoints via Second-Split Forgetting [\[paper\]](https://openreview.net/pdf?id=yKDKNzjHg8N)
- (ICLR 2023) Measuring Forgetting of Memorized Training Examples [\[paper\]](https://openreview.net/pdf?id=7bJizxLKrR)
- (arXiv 2023) The Curse of Recursion: Training on Generated Data Makes Models Forget [\[paper\]](https://arxiv.org/pdf/2305.17493)


### Membership Inference Attack
#### Membership Inference Attack, Improvements and Interpretations
- (ACM Computing Surveys 2022) Membership Inference Attacks on Machine Learning: A Survey [\[paper\]](https://dl.acm.org/doi/10.1145/3523273)
- (IEEE S&P 2017) Membership Inference Attacks against Machine Learning Models [\[paper\]](http://arxiv.org/abs/1610.05820)
- (IEEE CSF 2018) Privacy Risk in Machine Learning: Analyzing the Connection to Overfitting [\[paper\]](https://arxiv.org/abs/1709.01604)
- (CCS 2022) Enhanced Membership Inference Attacks against Machine Learning Models [\[paper\]](https://dl.acm.org/doi/10.1145/3548606.3560675)
- (IEEE S&P 2022) Membership Inference Attacks From First Principles [\[paper\]](https://arxiv.org/abs/2112.03570v2)
- (ICLR 2022) On the Importance of Difficulty Calibration in Membership Inference Attacks [\[paper\]](https://arxiv.org/pdf/2111.08440)
- (AISTATS 2023) A Blessing of Dimensionality in Membership Inference through Regularization [\[paper\]](https://proceedings.mlr.press/v206/tan23b/tan23b.pdf)
- (ICLR 2023) Canary in a Coalmine: Better Membership Inference with Ensembled Adversarial Queries [\[paper\]](https://arxiv.org/pdf/2210.10750)
- (NeurIPS 2023) Scalable membership inference attacks via quantile regression [\[paper\]](https://openreview.net/pdf?id=t3WCiGjHqd)
- (IEEE CSF 2023) Investigating Membership Inference Attacks under Data Dependencies [\[paper\]](https://arxiv.org/pdf/2010.12112)
- (AAAI 2023) Why Does Differential Privacy with Large Epsilon Defend Against Practical Membership Inference Attacks? [\[paper\]](https://arxiv.org/pdf/2402.09540)
- (arXiv 2024) Privacy Backdoors: Enhancing Membership Inference through Poisoning Pre-trained Models. [\[paper\]](https://arxiv.org/pdf/2404.01231)
- (ICLR 2024) Leave-one-out Distinguishability in Machine Learning [\[paper\]](https://openreview.net/pdf?id=9RNfX0ah0K)
- (ICML 2024) Mitigating Privacy Risk in Membership Inference by Convex-Concave Loss [\[paper\]](https://arxiv.org/pdf/2402.05453)
- (ICML 2024) Low-Cost High-Power Membership Inference by Boosting Relativity [\[paper\]](https://openreview.net/pdf?id=dRel8fuUK4)


#### Membership Inference Attack in Specific Scenarios
##### Diffusion Models
- (IEEE S&P Workshops 2023) Membership Inference Attacks against Diffusion Models [\[paper\]](https://arxiv.org/pdf/2302.03262)
- (ICML 2023) Are Diffusion Models Vulnerable to Membership Inference Attacks? [\[paper\]](https://arxiv.org/pdf/2302.01316)
- (arXiv 2023) White-box Membership Inference Attacks against Diffusion Models [\[paper\]](https://arxiv.org/pdf/2308.06405)
- (WACV 2024) Towards More Realistic Membership Inference Attacks on Large Diffusion Models [\[paper\]](https://openaccess.thecvf.com/content/WACV2024/papers/Dubinski_Towards_More_Realistic_Membership_Inference_Attacks_on_Large_Diffusion_Models_WACV_2024_paper.pdf)
- (ICLR 2024) An Efficient Membership Inference Attack for the Diffusion Model by Proximal Initialization [\[paper\]](https://openreview.net/pdf?id=rpH9FcCEV6)
- (ICML 2024) Membership Inference Attacks on Diffusion Models via Quantile Regression [\[paper\]](https://arxiv.org/pdf/2312.05140)

##### Large Language Models
- (ACL 2023) Membership Inference Attacks against Language Models via Neighbourhood Comparison [\[paper\]](https://arxiv.org/pdf/2305.18462)
- (arXiv 2023) Do Membership Inference Attacks Work on Large Language Models? [\[paper\]](https://arxiv.org/pdf/2402.07841)

##### Semi-supervised Learning
- (ECCV 2022) Semi-Leak: Membership Inference Attacks Against Semi-supervised Learning [\[paper\]](https://arxiv.org/pdf/2207.12535)

##### Synthetic Dataset
- (AISTATS 2023) Membership Inference Attacks against Synthetic Data through Overfitting Detection [\[paper\]](https://arxiv.org/pdf/2302.12580)

##### Model Distillation/Compression
- (NeurIPS 2023) Students Parrot Their Teachers: Membership Inference on Model Distillation [\[paper\]](https://openreview.net/pdf?id=a2Yg9Za6Rb)


### Differential Privacy




### Neural Collapse
- (ICML 2024) Neural Collapse meets Differential Privacy: Curious behaviors of NoisyGD with Near-Perfect Representation Learning [\[paper\]](https://openreview.net/pdf?id=ZVi81SH1Ob)

### Data Pruning/Data Condensation/Data Selection/Example Hardness
- (NeurIPS 2023) Data pruning and neural scaling laws: fundamental limitations of score-based algorithms [\[paper\]](http://arxiv.org/pdf/2302.06960)
- (ICML 2024) Ameliorate Spurious Correlations in Dataset Condensation [\[paper\]]

### Noisy Learning
#### Privilage Information
- (NN 2009) Learning Using Privileged Information: Similarity Control and Knowledge Transfer [\[paper\]](https://www.jmlr.org/papers/volume16/vapnik15b/vapnik15b.pdf)
- (NIPS 2014) Mind the Nuisance: Gaussian Process Classification using Privileged Noise [\[paper\]](https://proceedings.neurips.cc/paper_files/paper/2014/file/6e2713a6efee97bacb63e52c54f0ada0-Paper.pdf)
- (ICLR 2016) Unifying distillation and privileged information [\[paper\]](https://arxiv.org/pdf/1511.03643)
- (ICML 2022) Transfer and Marginalize: Explaining Away Label Noise with Privileged Information [\[paper\]](https://arxiv.org/pdf/2202.09244)
- (ICML 2023) When does Privileged Information Explain Away Label Noise? [\[paper\]](https://proceedings.mlr.press/v202/ortiz-jimenez23a/ortiz-jimenez23a.pdf)
- (ICML 2024) Pi-DUAL: Using privileged information to distinguish clean from noisy labels [\[paper\]](https://arxiv.org/pdf/2310.06600)

### Memorization, Generalization and Optimization
- (ICML 2024) Information Complexity of Stochastic Convex Optimization: Applications to Generalization and Memorization [\[paper\]](https://arxiv.org/pdf/2402.09327)

