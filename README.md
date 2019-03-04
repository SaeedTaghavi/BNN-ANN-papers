# Papers : Biological and Artificial Neural Networks
ニューラルネットワークの論文のなかで計算神経科学と関係しているもの（の中で **個人的に** 気になったもの）を集めました。重要なのに記載できてない論文がある場合や内容に誤りがある場合、解説を追加していただける場合はIssue または Pull reqからお願いします。

<!--
- [ニューラルネットワークと計算神経科学 (Neural Networks and computational neuroscience)](##ニューラルネットワークと計算神経科学)
  - ([解説](https://github.com/takyamamoto/BNN-ANN-papers/blob/master/%E3%83%8B%E3%83%A5%E3%83%BC%E3%83%A9%E3%83%AB%E3%83%8D%E3%83%83%E3%83%88%E3%83%AF%E3%83%BC%E3%82%AF%E3%81%A8%E8%A8%88%E7%AE%97%E7%A5%9E%E7%B5%8C%E7%A7%91%E5%AD%A6.md))
- [ニューラルネットワークによる神経表現の再現 (Emergence of neural representation in artificial neural networks)](##ニューラルネットによる神経表現の再現)
  - (解説 [[視覚](https://github.com/takyamamoto/BNN-ANN-papers/blob/master/%E8%84%B3%E3%81%AE%E7%A5%9E%E7%B5%8C%E8%A1%A8%E7%8F%BE%E3%81%AE%E5%86%8D%E7%8F%BE_%E8%A6%96%E8%A6%9A.md)] / [[視覚以外](https://github.com/takyamamoto/BNN-ANN-papers/blob/master/%E8%84%B3%E3%81%AE%E7%A5%9E%E7%B5%8C%E8%A1%A8%E7%8F%BE%E3%81%AE%E5%86%8D%E7%8F%BE_%E8%A6%96%E8%A6%9A%E4%BB%A5%E5%A4%96.md)])
- [神経科学に基づいたアーキテクチャ (Neural network architecture based on neuroscience)](##神経科学に基づいたアーキテクチャ)
  - ([解説](https://github.com/takyamamoto/BNN-ANN-papers/blob/master/%E7%A5%9E%E7%B5%8C%E7%A7%91%E5%AD%A6%E3%81%AB%E5%9F%BA%E3%81%A5%E3%81%84%E3%81%9F%E3%82%A2%E3%83%BC%E3%82%AD%E3%83%86%E3%82%AF%E3%83%81%E3%83%A3.md))
- [学習と発達 (Learning and development)](##学習と発達)
- [Brain-computer interface](##Brain-computer interface)
-->

## Artificial neural networks and computational neuroscience
#### Survey
- D. Cox, T. Dean. "Neural networks and neuroscience-inspired computer vision". *Curr. Biol.* **24**(18) 921-929 (2014). ([sciencedirect](https://www.sciencedirect.com/science/article/pii/S0960982214010392?via%3Dihub))
- A. Marblestone, G. Wayne, K. Kording. "Toward an integration of deep learning and neuroscience". (2016). ([arXiv](https://arXiv.org/abs/1606.03813))
- D. Silva, P. Cruz, A. Gutierrez. "Are the long-short term memory and convolution neural net biological system?". *KICS.* **4**(2), 100-106 (2018). ([sciencedirect](https://www.sciencedirect.com/science/article/pii/S2405959518300249))
- N. Kriegeskorte, T. Golan. "Neural network models and deep learning - a primer for biologists". (2019). ([arXiv](https://arxiv.org/abs/1902.04704))

### ニューラルネットワークの解析手法 (Analyzing methods for neural networks)
Methods for understanding of neural representation of ANN.
#### Survey
- D. Barrett, A. Morcos, J. Macke. "Analyzing biological and artificial neural networks: challenges with opportunities for synergy?". (2018). ([arXiv](https://arXiv.org/abs/1810.13373))

#### Canonical correlation analysis (CCA)
- M. Raghu, J. Gilmer, J. Yosinski, J. Sohl-Dickstein. "SVCCA: Singular Vector Canonical Correlation Analysis for Deep Learning Dynamics and Interpretability". *NIPS.* (2017). ([arXiv](https://arXiv.org/abs/1706.05806))
- H. Wang, et al. "Finding the needle in high-dimensional haystack: A tutorial on canonical correlation analysis". (2018). ([arXiv](https://arxiv.org/abs/1812.02598))

#### Fixed point analysis for RNN
- M.B. Ottaway, P.Y. Simard, D.H. Ballard. "Fixed point analysis for recurrent networks". *NIPS.* (1989). ([pdf](https://papers.nips.cc/paper/181-fixed-point-analysis-for-recurrent-networks.pdf))
- D. Sussillo, O. Barak. "Opening the black box: low-dimensional dynamics in high-dimensional recurrent neural networks". *Neural Comput.* **25**(3), 626-649 (2013). ([MIT Press](https://www.mitpressjournals.org/doi/full/10.1162/NECO_a_00409?url_ver=Z39.88-2003&rfr_id=ori:rid:crossref.org&rfr_dat=cr_pub%3dpubmed))
- M.D. Golub, D. Sussillo. "FixedPointFinder: A Tensorflow toolbox for identifying and characterizing fixed points in recurrent neural networks". *JOSS.* (2018). ([pdf](https://web.stanford.edu/~mgolub/publications/GolubJOSS2018.pdf)), ([GitHub](https://github.com/mattgolub/fixed-point-finder))
- G.E. Katz, J.A. Reggia. "Using Directional Fibers to Locate Fixed Points of Recurrent Neural Networks". *IEEE.* (2018). ([IEEE](https://ieeexplore.ieee.org/document/8016349))

#### Others
- M. Haesemeyer, A. Schier, F. Engert. "Convergent temperature representations in artificial and biological neural networks". (2018). ([bioRxiv](https://www.biorxiv.org/content/early/2018/08/29/390435))

### 認知計算神経科学 (Cognitive computational neuroscience)
- N. Kriegeskorte, P. Douglas. "Cognitive computational neuroscience". *Nat. Neurosci.* **21**(9), 1148-1160 (2018). ([arXiv](https://arXiv.org/abs/1807.11819))
- J.S. Bowers. "Parallel Distributed Processing Theory in the Age of Deep Networks". *Trends. Cogn. Sci.* (2019). ([sciencedirect](https://www.sciencedirect.com/science/article/pii/S1364661317302164?via%3Dihub))
- R.M. Cichy, D. Kaiser. "Deep Neural Networks as Scientific Models". *Trends. Cogn. Sci.* (2019). ([sciencedirect](https://www.sciencedirect.com/science/article/pii/S1364661319300348?via%3Dihub))

### 計算論的精神医学 (Computational psychiatry)
(この分野はもっと論文ありますが、追えてません)
- R.E. Hoffman, U. Grasemann, R. Gueorguieva, D. Quinlan, D. Lane, R. Miikkulainen. "Using computational patients to evaluate illness mechanisms in schizophrenia". *Biol. Psychiatry.* **69**(10), 997–1005 (2011). ([PMC](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3105006/))

## Deep neural network as models of the Brain
脳の神経表現の理解は難しい。ニューラルネットワークに特定のタスクを学習（特定の損失関数に対して最適化）させると、脳の神経表現と同じ表現を獲得する場合がある。このとき、間接的に脳の神経表現の目的を知ることができる(Whyの解決手法)。

### 視覚 (Vision)
- D. Zipser, R.A. Andersen. "A back-propagation programmed network that simulates response properties of a subset of posterior parietal neurons". *Nat.* **331**, 679–684 (1988). ([Nat.](https://www.nature.com/articles/331679a0))
- A. Krizhevsky, I. Sutskever, G. Hinton. "ImageNet classification with deep convolutional neural networks". *NIPS* (2012). ([pdf](https://papers.nips.cc/paper/4824-imagenet-classification-with-deep-convolutional-neural-networks.pdf))
  - (cf.) I. Goodfellow, Y. Bengio, A. Courville. "[Deep Learning](https://www.deeplearningbook.org/)". MIT Press. (2016) : Chapter 9.10 "The Neuroscientiﬁc Basis for ConvolutionalNetworks"
- D. Yamins, et al. "Performance-optimized hierarchical models predict neural responses in higher visual cortex". *PNAS.* **111**(23) 8619-8624 (2014). ([PNAS](https://www.pnas.org/content/111/23/8619))
- S. Khaligh-Razavi, N. Kriegeskorte. "Deep supervised, but not unsupervised, models may explain IT cortical representation". *PLoS Comput. Biol*. **10**(11), (2014). ([PLOS](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1003915))
- U. Güçlü, M.A.J. van Gerven. "Deep Neural Networks Reveal a Gradient in the Complexity of Neural Representations across the Ventral Stream". *J. Neurosci.* **35**(27), (2015). ([J. Neurosci.](http://www.jneurosci.org/content/35/27/10005))
- K.M. Jozwik, N. Kriegeskorte, K.R. Storrs, M. Mur. "Deep Convolutional Neural Networks Outperform Feature-Based But Not Categorical Models in Explaining Object Similarity Judgments". *Front. Psychol*. (2017). ([Front. Psychol](https://www.frontiersin.org/articles/10.3389/fpsyg.2017.01726/full))
- C. J. Spoerer, P. McClure, N. Kriegeskorte. "Recurrent Convolutional Neural Networks: A Better Model of Biological Object Recognition". *Front. Psychol.* (2017). ([Front. Psychol](https://www.frontiersin.org/articles/10.3389/fpsyg.2017.01551/full))
- M.N.U. Laskar, L.G.S. Giraldo, O. Schwartz. "Correspondence of Deep Neural Networks and the Brain for Visual Textures". (2018). ([arXiv](https://arxiv.org/abs/1806.02888))
- I. Kuzovkin, et al. "Activations of Deep Convolutional Neural Network are Aligned with Gamma Band Activity of Human Visual Cortex". *Commun. Biol.* **1** (2018). ([Commun. Biol.](https://www.nature.com/articles/s42003-018-0110-y))
- M. Schrimpf, et al. "Brain-Score: Which Artificial Neural Network for Object Recognition is most Brain-Like?". (2018). ([bioRxiv](https://www.biorxiv.org/content/early/2018/09/05/407007))
- E. Kim, D. Hannan, G. Kenyon. "Deep Sparse Coding for Invariant Multimodal Halle Berry Neurons". *CVPR.* (2018). ([arXiv](https://arXiv.org/abs/1711.07998))
- S. Ocko, J. Lindsey, S. Ganguli, S. Deny. "The emergence of multiple retinal cell types through efficient coding of natural movies". (2018). ([bioRxiv](https://www.biorxiv.org/content/early/2018/10/31/458737))
- Q. Yan, et al. "Revealing Fine Structures of the Retinal Receptive Field by Deep Learning Networks". (2018). ([arXiv](https://arXiv.org/abs/1811.02290))
- A. Nayebi, D. Bear, J. Kubilius, K. Kar, S. Ganguli, D. Sussillo, J. DiCarlo, D. Yamins. "Task-Driven Convolutional Recurrent Models of the Visual System". (2018). ([arXiv](https://arXiv.org/abs/1807.00053))
- J. Lindsey, S. Ocko, S. Ganguli, S. Deny. "A Unified Theory of Early Visual Representations from Retina to Cortex through Anatomically Constrained Deep CNNs". (2019). ([arXiv](https://arXiv.org/abs/1901.00945))

#### Recursive Cortical Network (RCN)
This is non NN model.
- D. George, et al. "A generative vision model that trains with high data efficiency and breaks text-based CAPTCHAs". *Science* (2017). ([Science](http://science.sciencemag.org/content/358/6368/eaag2612.full)), ([GitHub](https://github.com/vicariousinc/science_rcn))

#### ResNetの考察
- Q. Liao, T. Poggio. "Bridging the Gaps Between Residual Learning, Recurrent Neural Networks and Visual Cortex". ([arXiv](https://arXiv.org/abs/1604.03640))

### 聴覚野 (Auditory cortex)
- U. Güçlü, J. Thielen, M. Hanke, M. van Gerven. "Brains on Beats". *NIPS* (2016) ([arXiv](https://arxiv.org/abs/1606.02627))
- A.J.E. Kell,D.L.K. Yamins,E.N. Shook, S.V. Norman-Haignere, J.H.McDermott. "A Task-Optimized Neural Network Replicates Human Auditory Behavior, Predicts Brain Responses, and Reveals a Cortical Processing Hierarchy". *Neuron* **98**(3), (2018)  ([sciencedirect](https://www.sciencedirect.com/science/article/pii/S0896627318302502?via%3Dihub))

### 運動野 (Motor cortex)
- D. Sussillo, M. Churchland, M. Kaufman, K. Shenoy. "A neural network that finds a naturalistic solution for the production of muscle activity". *Nat. Neurosci.* **18**(7), 1025–1033 (2015). ([PubMed](https://www.ncbi.nlm.nih.gov/pubmed/26075643))

### Spatial coding (Place cells, Grid cells)
- C. Cueva, X. Wei. "Emergence of grid-like representations by training recurrent neural networks to perform spatial localization". *ICLR.* (2018). ([arXiv](https://arXiv.org/abs/1803.07770))
- A. Banino, et al. "Vector-based navigation using grid-like representations in artificial agents". *Nat.* **557**(7705), 429–433 (2018). ([pdf](https://deepmind.com/documents/201/Vector-based%20Navigation%20using%20Grid-like%20Representations%20in%20Artificial%20Agents.pdf))
- J.C.R. Whittington. et al. "Generalisation of structural knowledge in the hippocampal-entorhinal system".  *NIPS.* (2018). ([arXiv](https://arxiv.org/abs/1805.09042))

### Rodent barrel cortex
- C. Zhuang, J. Kubilius, M. Hartmann, D. Yamins. "Toward Goal-Driven Neural Network Models for the Rodent Whisker-Trigeminal System". *NIPS.* (2017). ([arXiv](https://arxiv.org/abs/1706.07555))

### 認知タスク (Cognitive task)
-  H.F. Song, G.R. Yang, X.J. Wang. "Reward-based training of recurrent neural networks for cognitive and value-based tasks". *eLife*. **6** (2017). ([eLife](https://elifesciences.org/articles/21492))
- G.R. Yang, M.R. Joglekar, H.F. Song, W.T. Newsome, X.J. Wang. "Task representations in neural networks trained to perform many cognitive tasks". *Nat. Neurosci.* (2019). ([Nat. Neurosci.](https://www.nature.com/articles/s41593-018-0310-2)) ([GitHub](https://github.com/gyyang/multitask))

### 時間認知 (Time perception)
- N.F. Hardy, V. Goudar, J.L. Romero-Sosa, D.V. Buonomano. "A model of temporal scaling correctly predicts that motor timing improves with speed". *Nat. Commun.* **9** (2018). ([Nat. Commun.](https://www.nature.com/articles/s41467-018-07161-6))
- W. Roseboom, Z. Fountas, K. Nikiforou, D. Bhowmik, M. Shanahan, A. K. Seth. "Activity in perceptual classification networks as a basis for human subjective time perception". *Nat. Commun.* **10** (2019). ([Nat. Commun.](https://www.nature.com/articles/s41467-018-08194-7))

### 短期記憶課題 (short-term memory task)
- K. Rajan, C.D.Harvey, D.W.Tank. "Recurrent Network Models of Sequence Generation and Memory". *Neuron.* **90**(1), 128-142 (2016). ([sciencedirect](https://www.sciencedirect.com/science/article/pii/S0896627316001021?via%3Dihub#fig1))
- A.E. Orhan, W.J. Ma. "Task representations in neural networks trained to perform many cognitive tasks". *Nat. Neurosci.* (2019). ([Nat. Neurosci.](https://www.nature.com/articles/s41593-018-0314-y)) ([GitHub](https://github.com/eminorhan/recurrent-memory))

## 神経科学に基づいたアーキテクチャ (Neural network architecture based on neuroscience)
ニューラルネットワークのアーキテクチャの中で神経科学の知見を取り入れたもの。

### Survey
- D. Hassabis, D. Kumaran, C. Summerfield, M. Botvinick. "Neuroscience-Inspired Artificial Intelligence". *Neuron.* **95**(2), 245-258 (2017).
([sciencedirect](https://www.sciencedirect.com/science/article/pii/S0896627317305093))

### PredNet (Predictive coding network)
- W. Lotter, G. Kreiman, D. Cox. "Deep predictive coding networks for video prediction and unsupervised learning". *ICLR.* (2017). ([arXiv](https://arXiv.org/abs/1605.08104))
- W. Lotter, G. Kreiman, D. Cox. "A neural network trained to predict future video frames mimics critical properties of biological neuronal responses and perception". (2018). ([arXiv](https://arXiv.org/abs/1805.10734))  
- E. Watanabe, A. Kitaoka, K. Sakamoto, M. Yasugi, K. Tanaka. "Illusory Motion Reproduced by Deep Neural Networks Trained for Prediction". *Front. Psychol.* (2018). ([Front. Psychol.](https://www.frontiersin.org/articles/10.3389/fpsyg.2018.00345/full))

#### subLSTM
- R. Costa, Y. Assael, B. Shillingford, N. Freitas, T. Vogels. "Cortical microcircuits as gated-recurrent neural networks". *NIPS.* (2017). ([arXiv](https://arXiv.org/abs/1711.02448))

#### Activation functions
- G.S. Bhumbra. "Deep learning improved by biological activation functions". (2018). ([arXiv](https://arxiv.org/abs/1804.11237))

#### Flexible normalization
- L. Gonzalo, S. Giraldo, O. Schwartz. "Integrating Flexible Normalization into Mid-Level Representations of Deep Convolutional Neural Networks". (2018). ([arXiv](https://arxiv.org/abs/1806.01823))

## 強化学習 (Reinforcement Learning)
（大事な分野なのに最近の研究を追えていません…。)  
- N. Haber, D. Mrowca, L. Fei-Fei, D. Yamins. "Learning to Play with Intrinsically-Motivated Self-Aware Agents". *NIPS.* (2018). ([arXiv](https://arxiv.org/abs/1802.07442))
- J. X. Wang, et al. "Prefrontal cortex as a meta-reinforcement learning system". *Nat. Neurosci.* (2018). ([Nat. Neurosci.](https://www.nature.com/articles/s41593-018-0147-8)), ([bioRxiv](https://www.biorxiv.org/content/10.1101/295964v2)),  ([blog](https://deepmind.com/blog/prefrontal-cortex-meta-reinforcement-learning-system/))

## 学習と発達 (Learning and development)

### 生物学的妥当性のある学習法則 (Biologically plausible learning algorithms)
ニューラルネットワークの強力な学習アルゴリズムである誤差逆伝搬法(Back propagation)は生物学的に妥当である(biological plausible)とは言えない。そこで、生体内でも可能そうな学習方法が考案されている（本当に可能かは議論の余地あり）。
- Y. Bengio, D. Lee, J. Bornschein, T. Mesnard, Z. Lin. "Towards Biologically Plausible Deep Learning". (2015). ([arXiv](https://arXiv.org/abs/1502.04156))
- T. Lillicrap, D. Cownden, D. Tweed, C. Akerman. "Random synaptic feedback weights support error backpropagation for deep learning". *Nat. Commun.* **7** (2016). ([Nat. Commun.](https://www.nature.com/articles/ncomms13276))
- M. Jaderberg, et al. "Decoupled Neural Interfaces using Synthetic Gradients" (2016). ([arXiv](https://arxiv.org/abs/1608.05343))
- B. Scellier, Y. Bengio. "Equilibrium Propagation: Bridging the Gap Between Energy-Based Models and Backpropagation". *Front. Comput. Neurosci.* **11**(24), (2017). ([arXiv](https://arXiv.org/abs/1602.05179))
- N. Ke, A. Goyal, O. Bilaniuk, J. Binas, M. Mozer, C. Pal, Y. Bengio. "Sparse Attentive Backtracking: Temporal CreditAssignment Through Reminding". *NIPS.* (2018). ([arXiv](https://arXiv.org/abs/1809.03702))
- S. Bartunov, A. Santoro, B. Richards, L. Marris, G. Hinton, T. Lillicrap. "Assessing the Scalability of Biologically-Motivated Deep Learning Algorithms and Architectures". *NIPS.* (2018). ([arXiv](https://arXiv.org/abs/1807.04587))
- J. Sacramento, R. P. Costa, Y. Bengio, W. Senn. "Dendritic cortical microcircuits approximate the backpropagation algorithm". *NIPS.* (2018). ([arXiv](https://arXiv.org/abs/1810.11393))
- A. Nøkland, L.H. Eidnes. "Training Neural Networks with Local Error Signals".  (2019). ([arXiv](https://arXiv.org/abs/1901.06656)) ([GitHub](https://github.com/anokland/local-loss))

#### Survey
- J. Whittington, R. Bogacz. "Theories of Error Back-Propagation in the Brain". *Trends. Cogn. Sci.* (2019). ([sciencedirect](https://www.sciencedirect.com/science/article/pii/S1364661319300129?via%3Dihub))

### 言語学習 (Language learning)
- B.M. Lake, T. Linzen, M. Baroni. "Human few-shot learning of compositional instructions". (2019). ([arXiv](https://arxiv.org/abs/1901.04587))
- A. Alamia, V. Gauducheau, D. Paisios, R. VanRullen. "Which Neural Network Architecture matches Human Behavior in Artificial Grammar Learning?". (2019). ([arXiv](https://arxiv.org/abs/1902.04861))

### ニューラルネットワークと脳の発達 (Development of neural networks and brains)
- A.M. Saxe, J. L. McClelland, S. Ganguli. "A mathematical theory of semantic development in deep neural networks". (2018). ([arXiv](https://arXiv.org/abs/1810.10531))
- J. Shen, M. D. Petkova, F. Liu, C. Tang. "Toward deciphering developmental patterning with deep neural network". (2018). ([bioRxiv](https://www.biorxiv.org/content/early/2018/08/09/374439))

## Brain Decoding & Brain-machine interface
- E. Matsuo, I. Kobayashi, S. Nishimoto, S. Nishida, H. Asoh. "Generating Natural Language Descriptions for Semantic Representations of Human Brain Activity". *ACL SRW.* (2016). ([ACL Anthology](https://aclanthology.info/papers/P16-3004/p16-3004))
- Y. Güçlütürk, U. Güçlü, K. Seeliger, S.E.Bosch, R.J. van Lier, M.A.J. van Gerven. "Reconstructing perceived faces from brain activations with deep adversarial neural decoding". *NIPS* (2017). ([NIPS](https://papers.nips.cc/paper/7012-reconstructing-perceived-faces-from-brain-activations-with-deep-adversarial-neural-decoding))
- R. Rao. "Towards Neural Co-Processors for the Brain: Combining Decoding and Encoding in Brain-Computer Interfaces". (2018). ([arXiv](https://arxiv.org/abs/1811.11876))
- G. Shen, T. Horikawa, K. Majima, Y. Kamitani. "Deep image reconstruction from human brain activity". *PLOS* (2019). ([PLOS](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1006633))
