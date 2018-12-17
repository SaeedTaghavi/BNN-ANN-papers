# Papers : Biological and Artificial Neural Networks
2018年までのニューラルネットワークの論文のなかで計算神経科学と関係しているもの（の中で個人的に気になったもの）を集めました。重要なのに記載できてない論文がある場合はIssueからお願いします。

- [ニューラルネットワークと計算神経科学](## ニューラルネットワークと計算神経科学)
- [ニューラルネットによる脳の神経表現の再現](## ニューラルネットによる脳の神経表現の再現)
- [神経科学に基づいたアーキテクチャ](## 神経科学に基づいたアーキテクチャ)
- [学習と発達](## 学習と発達)

## ニューラルネットワークと計算神経科学
ほとんど総説。

### 全般
- D. Cox, T. Dean. "Neural networks and neuroscience-inspired computer vision". *Curr. Biol.* **24**(18) 921-929 (2014). ([sciencedirect](https://www.sciencedirect.com/science/article/pii/S0960982214010392?via%3Dihub))
- A. Marblestone, G. Wayne, K. Kording. "Toward an integration of deep learning and neuroscience". (2016). ([arxiv](https://arxiv.org/abs/1606.03813))
- D. Silva, P. Cruz, A. Gutierrez. "Are the long-short term memory and convolution neural net biological system?". *KICS.* **4**(2), 100-106 (2018). ([sciencedirect](https://www.sciencedirect.com/science/article/pii/S2405959518300249))

### ニューラルネットワークの解析手法
ニューラルネットワークの神経表現を理解するための手法。Saliency mapとかは触れません。
- D. Barrett, A. Morcos, J. Macke. "Analyzing biological and artificial neural networks: challenges with opportunities for synergy?". (2018). ([arxiv](https://arxiv.org/abs/1810.13373))
- M. Haesemeyer, A. Schier, F. Engert. "Convergent temperature representations in artificial and biological neural networks". (2018). ([bioRxiv](https://www.biorxiv.org/content/early/2018/08/29/390435))

#### SVCCA
- M. Raghu, J. Gilmer, J. Yosinski, J. Sohl-Dickstein. "SVCCA: Singular Vector Canonical Correlation Analysis for Deep Learning Dynamics and Interpretability". *NIPS.* (2017). ([arxiv](https://arxiv.org/abs/1706.05806))

### 認知計算神経科学
N. Kriegeskorte, P. Douglas. "Cognitive computational neuroscience". *Nat. Neurosci.* **21**(9), 1148-1160 (2018). ([arxiv](https://arxiv.org/abs/1807.11819))

## ニューラルネットによる脳の神経表現の再現
脳の神経表現の理解は難しい。ニューラルネットワークに特定のタスクを学習（特定の損失関数に対して最適化）させると、脳の神経表現と同じ表現を獲得する場合がある。このとき、間接的に脳の神経表現の目的を知ることができる(Whyの解決手法)。

### 視覚
ニューラルネットワークが一番成功したといってもいいのが視覚。そのため論文の数も多い。
- D. Yamins, et al. "Performance-optimized hierarchical models predict neural responses in higher visual cortex". *PNAS.* **111**(23) 8619-8624 (2014). ([PNAS](https://www.pnas.org/content/111/23/8619))
- S. Khaligh-Razavi, N. Kriegeskorte. "Deep supervised, but not unsupervised, models may explain IT cortical representation". *PLoS Comput. Biol*. **10**(11), (2014). ([PLOS](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1003915))
- I. Kuzovkin, et al. "Activations of Deep Convolutional Neural Network are Aligned with Gamma Band Activity of Human Visual Cortex". *Commun. Biol.* **1** (2018). ([Commun. Biol.](https://www.nature.com/articles/s42003-018-0110-y))
- M. Schrimpf, et al. "Brain-Score: Which Artificial Neural Network for Object Recognition is most Brain-Like?". (2018). ([bioRxiv](https://www.biorxiv.org/content/early/2018/09/05/407007))
- S. Ocko, J. Lindsey, S. Ganguli, S. Deny. "The emergence of multiple retinal cell types through efficient coding of natural movies". (2018). ([bioRxiv](https://www.biorxiv.org/content/early/2018/10/31/458737))
- Q. Yan, et al. "Revealing Fine Structures of the Retinal Receptive Field by Deep Learning Networks". (2018). ([arxiv](https://arxiv.org/abs/1811.02290))

### 運動野
- D. Sussillo, M. Churchland, M. Kaufman, K. Shenoy. "A neural network that finds a naturalistic solution for the production of muscle activity". *Nat. Neurosci.* **18**(7), 1025–1033 (2015). ([PubMed](https://www.ncbi.nlm.nih.gov/pubmed/26075643))

### 場所受容野
- C. Cueva, X. Wei. "Emergence of grid-like representations by training recurrent neural networks to perform spatial localization". *ICLR.* (2018). ([arxiv](https://arxiv.org/abs/1803.07770))
- A. Banino, et al. "Vector-based navigation using grid-like representations in artificial agents". *Nat.* **557**(7705), 429–433 (2018). ([pdf](https://deepmind.com/documents/201/Vector-based%20Navigation%20using%20Grid-like%20Representations%20in%20Artificial%20Agents.pdf))

### おばあさん細胞
- E. Kim, D. Hannan, G. Kenyon. "Deep Sparse Coding for Invariant Multimodal Halle Berry Neurons". *CVPR.* (2018). ([arxiv](https://arxiv.org/abs/1711.07998))

## 神経科学に基づいたアーキテクチャ
ニューラルネットワークのアーキテクチャの中で神経科学の知見を取り入れたもの。強化学習系は思いっきり見落としてる気がします。

### 全般
- D. Hassabis, D. Kumaran, C. Summerfield, M. Botvinick. "Neuroscience-Inspired Artificial Intelligence". *Neuron.* **95**(2), 245-258 (2017).
([sciencedirect](https://www.sciencedirect.com/science/article/pii/S0896627317305093))

### PredNet
- W. Lotter, G. Kreiman, D. Cox. "Deep predictive coding networks for video prediction and unsupervised learning". *ICLR.* (2017). ([arxiv](https://arxiv.org/abs/1605.08104))

#### PredNetの分析
- W. Lotter, G. Kreiman, D. Cox. "A neural network trained to predict future video frames mimics critical properties of biological neuronal responses and perception". (2018). ([arxiv](https://arxiv.org/abs/1805.10734))  
- E. Watanabe, A. Kitaoka, K. Sakamoto, M. Yasugi, K. Tanaka. "Illusory Motion Reproduced by Deep Neural Networks Trained for Prediction". *Front. Psychol.* (2018). ([Front. Psychol.](https://www.frontiersin.org/articles/10.3389/fpsyg.2018.00345/full))

### subLSTM
R. Costa, Y. Assael, B. Shillingford, N. Freitas, T. Vogels. "Cortical microcircuits as gated-recurrent neural networks". *NIPS.* (2017). ([arxiv](https://arxiv.org/abs/1711.02448))

## 学習と発達

### 生物学的妥当性のある学習法則
ニューラルネットワークの強力な学習アルゴリズムである誤差逆伝搬法(Back propagation)は生物学的に妥当である(biological plausible)とは言えない。そこで、生体内でも可能と言えそうな学習方法が考案されている。
- Y. Bengio, D. Lee, J. Bornschein, T. Mesnard, Z. Lin. "Towards Biologically Plausible Deep Learning". (2015). ([arxiv](https://arxiv.org/abs/1502.04156))
- T. Lillicrap, D. Cownden, D. Tweed, C. Akerman. "Random synaptic feedback weights support error backpropagation for deep learning". *Nat. Commun.* **7** (2016). ([Nat. Commun.](https://www.nature.com/articles/ncomms13276))
- B. Scellier, Y. Bengio. "Equilibrium Propagation: Bridging the Gap Between Energy-Based Models and Backpropagation". *Front. Comput. Neurosci.* **11**(24), (2017). ([arxiv](https://arxiv.org/abs/1602.05179))
- N. Ke, A. Goyal, O. Bilaniuk, J. Binas, M. Mozer, C. Pal, Y. Bengio. "Sparse Attentive Backtracking: Temporal CreditAssignment Through Reminding". *NIPS.* (2018). ([arxiv](https://arxiv.org/abs/1809.03702))
- S. Bartunov, A. Santoro, B. Richards, L. Marris, G. Hinton, T. Lillicrap. "Assessing the Scalability of Biologically-Motivated Deep Learning Algorithms and Architectures". *NIPS.* (2018). ([arxiv](https://arxiv.org/abs/1807.04587))
- J. Sacramento, R. P. Costa, Y. Bengio, W. Senn. "Dendritic cortical microcircuits approximate the backpropagation algorithm". *NIPS.* (2018). ([arxiv](https://arxiv.org/abs/1810.11393))

### ニューラルネットワークと脳の発達
「発達」というのは技術的発達ではなく、幼児の脳が如何にして成人と同じような脳機能を獲得するか、ということの発達。
- A. M. Saxe, J. L. McClelland, S. Ganguli. "A mathematical theory of semantic development in deep neural networks". (2018). ([arxiv](https://arxiv.org/abs/1810.10531))
- J. Shen, M. D. Petkova, F. Liu, C. Tang. "Toward deciphering developmental patterning with deep neural network". (2018). ([bioRxiv](https://www.biorxiv.org/content/early/2018/08/09/374439))
