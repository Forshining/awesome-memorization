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
- (arXiv 2024) Déjà Vu Memorization in Vision-Language Models [\[paper\]](https://arxiv.org/pdf/2402.02103)
- (arXiv 2024) Rethinking LLM Memorization through the Lens of Adversarial Compression [\[paper\]](https://arxiv.org/pdf/2404.15146)
- (ICLR 2024) Detecting, Explaining, and Mitigating Memorization in Diffusion Models [\[paper\]](https://openreview.net/pdf?id=84n3UwkH7b)
- (ICLR 2024) Memorization in Self-Supervised Learning Improves Downstream Generalization [\[paper\]](https://openreview.net/pdf?id=KSjPaXtxP8)
- (INLG 2023) Preventing Generation of Verbatim Memorization in Language Models Gives a False Sense of Privacy [\[paper\]](https://arxiv.org/pdf/2210.17546)
- (ICLR 2023) Quantifying Memorization Across Neural Language Models [\[paper\]](https://arxiv.org/pdf/2202.07646)
- (NeurIPS 2023) Do SSL Models Have Déjà Vu? A Case of Unintended Memorization in Self-supervised Learning [\[paper\]](https://openreview.net/pdf?id=lkBygTc0SI)
- (NeurIPS 2023) Emergent and Predictable Memorization in Large Language Models [\[paper\]](https://openreview.net/pdf?id=Iq0DvhB4Kf)
- (NeurIPS 2023) Counterfactual Memorization in Neural Language Models [\[paper\]](http://arxiv.org/pdf/2112.12938)
- (NeurIPS 2023) Understanding and Mitigating Copying in Diffusion Models [\[paper\]](https://arxiv.org/pdf/2305.20086) [\[code\]](https://github.com/somepago/DCR)
- (CVPR 2023) Diffusion Art or Digital Forgery? Investigating Data Replication in Diffusion Models [\[paper\]](https://openaccess.thecvf.com/content/CVPR2023/papers/Somepalli_Diffusion_Art_or_Digital_Forgery_Investigating_Data_Replication_in_Diffusion_CVPR_2023_paper.pdf) [\[code\]](https://github.com/somepago/DCR)
- (UAI 2023) Mnemonist: Locating Model Parameters that Memorize Training Examples [\[paper\]](https://proceedings.mlr.press/v216/shahin-shamsabadi23a/shahin-shamsabadi23a.pdf)
- (ICML 2023) Can Neural Network Memorization Be Localized? [\[paper\]](https://proceedings.mlr.press/v202/maini23a/maini23a.pdf)
- (ACL 2022) Preventing Verbatim Memorization in Language Models Gives a False Sense of Privacy [\[paper\]](https://arxiv.org/pdf/2210.17546)
- (STOC 2021) When is memorization of irrelevant training data necessary for high-accuracy learning? [\[paper\]](https://arxiv.org/pdf/2012.06421)
- (ICLR 2021) On the geometry of generalization and memorization in deep neural networks [\[paper\]](https://arxiv.org/pdf/2105.14602)
- (NIPS 2021) On Memorization in Probabilistic Deep Generative Models [\[paper\]](https://proceedings.neurips.cc/paper_files/paper/2021/file/eae15aabaa768ae4a5993a8a4f4fa6e4-Paper.pdf)
- (arXiv 2020) Modifying Memories in Transformer Models [\[paper\]](https://arxiv.org/pdf/2012.00363)
- (STOC 2020) Does Learning Require Memorization? A Short Tale about a Long Tail [\[paper\]](https://arxiv.org/pdf/1906.05271)
- (ICLR 2020) Identity Crisis: Memorization and Generalization under Extreme Overparameterization [\[paper\]](https://openreview.net/pdf?id=B1l6y0VFPr)
- (NeurIPS 2020) What Neural Networks Memorize and Why: Discovering the Long Tail via Influence Estimation [\[paper\]](https://arxiv.org/pdf/2008.03703)
- (ICML 2017) A Closer Look at Memorization in Deep Networks [\[paper\]](https://proceedings.mlr.press/v70/arpit17a/arpit17a.pdf)
- (ICLR 2017) Understanding deep learning requires rethinking generalization [\[paper\]](https://openreview.net/pdf?id=Sy8gdB9xx)


#### Overparameterized Neural Networks
##### Theoretical Analysis 
- (arXiv 2023) On the Impact of Overparameterization on the Training of a Shallow Neural Network in High Dimensions [\[paper\]](http://arxiv.org/pdf/2311.03794)
- (NIPS 2023) Initialization Matters: Privacy-Utility Analysis of Overparameterized Neural Networks [\[paper\]](https://openreview.net/pdf?id=IKvxmnHjkL)
- (JMLR 2023) Benign overﬁtting in ridge regression [\[paper\]](https://www.jmlr.org/papers/volume24/22-1398/22-1398.pdf)
- (Acta Numerica 2022) Fit without fear: remarkable mathematical phenomena of deep learning through the prism of interpolation [\[paper\]](https://arxiv.org/pdf/2105.14368)
- (arXiv 2022) Scaling Laws and Interpretability of Learning from Repeated Data [\[paper\]](https://arxiv.org/pdf/2205.10487)
- (JMLR 2022) Underspecification Presents Challenges for Credibility in Modern Machine Learning [\[paper\]](https://www.jmlr.org/papers/volume23/20-1335/20-1335.pdf)
- (NIPS 2022) Memorization and Optimization in Deep Neural Networks with Minimum Over-parameterization [\[paper\]](https://proceedings.neurips.cc/paper_files/paper/2022/file/323746f0ae2fbd8b6f500dc2d5c5f898-Paper-Conference.pdf)
- (COLT 2022) Memorize to generalize: on the necessity of interpolation in high dimensional linear regression [\[paper\]](https://proceedings.mlr.press/v178/cheng22a/cheng22a.pdf)
- (arXiv 2022) The Interpolation Phase Transition in Neural Networks: Memorization and Generalization under Lazy Training [\[paper\]](https://arxiv.org/pdf/2007.12826)
- (arXiv 2022) Dimension Independent Generalization of DP-SGD for Overparameterized Smooth Convex Optimization [\[paper\]](http://arxiv.org/pdf/2206.01836)
- (NIPS 2022) Parameters or Privacy: A Provable Tradeoff Between Overparameterization and Membership Inference [\[paper\]](https://openreview.net/pdf?id=7nypt7cjNL)
- (Physical Review Research 2022) Memorizing without overfitting: Bias, variance, and interpolation in overparameterized models [\[paper\]](https://arxiv.org/pdf/2010.13933)
- (NIPS 2021) A Universal Law of Robustness via Isoperimetry [\[paper\]](https://proceedings.neurips.cc/paper_files/paper/2021/file/f197002b9a0853eca5e046d9ca4663d5-Paper.pdf)
- (NIPS 2021) Overparameterization Improves Robustness to Covariate Shift in High Dimensions [\[paper\]](https://openreview.net/pdf?id=PxMfDdPnTfV)
- (ICML 2020) An Investigation of Why Overparameterization Exacerbates Spurious Correlations [\[paper\]](https://proceedings.mlr.press/v119/sagawa20a/sagawa20a.pdf)
- (arXiv 2020) Surprises in high-dimensional ridgeless least squares interpolation [\[paper\]](https://arxiv.org/pdf/1903.08560)
- (arXiv 2020) The generalization error of random features regression: Precise asymptotics and double descent curve [\[paper\]](https://arxiv.org/pdf/1908.05355)
- (PNAS 2019) Benign overfitting in linear regression [\[paper\]](https://arxiv.org/pdf/1906.11300)
- (arXiv 2019) Harmless interpolation of noisy data in regression [\[paper\]](https://arxiv.org/pdf/1903.09139)
- (arXiv 2019) Reconciling modern machine learning practice and the bias-variance trade-off [\[paper\]](https://arxiv.org/pdf/1812.11118)

##### Empirical Analysis
- (NIPS 2022) Memorization Without Overfitting: Analyzing the Training Dynamics of Large Language Models [\[paper\]](https://proceedings.neurips.cc/paper_files/paper/2022/file/fa0509f4dab6807e2cb465715bf2d249-Paper-Conference.pdf)
- (ICML 2022) Robust Training under Label Noise by Over-parameterization [\[paper\]](https://arxiv.org/pdf/2202.14026)
- (ICML 2021) Characterizing Structural Regularities of Labeled Data in Overparameterized Models [\[paper\]](https://arxiv.org/pdf/2002.03206)
- (ICML 2020) Overfitting in adversarially robust deep learning [\[paper\]](https://proceedings.mlr.press/v119/rice20a/rice20a.pdf)
- (NIPS 2020) Robust Recovery via Implicit Bias of Discrepant Learning Rates for Double Over-parameterization [\[paper\]](https://proceedings.neurips.cc/paper/2020/file/cd42c963390a9cd025d007dacfa99351-Paper.pdf)
- (ICLR 2020) Deep Double Descent: Where Bigger Models and More Data Hurt [\[paper\]](https://openreview.net/pdf?id=B1g5sA4twr)
- (AISTATS 2020) Gradient Descent with Early Stopping is Provably Robust to Label Noise for Overparameterized Neural Networks [\[paper\]](https://proceedings.mlr.press/v108/li20j/li20j.pdf)
- 


#### Forgetting and Machine Unlearning
- (arXiv 2024) Inexact Unlearning Needs More Careful Evaluations to Avoid a False Sense of Privacy [\[paper\]](http://arxiv.org/pdf/2403.01218)
- (ICLR 2024) Machine Unlearning for Image-to-Image Generative Models [\[paper\]](https://openreview.net/pdf?id=9hjVoPWPnh)
- (arXiv 2023) The Curse of Recursion: Training on Generated Data Makes Models Forget [\[paper\]](https://arxiv.org/pdf/2305.17493)
- (ICLR 2023) Measuring Forgetting of Memorized Training Examples [\[paper\]](https://openreview.net/pdf?id=7bJizxLKrR)
- (NeurIPS 2023) Model Sparsity Can Simplify Machine Unlearning [\[paper\]](https://openreview.net/pdf?id=0jZH883i34)
- (NeurIPS 2022) Characterizing Datapoints via Second-Split Forgetting [\[paper\]](https://openreview.net/pdf?id=yKDKNzjHg8N)
- (ICLR 2019) An Empirical Study of Example Forgetting during Deep Neural Network Learning [\[paper\]](https://openreview.net/pdf?id=BJlxm30cKm)
- (IJCNN 2020) On Catastrophic Forgetting and Mode Collapse in Generative Adversarial Networks [\[paper\]](https://arxiv.org/pdf/1807.04015)
- (PNAS 2017) Overcoming catastrophic forgetting in neural networks [\[paper\]](https://arxiv.org/pdf/1612.00796)


### Membership Inference Attack
#### Membership Inference Attack, Improvements and Interpretations
- (ICML 2024) Low-Cost High-Power Membership Inference by Boosting Relativity [\[paper\]](https://openreview.net/pdf?id=dRel8fuUK4)
- (ICML 2024) Mitigating Privacy Risk in Membership Inference by Convex-Concave Loss [\[paper\]](https://arxiv.org/pdf/2402.05453)
- (ICLR 2024) Leave-one-out Distinguishability in Machine Learning [\[paper\]](https://openreview.net/pdf?id=9RNfX0ah0K)
- (arXiv 2024) Privacy Backdoors: Enhancing Membership Inference through Poisoning Pre-trained Models. [\[paper\]](https://arxiv.org/pdf/2404.01231)
- (AAAI 2023) Why Does Differential Privacy with Large Epsilon Defend Against Practical Membership Inference Attacks? [\[paper\]](https://arxiv.org/pdf/2402.09540)
- (IEEE CSF 2023) Investigating Membership Inference Attacks under Data Dependencies [\[paper\]](https://arxiv.org/pdf/2010.12112)
- (NeurIPS 2023) Scalable membership inference attacks via quantile regression [\[paper\]](https://openreview.net/pdf?id=t3WCiGjHqd)
- (ICLR 2023) Canary in a Coalmine: Better Membership Inference with Ensembled Adversarial Queries [\[paper\]](https://arxiv.org/pdf/2210.10750)
- (AISTATS 2023) A Blessing of Dimensionality in Membership Inference through Regularization [\[paper\]](https://proceedings.mlr.press/v206/tan23b/tan23b.pdf)
- (ICLR 2022) On the Importance of Difficulty Calibration in Membership Inference Attacks [\[paper\]](https://arxiv.org/pdf/2111.08440)
- (IEEE S&P 2022) Membership Inference Attacks From First Principles [\[paper\]](https://arxiv.org/abs/2112.03570v2)
- (CCS 2022) Enhanced Membership Inference Attacks against Machine Learning Models [\[paper\]](https://dl.acm.org/doi/10.1145/3548606.3560675)
- (IEEE CSF 2018) Privacy Risk in Machine Learning: Analyzing the Connection to Overfitting [\[paper\]](https://arxiv.org/abs/1709.01604)
- (IEEE S&P 2017) Membership Inference Attacks against Machine Learning Models [\[paper\]](http://arxiv.org/abs/1610.05820)
- (ACM Computing Surveys 2022) Membership Inference Attacks on Machine Learning: A Survey [\[paper\]](https://dl.acm.org/doi/10.1145/3523273)



#### Membership Inference Attack in Specific Scenarios
##### Diffusion Models
- (ICML 2024) Membership Inference Attacks on Diffusion Models via Quantile Regression [\[paper\]](https://arxiv.org/pdf/2312.05140)
- (ICLR 2024) An Efficient Membership Inference Attack for the Diffusion Model by Proximal Initialization [\[paper\]](https://openreview.net/pdf?id=rpH9FcCEV6)
- (WACV 2024) Towards More Realistic Membership Inference Attacks on Large Diffusion Models [\[paper\]](https://openaccess.thecvf.com/content/WACV2024/papers/Dubinski_Towards_More_Realistic_Membership_Inference_Attacks_on_Large_Diffusion_Models_WACV_2024_paper.pdf)
- (arXiv 2023) White-box Membership Inference Attacks against Diffusion Models [\[paper\]](https://arxiv.org/pdf/2308.06405)
- (ICML 2023) Are Diffusion Models Vulnerable to Membership Inference Attacks? [\[paper\]](https://arxiv.org/pdf/2302.01316)
- (IEEE S&P Workshops 2023) Membership Inference Attacks against Diffusion Models [\[paper\]](https://arxiv.org/pdf/2302.03262)


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
- (NIPS 2021) A Geometric Analysis of Neural Collapse with Unconstrained Features [\[paper\]](https://proceedings.neurips.cc/paper_files/paper/2021/file/f92586a25bb3145facd64ab20fd554ff-Paper.pdf)

### Data Pruning/Data Condensation/Data Selection/Example Hardness
- (ICML 2024) Ameliorate Spurious Correlations in Dataset Condensation [\[paper\]]
- (ICLR 2024) On the Joint Interaction of Models, Data, and Features [\[paper\]](https://openreview.net/pdf?id=ze7DOLi394)
- (NeurIPS 2023) Data pruning and neural scaling laws: fundamental limitations of score-based algorithms [\[paper\]](http://arxiv.org/pdf/2302.06960)
- (NeurIPS 2022) Characterizing Datapoints via Second-Split Forgetting [\[paper\]](https://openreview.net/pdf?id=yKDKNzjHg8N)
- (NeurIPS 2022) Lottery Tickets on a Data Diet: Finding Initializations with Sparse Trainable Networks [\[paper\]](https://proceedings.neurips.cc/paper_files/paper/2022/file/77dd8e90fe833eba5fae86cf017d7a56-Paper-Conference.pdf)
- (NeurIPS 2021) Deep Learning on a Data Diet: Finding Important Examples Early in Training [\[paper\]](https://openreview.net/pdf?id=Uj7pF-D-YvT)
- (ICLR 2020) Estimating informativeness of samples with Smooth Unique Information [\[paper\]](https://openreview.net/pdf?id=kEnBH98BGs5)


### Noisy Learning
- (ICML 2023) CrossSplit: Mitigating Label Noise Memorization through Data Splitting [\[paper\]](https://openreview.net/pdf?id=yeF3FMIIpm)
- (ICML 2023) Mitigating Memorization of Noisy Labels by Clipping the Model Prediction [\[paper\]](https://openreview.net/pdf?id=g0ofsq1NRL)
- (ICLR 2021) Robust early-learning: Hindering the memorization of noisy labels [\[paper\]](https://openreview.net/pdf?id=Eql5b1_hTE4)
- (NIPS 2021) Understanding and Improving Early Stopping for Learning with Noisy Labels [\[paper\]](https://proceedings.neurips.cc/paper_files/paper/2021/file/cc7e2b878868cbae992d1fb743995d8f-Paper.pdf)
- (NeurIPS 2020) Early-Learning Regularization Prevents Memorization of Noisy Labels [\[paper\]](https://proceedings.neurips.cc/paper/2020/file/ea89621bee7c88b2c5be6681c8ef4906-Paper.pdf)

#### Privilage Information
- (ICML 2024) Pi-DUAL: Using privileged information to distinguish clean from noisy labels [\[paper\]](https://arxiv.org/pdf/2310.06600)
- (ICML 2023) When does Privileged Information Explain Away Label Noise? [\[paper\]](https://proceedings.mlr.press/v202/ortiz-jimenez23a/ortiz-jimenez23a.pdf)
- (ICML 2022) Transfer and Marginalize: Explaining Away Label Noise with Privileged Information [\[paper\]](https://arxiv.org/pdf/2202.09244)
- (ICLR 2016) Unifying distillation and privileged information [\[paper\]](https://arxiv.org/pdf/1511.03643)
- (NIPS 2014) Mind the Nuisance: Gaussian Process Classification using Privileged Noise [\[paper\]](https://proceedings.neurips.cc/paper_files/paper/2014/file/6e2713a6efee97bacb63e52c54f0ada0-Paper.pdf)
- (NN 2009) Learning Using Privileged Information: Similarity Control and Knowledge Transfer [\[paper\]](https://www.jmlr.org/papers/volume16/vapnik15b/vapnik15b.pdf)

### Memorization, Generalization and Optimization
- (ICML 2024) Information Complexity of Stochastic Convex Optimization: Applications to Generalization and Memorization [\[paper\]](https://arxiv.org/pdf/2402.09327)

#### Grokking
- (arXiv 2022) Grokking: Generalization Beyond Overfitting on Small Algorithmic Datasets [\[paper\]](https://arxiv.org/pdf/2201.02177)

### Miscellaneous
- Analyzing Leakage of Personally Identifiable Information in Language Models
- (arXiv 2024) Evaluating Model Bias Requires Characterizing its Mistakes [\[paper\]](https://openreview.net/pdf?id=16JbY5O0kS)
- (arXiv 2024) LMD3: Language Model Data Density Dependence [\[paper\]](https://arxiv.org/pdf/2405.06331)
- (arXiv 2024) Investigating Data Contamination for Pre-training Language Models [\[paper\]](https://arxiv.org/pdf/2401.06059)
- (arXiv 2023) Rethinking Benchmark and Contamination for Language Models with Rephrased Samples [\[paper\]](https://arxiv.org/pdf/2311.04850)

