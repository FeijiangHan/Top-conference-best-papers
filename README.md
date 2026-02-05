# Top-Conference-Best-Papers
This repo collects Best Paper award papers from ICLR, NeurIPS, ICML, ACL, EMNLP, NAACL, AAAI, etc., from 2022 to 2026.

## Preface

I put this repo together for a simple reason: as a young researcher, I want to develop better research taste.

Reading these Best Paper winners made one thing obvious to me. Compared to truly top-tier work, a lot of my past research still falls short in terms of framing, ambition, and real-world impact.

To be honest, I used to mainly follow papers in my own niche or whatever looked new and interesting. At conferences, I’d often skip orals and just go straight to posters I liked. I rarely paid attention to award papers. But after organizing and reviewing them, I realized they’re worth reading regularly even when they’re outside your exact area.

One big benefit is getting a higher-level view of how the field evolves. You can start to see the shifts in trends and research styles, and then think more clearly about what might come next. Here’s a rough (and very personal) summary of the themes I noticed each year:

- 2022: The foundation of modern generative AI and diffusion dominating the scene
- 2023: Alignment concerns, emergence, and mechanistic understanding
- 2024: Multimodal unification, self-improvement, and a return to linguistic perspectives
- 2025: Deep safety, efficiency-first thinking, and early signs of homogenization
- 2026: A new synthesis around logic, causality, and embodiment

Another thing I’ve learned from these papers is craftsmanship. Many of them are extremely strong in writing and experimental design. They don’t just have a good idea; they explain why it matters, set up the story cleanly, and build experiments that can survive serious reviewer pushback. That’s a very different skill from simply polishing a “nice story” around something trivial. If you read too many of the latter, it’s easy to develop the wrong instincts.

There are already similar repos on GitHub, but this one focuses more on the post-2022 “post-GPT era” and puts extra emphasis on NLP venues.

## How to use this list

I’ve found this list is most useful if you go through it twice.

Pass 1: zoom out (build taste and spot trends).
Skim broadly across years and venues, and use AI to quickly summarize for each paper: what area it’s in, what it actually does, the key takeaway, and most importantly, why it might have won. From that, you can sketch a simple “research map” of how topics and methods shift over time, what the top groups keep betting on, and where your own work sits relative to that.

Pass 2: zoom in (learn how winners think and write).
Pick papers close to your own area and read them carefully. The goal is not to copy details, but to ask: “In the same problem space, why didn’t I think of this?” I like using an LLM to backtrack the likely chain of reasoning that led to the idea, then study how the paper frames the story and designs the experiments. Try to step back from the math and implementation and learn the author’s taste: what they chose to emphasize, what they cut, and how they made the contribution feel inevitable.

If you do both passes, you get two things at once: a better sense of the field’s direction, and a clearer standard for what “high-impact” work looks like.

Note: To keep this list concise and focused, I left out some Outstanding Paper nominations since there are far more of them than Best Paper winners.

# Best Papers from Top-Conference

## ICLR

### Outstanding Papers 2025

* Safety Alignment Should be Made More Than Just a Few Tokens Deep (ICLR 2025) 
  [[Paper](https://openreview.net/forum?id=6Mxhg9PtDE)]<br>
  *Authors: Xiangyu Qi, Ashwinee Panda, Kaifeng Lyu, Xiao Ma, Subhrajit Roy, Ahmad Beirami, Prateek Mittal, Peter Henderson*

* Learning Dynamics of LLM Finetuning (ICLR 2025) 
  [[Paper](https://openreview.net/forum?id=tPNHOoZFl9)]<br>
  *Authors: Yi Ren, Danica J. Sutherland*

* AlphaEdit: Null-Space Constrained Model Editing for Language Models (ICLR 2025) 
  [[Paper](https://openreview.net/forum?id=HvSytvg3Jh)]<br>
  *Authors: Junfeng Fang, Houcheng Jiang, Kun Wang, Yunshan Ma, Jie Shi, Xiang Wang, Xiangnan He, Tat-Seng Chua*

#### Outstanding Paper Honorable Mentions

* Data Shapley in One Training Run (ICLR 2025) 
  [[Paper](https://openreview.net/forum?id=HD6bWcj87Y)]<br>
  *Authors: Jiachen T. Wang, Prateek Mittal, Dawn Song, Ruoxi Jia*

* SAM 2: Segment Anything in Images and Videos (ICLR 2025) 
  [[Paper](https://openreview.net/forum?id=Ha6RTeWMd0)]<br>
  *Authors: Nikhila Ravi, Valentin Gabeur, Yuan-Ting Hu, Ronghang Hu, Chaitanya Ryali, Tengyu Ma, Haitham Khedr, Roman Rädle, Chloe Rolland, Laura Gustafson, Eric Mintun, Junting Pan, Kalyan Vasudev Alwala, Nicolas Carion, Chao-Yuan Wu, Ross Girshick, Piotr Dollar, Christoph Feichtenhofer*

* Faster Cascades via Speculative Decoding (ICLR 2025) 
  [[Paper](https://openreview.net/forum?id=vo9t20wsmd)]<br>
  *Authors: Harikrishna Narasimhan, Wittawat Jitkrittum, Ankit Singh Rawat, Seungyeon Kim, Neha Gupta, Aditya Krishna Menon, Sanjiv Kumar*

#### Test of Time

* Adam: A Method for Stochastic Optimization (ICLR 2015) 
  [[Paper](https://arxiv.org/abs/1412.6980)]<br>
  *Authors: Diederik P. Kingma, Jimmy Ba*

#### Test of Time Runner Up

* Neural Machine Translation by Jointly Learning to Align and Translate (ICLR 2015) 
  [[Paper](https://arxiv.org/abs/1409.0473)]<br>
  *Authors: Dzmitry Bahdanau, Kyunghyun Cho, Yoshua Bengio*

### Outstanding Papers 2024

* Generalization in diffusion models arises from geometry-adaptive harmonic representations (ICLR 2024) 
  [[Paper](https://openreview.net/forum?id=ANvmVS2Yr0)]<br>
  *Authors: Zahra Kadkhodaie, Florentin Guth, Eero P Simoncelli, Stéphane Mallat*

* Learning Interactive Real-World Simulators (ICLR 2024) 
  [[Paper](https://openreview.net/forum?id=sFyTZEqmUY)]<br>
  *Authors: Sherry Yang, Yilun Du, Seyed Kamyar Seyed Ghasemipour, Jonathan Tompson, Leslie Pack Kaelbling, Dale Schuurmans, Pieter Abbeel*

* Never Train from Scratch: Fair Comparison of Long-Sequence Models Requires Data-Driven Priors (ICLR 2024) 
  [[Paper](https://openreview.net/forum?id=PdaPky8MUn)]<br>
  *Authors: Ido Amos, Jonathan Berant, Ankit Gupta*

* Protein Discovery with Discrete Walk-Jump Sampling (ICLR 2024) 
  [[Paper](https://openreview.net/forum?id=zMPHKOmQNb)]<br>
  *Authors: Nathan C. Frey, Dan Berenberg, Karina Zadorozhny, Joseph Kleinhenz, Julien Lafrance-Vanasse, Isidro Hotzel, Yan Wu, Stephen Ra, Richard Bonneau, Kyunghyun Cho, Andreas Loukas, Vladimir Gligorijevic, Saeed Saremi*

* Vision Transformers Need Registers (ICLR 2024) 
  [[Paper](https://openreview.net/forum?id=2dnO3LLiJ1)]<br>
  *Authors: Timothée Darcet, Maxime Oquab, Julien Mairal, Piotr Bojanowski*

#### Outstanding Paper Honorable Mentions

* Amortizing intractable inference in large language models (ICLR 2024) 
  [[Paper](https://openreview.net/forum?id=Ouj6p4ca60)]<br>
  *Authors: Edward J Hu, Moksh Jain, Eric Elmoznino, Younesse Kaddar, Guillaume Lajoie, Yoshua Bengio, Nikolay Malkin*

* Approximating Nash Equilibria in Normal-Form Games via Stochastic Optimization (ICLR 2024) 
  [[Paper](https://openreview.net/forum?id=cc8h3I3V4E)]<br>
  *Authors: Ian Gemp, Luke Marris, Georgios Piliouras*

* Beyond Weisfeiler-Lehman: A Quantitative Framework for GNN Expressiveness (ICLR 2024) 
  [[Paper](https://openreview.net/forum?id=HSKaGOi7Ar)]<br>
  *Authors: Bohang Zhang, Jingchu Gai, Yiheng Du, Qiwei Ye, Di He, Liwei Wang*

* Flow Matching on General Geometries (ICLR 2024) 
  [[Paper](https://openreview.net/forum?id=g7ohDlTITL)]<br>
  *Authors: Ricky T. Q. Chen, Yaron Lipman*

* Is ImageNet worth 1 video? Learning strong image encoders from 1 long unlabelled video (ICLR 2024) 
  [[Paper](https://openreview.net/forum?id=Yen1lGns2o)]<br>
  *Authors: Shashanka Venkataramanan, Mamshad Nayeem Rizve, Joao Carreira, Yuki M Asano, Yannis Avrithis*

* Meta Continual Learning Revisited: Implicitly Enhancing Online Hessian Approximation via Variance Reduction (ICLR 2024) 
  [[Paper](https://openreview.net/forum?id=TpD2aG1h0D)]<br>
  *Authors: Yichen Wu, Long-Kai Huang, Renzhen Wang, Deyu Meng, Ying Wei*

* Model Tells You What to Discard: Adaptive KV Cache Compression for LLMs (ICLR 2024) 
  [[Paper](https://openreview.net/forum?id=uNrFpDPMyo)]<br>
  *Authors: Suyu Ge, Yunan Zhang, Liyuan Liu, Minjia Zhang, Jiawei Han, Jianfeng Gao*

* Proving Test Set Contamination in Black-Box Language Models (ICLR 2024) 
  [[Paper](https://openreview.net/forum?id=KS8mIvetg2)]<br>
  *Authors: Yonatan Oren, Nicole Meister, Niladri S. Chatterji, Faisal Ladhak, Tatsunori Hashimoto*

* Robust agents learn causal world models (ICLR 2024) 
  [[Paper](https://openreview.net/forum?id=pOoKI3ouv1)]<br>
  *Authors: Jonathan Richens, Tom Everitt*

* The mechanistic basis of data dependence and abrupt learning in an in-context classification task (ICLR 2024) 
  [[Paper](https://openreview.net/forum?id=aN4Jf6Cx69)]<br>
  *Authors: Gautam Reddy*

* Towards a statistical theory of data selection under weak supervision (ICLR 2024) 
  [[Paper](https://openreview.net/forum?id=HhfcNgQn6p)]<br>
  *Authors: Germain Kolossov, Andrea Montanari, Pulkit Tandon*

#### Test of Time

* Auto-Encoding Variational Bayes (ICLR 2014) 
  [[Paper](https://arxiv.org/abs/1312.6114)]<br>
  *Authors: Diederik Kingma, Max Welling*

#### Test of Time Runner Up

* Intriguing properties of neural networks (ICLR 2014) 
  [[Paper](https://arxiv.org/abs/1312.6199)]<br>
  *Authors: Christian Szegedy, Wojciech Zaremba, Ilya Sutskever, Joan Bruna, Dumitru Erhan, Ian Goodfellow, Rob Fergus*
  
  

### Outstanding Papers 2023

* Universal Few-shot Learning of Dense Prediction Tasks with Visual Token Matching (ICLR 2023) 
  [[Paper](https://openreview.net/forum?id=88nT0j5jAn)]<br>
  *Authors: Donggyun Kim, Jinwoo Kim, Seongwoong Cho, Chong Luo, Seunghoon Hong*

* Rethinking the Expressive Power of GNNs via Graph Biconnectivity (ICLR 2023) 
  [[Paper](https://openreview.net/forum?id=r9hNv76KoT3)]<br>
  *Authors: Bohang Zhang, Shengjie Luo, Liwei Wang, Di He*

* DreamFusion: Text-to-3D using 2D Diffusion (ICLR 2023) 
  [[Paper](https://openreview.net/forum?id=FjNys5c7VyY)]<br>
  *Authors: Ben Poole, Ajay Jain, Jonathan T. Barron, Ben Mildenhall*

* Emergence of Maps in the Memories of Blind Navigation Agents (ICLR 2023) 
  [[Paper](https://openreview.net/forum?id=lTt4KjHSsyl)]<br>
  *Authors: Erik Wijmans, Manolis Savva, Irfan Essa, Stefan Lee, Ari S. Morcos, Dhruv Batra*

#### Outstanding Paper Honorable Mentions

* Towards Understanding Ensemble, Knowledge Distillation and Self-Distillation in Deep Learning (ICLR 2023) 
  [[Paper](https://openreview.net/forum?id=Uuf2q9TfXGA)]<br>
  *Authors: Zeyuan Allen-Zhu, Yuanzhi Li*

* Mastering the Game of No-Press Diplomacy via Human-Regularized Reinforcement Learning and Planning (ICLR 2023) 
  [[Paper](https://openreview.net/forum?id=F61FwJTZhb)]<br>
  *Authors: Anton Bakhtin, David J Wu, Adam Lerer, Jonathan Gray, Athul Paul Jacob, Gabriele Farina, Alexander H Miller, Noam Brown*

* On the duality between contrastive and non-contrastive self-supervised learning (ICLR 2023) 
  [[Paper](https://openreview.net/forum?id=kDEL91Dufpa)]<br>
  *Authors: Quentin Garrido, Yubei Chen, Adrien Bardes, Laurent Najman, Yann LeCun*

* Conditional Antibody Design as 3D Equivariant Graph Translation (ICLR 2023) 
  [[Paper](https://openreview.net/forum?id=LFHFQbjxIiP)]<br>
  *Authors: Xiangzhe Kong, Wenbing Huang, Yang Liu*

* Disentanglement with Biological Constraints: A Theory of Functional Cell Types (ICLR 2023) 
  [[Paper](https://openreview.net/forum?id=9Z_GfhZnGH)]<br>
  *Authors: James C. R. Whittington, Will Dorrell, Surya Ganguli, Timothy Behrens*

### Outstanding Papers 2022

* Analytic-DPM: an Analytic Estimate of the Optimal Reverse Variance in Diffusion Probabilistic Models (ICLR 2022) 
  [[Paper](https://openreview.net/forum?id=0xiJLKH-ufZ)]<br>
  *Authors: Fan Bao, Chongxuan Li, Jun Zhu, Bo Zhang*

* Hyperparameter Tuning with Renyi Differential Privacy (ICLR 2022) 
  [[Paper](https://openreview.net/forum?id=-70L8lpp9DF)]<br>
  *Authors: Nicolas Papernot, Thomas Steinke*

* Learning Strides in Convolutional Neural Networks (ICLR 2022) 
  [[Paper](https://openreview.net/forum?id=M752z9FKJP)]<br>
  *Authors: Rachid Riad, Olivier Teboul, David Grangier, Neil Zeghidour*

* Expressiveness and Approximation Properties of Graph Neural Networks (ICLR 2022) 
  [[Paper](https://openreview.net/forum?id=wIzUeM3TAU)]<br>
  *Authors: Floris Geerts, Juan L Reutter*

* Comparing Distributions by Measuring Differences that Affect Decision Making (ICLR 2022) 
  [[Paper](https://openreview.net/forum?id=KB5onONJIAU)]<br>
  *Authors: Shengjia Zhao, Abhishek Sinha, Yutong (Kelly) He, Aidan Perreault, Jiaming Song, Stefano Ermon*

* Neural Collapse Under MSE Loss: Proximity to and Dynamics on the Central Path (ICLR 2022) 
  [[Paper](https://openreview.net/forum?id=w1UbdvWH_R3)]<br>
  *Authors: X.Y. Han, Vardan Papyan, David L. Donoho*

* Bootstrapped Meta-Learning (ICLR 2022) 
  [[Paper](https://openreview.net/forum?id=b-ny3x071E5)]<br>
  *Authors: Sebastian Flennerhag, Yannick Schroecker, Tom Zahavy, Hado van Hasselt, David Silver, Satinder Singh*

#### Outstanding Paper Honorable Mentions

* Understanding over-squashing and bottlenecks on graphs via curvature (ICLR 2022) 
  [[Paper](https://openreview.net/forum?id=7UmjRGzp-A)]<br>
  *Authors: Jake Topping, Francesco Di Giovanni, Benjamin Paul Chamberlain, Xiaowen Dong, Michael M. Bronstein*

* Efficiently Modeling Long Sequences with Structured State Spaces (ICLR 2022) 
  [[Paper](https://openreview.net/forum?id=uYLFoz1vlAC)]<br>
  *Authors: Albert Gu, Karan Goel, Christopher Re*

* PiCO: Contrastive Label Disambiguation for Partial Label Learning (ICLR 2022) 
  [[Paper](https://openreview.net/forum?id=EhYjZy6e1gJ)]<br>
  *Authors: Haobo Wang, Ruixuan Xiao, Yixuan (Sharon) Li, Lei Feng, Gang Niu, Gang Chen, Junbo Zhao*





## NeurIPS



### Best Papers 2025

#### Best papers:

* Artificial Hivemind: The Open-Ended Homogeneity of Language Models (and Beyond) (NeurIPS 2025) 
  [[Paper](https://arxiv.org/abs/2510.22954)]<br>
  *Authors: Liwei Jiang, Yuanjun Chai, Margaret Li, Mickel Liu, Raymond Fok, Nouha Dziri, Yulia Tsvetkov, Maarten Sap, Yejin Choi*

* Gated Attention for Large Language Models: Non-linearity, Sparsity, and Attention-Sink-Free (NeurIPS 2025) 
  [[Paper](https://arxiv.org/abs/2505.06708)]<br>
  *Authors: Zihan Qiu, Zekun Wang, Bo Zheng, Zeyu Huang, Kaiyue Wen, Songlin Yang, Rui Men, Le Yu, Fei Huang, Suozhi Huang, Dayiheng Liu, Jingren Zhou, Junyang Lin*

* 1000 Layer Networks for Self-Supervised RL: Scaling Depth Can Enable New Goal-Reaching Capabilities (NeurIPS 2025) 
  [[Paper](https://arxiv.org/abs/2503.14858)]<br>
  *Authors: Kevin Wang, Ishaan Javali, Michał Bortkiewicz, Tomasz Trzcinski, Benjamin Eysenbach*


* Why Diffusion Models Don’t Memorize: The Role of Implicit Dynamical Regularization in Training (NeurIPS 2025) 
  [[Paper](https://arxiv.org/abs/2505.17638)]<br>
  *Authors: Tony Bonnaire, Raphaël Urfin, Giulio Biroli, Marc Mezard*

#### Runners ups:

* Does Reinforcement Learning Really Incentivize Reasoning Capacity in LLMs Beyond the Base Model? (NeurIPS 2025) 
  [[Paper](https://arxiv.org/abs/2504.13837)]<br>
  *Authors: Yang Yue, Zhiqi Chen, Rui Lu, Andrew Zhao, Zhaokai Wang, Yang Yue, Shiji Song, Gao Huang*

* Optimal Mistake Bounds for Transductive Online Learning (NeurIPS 2025) 
  [[Paper](https://openreview.net/forum?id=EoebmBe9fG)]<br>
  *Authors: Zachary Chase, Steve Hanneke, Shay Moran, Jonathan Shafer*

* Superposition Yields Robust Neural Scaling (NeurIPS 2025) 
  [[Paper](https://arxiv.org/abs/2505.10465)]<br>
  *Authors: Yizhou Liu, Ziming Liu, Jeff Gore*

#### Test of Time

* Faster R-CNN: Towards Real-Time Object Detection with Region Proposal Networks (NeurIPS 2015) 
  [[Paper](https://arxiv.org/abs/1506.01497)]<br>
  *Authors: Shaoqing Ren, Kaiming He, Ross Girshick, Jian Sun*

#### Sejnowski-Hinton Prize

* Random synaptic feedback weights support error backpropagation for deep learning 
  [[Paper](https://arxiv.org/abs/1411.0247)]<br>
  *Authors: Timothy Lillicrap, Daniel Cownden, Douglas Tweed, and Colin Akerman*



### Best Papers 2024

#### Best papers for the main track:

* Visual Autoregressive Modeling: Scalable Image Generation via Next-Scale Prediction (NeurIPS 2024) 
  [[Paper](https://openreview.net/forum?id=gojL67CfS8)]<br>
  *Authors: Keyu Tian, Yi Jiang, Zehuan Yuan, Bingyue Peng, Liwei Wang*

* Stochastic Taylor Derivative Estimator: Efficient amortization for arbitrary differential operators (NeurIPS 2024) 
  [[Paper](https://openreview.net/forum?id=J2wI2rCG2u)]<br>
  *Authors: Zekun Shi, Zheyuan Hu, Min Lin, Kenji Kawaguchi*

#### Runners ups for the main track:

* Not All Tokens Are What You Need for Pretraining (NeurIPS 2024) 
  [[Paper](https://openreview.net/forum?id=0NMzBwqaAJ)]<br>
  *Authors: Zhenghao Lin, Zhibin Gou, Yeyun Gong, Xiao Liu, Yelong Shen, Ruochen Xu, Chen Lin, Yujiu Yang, Jian Jiao, Nan Duan, Weizhu Chen*

* Guiding a Diffusion Model with a Bad Version of Itself (NeurIPS 2024) 
  [[Paper](https://openreview.net/forum?id=bg6fVPVs3s)]<br>
  *Authors: Tero Karras, Miika Aittala, Tuomas Kynkäänniemi, Jaakko Lehtinen, Timo Aila, Samuli Laine*

#### Best paper for Datasets & Benchmarks track:

* The PRISM Alignment Dataset: What Participatory, Representative and Individualised Human Feedback Reveals About the Subjective and Multicultural Alignment of Large Language Models (NeurIPS 2024) 
  [[Paper](https://openreview.net/forum?id=DFr5hteojx#discussion)]<br>
  *Authors: Hannah Rose Kirk, Alexander Whitefield, Paul Röttger, Andrew Bean, Katerina Margatina, Juan Ciro, Rafael Mosquera, Max Bartolo, Adina Williams, He He, Bertie Vidgen, Scott A. Hale*

#### Test of Time

* Generative Adversarial Nets (NeurIPS 2014) 
  [[Paper](https://arxiv.org/abs/1406.2661)]<br>
  *Authors: Ian Goodfellow, Jean Pouget-Abadie, Mehdi Mirza, Bing Xu, David Warde-Farley, Sherjil Ozair, Aaron Courville, Yoshua Bengio*

* Sequence to Sequence Learning with Neural Networks (NeurIPS 2014) 
  [[Paper](https://arxiv.org/abs/1409.3215)]<br>
  *Authors: Ilya Sutskever, Oriol Vinyals, Quoc V. Le*
  
  

### Outstanding Papers 2023

* Privacy Auditing with One (1) Training Run (NeurIPS 2023) 
  [[Paper](https://arxiv.org/abs/2305.08846)]<br>
  *Authors: Thomas Steinke, Milad Nasr, Matthew Jagielski*

* Are Emergent Abilities of Large Language Models a Mirage? (NeurIPS 2023) 
  [[Paper](https://arxiv.org/abs/2304.15004)]<br>
  *Authors: Rylan Schaeffer · Brando Miranda · Sanmi Koyejo*

#### Outstanding Main Track Runner-Ups:

* Scaling Data-Constrained Language Models (NeurIPS 2023) 
  [[Paper](https://arxiv.org/abs/2305.16264)]<br>
  *Authors: Niklas Muennighoff · Alexander Rush · Boaz Barak · Teven Le Scao · Nouamane Tazi · Aleksandra Piktus · Sampo Pyysalo · Thomas Wolf · Colin Raffel*

* Direct Preference Optimization: Your Language Model is Secretly a Reward Model (NeurIPS 2023) 
  [[Paper](https://arxiv.org/abs/2305.18290)]<br>
  *Authors: Rafael Rafailov · Archit Sharma · Eric Mitchell · Christopher D Manning · Stefano Ermon · Chelsea Finn*

#### Outstanding Datasets and Benchmarks Papers

* ClimSim: A large multi-scale dataset for hybrid physics-ML climate emulation (NeurIPS 2023) 
  [[Paper](https://arxiv.org/abs/2306.08754)]<br>
  *Authors: Sungduk Yu, Walter Hannah, Liran Peng, Jerry Lin, Mohamed Aziz Bhouri, Ritwik Gupta, Björn Lütjens, Justus Christopher Will, Gunnar Behrens, Julius Busecke, Nora Loose, Charles I Stern, Tom Beucler, Bryce Harrop, Benjamin R Hillman, Andrea Jenney, Savannah Ferretti, Nana Liu, Anima Anandkumar, Noah D Brenowitz, Veronika Eyring, Nicholas Geneva, Pierre Gentine, Stephan Mandt, Jaideep Pathak, Akshay Subramaniam, Carl Vondrick, Rose Yu, Laure Zanna, Tian Zheng, Ryan Abernathey, Fiaz Ahmed, David C Bader, Pierre Baldi, Elizabeth Barnes, Christopher Bretherton, Peter Caldwell, Wayne Chuang, Yilun Han, Yu Huang, Fernando Iglesias-Suarez, Sanket Jantre, Karthik Kashinath, Marat Khairoutdinov, Thorsten Kurth, Nicholas Lutsko, Po-Lun Ma, Griffin Mooers, J. David Neelin, David Randall, Sara Shamekh, Mark A Taylor, Nathan Urban, Janni Yuval, Guang Zhang, Michael Pritchard*

* DecodingTrust: A Comprehensive Assessment of Trustworthiness in GPT Models (NeurIPS 2023) 
  [[Paper](https://arxiv.org/abs/2306.11698)]<br>
  *Authors: Boxin Wang, Weixin Chen, Hengzhi Pei, Chulin Xie, Mintong Kang, Chenhui Zhang, Chejian Xu, Zidi Xiong, Ritik Dutta, Rylan Schaeffer, Sang T. Truong, Simran Arora, Mantas Mazeika, Dan Hendrycks, Zinan Lin, Yu Cheng, Sanmi Koyejo, Dawn Song, Bo Li*

#### Test of Time

* Distributed Representations of Words and Phrases and their Compositionality (NeurIPS 2013) 
  [[Paper](https://papers.nips.cc/paper_files/paper/2013/hash/9aa42b31882ec039965f3c4923ce901b-Abstract.html)]<br>
  *Authors: Tomas Mikolov, Ilya Sutskever, Kai Chen, Greg Corrado, and Jeffrey Dean*



### Outstanding Papers 2022

* Is Out-of-distribution Detection Learnable? (NeurIPS 2022) 
  [[Paper](https://openreview.net/forum?id=sde_7ZzGXOE)]<br>
  *Authors: Zhen Fang, Yixuan Li, Jie Lu, Jiahua Dong, Bo Han, Feng Liu*

* Photorealistic Text-to-Image Diffusion Models with Deep Language Understanding (NeurIPS 2022) 
  [[Paper](https://openreview.net/forum?id=08Yk-n5l2Al)]<br>
  *Authors: Chitwan Saharia, William Chan, Saurabh Saxena, Lala Li, Jay Whang, Emily Denton, Seyed Kamyar Seyed Ghasemipour, Burcu Karagol Ayan, S. Sara Mahdavi, Raphael Gontijo-Lopes, Tim Salimans, Jonathan Ho, David J Fleet, Mohammad Norouzi*

* Elucidating the Design Space of Diffusion-Based Generative Models (NeurIPS 2022) 
  [[Paper](https://openreview.net/forum?id=k7FuTOWMOc7)]<br>
  *Authors: Tero Karras, Miika Aittala, Timo Aila, Samuli Laine*

* ProcTHOR: Large-Scale Embodied AI Using Procedural Generation (NeurIPS 2022) 
  [[Paper](https://openreview.net/forum?id=4-bV1bi74M)]<br>
  *Authors: Matt Deitke, Eli VanderBilt, Alvaro Herrasti, Luca Weihs, Kiana Ehsani, Jordi Salvador, Winson Han, Eric Kolve, Aniruddha Kembhavi, Roozbeh Mottaghi*

* Using natural language and program abstractions to instill human inductive biases in machines (NeurIPS 2022) 
  [[Paper](https://openreview.net/forum?id=buXZ7nIqiwE)]<br>
  *Authors: Sreejan Kumar, Carlos G Correa, Ishita Dasgupta, Raja Marjieh, Michael Hu, Robert D. Hawkins, Jonathan Cohen, Nathaniel Daw, Karthik R Narasimhan, Thomas L. Griffiths*

* A Neural Corpus Indexer for Document Retrieval (NeurIPS 2022) 
  [[Paper](https://openreview.net/forum?id=fSfcEYQP_qc)]<br>
  *Authors: Yujing Wang, Yingyan Hou, Haonan Wang, Ziming Miao, Shibin Wu, Hao Sun, Qi Chen, Yuqing Xia, Chengmin Chi, Guoshuai Zhao, Zheng Liu, Xing Xie, Hao Sun, Weiwei Deng, Qi Zhang, Mao Yang*

* High-dimensional limit theorems for SGD: Effective dynamics and critical scaling (NeurIPS 2022) 
  [[Paper](https://openreview.net/forum?id=Q38D6xxrKHe)]<br>
  *Authors: Gerard Ben Arous, Reza Gheissari, Aukosh Jagannath*


* Gradient Descent: The Ultimate Optimizer (NeurIPS 2022) 
  [[Paper](https://openreview.net/forum?id=-Qp-3L-5ZdI)]<br>
  *Authors: Kartik Chandra, Audrey Xie, Jonathan Ragan-Kelley, Erik Meijer*

* Riemannian Score-Based Generative Modelling (NeurIPS 2022) 
  [[Paper](https://openreview.net/forum?id=oDRQGo8I7P)]<br>
  *Authors: Valentin De Bortoli, Emile Mathieu, Michael John Hutchinson, James Thornton, Yee Whye Teh, Arnaud Doucet*

* Gradient Estimation with Discrete Stein Operators (NeurIPS 2022) 
  [[Paper](https://openreview.net/forum?id=I1mkUkaguP)]<br>
  *Authors: Jiaxin Shi, Yuhao Zhou, Jessica Hwang, Michalis Titsias, Lester Mackey*

* An empirical analysis of compute-optimal large language model training (NeurIPS 2022) 
  [[Paper](https://openreview.net/forum?id=iBBcRUlOAPR)]<br>
  *Authors: Jordan Hoffmann, Sebastian Borgeaud, Arthur Mensch, Elena Buchatskaya, Trevor Cai, Eliza Rutherford, Diego de las Casas, Lisa Anne Hendricks, Johannes Welbl, Aidan Clark, Tom Hennigan, Eric Noland, Katherine Millican, George van den Driessche, Bogdan Damoc, Aurelia Guy, Simon Osindero, Karen Simonyan, Erich Elsen, Oriol Vinyals, Jack William Rae, Laurent Sifre*

* Beyond neural scaling laws: beating power law scaling via data pruning (NeurIPS 2022) 
  [[Paper](https://openreview.net/forum?id=UmvSlP-PyV)]<br>
  *Authors: Ben Sorscher, Robert Geirhos, Shashank Shekhar, Surya Ganguli, Ari S. Morcos*

* On-Demand Sampling: Learning Optimally from Multiple Distributions (NeurIPS 2022) 
  [[Paper](https://openreview.net/forum?id=FR289LMkmxZ)]<br>
  *Authors: Nika Haghtalab, Michael Jordan, Eric Zhao*

* LAION-5B: An open large-scale dataset for training next generation image-text models (NeurIPS 2022) 
  [[Paper](https://openreview.net/forum?id=M3Y74vmsMcY)]<br>
  *Authors: Christoph Schuhmann, Romain Beaumont, Richard Vencu, Cade W Gordon, Ross Wightman, Mehdi Cherti, Theo Coombes, Aarush Katta, Clayton Mullis, Mitchell Wortsman, Patrick Schramowski, Srivatsa R Kundurthy, Katherine Crowson, Ludwig Schmidt, Robert Kaczmarczyk, Jenia Jitsev*

* MineDojo: Building Open-Ended Embodied Agents with Internet-Scale Knowledge (NeurIPS 2022) 
  [[Paper](https://openreview.net/forum?id=rc8o_j8I8PX)]<br>
  *Authors: Linxi Fan, Guanzhi Wang, Yunfan Jiang, Ajay Mandlekar, Yuncong Yang, Haoyi Zhu, Andrew Tang, De-An Huang, Yuke Zhu, Anima Anandkumar*

#### Test of Time

* ImageNet Classification with Deep Convolutional Neural Networks (NeurIPS 2012) 
  [[Paper](https://proceedings.neurips.cc/paper/2012/file/c399862d3b9d6b76c8436e924a68c45b-Paper.pdf)]<br>
  *Authors: Alex Krizhevsky, Ilya Sutskever, and Geoffrey Hinton*



## ICML

### Outstanding Papers 2025

* CollabLLM: From Passive Responders to Active Collaborators (ICML 2025) 
  [[Paper](https://arxiv.org/abs/2502.00640)]<br>
  *Authors: Shirley Wu, Michel Galley, Baolin Peng, Hao Cheng, Gavin Li, Yao Dou, Weixin Cai, James Zou, Jure Leskovec, Jianfeng Gao*

* Train for the Worst, Plan for the Best: Understanding Token Ordering in Masked Diffusions (ICML 2025) 
  [[Paper](https://arxiv.org/abs/2502.06768)]<br>
  *Authors: Jaeyeon Kim · Kulin Shah · Vasilis Kontonis · Sham Kakade · Sitan Chen*

* Score Matching with Missing Data (ICML 2025) 
  [[Paper](https://arxiv.org/abs/2506.00557)]<br>
  *Authors: Josh Givens · Song Liu · Henry Reeve*

* Conformal Prediction as Bayesian Quadrature (ICML 2025) 
  [[Paper](https://arxiv.org/abs/2502.13228)]<br>
  *Authors: Jake Snell · Thomas Griffiths*

* Roll the dice & look before you leap: Going beyond the creative limits of next-token prediction (ICML 2025) 
  [[Paper](https://arxiv.org/abs/2504.15266)]<br>
  *Authors: Vaishnavh Nagarajan · Chen Wu · Charles Ding · Aditi Raghunathan*

* The Value of Prediction in Identifying the Worst-Off (ICML 2025) 
  [[Paper](https://arxiv.org/abs/2501.19334)]<br>
  *Authors: Unai Fischer Abaigar · Christoph Kern · Juan Perdomo*

#### Outstanding Position Paper:

* Position: The AI Conference Peer Review Crisis Demands Author Feedback and Reviewer Rewards (ICML 2025) 
  [[Paper](https://arxiv.org/abs/2505.04966)]<br>
  *Authors: Jaeho Kim · Yunseok Lee · Seulki Lee*

* Position: AI Safety should prioritize the Future of Work (ICML 2025) 
  [[Paper](https://arxiv.org/abs/2504.13959)]<br>
  *Authors: Sanchaita Hazra · Bodhisattwa Prasad Majumder · Tuhin Chakrabarty*

#### Test of Time Award:

* Batch Normalization: Accelerating Deep Network Training by Reducing Internal Covariate Shift (ICML 2015) 
  [[Paper](https://arxiv.org/abs/1502.03167)]<br>
  *Authors: Sergey Ioffe · Christian Szegedy*

#### Test of Time Honorable Mention:

* Trust Region Policy Optimization (ICML 2015) 
  [[Paper](https://arxiv.org/abs/1502.05477)]<br>
  *Authors: John Schulman · Sergey Levine · Pieter Abbeel · Michael Jordan · Philipp Moritz*

* Variational Inference with Normalizing Flows (ICML 2015) 
  [[Paper](https://arxiv.org/abs/1505.05770)]<br>
  *Authors: Danilo Jimenez Rezende · Shakir Mohamed*

### Best Papers 2024

* VideoPoet: A Large Language Model for Zero-Shot Video Generation (ICML 2024) 
  [[Paper](https://arxiv.org/abs/2312.14125)]<br>
  *Authors: Dan Kondratyuk · Lijun Yu · Xiuye Gu · Jose Lezama · Jonathan Huang · Grant Schindler · Rachel Hornung · Vighnesh N Birodkar · Jimmy Yan · Ming-Chang Chiu · Krishna Somandepalli · Hassan Akbari · Yair Alon · Yong Cheng · Joshua V Dillon · Agrim Gupta · Meera Hahn · Anja Hauth · David Hendon · Alonso Martinez · David Minnen · Mikhail Sirotenko · Kihyuk Sohn · Xuan Yang · Hartwig Adam · Ming-Hsuan Yang · Irfan Essa · Huisheng Wang · David Ross · Bryan Seybold · Lu Jiang*

* Debating with More Persuasive LLMs Leads to More Truthful Answers (ICML 2024) 
  [[Paper](https://arxiv.org/abs/2402.06782)]<br>
  *Authors: Akbir Khan · John Hughes · Dan Valentine · Laura Ruis · Kshitij Sachan · Ansh Radhakrishnan · Edward Grefenstette · Samuel Bowman · Tim Rocktäschel · Ethan Perez*

* Genie: Generative Interactive Environments (ICML 2024) 
  [[Paper](https://arxiv.org/abs/2402.15391)]<br>
  *Authors: Jake Bruce · Michael Dennis · Ashley Edwards · Jack Parker-Holder · Yuge Shi · Edward Hughes · Matthew Lai · Aditi Mavalankar · Richie Steigerwald · Chris Apps · Yusuf Aytar · Sarah Bechtle · Feryal Behbahani · Stephanie Chan · Nicolas Heess · Lucy Gonzalez · Simon Osindero · Sherjil Ozair · Scott Reed · Jingwei Zhang · Konrad Zolna · Jeff Clune · Nando de Freitas · Satinder Singh · Tim Rocktäschel*

* Position: Measure Dataset Diversity, Don't Just Claim It (ICML 2024) 
  [[Paper](https://arxiv.org/abs/2407.08188)]<br>
  *Authors: Dora Zhao · Jerone Andrews · Orestis Papakyriakopoulos · Alice Xiang*

* Stealing part of a production language model (ICML 2024) 
  [[Paper](https://arxiv.org/abs/2403.06634)]<br>
  *Authors: Nicholas Carlini · Daniel Paleka · Krishnamurthy Dvijotham · Thomas Steinke · Jonathan Hayase · A. Feder Cooper · Katherine Lee · Matthew Jagielski · Milad Nasr · Arthur Conmy · Eric Wallace · David Rolnick · Florian Tramer*

* Scaling Rectified Flow Transformers for High-Resolution Image Synthesis (ICML 2024) 
  [[Paper](https://arxiv.org/abs/2403.03206)]<br>
  *Authors: Patrick Esser · Sumith Kulal · Andreas Blattmann · Rahim Entezari · Jonas Müller · Harry Saini · Yam Levi · Dominik Lorenz · Axel Sauer · Frederic Boesel · Dustin Podell · Tim Dockhorn · Zion English · Robin Rombach*

* Position: Considerations for Differentially Private Learning with Large-Scale Public Pretraining (ICML 2024) 
  [[Paper](https://arxiv.org/abs/2212.06470)]<br>
  *Authors: Florian Tramer · Gautam Kamath · Nicholas Carlini*

* Information Complexity of Stochastic Convex Optimization: Applications to Generalization, Memorization, and Tracing (ICML 2024) 
  [[Paper](https://arxiv.org/abs/2402.09327)]<br>
  *Authors: Idan Attias · Gintare Karolina Dziugaite · Mahdi Haghifam · Roi Livni · Daniel Roy*

* Probabilistic Inference in Language Models via Twisted Sequential Monte Carlo (ICML 2024) 
  [[Paper](https://arxiv.org/abs/2404.17546)]<br>
  *Authors: Stephen Zhao · Rob Brekelmans · Alireza Makhzani · Roger Grosse*

* Discrete Diffusion Modeling by Estimating the Ratios of the Data Distribution (ICML 2024) 
  [[Paper](https://arxiv.org/abs/2310.16834)]<br>
  *Authors: Aaron Lou · Chenlin Meng · Stefano Ermon*

#### Test of Time Award:

* DeCAF: A Deep Convolutional Activation Feature for Generic Visual Recognition (ICML 2014) 
  [[Paper](https://arxiv.org/abs/1310.1531)]<br>
  *Authors: Jeff Donahue, Yangqing Jia, Oriol Vinyals, Judy Hoffman, Ning Zhang, Eric Tzeng, Trevor Darrell*



### Outstanding Papers 2023

* Learning-Rate-Free Learning by D-Adaptation (ICML 2023) 
  [[Paper](https://openreview.net/forum?id=GXZ6cT5cvY)]<br>
  *Authors: Aaron Defazio (FAIR), Konstantin Mishchenko (Samsung AI Center)*

* A Watermark for Large Language Models (ICML 2023) 
  [[Paper](https://openreview.net/forum?id=aX8ig9X2a7)]<br>
  *Authors: John Kirchenbauer, Jonas Geiping, Yuxin Wen, Jonathan Katz, Ian Miers, Tom Goldstein (University of Maryland)*

* Generalization on the Unseen, Logic Reasoning and Degree Curriculum (ICML 2023) 
  [[Paper](https://openreview.net/forum?id=3dqwXb1te4)]<br>
  *Authors: Emmanuel Abbe (EPFL, Apple) , Samy Bengio (Apple), Aryo Lotfi (EPFL), Kevin Rizk (EPFL)*

* Adapting to game trees in zero-sum imperfect information games (ICML 2023) 
  [[Paper](https://openreview.net/forum?id=O1j4uFuSVW)]<br>
  *Authors: Côme Fiegel (CREST, ENSAE, IP Paris), Pierre MENARD (ENS Lyon), Tadashi Kozuno (Omron Sinic X), Remi Munos (Deepmind), Vianney Perchet (CREST, ENSAE, IP Paris and CRITEO AI Lab), Michal Valko (Deepmind)*

* Self-Repellent Random Walks on General Graphs - Achieving Minimal Sampling Variance via Nonlinear Markov Chains (ICML 2023) 
  [[Paper](https://openreview.net/forum?id=450iImFM4U)]<br>
  *Authors: Vishwaraj Doshi (IQVIA Inc), Jie Hu (North Carolina State University), Do Young Eun (North Carolina State University)*

* Bayesian Design Principles for Frequentist Sequential Learning (ICML 2023) 
  [[Paper](https://openreview.net/forum?id=tRhQsHnoFw)]<br>
  *Authors: Yunbei Xu, Assaf Zeevi (Columbia University)*

#### Test of Time Award:

* Learning Fair Representations (ICML 2013) 
  [[Paper](https://proceedings.mlr.press/v28/zemel13.html)]<br>
  *Authors: Rich Zemel, Yu Wu, Kevin Swersky, Toni Pitassi, Cynthia Dwork*



### Outstanding Papers 2022 

* Do Differentiable Simulators Give Better Policy Gradients (ICML 2022) 
  [[Paper](https://icml.cc/virtual/2022/oral/16770)]<br>
  *Authors: Hyung Ju Suh · Max Simchowitz · Kaiqing Zhang · Russ Tedrake*

* Causal Conceptions of Fairness and their Consequences (ICML 2022) 
  [[Paper](https://icml.cc/virtual/2022/poster/17121)]<br>
  *Authors: Hamed Nilforoshan · Johann Gaebler · Ravi Shroff · Sharad Goel*

* G-Mixup: Graph Data Augmentation for Graph Classification (ICML 2022) 
  [[Paper](https://icml.cc/virtual/2022/poster/16665)]<br>
  *Authors: Xiaotian Han · Zhimeng Jiang · Ninghao Liu · Xia Hu*

* Stable Conformal Prediction Sets (ICML 2022) 
  [[Paper](https://icml.cc/virtual/2022/oral/16842)]<br>
  *Authors: Eugene Ndiaye*

* Privacy for Free: How does Dataset Condensation Help Privacy? (ICML 2022) 
  [[Paper](https://icml.cc/virtual/2022/poster/18235)]<br>
  *Authors: Tian Dong · Bo Zhao · Lingjuan Lyu*

* Solving Stackelberg Prediction Game with Least Squares Loss via Spherically Constrained Least Squares Reformulation (ICML 2022) 
  [[Paper](https://icml.cc/virtual/2022/oral/17692)]<br>
  *Authors: Jiali Wang · Wen Huang · Rujun Jiang · Xudong Li · Alex Wang*

* The Importance of Non-Markovianity in Maximum State Entropy Exploration (ICML 2022) 
  [[Paper](https://icml.cc/virtual/2022/poster/16289)]<br>
  *Authors: Mirco Mutti · Riccardo De Santi · Marcello Restelli*

* Bayesian Model Selection, the Marginal Likelihood, and Generalization (ICML 2022) 
  [[Paper](https://icml.cc/virtual/2022/oral/17992)]<br>
  *Authors: Sanae Lotfi · Pavel Izmailov · Gregory Benton · Micah Goldblum · Andrew Wilson*

* Understanding Dataset Difficulty with V-Usable Information (ICML 2022) 
  [[Paper](https://icml.cc/virtual/2022/oral/16634)]<br>
  *Authors: Kawin Ethayarajh · Yejin Choi · Swabha Swayamdipta*

* Learning Mixtures of Linear Dynamical Systems (ICML 2022) 
  [[Paper](https://icml.cc/virtual/2022/poster/15993)]<br>
  *Authors: Yanxi Chen · H. Vincent Poor*

#### Outstanding Paper Runner Up

* Active fairness auditing (ICML 2022) 
  [[Paper](https://icml.cc/virtual/2022/oral/17204)]<br>
  *Authors: Tom Yan · Chicheng Zhang*

* Adversarially Trained Actor Critic for Offline Reinforcement Learning (ICML 2022) 
  [[Paper](https://icml.cc/virtual/2022/oral/17174)]<br>
  *Authors: Ching-An Cheng · Tengyang Xie · Nan Jiang · Alekh Agarwal*

* Monarch: Expressive Structured Matrices for Efficient and Accurate Training (ICML 2022) 
  [[Paper](https://icml.cc/virtual/2022/poster/17899)]<br>
  *Authors: Tri Dao · Beidi Chen · Nimit Sohoni · Arjun Desai · Michael Poli · Jessica Grogan · Alexander Liu · Aniruddh Rao · Atri Rudra · Christopher Re*

* Learning inverse folding from millions of predicted structures (ICML 2022) 
  [[Paper](https://icml.cc/virtual/2022/oral/16886)]<br>
  *Authors: Chloe Hsu · Robert Verkuil · Jason Liu · Zeming Lin · Brian Hie · Tom Sercu · Adam Lerer · Alexander Rives*

* Minimum Cost Intervention Design for Causal Effect Identification (ICML 2022) 
  [[Paper](https://icml.cc/virtual/2022/oral/17380)]<br>
  *Authors: Sina Akbari · Jalal Etesami · Negar Kiyavash*

#### Test of Time Award:

* Poisoning Attacks Against Support Vector Machines (ICML 2012) 
  [[Paper](https://arxiv.org/abs/1206.6389)]<br>
  *Authors: Battista Biggio, Blaine Nelson, Pavel Laskov*

#### Test of Time Honorable Mention:

* Building high-level features using large scale unsupervised learning (ICML 2012) 
  [[Paper](https://arxiv.org/abs/1112.6209)]<br>
  *Authors: Quoc V. Le, Marc'Aurelio Ranzato, Rajat Monga, Matthieu Devin, Kai Chen, Greg S. Corrado, Jeff Dean, Andrew Y. Ng*

* On causal and anticausal learning (ICML 2012) 
  [[Paper](https://arxiv.org/abs/1206.6471)]<br>
  *Authors: Bernhard Schölkopf, Dominik Janzing, Jonas Peters, Eleni Sgouritsa, Kun Zhang, Joris Mooij*



# ACL

## Best Papers 2025

- **A Theory of Response Sampling in LLMs: Part Descriptive and Part Prescriptive**
  *Sarath Sivaprasad, Pramod Kaushik, Sahar Abdelnabi, Mario Fritz*
- **Fairness through Difference Awareness: Measuring Desired Group Discrimination in LLMs**
  *Angelina Wang, Michelle Phan, Daniel E. Ho, Sanmi Koyejo*
- **Language Models Resist Alignment: Evidence From Data Compression**
  *Jiaming Ji, Kaile Wang, Tianyi Qiu, Boyuan Chen, Jiayi Zhou, Changye Li, Hantao Lou, Juntao Dai, Yunhuai Liu, Yaodong Yang*
- **Native Sparse Attention: Hardware-Aligned and Natively Trainable Sparse Attention**
  *Jingyang Yuan, Huazuo Gao, Damai Dai, Junyu Luo, Liang Zhao, Zhengyan Zhang, Zhenda Xie, Y. X. Wei, Lean Wang, Zhiping Xiao, Yuqing Wang, Chong Ruan, Ming Zhang, Wenfeng Liang, Wangding Zeng*

### Best Social Impact Paper 

- **AfriMed-QA: A Pan-African, Multi-Specialty, Medical Question-Answering Benchmark Dataset**
  *Charles Nimo, Tobi Olatunji, Abraham Toluwase Owodunni, Tassallah Abdullahi, Emmanuel Ayodele, Mardhiyah Sanni, Ezinwanne C. Aka, Folafunmi Omofoye, Foutse Yuehgoh, Timothy Faniran, Bonaventure F. P. Dossou, Moshood O. Yekini, Jonas Kemp, Katherine A Heller, Jude Chidubem Omeke, Chidi Asuzu MD, Naome A Etori, Aïmérou Ndiaye, Ifeoma Okoh, Evans Doe Ocansey, Wendy Kinara, Michael Best, Irfan Essa, Stephen Edward Moore, Chris Fourie, Mercy Nyamewaa Asiedu*
- **The AI Gap: How Socioeconomic Status Affects Language Technology Interactions**
  *Elisa Bassignana, Amanda Cercas Curry, Dirk Hovy*

### Best Resource Paper 

- **Are Rules Meant to be Broken? Understanding Multilingual Moral Reasoning as a Computational Pipeline with UniMoral**
  *Shivani Kumar, David Jurgens*
- **BRIGHTER: BRIdging the Gap in Human-Annotated Textual Emotion Recognition Datasets for 28 Languages**
  *Shamsuddeen Hassan Muhammad, Nedjma Ousidhoum, Idris Abdulmumin, Jan Philip Wahle, Terry Ruas, Meriem Beloucif, Christine de Kock, Nirmal Surange, Daniela Teodorescu, Ibrahim Said Ahmad, David Ifeoluwa Adelani, Alham Fikri Aji, Felermino D. M. A. Ali, Ilseyar Alimova, Vladimir Araujo, Nikolay Babakov, Naomi Baes, Ana-Maria Bucur, Andiswa Bukula, Guanqun Cao, Rodrigo Tufiño, Rendi Chevi, Chiamaka Ijeoma Chukwuneke, Alexandra Ciobotaru, Daryna Dementieva, Murja Sani Gadanya, Robert Geislinger, Bela Gipp, Oumaima Hourrane, Oana Ignat, Falalu Ibrahim Lawan, Rooweither Mabuya, Rahmad Mahendra, Vukosi Marivate, Alexander Panchenko, Andrew Piper, Charles Henrique Porto Ferreira, Vitaly Protasov, Samuel Rutunda, Manish Shrivastava, Aura Cristina Udrea, Lilian Diana Awuor Wanzare, Sophie Wu, Florian Valentin Wunderlich, Hanif Muhammad Zhafran, Tianhui Zhang, Yi Zhou, Saif M. Mohammad*
- **Palm: A Culturally Inclusive and Linguistically Diverse Dataset for Arabic LLMs**
  *Fakhraddin Alwajih, Abdellah EL MEKKI, Samar Mohamed Magdy, AbdelRahim A. Elmadany, OMER NACAR, El Moatez Billah Nagoudi, Reem Abdel-Salam, Hanin atwany, Youssef Nafea, Abdulfattah Mohammed Yahya, Rahaf Alhamouri, Hamzah A. Alsayadi, Hiba Zayed, Sara Shatnawi, Serry Sibaee, Yasir ECH-CHAMMAKHY, Walid Al-Dhabyani, Marwa Mohamed Ali, Imen JARRAYA, Ahmed Oumar El-Shangiti, Aisha Alraeesi, Mohammed Anwar AL-Ghrawi, Abdulrahman S. Al-Batati, Elgizouli Mohamed, Noha Taha Elgindi, Muhammed Saeed, Houdaifa Atou, Issam AIT YAHIA, Abdelhak Bouayad, Mohammed Machrouh, AMAL MAKOUAR, Dania Alkawi, Mukhtar Mohamed, Safaa Taher Abdelfadil, Amine Ziad Ounnoughene, Anfel ROUABHIA, Rwaa Assi, Ahmed Sorkatti, Mohamedou cheikh tourad, Anis Koubaa, Ismail Berrada, Mustafa Jarrar, Shady Shehata, Muhammad Abdul-Mageed*

### Best Theme Paper 

- **MaCP: Minimal yet Mighty Adaptation via Hierarchical Cosine Projection**
  *Yixian Shen, Qi Bi, JIA-HONG HUANG, Hongyi Zhu, Andy D. Pimentel, Anuj Pathania*
- **Meta-rater: A Multi-dimensional Data Selection Method for Pre-training Language Models**
  *Xinlin Zhuang, Jiahui Peng, Ren Ma, Yinfan Wang, Tianyi Bai, Xingjian Wei, Qiu Jiantao, Chi Zhang, Ying Qian, Conghui He*
- **SubLIME: Subset Selection via Rank Correlation Prediction for Data-Efficient LLM Evaluation**
  *Gayathri Saranathan, Cong Xu, Mahammad Parwez Alam, Tarun Kumar, Martin Foltin, Soon Yee Wong, Suparna Bhattacharya*



## Best Paper Awards 2024

- **Mission: Impossible Language Models**
  *Julie Kallini, Isabel Papadimitriou, Richard Futrell, Kyle Mahowald, Christopher Potts*
- **Semisupervised Neural Proto-Language Reconstruction**
  *Liang Lu, Peirong Xie, David R Mortensen*
- **Why are Sensitive Functions Hard for Transformers?**
  *Michael Hahn, Mark Rofin*
- **Natural Language Satisfiability: Exploring the Problem Distribution and Evaluating Transformer-based Language Models**
  *Tharindu Madusanka, Ian Pratt-Hartmann, Riza Batista-Navarro*
- **Deciphering Oracle Bone Language with Diffusion Models**
  *Haisu Guan, Huanxin Yang, Xinyu Wang, Shengwei Han, Yongge Liu, Lianwen Jin, Xiang Bai, Yuliang Liu*
- **Causal Estimation of Memorisation Profiles**
  *Pietro Lesci, Clara Meister, Thomas Hofmann, Andreas Vlachos, Tiago Pimentel*
- **Aya Model: An Instruction Finetuned Open-Access Multilingual Language Model**
  *Ahmet Üstün, Viraat Aryabumi, Zheng Xin Yong, Wei-Yin Ko, Daniel D’souza, Gbemileke Onilude, Neel Bhandari, Shivalika Singh, Hui-Lee Ooi, Amr Kayid, Freddie Vargus, Phil Blunsom, Shayne Longpre, Niklas Muennighoff, Marzieh Fadaee, Julia Kreutzer, Sara Hooker*

### Best Social Impact Paper Awards

- **How Johnny Can Persuade LLMs to Jailbreak Them: Rethinking Persuasion to Challenge AI Safety by Humanizing LLMs**
  *Yi Zeng, Hongpeng Lin, Jingwen Zhang, Diyi Yang, Ruoxi Jia, Weiyan Shi*
- **DIALECTBENCH: An NLP Benchmark for Dialects, Varieties, and Closely-Related Languages**
  *Fahim Faisal, Orevaoghene Ahia, Aarohi Srivastava, Kabir Ahuja, David Chiang, Yulia Tsvetkov, Antonios Anastasopoulos*
- **Having Beer after Prayer? Measuring Cultural Bias in Large Language Models”**
  *Tarek Naous, Michael J Ryan, Alan Ritter, Wei Xu*

### Best Resource Paper Awards

- **Latxa: An Open Language Model and Evaluation Suite for Basque**
  *Julen Etxaniz, Oscar Sainz, Naiara Perez Miguel, Itziar Aldabe, German Rigau, Eneko Agirre, Aitor Ormazabal, Mikel Artetxe, Aitor Soroa*
- **Dolma: an Open Corpus of Three Trillion Tokens for Language Model Pretraining Research**
  *Luca Soldaini, Rodney Kinney, Akshita Bhagia, Dustin Schwenk, David Atkinson, Russell Authur, Ben Bogin, Khyathi Chandu, Jennifer Dumas, Yanai Elazar, Valentin Hofmann, Ananya Harsh Jha, Sachin Kumar, Li Lucy, Xinxi Lyu, Nathan Lambert, Ian Magnusson, Jacob Morrison, Niklas Muennighoff, Aakanksha Naik, Crystal Nam, Matthew E Peters, Abhilasha Ravichander, Kyle Richardson, Zejiang Shen, Emma Strubell, Nishant Subramani, Oyvind Tafjord, Evan Pete Walsh, Luke Zettlemoyer, Noah A. Smith, Hannaneh Hajishirzi, Iz Beltagy, Dirk Groeneveld, Jesse Dodge, Kyle Lo*
- **AppWorld: A Controllable World of Apps and People for Benchmarking Interactive Coding Agents**
  *Harsh Trivedi, Tushar Khot, Mareike Hartmann, Ruskin Manku, Vinty Dong, Edward Li, Shashank Gupta, Ashish Sabharwal, Niranjan Balasubramanian*

### Best Theme Paper Awards 

- **OLMo: Accelerating the Science of Language Models**
  *Dirk Groeneveld, Iz Beltagy, Evan Pete Walsh, Akshita Bhagia, Rodney Kinney, Oyvind Tafjord, Ananya Harsh Jha, Hamish Ivison, Ian Magnusson, Yizhong Wang, Shane Arora, David Atkinson, Russell Authur, Khyathi Chandu, Arman Cohan, Jennifer Dumas, Yanai Elazar, Yuling Gu, Jack Hessel, Tushar Khot, William Merrill, Jacob Morrison, Niklas Muennighoff, Aakanksha Naik, Crystal Nam, Matthew E Peters, Valentina Pyatkin, Abhilasha Ravichander, Dustin Schwenk, Saurabh Shah, William H. Smith, Emma Strubell, Nishant Subramani, Mitchell Wortsman, Pradeep Dasigi, Nathan Lambert, Kyle Richardson, Luke Zettlemoyer, Jesse Dodge, Kyle Lo, Luca Soldaini, Noah A. Smith, Hannaneh Hajishirzi*



## Best Paper Awards 2023

- Do Androids Laugh at Electric Sheep? Humor “Understanding” Benchmarks from The New Yorker Caption Contest
  *Jack Hessel, Ana Marasovic, Jena D. Hwang, Lillian Lee, Jeff Da, Rowan Zellers, Robert Mankoff and Yejin Choi*
- What the DAAM: Interpreting Stable Diffusion Using Cross Attention
  *Raphael Tang, Linqing Liu, Akshat Pandey, Zhiying Jiang, Gefei Yang, Karun Kumar, Pontus Stenetorp, Jimmy Lin and Ferhan Ture*
- From Pretraining Data to Language Models to Downstream Tasks: Tracking the Trails of Political Biases Leading to Unfair NLP Models
  *Shangbin Feng, Chan Young Park, Yuhan Liu and Yulia Tsvetkov*

### Special Awards

**Reproduction Award**:

Do CoNLL-2003 Named Entity Taggers Still Work Well in 2023?
*Shuheng Liu and Alan Ritter*

**Resource Award**:

When Does Translation Require Context? A Data-driven, Multilingual Exploration
*Patrick Fernandes, Kayo Yin, Emmy Liu, André Martins and Graham Neubig*

**Social Impact Award**:

Marked Personas: Using Natural Language Prompts to Measure Stereotypes in Language Models
*Myra Cheng, Esin Durmus and Dan Jurafsky*

**Theme Paper Award**:

Weaker Than You Think: A Critical Look at Weakly Supervised Learning
*Dawei Zhu, Xiaoyu Shen, Marius Mosbach, Andreas Stephan and Dietrich Klakow*



## Best Paper Awards 2022

- **Best Paper**
  - **Learned Incremental Representations for Parsing** (Nikita Kitaev, Thomas Lu and Dan Klein)

- **Best Special Theme Paper** 
  - **Requirements and Motivations of Low-Resource Speech Synthesis for Language Revitalization** (Aidan Pine, Dan Wells, Nathan Brinklow, Patrick William Littell and Korin Richmond)

- **Best Resource Paper**
  - **DiBiMT: A Novel Benchmark for Measuring Word Sense Disambiguation Biases in Machine Translation** (Niccolò Campolungo, Federico Martelli, Francesco Saina and Roberto Navigli)

- **Best Linguistic Insight Paper** 
  - **KinyaBERT: a Morphology-aware Kinyarwanda Language Model** (Antoine Nzeyimana and Andre Niyongabo Rubungo)

- **Outstanding Papers**
  - **Evaluating Factuality in Text Simplification** (By Ashwin Devaraj, William Berkeley Sheffield, Byron C Wallace and Junyi Jessy Li)
  - **Online Semantic Parsing for Latency Reduction in Task-Oriented Dialogue** (Jiawei Zhou, Jason Eisner, Michael Newman, Emmanouil Antonios Platanios and Sam Thomson)
  - **Learning to Generalize to More: Continuous Semantic Augmentation for Neural Machine Translation** (Xiangpeng Wei, Heng Yu, Yue Hu, Rongxiang Weng, Weihua Luo and Rong Jin)
  - **Fantastically Ordered Prompts and Where to Find Them: Overcoming Few-Shot Prompt Order Sensitivity** (Yao Lu, Max Bartolo, Alastair Moore, Sebastian Riedel and Pontus Stenetorp)
  - **Inducing Positive Perspectives with Text Reframing** (Caleb Ziems, Minzhi Li, Anthony Zhang and Diyi Yang)
  - **Ditch the Gold Standard: Re-evaluating Conversational Question Answering** (Huihan Li, Tianyu Gao, Manan Goenka and Danqi Chen)
  - **Active Evaluation: Efficient NLG Evaluation with Few Pairwise Comparisons** (Akash Kumar Mohankumar and Mitesh M Khapra)
  - **Compression of Generative Pre-trained Language Models via Quantization** (Chaofan Tao, Lu Hou, Wei Zhang, Lifeng Shang, Xin Jiang, Qun Liu, Ping Luo, Ngai Wong)





# EMNLP

### Best Paper 2025

- **Infini-gram mini: Exact n-gram Search at the Internet Scale with FM-Index**
  *Hao Xu, Jiacheng Liu, Yejin Choi, Noah A. Smith, Hannaneh Hajishirzi*

#### Outstanding Papers

1. **LingGym: How Far Are LLMs from Thinking Like Field Linguists?**
   *Changbing Yang, Franklin Ma, Freda Shi, Jian Zhu*
2. **Mind the Value-Action Gap: Do LLMs Act in Alignment with Their Values?**
   *Hua Shen, Nicholas Clark, Tanu Mitra*
3. **DiscoSG: Towards Discourse-Level Text Scene Graph Parsing through Iterative Graph Refinement**
   *Shaoqing Lin, Chong Teng, Fei Li, Donghong Ji, Lizhen Qu, Zhuang Li*
4. **Generative or Discriminative? Revisiting Text Classification in the Era of Transformers**
   *Siva Rajesh Kasa, Karan Gupta, Sumegh Roychowdhury, Ashutosh Kumar,
   Yaswanth Biruduraju, Santhoh Kumar Kasa, Pattisapu Nikhil Priyatam,
   Arindam Bhattacharya, Shailendra Agarwal, Vijay Huddar*
5. **Measuring Chain of Thought Faithfulness by Unlearning Reasoning Steps**
   *Martin Tutek, Fateme Hashemi Chaleshtori, Ana Marasovic, Yonatan Belinkov*
6. **MiCRo: Mixture Modeling and Context-aware Routing for Personalized Preference Learning**
   *Jingyan Shen, Jiarui Yao, Rui Yang, Yifan Sun, Feng Luo, Rui Pan, Tong Zhang, Han Zhao*
7. **Causal Interventions Reveal Shared Structure Across English Filler-Gap Constructions**
   *Sasha Boguraev, Christopher Potts, Kyle Mahowald*

#### Best Special Theme Paper

- **InterIDEAS: Philosophical Intertextuality via LLMs**
  *Yue Yang, Yinzhi Xu, Chenghao Huang, JohnMichael Jurgensen, Han Hu, Hao Wang*

#### Best Resource Paper

- **Autoformalization in the Wild: Assessing LLMs on Real-World Mathematical Definitions**
  *Lan Zhang, Marco Valentino, Andre Freitas*

#### Social Impact Award

- **AccessEval: Benchmarking Disability Bias in Large Language Models**
  *Srikant Panda, Amit Agarwal, Hitesh Laxmichand Patel*

#### People’s Choice Award

- **Randomly Removing 50% of Dimensions in Text Embeddings has Minimal Impact on Retrieval and Classification Tasks**
  *Sotaro Takeshita, Yurina Takeshita, Daniel Ruffinelli, Simone Paolo Ponzetto*



## Best Paper 2024

- An image speaks a thousand words, but can everyone listen? On image transcreation for cultural relevance
  *Simran Khanuja, Sathyanarayanan Ramamoorthy, Yueqi Song, Graham Neubig*
- Towards Robust Speech Representation Learning for Thousands of Languages
  *William Chen, Wangyou Zhang, Yifan Peng, Xinjian Li, Jinchuan Tian, Jiatong Shi, Xuankai Chang, Soumi Maiti, Karen Livescu, Shinji Watanabe*
- Backward Lens: Projecting Language Model Gradients into the Vocabulary Space
  *Shahar Katz, Yonatan Belinkov, Mor Geva, Lior Wolf*
- Pretraining Data Detection for Large Language Models: A Divergence-based Calibration Method
  *Weichao Zhang, Ruqing Zhang, Jiafeng Guo, Maarten de Rijke, Yixing Fan, Xueqi Cheng*
- CoGen: Learning from Feedback with Coupled Comprehension and Generation
  *Mustafa Omer Gul, Yoav Artzi*

### Best Demo Paper Award

- OpenOmni: A Collaborative Open Source Tool for Building Future-Ready Multimodal Conversational Agents
  *Qiang Sun, Yuanyi Luo, Sirui Li, Wenxiao Zhang, Wei Liu*

### Outstanding Demo Paper

- sign.mt: Real-Time Multilingual Sign Language Translation Application
  *Amit Moryossef*

### Resource Paper Awards

- KidLM: Advancing Language Models for Children – Early Insights and Future Directions
  *Mir Tafseer Nayeem, Davood Rafiei*
- A User-Centric Multi-Intent Benchmark for Evaluating Large Language Models
  *Jiayin Wang, Fengran Mo, Weizhi Ma, Peijie Sun, Min Zhang, Jian-Yun Nie*

### Social Impact Paper Awards

- What the Harm? Quantifying the Tangible Impact of Gender Bias in Machine Translation with a Human-centered Study
  *Beatrice Savoldi, Sara Papi, Matteo Negri, Ana Guerberof-Arenas, Luisa Bentivogli*
- STOP! Benchmarking Large Language Models with Sensitivity Testing on Offensive Progressions
  *Robert Morabito, Sangmitra Madhusudan, Tyler McDonald, Ali Emami*
- Twists, Humps, and Pebbles: Multilingual Speech Recognition Models Exhibit Gender Performance Gaps
  *Giuseppe Attanasio, Beatrice Savoldi, Dennis Fucci, Dirk Hovy*

### Special Theme Paper Award

- DEM: Distribution Edited Model for Training with Mixed Data Distributions
  *Dhananjay Ram, Aditya Rawal, Momchil Hardalov,Nikolaos Pappas, Sheng Zha*



## Best Paper 2023

- Label Words are Anchors: An Information Flow Perspective for Understanding In-Context Learning
  *Lean Wang, Lei Li, Damai Dai, Deli Chen, Hao Zhou, Fandong Meng, Jie Zhou and Xu Sun*
- Faster Minimum Bayes Risk Decoding with Confidence-based Pruning
  *Julius Cheng and Andreas Vlachos*
- Ignore This Title and HackAPrompt: Exposing Systemic Vulnerabilities of LLMs Through a Global Prompt Hacking Competition
  *Sander V Schulhoff, Jeremy Pinto, Anaum Khan, Louis-François Bouchard, Chenglei Si, Svetlina Anati, Valen Tagliabue, Anson Liu Kost, Christopher R Carnahan and Jordan Lee Boyd-Graber*
- PaperMage: A Unified Toolkit for Processing, Representing, and Manipulating Visually-Rich Scientific Documents
  _Kyle Lo, Zejiang Shen, Benjamin Newman, Joseph Chee Chang, Russell Authur, Erin Bransom, Stefan Candra, Yoganand Chandrasekhar, Regan Huff, Bailey Kuehl, Amanpreet Singh, Chris Wilhelm, Angele Zamarron, Marti A. Hearst, Daniel Weld, Doug Downey and Luca Soldaini _
- Personalized Dense Retrieval on Global Index for Voice-enabled Conversational Systems
  *Masha Belyi, Charlotte Dzialo, Chaitanya Dwivedi, Prajit Reddy Muppidi and Kanna Shimizu*



# NAACL

## Best Paper Awards 2025

- **Best Paper Award:**
  *The BiGGen Bench: A Principled Benchmark for Fine-grained Evaluation of Language Models with Language Models* \
  Seungone Kim, Juyoung Suk, Ji Yong Cho, Shayne Longpre, Chaeeun Kim, Dongkeun Yoon, Guijin Son, Yejin Cho, Sheikh Shafayat, Jinheon Baek, Sue Hyun Park, Hyeonbin Hwang, Jinkyung Jo, Hyowon Cho, Haebin Shin, Seongyun Lee, Hanseok Oh, Noah Lee, Namgyu Ho, Se June Joo, Miyoung Ko, Yoonjoo Lee, Hyungjoo Chae, Jamin Shin, Joel Jang, Seonghyeon Ye, Bill Yuchen Lin, Sean Welleck, Graham Neubig, Moontae Lee, Kyungjae Lee, Minjoon Seo
- **Best Paper Runner-Up:**
  *REL-A.I.: An Interaction-Centered Approach To Measuring Human-LM Reliance*
  Kaitlyn Zhou, Jena D. Hwang, Xiang Ren, Nouha Dziri, Dan Jurafsky, Maarten Sap
- **Best Demo Award:**
  *Towards Unified, Dynamic and Annotation-based Visualisations and Exploration of Annotated Big Data Corpora with the Help of Unified Corpus Explorer*
  Alexander Mehler; Giuseppe Abrami; Kevin Bönisch
- **Best Social Impact Award:**
  *FLEURS-ASL: Including American Sign Language in Massively Multilingual Multitask Evaluation*
  Garrett Tanzer
- **Best Theme Paper Award:**
  *WorldCuisines: A Massive-Scale Benchmark for Multilingual and Multicultural Visual Question Answering on Global Cuisines*
  Genta Indra Winata, Frederikus Hudi, Patrick Amadeus Irawan, David Anugraha, Rifki Afina Putri, WANG YUTONG, Adam Nohejl, Ubaidillah Ariq Prathama, Nedjma Ousidhoum, Afifa Amriani, Anar Sabuhi Rzayev, Anirban Das, Ashmari Pramodya, Aulia Adila, Bryan Wilie, Candy Olivia Mawalim, CHENG Ching Lam, Daud Abolade, Emmanuele Chersoni, Enrico Santus, Fariz Ikhwantri, Garry Kuwanto, Hanyang Zhao, Haryo Akbarianto Wibowo, Holy Lovenia, Jan Christian Blaise Cruz, Jan Wira Gotama Putra, Junho Myung, Lucky Susanto, Maria Angelica Riera Machin, Marina Zhukova, Michael Anugraha, Muhammad Farid Adilazuarda, Natasha Christabelle Santosa, Peerat Limkonchotiwat, Raj Dabre, Rio Alexander Audino, Samuel Cahyawijaya, Shi-Xiong Zhang, Stephanie Yulia Salim, Yi Zhou, Yinxuan Gui, David Ifeoluwa Adelani, En-Shiun Annie Lee, Shogo Okada, Ayu Purwarianti, Alham Fikri Aji, Taro Watanabe, Derry Tanti Wijaya, Alice Oh, Chong-Wah Ngo
- **Best Theme Paper Runner-Up:**
  *Developing multilingual speech synthesis system for Ojibwe, Mi’kmaq, and Maliseet*
  Shenran Wang, Changbing Yang, Michael l parkhill, Chad Quinn, Christopher Hammerly, Jian Zhu



### Senior Area Chair (SAC) Awards

- **SAC Award for Generation:** *Decoding Speculative Decoding*
  Minghao Yan, Saurabh Agarwal, Shivaram Venkataraman
- **SAC Award for Interpretability and Analysis of Models for NLP:**
  *On Behalf of the Stakeholders: Trends in NLP Model Interpretability in the Era of LLMs*
  Nitay Calderon, Roi Reichart
- **SAC Award for Language Modeling:**
  *In-Context Learning with Long-Context Models: An In-Depth Exploration*
  Amanda Bertsch, Maor Ivgi, Emily Xiao, Uri Alon, Jonathan Berant, Matthew R. Gormley, Graham Neubig
- **SAC Award for Linguistic Theories, Cognitive Modeling and Psycholinguistics:**
  *Language Models Largely Exhibit Human-like Constituent Ordering Preferences*
  Ada Tur, Gaurav Kamath, Siva Reddy
- **SAC Award for Low-resource Methods for NLP:**
  *Advancing MoE Efficiency: A Collaboration-Constrained Routing C2R Strategy for Better Expert Parallelism Design*
  Mohan Zhang, Pingzhi Li, Jie Peng, Mufan Qiu, Tianlong Chen
- **SAC Award for Resources and Evaluation:**
  *Unifying AI Tutor Evaluation: An Evaluation Taxonomy for Pedagogical Ability Assessment of LLM-Powered AI Tutors*
  Kaushal Kumar Maurya, KV Aditya Srivatsa, Kseniia Petukhova, Ekaterina Kochmar
- **SAC Award for Special Theme:**
  *Meta-Cultural Competence: Climbing the Right Hill of Cultural Awareness*
  Sougata Saha, Saurabh Kumar Pandey, Monojit Choudhury
- **SAC Award for Speech Processing and Spoken Language Understanding:**
  *Behavior-SD: Behaviorally Aware Spoken Dialogue Generation with Large Language Models*
  Sehun Lee, Kang-wook Kim, Gunhee Kim
- **SAC Award for Summarization:**
  *Coverage-based Fairness in Multi-document Summarization*
  Haoyuan Li, Yusen Zhang, Rui Zhang, Snigdha Chaturvedi
  
  



## Best Paper 2024

### Theme track award

**Grammar-based Data Augmentation for Low-Resource Languages: The Case of Guarani-Spanish Neural Machine Translation**
Agustín Lucas, Alexis Baladón Ferreira de Araujo, Victoria Pardiñas, Marvin M. Agüero-Torales, Santiago Góngora, Luis Chiruzzo

### Social impact award

**Understanding the Capabilities and Limitations of Large Language Models for Cultural Commonsense**
Siqi Shen, Lajanugen Logeswaran, Moontae Lee, Honglak Lee, Soujanya Poria, Rada Mihalcea

### Resource award

**Exploring Cross-Cultural Differences in English Hate Speech Annotations: From Dataset Construction to Analysis**

Nayeon Lee, Chani Jung, Junho Myung, Jiho Jin, Jose Camacho-Collados, Juho Kim, Alice O

### Outstanding paper award

**LM-Infinite: Zero-Shot Extreme Length Generalization for Large Language Models**
Chi Han, Qifan Wang, Hao Peng, Wenhan Xiong, Yu Chen, Heng Ji, Sinong Wang

**Defining and Detecting Vulnerability in Human Evaluation Guidelines: A Preliminary Study Towards Reliable NLG Evaluation**
Jie Ruan, Wang Wenqing, Xiaojun Wan

**Unlocking Emergent Modularity in Large Language Models**
Zihan Qiu, Zeyu Huang, Jie Fu

**R-Tuning: Instructing Large Language Models to Say `I Don't Know'**
Hanning Zhang, Shizhe Diao, Yong Lin, Yi Fung, Qing LIAN, Xingyao Wang, Yangyi Chen, Heng Ji, Tong Zhang

**Teaching Language Models to Self-Improve through Interactive Demonstrations**
Xiao Yu, Baolin Peng, Michel Galley, Jianfeng Gao, Zhou Yu

**A Pretrainer's Guide to Training Data: Measuring the Effects of Data Age, Domain Coverage, Quality, & Toxicity**
Shayne Longpre, Gregory Yauney, Emily Reif, Katherine Lee, Adam Roberts, Barret Zoph, Denny Zhou, Jason Wei, Kevin Robinson, David Mimno, Daphne Ippolito

### Best Paper Awards

**Visual Grounding Helps Learn Word Meanings in Low-Data Regimes**
Chengxu Zhuang, Evelina Fedorenko, Jacob Andreas

**Evaluating the Deductive Competence of Large Language Models**
S M Seals, Valerie Shalin



## Best Paper Awards 2022

### Best new task (tied) and new resource paper

**Automatic Correction of Human Translations**

Jessy Lin, Geza Kovacs, Aditya Shastry, Joern Wuebker, John DeNero

### Best efficient NLP paper

**FNet: Mixing Tokens with Fourier Transforms**

James Lee-Thorp, Joshua Ainslie, Ilya Eckstein, Santiago Ontanon

### Best new task paper (tied)

**FRUIT: Faithfully Reflecting Updated Information in Text**

Robert L. Logan IV, Alexandre Tachard Passos, Sameer Singh, Ming-Wei Chang

### Best new method paper

**NeuroLogic A*esque Decoding: Constrained Text Generation with Lookahead Heuristics**

Ximing Lu, Sean Welleck, Peter West, Liwei Jiang, Jungo Kasai, Daniel Khashabi, Ronan Le Bras, Lianhui Qin, Youngjae Yu, Rowan Zellers, Noah Smith, Yejin Choi

### Best paper on human-centered NLP special theme

**User-Driven Research of Medical Note Generation Software**

Tom Knoll, Francesco Moramarco, Alex Papadopoulos Korfiatis, Rachel Young, Claudia Ruffini, Mark Perera, Christian Perstl, Ehud Reiter, Anya Belz, Aleksandar Savkov

### Honorable mention for contribution to special theme on human-centered NLP

**Automatic Correction of Human Translations**

Jessy Lin, Geza Kovacs, Aditya Shastry, Joern Wuebker, John DeNero

### Honorable mention for contribution to methods

**Balanced Data Approach for Evaluating Cross-Lingual Transfer: Mapping the Linguistic Blood Bank**

Dan Malkin, Tomasz Limisiewicz, Gabriel Stanovsky

### Honorable mention for contributions to resources

**NewsEdits: A Dataset of News Article Revision Histories and a Novel Document-Level Reasoning Challenge**

Alexander Spangher, Xiang Ren, Jonathan May, Nanyun Peng





# CVPR 

### Best Papers 2025

#### Best Paper Award:

* VGGT: Visual Geometry Grounded Transformer (CVPR 2025) 
  [[Paper](https://arxiv.org/abs/2503.11651)]<br>
  *Authors: Jianyuan Wang, Minghao Chen, Nikita Karaev, Andrea Vedaldi, Christian Rupprecht, David Novotny*

#### Best Paper Honorable Mention:

* MegaSaM: Accurate, Fast and Robust Structure and Motion from Casual Dynamic Videos (CVPR 2025) 
  [[Paper](https://arxiv.org/abs/2412.04463)]<br>
  *Authors: Zhengqi Li, Richard Tucker, Forrester Cole, Qianqian Wang, Linyi Jin, Vickie Ye, Angjoo Kanazawa, Aleksander Holynski, Noah Snavely*

* Navigation World Models (CVPR 2025) 
  [[Paper](https://arxiv.org/abs/2412.03572)]<br>
  *Authors: Amir Bar, Gaoyue Zhou, Danny Tran, Trevor Darrell, Yann LeCun*

* Molmo and PixMo: Open Weights and Open Data for State-of-the-Art Vision-Language Models (CVPR 2025) 
  [[Paper](https://arxiv.org/abs/2409.17146)]<br>
  *Authors: Matt Deitke, Christopher Clark, Sangho Lee, Rohun Tripathi, Yue Yang, Jae Sung Park, Mohammadreza Salehi, Niklas Muennighoff, Kyle Lo, Luca Soldaini, Jiasen Lu, Taira Anderson, Erin Bransom, Kiana Ehsani, Huong Ngo, YenSung Chen, Ajay Patel, Mark Yatskar, Chris Callison-Burch, Andrew Head, Rose Hendrix, Favyen Bastani, Eli VanderBilt, Nathan Lambert, Yvonne Chou, Arnavi Chheda, Jenna Sparks, Sam Skjonsberg, Michael Schmitz, Aaron Sarnat, Byron Bischoff, Pete Walsh, Chris Newell, Piper Wolters, Tanmay Gupta, Kuo-Hao Zeng, Jon Borchardt, Dirk Groeneveld, Crystal Nam, Sophie Lebrecht, Caitlin Wittlif, Carissa Schoenick, Oscar Michel, Ranjay Krishna, Luca Weihs, Noah A. Smith, Hannaneh Hajishirzi, Ross Girshick, Ali Farhadi, Aniruddha Kembhavi*

* 3D Student Splatting and Scooping (CVPR 2025) 
  [[Paper](https://arxiv.org/abs/2503.10148)]<br>
  *Authors: Jialin Zhu, Jiangbei Yue, Feixiang He, He Wang*

#### Best Student Paper Award:

* Neural Inverse Rendering from Propagating Light (CVPR 2025) 
  [[Paper](https://arxiv.org/abs/2506.05347)]<br>
  *Authors: Anagh Malik, Benjamin Attal, Andrew Xie, Matthew O'Toole, David B. Lindell*

#### Best Student Paper Honorable Mention:

* Generative Multimodal Pretraining with Discrete Diffusion Timestep Tokens (CVPR 2025) 
  [[Paper](https://arxiv.org/abs/2504.14666)]<br>
  *Authors: Kaihang Pan, Wang Lin, Zhongqi Yue, Tenglong Ao, Liyu Jia, Wei Zhao, Juncheng Li, Siliang Tang, Hanwang Zhang*

#### Longuet-Higgins Prize (Test of Time):

* Going Deeper with Convolutions (CVPR 2015) 
  [[Paper](https://arxiv.org/abs/1409.4842)]<br>
  *Authors:  Christian Szegedy, Wei Liu, Yangqing Jia, Pierre Sermanet, Scott Reed, Dragomir Anguelov, Dumitru Erhan, Vincent Vanhoucke, Andrew Rabinovich*

* Fully Convolutional Networks for Semantic Segmentation (CVPR 2015) 
  [[Paper](https://arxiv.org/abs/1411.4038)]<br>
  *Authors:  Jonathan Long, Evan Shelhamer, Trevor Darrell*



### Best Papers 2024

#### Best Paper Award:

* Generative Image Dynamics (CVPR 2024) 
  [[Paper](https://arxiv.org/abs/2309.07906)]<br>
  *Authors: Zhengqi Li, Richard Tucker, Noah Snavely, Aleksander Holynski*

* Rich Human Feedback for Text-to-Image Generation (CVPR 2024) 
  [[Paper](https://arxiv.org/abs/2312.10240)]<br>
  *Authors: Youwei Liang, Junfeng He, Gang Li, Peizhao Li, Arseniy Klimovskiy, Nicholas Carolan, Jiao Sun, Jordi Pont-Tuset, Sarah Young, Feng Yang, Junjie Ke, Krishnamurthy Dj Dvijotham, Katherine M. Collins, Yiwen Luo, Yang Li, Kai J. Kohlhoff, Deepak Ramachandran, and Vidhya Navalpakkam*

#### Best Paper Honorable Mention:

* EventPS: Real-Time Photometric Stereo Using an Event Camera (CVPR 2024) 
  [[Paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Yu_EventPS_Real-Time_Photometric_Stereo_Using_an_Event_Camera_CVPR_2024_paper.pdf)]<br>
  *Authors: Bohan Yu, Jieji Ren, Jin Han, Feishi Wang, Jinxiu Liang, Boxin Shi*

* pixelSplat: 3D Gaussian Splats from Image Pairs for Scalable Generalizable 3D Reconstruction (CVPR 2024) 
  [[Paper](https://arxiv.org/abs/2312.12337)]<br>
  *Authors: David Charatan, Sizhe Li, Andrea Tagliasacchi, Vincent Sitzmann*

#### Best Student Paper Award:

* Mip-Splatting: Alias-free 3D Gaussian Splatting (CVPR 2024) 
  [[Paper](https://arxiv.org/abs/2311.16493)]<br>
  *Authors: Zehao Yu, Anpei Chen, Binbin Huang, Torsten Sattler, Andreas Geiger*

* BIOCLIP: A Vision Foundation Model for the Tree of Life (CVPR 2024) 
  [[Paper](https://arxiv.org/abs/2311.18803)]<br>
  *Authors: Samuel Stevens, Jiaman Wu, Matthew J. Thompson, Elizabeth G. Campolongo, Chan Hee Song, David Edward Carlyn, Li Dong, Wasila M. Dahdul, Charles Stewart, Tanya Berger-Wolf, Wei-Lun Chao, and Yu Su*

#### Best Student Paper Honorable Mention:

* SpiderMatch: 3D Shape Matching with Global Optimality and Geometric Consistency (CVPR 2024) 
  [[Paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Roetzer_SpiderMatch_3D_Shape_Matching_with_Global_Optimality_and_Geometric_Consistency_CVPR_2024_paper.pdf)]<br>
  *Authors: Paul Roetzer, Florian Bernard*

* Objects as volumes: A stochastic geometry view of opaque solids (CVPR 2024) 
  [[Paper](https://arxiv.org/abs/2312.15406)]<br>
  *Authors: Bailey Miller, Hanyu Chen, Alice Lai, Ioannis Gkioulekas*

* Comparing the Decision-Making Mechanisms by Transformers and CNNs via Explanation Methods (CVPR 2024) 
  [[Paper](https://arxiv.org/abs/2212.06872)]<br>
  *Authors: Mingqi Jiang, Saeed Khorram, Li Fuxin*

#### Longuet-Higgins Prize (Test of Time):

* Rich feature hierarchies for accurate object detection and semantic segmentation (CVPR 2014) 
  [[Paper](https://arxiv.org/abs/1311.2524)]<br>
  *Authors: Ross Girshick, Jeff Donahue, Trevor Darrell, Jitendra Malik*



### Best Papers 2023

#### Best Paper Award:

* Visual Programming: Compositional visual reasoning without training (CVPR 2023) 
  [[Paper](http://arxiv.org/abs/2211.11559)]<br>
  *Authors: Tanmay Gupta, Aniruddha Kembhavi*

* Planning-oriented Autonomous Driving (CVPR 2023) 
  [[Paper](http://arxiv.org/abs/2212.10156)]<br>
  *Authors: Yihan Hu, Jiazhi Yang, Li Chen, Keyu Li, Chonghao Sima, Xizhou Zhu, Siqi Chai, Senyao Du, Tianwei Lin, Wenhai Wang, Lewei Lu, Xiaosong Jia, Qiang Liu, Jifeng Dai, Yu Qiao, Hongyang Li*

#### Best Paper Honorable Mention:

* DynIBaR: Neural Dynamic Image-Based Rendering (CVPR 2023) 
  [[Paper](http://arxiv.org/abs/2211.11082)]<br>
  *Authors: Zhengqi Li, Qianqian Wang, Forrester Cole, Richard Tucker, Noah Snavely*

#### Best Student Paper Award:

* 3D Registration with Maximal Cliques (CVPR 2023) 
  [[Paper](http://arxiv.org/abs/2305.10854)]<br>
  *Authors: Xiyu Zhang, Jiaqi Yang, Shikun Zhang, Yanning Zhang*

#### Best Student Paper Honorable Mention:

* DreamBooth: Fine Tuning Text-to-Image Diffusion Models for Subject-Driven Generation (CVPR 2023) 
  [[Paper](http://arxiv.org/abs/2208.12242)]<br>
  *Authors: Nataniel Ruiz, Yuanzhen Li, Varun Jampani, Yael Pritch, Michael Rubinstein, Kfir Aberman*

#### Award Candidates:

* Ego-Body Pose Estimation via Ego-Head Pose Estimation (CVPR 2023) 
  [[Paper](http://arxiv.org/abs/2212.04636)]<br>
  *Authors: Jiaman Li, Karen Liu, Jiajun Wu*

* OmniObject3D: Large Vocabulary 3D Object Dataset for Realistic Perception, Reconstruction and Generation (CVPR 2023) 
  [[Paper](http://arxiv.org/abs/2301.07525)]<br>
  *Authors: Tong Wu, Jiarui Zhang, Xiao Fu, Yuxin Wang, Jiawei Ren, Liang Pan, Wayne Wu, Lei Yang, Jiaqi Wang, Chen Qian, Dahua Lin, Ziwei Liu*

* MobileNeRF: Exploiting the Polygon Rasterization Pipeline for Efficient Neural Field Rendering on Mobile Architectures (CVPR 2023) 
  [[Paper](http://arxiv.org/abs/2208.00277)]<br>
  *Authors: Zhiqin Chen, Thomas Funkhouser, Peter Hedman, Andrea Tagliasacchi*

* On Distillation of Guided Diffusion Models (CVPR 2023) 
  [[Paper](http://arxiv.org/abs/2210.03142)]<br>
  *Authors: Chenlin Meng, Robin Rombach, Ruiqi Gao, Diederik Kingma, Stefano Ermon, Jonathan Ho, Tim Salimans*

* What Can Human Sketches Do for Object Detection? (CVPR 2023) 
  [[Paper](http://arxiv.org/abs/2303.15149)]<br>
  *Authors: Pinaki Nath Chowdhury, Ayan Kumar Bhunia, Aneeshan Sain, Subhadeep Koley, Tao Xiang, Yi-Zhe Song*

* Data-driven Feature Tracking for Event Cameras (CVPR 2023) 
  [[Paper](http://arxiv.org/abs/2211.12826)]<br>
  *Authors: Nico Messikommer, Carter Fang, Mathias Gehrig, Davide Scaramuzza*

* Integral Neural Networks (CVPR 2023) 
  [[Paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Solodskikh_Integral_Neural_Networks_CVPR_2023_paper.pdf)]<br>
  *Authors: Kirill Solodskikh, Azim Kurbanov, Ruslan Aydarkhanov, Irina Zhelavskaya, Yury Parfenov, Dehua Song, Stamatios Lefkimmiatis*

#### Longuet-Higgins Prize (Test of Time):

* Online Object Tracking: A Benchmark (CVPR 2013) 
  [[Paper](https://faculty.ucmerced.edu/mhyang/papers/cvpr13_benchmark.pdf)]<br>
  *Authors: Yi Wu, Jongwoo Lim, Ming-Hsuan Yang*



### Best Papers 2022

#### Best Paper Award:

* Learning to Solve Hard Minimal Problems (CVPR 2022) 
  [[Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Hruby_Learning_To_Solve_Hard_Minimal_Problems_CVPR_2022_paper.pdf)]<br>
  *Authors: Petr Hruby, Timothy Duff, Anton Leykin, and Tomas Pajdla*

#### Best Paper Honorable Mention:

* Dual-Shutter Optical Vibration Sensing (CVPR 2022) 
  [[Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Sheinin_Dual-Shutter_Optical_Vibration_Sensing_CVPR_2022_paper.pdf)]<br>
  *Authors: Mark Sheinin, Dorian Chan, Matthew O'Toole, Srinivasa Narasimhan*

#### Best Student Paper Award:

* EPro-PnP: Generalized End-to-End Probabilistic Perspective-n-Points for Monocular Object Pose Estimation (CVPR 2022) 
  [[Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Chen_EPro-PnP_Generalized_End-to-End_Probabilistic_Perspective-N-Points_for_Monocular_Object_Pose_Estimation_CVPR_2022_paper.pdf)]<br>
  *Authors: Hansheng Chen, Pichao Wang, Fan Wang, Wei Tian, Lu Xiong, Hao Li*

#### Best Student Paper Honorable Mention:

* Ref-NeRF: Structured View-Dependent Appearance for Neural Radiance Fields (CVPR 2022) 
  [[Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Verbin_Ref-NeRF_Structured_View-Dependent_Appearance_for_Neural_Radiance_Fields_CVPR_2022_paper.pdf)]<br>
  *Authors: Dor Verbin, Peter Hedman, Ben Mildenhall, Todd Zickler, Jonathan Barron, Pratul Srinivasan*

#### Longuet-Higgins Prize (Test of Time):

* Are We Ready for Autonomous Driving? The KITTI Vision Benchmark Suite (CVPR 2012) 
  [[Paper](https://www.cvlibs.net/publications/Geiger2012CVPR.pdf)]<br>
  *Authors: Andreas Geiger, Philip Lenz, Raquel Urtasun*
  
  



## ECCV

### Best Papers 2024

#### Best Paper Award:

* Minimalist Vision with Freeform Pixels (ECCV 2024) 
  [[Paper](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/08113.pdf)]<br>
  *Authors: Jeremy Klotz, Shree Nayar*

#### Best Paper Honorable Mention Award:

* Rasterized Edge Gradients: Handling Discontinuities Differentiably (ECCV 2024) 
  [[Paper](https://arxiv.org/abs/2405.02508)]<br>
  *Authors: Stanislav Pidhorskyi, Tomas Simon, Gabriel Schwartz, He Wen, Yaser Sheikh, Jason Saragih*

* Concept Arithmetics for Circumventing Concept Inhibition in Diffusion Models (ECCV 2024) 
  [[Paper](https://arxiv.org/abs/2404.13706)]<br>
  *Authors: Vitali Petsiuk, Kate Saenko*

#### Award Candidates:

* Robust Fitting on a Gate Quantum Computer (ECCV 2024) 
  [[Paper](https://arxiv.org/abs/2409.02006)]<br>
  *Authors: Frances Fengyi Yang, Michele Sasdelli, Tat-Jun Chin*

* Sapiens: Foundation for Human Vision Models (ECCV 2024) 
  [[Paper](https://arxiv.org/abs/2408.12569)]<br>
  *Authors: Rawal Khirodkar, Timur Bagautdinov, Julieta Martinez, Su Zhaoen, Austin James, Peter Selednik, Stuart Anderson, Shunsuke Saito*

* SEA-RAFT: Simple, Efficient, Accurate RAFT for Optical Flow (ECCV 2024) 
  [[Paper](https://arxiv.org/abs/2405.14793)]<br>
  *Authors: Yihan Wang, Lahav Lipson, Jia Deng*

* Expanding Scene Graph Boundaries: Fully Open-vocabulary Scene Graph Generation via Visual-Concept Alignment and Retention (ECCV 2024) 
  [[Paper](https://arxiv.org/pdf/2311.10988)]<br>
  *Authors: Zuyao Chen, Jinlin Wu, Zhen Lei, Zhaoxiang Zhang, Chang Wen Chen*

* Integer-Valued Training and Spike-driven Inference Spiking Neural Network for High-performance and Energy-efficient Object Detection (ECCV 2024) 
  [[Paper](https://arxiv.org/abs/2407.20708)]<br>
  *Authors: Xinhao Luo, Man Yao, Yuhong Chou, Bo Xu, Guoqi Li*

* Latent Diffusion Prior Enhanced Deep Unfolding for Snapshot Spectral Compressive Imaging (ECCV 2024) 
  [[Paper](https://arxiv.org/abs/2311.14280)]<br>
  *Authors: Zongliang Wu, Ruiying Lu, Ying Fu, Xin Yuan*

* Efficient Bias Mitigation Without Privileged Information (ECCV 2024) 
  [[Paper](https://arxiv.org/abs/2409.17691)]<br>
  *Authors: Mateo Espinosa Zarlenga, Swami Sankaranarayanan, Jerone T. A. Andrews, Zohreh Shams, Mateja Jamnik, Alice Xiang*

* PathMMU: A Massive Multimodal Expert-Level Benchmark for Understanding and Reasoning in Pathology (ECCV 2024) 
  [[Paper](https://arxiv.org/abs/2401.16355)]<br>
  *Authors: Yuxuan Sun, Hao Wu, Chenglu Zhu, Sunyi Zheng, Qizi Chen, Kai Zhang, Yunlong Zhang, Dan Wan, Xiaoxiao Lan, Mengyue Zheng, Jingxiong Li, Xinheng Lyu, Tao Lin, Lin Yang*

* PointLLM: Empowering Large Language Models to Understand Point Clouds (ECCV 2024) 
  [[Paper](https://arxiv.org/abs/2308.16911)]<br>
  *Authors: Runsen Xu, Xiaolong Wang, Tai Wang, Yilun Chen, Jiangmiao Pang, Dahua Lin*

* LEGO: Learning EGOcentric Action Frame Generation via Visual Instruction Tuning (ECCV 2024) 
  [[Paper](https://arxiv.org/abs/2312.03849)]<br>
  *Authors: Bolin Lai, Xiaoliang Dai, Lawrence Chen, Guan Pang, James M Rehg, Miao Liu*

* Controlling the World by Sleight of Hand (ECCV 2024) 
  [[Paper](https://arxiv.org/abs/2408.07147)]<br>
  *Authors: Sruthi Sudhakar, Ruoshi Liu, Basile Van Hoorick, Carl Vondrick, Richard Zemel*

* On the Topology Awareness and Generalization Performance of Graph Neural Networks (ECCV 2024) 
  [[Paper](https://arxiv.org/abs/2403.04482)]<br>
  *Authors: Junwei Su, Chuan Wu*

#### Koenderink Prize (Test of Time):

* Microsoft COCO: Common Objects in Context (ECCV 2014) 
  [[Paper](https://arxiv.org/abs/1405.0312)]<br>
  *Authors: Tsung-Yi Lin, Michael Maire, Serge Belongie, Lubomir Bourdev, Ross Girshick, James Hays, Pietro Perona, Deva Ramanan, C. Lawrence Zitnick, Piotr Dollár*

* LSD-SLAM: Large-Scale Direct Monocular SLAM (ECCV 2014) 
  [[Paper](https://link.springer.com/chapter/10.1007/978-3-319-10605-2_54)]<br>
  *Authors: Jakob Engel, Thomas Schöps, Daniel Cremers*


### Best Papers 2022

#### Best Paper Award:

* On the Versatile Uses of Partial Distance Correlation in Deep Learning (ECCV 2022) 
  [[Paper](https://arxiv.org/abs/2207.09684)]<br>
  *Authors: Xingjian Zhen, Zihang Meng, Rudrasis Chakraborty, Vikas Singh*

#### Best Paper Honorable Mention:

* Pose-NDF: Modelling Human Pose Manifolds with Neural Distance Fields (ECCV 2022) 
  [[Paper](https://arxiv.org/abs/2207.13807)]<br>
  *Authors: Garvita Tiwari, Dimitrije Antic, Jan E. Lenssen,  Nikolaos Sarafianos, Tony Tung, Gerard Pons-Moll*

* A Level Set Theory for Neural Implicit Evolution under Explicit Flows (ECCV 2022) 
  [[Paper](https://arxiv.org/abs/2204.07159)]<br>
  *Authors: Ishit Mehta, Manmohan Chandraker, Ravi Ramamoorthi*

#### Koenderink Prize (Test of Time):

* A Naturalistic Open Source Movie for Optical Flow Evaluation (ECCV 2012) 
  [[Paper](https://link.springer.com/chapter/10.1007/978-3-642-33783-3_44)]<br>
  *Authors: D. Butler, J. Wulff, G.Stanley, M. Black*

* Indoor Segmentation and Support Inference from RGBD Images (ECCV 2012) 
  [[Paper](https://link.springer.com/chapter/10.1007/978-3-642-33715-4_54)]<br>
  *Authors: N. Silberman, D. Hoiem, P. Kohli, R. Fergus*



## AAAI



### Best Papers 2026

#### AAAI-26 outstanding papers

**Model Change for Description Logic Concepts**
*Ana Ozaki, Jandson S Ribeiro*

**Causal Structure Learning for Dynamical Systems with Theoretical Score Analysis**
*Nicholas Tagliapietra, Katharina Ensinger, Christoph Zimmer, Osman Mian*

**ReconVLA: Reconstructive Vision-Language-Action Model as Effective Robot Perceiver**
*Wenxuan Song, Ziyang Zhou, Han Zhao, Jiayi Chen, Pengxiang Ding, Haodong Yan, Yuxin Huang, Feilong Tang, Donglin Wang, Haoang Li*

**LLM2CLIP: Powerful Language Model Unlocks Richer Cross-Modality Representation**
*Weiquan Huang, Aoqi Wu, Yifan Yang, Xufang Luo, Yuqing Yang, Liang Hu, Qi Dai, Chunyu Wang, Xiyang Dai, Dongdong Chen, Chong Luo, Lili Qiu*

**High-pass matters: Theoretical insights and sheaflet-based design for hypergraph neural networks**
*Ming Li, Yujie Fang, Dongrui Shen, Han Feng, Xiaosheng Zhuang, Kelin Xia, Pietro Lio*

#### AAAI-26 outstanding papers – special track on AI for social impact (AISI)

**PlantTraitNet: An Uncertainty-Aware Multimodal Framework for Global-Scale Plant Trait Inference from Citizen Science Data**
*Ayushi Sharma, Johanna Trost, Daniel Lusk, Johannes Dollinger, Julian Schrader, Christian Rossi, Javier Lopatin, Etienne Laliberté, Simon Haberstroh, Jana Eichel, Daniel Mederer, Jose Miguel Cerda-Paredes, Shyam S. Phartyal, Lisa-Maricia Schwarz, Anja Linstädter, Maria Conceição Caldeira, Teja Kattenborn*

**Generalizable Slum Detection from Satellite Imagery with Mixture-of-Experts**
*Sumin Lee, Sungwon Park, Jeasurk Yang, Jihee Kim, Meeyoung Cha*



### Best Papers 2025

#### AAAI-25 Outstanding Paper Awards

**Every Bit Helps: Achieving the Optimal Distortion with a Few Queries**

Soroush Ebadian, Nisarg Shah

**Efficient Rectification of Neuro-Symbolic Reasoning Inconsistencies by Abductive Reflection**

Wen-Chao Hu, Wang-Zhou Dai ,Yuan Jiang, Zhi-Hua Zhou

**Revelations: A Decidable Class of POMDPs with Omega-Regular Objectives**

Marius Belly, Nathanaël Fijalkow, Hugo Gimbert, Florian Horn, Guillermo Perez, Pierre Vandenhove

#### AAAI-25 Outstanding Paper Award – AI for Social Alignment Track

**DivShift: Exploring Domain-Specific Distribution Shifts in Large-Scale, Volunteer-Collected Biodiversity Datasets**

Elena Sierra; Lauren Gillespie; Moises Exposito Alonso

#### AAAI-25 Best Poster Award

**Computing Game Symmetries and Equilibria That Respect Them**

Emanuel Tewolde, Brian Hu Zhang, Caspar Oesterheld, Tuomas Sandholm, Vincent Conitzer

**BindGPT: A Scalable Framework for 3D Molecular Design via Language Modeling and Reinforcement Learning**

Artem Zholus, Maksim Kuznetsov, Roman Schutski, Rim Shayakhmetov, Daniil Polykovskiy, Sarath Chandar, Alex Zhavoronkov

**Eliminating Majority Illusion is Easy**

Jack Dippel, Max Dupre la Tour, April Niu, Sanjukta Roy, Adrian Vetta

#### AAAI-25 Demonstration Awards

**Neurosymbolic Reinforcement Learning: Playing MiniHack With Probabilistic Logic Shields**

David Debot; Gabriele Venturato; Giuseppe Marra; Luc De Raedt

**MerryQuery: A Trustworthy LLM-Powered Tool Providing Personalized Support for Educators and Students**

Benyamin Tabarsi; Aditya Basarkar; Xukun Liu; Dongkuan (DK) Xu; Tiffany Barnes



### Best Papers 2024 

#### Outstanding Paper Award

* GxVAEs: Two Joint VAEs Generate Hit Molecules from Gene Expression Profiles (AAAI 2024) 
  [[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/29248)]<br>
  *Authors: Chen Li; Yoshihiro Yamanishi*

* Reliable Conflictive Multi-view Learning (AAAI 2024) 
  [[Paper](https://arxiv.org/abs/2402.16897)]<br>
  *Authors: Cai Xu; Jiajun Si; Ziyu Guan; Wei Zhao; Yue Wu; Xiyue Gao*

* Proportional Aggregation of Preferences for Sequential Decision Making (AAAI 2024) 
  [[Paper](https://arxiv.org/abs/2306.14858)]<br>
  *Authors: Nikhil Chandak; Shashwat Goel; Dominik Peters*

#### Best Paper for the AI for Social Impact track

* DISCount: Counting in Large Image Collections with Detector-Based Importance Sampling (AAAI 2024) 
  [[Paper](https://arxiv.org/abs/2306.03151)]<br>
  *Authors: Gustavo Perez; Subhransu Maji; Daniel Sheldon*

#### Best Paper for the AI for Social Impact track Honorable Mention

* Nowcasting Temporal Trends Using Indirect Surveys (AAAI 2024) 
  [[Paper](https://arxiv.org/abs/2307.06643)]<br>
  *Authors: Ajitesh Srivastava, Juan Marcos Ramirez, Sergio Díaz, Jose Aguilar, Antonio Fernández Anta, Antonio Ortega, Rosa Lillo*

#### Best Student Paper for the AI for Social Impact track

* Scaling Up Pareto Optimization for Tree Structures with Affine Transformations: Evaluating Hybrid Floating Solar-Hydropower Systems in the Amazon (AAAI 2024) 
  [[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/30210)]<br>
  *Authors: Marc Grimson; Rafael Almeida; Qinru Shi; Yiwei Bai; Hector Angarita; Felipe Siqueira Pacheco; Rafael Schmitt; Alexander Flecker; Carla Gomes*

#### Best Student Paper for the AI for Social Impact track Honorable Mention

* Is My Prediction Arbitrary? The Confounding Effects of Variance in Fair Classification Benchmarks (AAAI 2024) 
  [[Paper](https://arxiv.org/abs/2301.11562)]<br>
  *Authors: A. Feder Cooper; Katherine Lee; Madiha Choksi; Solon Barocas; Christopher De Sa; James Grimmelmann; Jon Kleinberg; Siddhartha Sen; Baobao Zhang*

#### Student Abstract Program Awards

* JoLT: Jointly Learned Representations of Language and Time-Series for Clinical Time-series Interpretation (AAAI 2024) 
  [[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/30423)]<br>
  *Authors: Yifu Cai, Arvind Srinivasan, Mononito Goswami, Arjun Choudhry and Artur Dubrawski*

* Strategic Recommendation: Revenue Optimal Matching for Online Platforms (AAAI 2024) 
  [[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/30432)]<br>
  *Authors: Luca D’Amico-Wong, Gary Qiurui Ma and David Parkes*

#### Best Demonstration Award

* Expressive and Flexible Simulation of Information Spread Strategies in Social Networks Using Planning (AAAI 2024) 
  [[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/30576)]<br>
  *Authors: Bharath Muppasani, Vignesh Narayanan, Biplav Srivastava and Michael N. Huhns*



### Best Papers 2023

#### Outstanding Paper Award

* Misspecification in Inverse Reinforcement Learning (AAAI 2023) 
  [[Paper](https://arxiv.org/abs/2212.03201)]<br>
  *Authors: Joar Skalse, Alessandro Abate*

#### Outstanding Student Paper Award

* Decorate the Newcomers: Visual Domain Prompt for Continual Test Time Adaptation (AAAI 2023) 
  [[Paper](https://arxiv.org/abs/2212.04145)]<br>
  *Authors: Yulu Gan, Yan Bai, Yihang Lou, Xianzheng Ma, Renrui Zhang, Nian Shi, Lin Luo*


#### Distinguished Paper Award

* DropMessage: Unifying Random Dropping for Graph Neural Networks (AAAI 2023) 
  [[Paper](https://arxiv.org/abs/2204.10037)]<br>
  *Authors: Taoran Fang, Zhiqing Xiao, Chunping Wang, Jiarong Xu, Xuan Yang, Yang Yang*

* Two Heads are Better than One: Image-Point Cloud Network for Depth-Based 3D Hand Pose Estimation (AAAI 2023) 
  [[Paper]]<br>
  *Authors: Pengfei Ren, Yuchen Chen, Jiachang Hao, Haifeng Sun, Qi Qi, Jingyu Wang, Jianxin Liao*

* Neural Architecture Search for Wide Spectrum Adversarial Robustness (AAAI 2023) 
  [[Paper]()]<br>
  *Authors: Zhi Cheng, Yanxi Li, Minjing Dong, Xiu Su, Shan You, Chang Xu*

* CowClip: Reducing CTR Prediction Model Training Time from 12 hours to 10 minutes on 1 GPU (AAAI 2023) 
  [[Paper](https://arxiv.org/abs/2204.06240)]<br>
  *Authors: Zangwei Zheng, Pengtai Xu, Xuan Zou, Da Tang, Zhen Li, Chenguang Xi, Peng Wu, Leqi Zou, Yijie Zhu, Ming Chen, Xiangzhuo Ding, Fuzhao Xue, Ziheng Qin, Youlong Cheng, Yang You*

* DICNet: Deep Instance-Level Contrastive Network for Double Incomplete Multi-View MultiLabel Classification (AAAI 2023) 
  [[Paper]]<br>
  *Authors: Chengliang Liu, Jie Wen, Xiaoling Luo, Chao Huang, Zhihao Wu, Yong Xu*

* Exploring Tuning Characteristics of Ventral Stream’s Neurons for Few-Shot Image Classification (AAAI 2023) 
  [[Paper]]<br>
  *Authors: Lintao Dong, Wei Zhai Zheng-Jun Zha*

* MaskBooster: End-to-End Self-Training for Sparsely Supervised Instance Segmentation (AAAI 2023) 
  [[Paper]]<br>
  *Authors: Shida Zheng, Chenshu Chen, Xi Yang, Wenming Tan*

* SimFair: A Unified Framework for Fairness-Aware Multi-Label Classification (AAAI 2023) 
  [[Paper]]<br>
  *Authors: Tianci Liu, Haoyu Wang, Yaqing Wang, Xiaoqian Wang, Lu Su, Jing Gao*

* XRand: Differentially Private Defense against Explanation-Guided Attacks (AAAI 2023) 
  [[Paper](https://arxiv.org/abs/2212.04454)]<br>
  *Authors: Truc Nguyen, Phung Lai, Hai Phan, My T. Thai*

* Clustering What Matters: Optimal Approximation for Clustering with Outliers (AAAI 2023) 
  [[Paper](https://arxiv.org/abs/2212.00696)]<br>
  *Authors: Akanksha Agrawal, Tanmay Inamdar, Saket Saurabh, Jie Xue*

* Robust Average-Reward Markov Decision Processes (AAAI 2023) 
  [[Paper](https://arxiv.org/abs/2301.00858)]<br>
  *Authors: Yue Wang, Alvaro Velasquez, George Atia, Ashley Prater-Bennette, Shaofeng Zou*

* Efficient Answer Enumeration in Description Logics with Functional Roles (AAAI 2023) 
  [[Paper](https://arxiv.org/abs/2211.15248)]<br>
  *Authors: Carsten Lutz, Marcin Przybylko*



### Best Papers 2022

#### Outstanding Paper Award

* Online certification of preference-based fairness for personalized recommender systems (AAAI 2022) 
  [[Paper](https://aaai-2022.virtualchair.net/poster_aaai3798)]<br>
  *Authors: Virginie Do, Sam Corbett-Davies, Jamal Atif, Nicolas Usunier*

#### Outstanding Paper Award Honorable Mention

* Bayesian Persuasion in Sequential Decision-Making (AAAI 2022) 
  [[Paper](https://aaai-2022.virtualchair.net/poster_aaai12585)]<br>
  *Authors: Jiarui Gan, Rupak Majumdar, Goran Radanovic, Adish Singla*

* Operator-Potential Heuristics for Symbolic Search (AAAI 2022) 
  [[Paper](https://aaai-2022.virtualchair.net/poster_aaai2018)]<br>
  *Authors: Daniel Fišer, Alvaro Torralba, Joerg Hoffmann*

#### Outstanding Student Paper Award

* InfoLM: A New Metric to Evaluate Summarization & Data2Text Generation (AAAI 2022) 
  [[Paper](https://aaai-2022.virtualchair.net/poster_aaai4389)]<br>
  *Authors: Pierre Colombo, Chloé Clavel, Pablo Piantanida*

#### Outstanding Student Paper Award Honorable Mention

* Compilation of Aggregates in ASP Systems (AAAI 2022) 
  [[Paper](https://aaai-2022.virtualchair.net/poster_aaai10258)]<br>
  *Authors: Giuseppe Mazzotta, Francesco Ricca, Carmine Dodaro*

* Entropy Estimation via Normalizing Flow (AAAI 2022) 
  [[Paper](https://aaai-2022.virtualchair.net/poster_aaai8184)]<br>
  *Authors: Ziqiao Ao, Jinglai Li*

#### Distinguished Paper Award

* AlphaHoldem: High-Performance Artificial Intelligence for Heads-Up No-Limit Poker via End-to-End Reinforcement Learning (AAAI 2022) 
  [[Paper](https://aaai-2022.virtualchair.net/poster_aaai2268)]<br>
  *Authors: Zhao, Yan, Li, Li, Xing*

* Certified Symmetry and Dominance Breaking for Combinatorial Optimisation (AAAI 2022) 
  [[Paper](https://aaai-2022.virtualchair.net/poster_aaai7842)]<br>
  *Authors: Bogaerts, Gocht, McCreesh, & Nordström*

* Online Elicitation of Necessarily Optimal Matchings (AAAI 2022) 
  [[Paper](https://aaai-2022.virtualchair.net/poster_aaai7693)]<br>
  *Authors: Peters*

* Sampling-Based Robust Control of Autonomous Systems with Non-Gaussian Noise (AAAI 2022) 
  [[Paper](https://aaai-2022.virtualchair.net/poster_aaai12974)]<br>
  *Authors: Badings, Abate, Jansen, Parker, Poonawala, & Stoelinga*

* Subset approximation of Pareto Regions with Bi-objective A* (AAAI 2022) 
  [[Paper](https://aaai-2022.virtualchair.net/poster_aaai10391)]<br>
  *Authors: Rivera, Baier, & Hernandez*

* The SoftCumulative Constraint with Quadratic Penalty (AAAI 2022) 
  [[Paper](https://aaai-2022.virtualchair.net/poster_aaai9956)]<br>
  *Authors: Ouellet & Quimper*



## Test of Time Papers

### ICLR

* Adam: A Method for Stochastic Optimization (ICLR 2015) 
  [[Paper](https://arxiv.org/abs/1412.6980)]<br>
  *Authors: Diederik P. Kingma, Jimmy Ba*

* Neural Machine Translation by Jointly Learning to Align and Translate (ICLR 2015) 
  [[Paper](https://arxiv.org/abs/1409.0473)]<br>
  *Authors: Dzmitry Bahdanau, Kyunghyun Cho, Yoshua Bengio*

* Auto-Encoding Variational Bayes (ICLR 2014) 
  [[Paper](https://arxiv.org/abs/1312.6114)]<br>
  *Authors: Diederik Kingma, Max Welling*

* Intriguing properties of neural networks (ICLR 2014) 
  [[Paper](https://arxiv.org/abs/1312.6199)]<br>
  *Authors: Christian Szegedy, Wojciech Zaremba, Ilya Sutskever, Joan Bruna, Dumitru Erhan, Ian Goodfellow, Rob Fergus*

### NeurIPS

* Faster R-CNN: Towards Real-Time Object Detection with Region Proposal Networks (NeurIPS 2015) 
  [[Paper](https://arxiv.org/abs/1506.01497)]<br>
  *Authors: Shaoqing Ren, Kaiming He, Ross Girshick, Jian*

* Generative Adversarial Nets (NeurIPS 2014) 
  [[Paper](https://arxiv.org/abs/1406.2661)]<br>
  *Authors: Ian Goodfellow, Jean Pouget-Abadie, Mehdi Mirza, Bing Xu, David Warde-Farley, Sherjil Ozair, Aaron Courville, Yoshua Bengio*

* Sequence to Sequence Learning with Neural Networks (NeurIPS 2014) 
  [[Paper](https://arxiv.org/abs/1409.3215)]<br>
  *Authors: Ilya Sutskever, Oriol Vinyals, Quoc V. Le*

* Distributed Representations of Words and Phrases and their Compositionality (NeurIPS 2013) 
  [[Paper](https://papers.nips.cc/paper_files/paper/2013/hash/9aa42b31882ec039965f3c4923ce901b-Abstract.html)]<br>
  *Authors: Tomas Mikolov, Ilya Sutskever, Kai Chen, Greg Corrado, and Jeffrey Dean*

* ImageNet Classification with Deep Convolutional Neural Networks (NeurIPS 2012) 
  [[Paper](https://proceedings.neurips.cc/paper/2012/file/c399862d3b9d6b76c8436e924a68c45b-Paper.pdf)]<br>
  *Authors: Alex Krizhevsky, Ilya Sutskever, and Geoffrey Hinton*

* HOGWILD!: A Lock-Free Approach to Parallelizing Stochastic Gradient Descent (NeurIPS 2011) 
  [[Paper](https://arxiv.org/abs/1106.5730)]<br>
  *Authors: Benjamin Recht, Christopher Re, Stephen Wright, Feng Niu*

* Online Learning for Latent Dirichlet Allocation (NeurIPS 2010) 
  [[Paper](https://proceedings.neurips.cc/paper/2010/file/71f6278d140af599e06ad9bf1ba03cb0-Paper.pdf)]<br>
  *Authors: Matthew Hoffman, David Blei, and Francis Bach*

* Dual Averaging Method for Regularized Stochastic Learning and Online Optimization (NeurIPS 2009) 
  [[Paper](https://papers.nips.cc/paper/3882-dual-averaging-method-for-regularized-stochastic-learning-and-online-optimization.pdf)]<br>
  *Authors: Lin Xiao*

* The Trade-Offs of Large Scale Learning (NeurIPS 2007) 
  [[Paper](https://leon.bottou.org/publications/pdf/nips-2007.pdf)]<br>
  *Authors: Leon Bottou, Olivier Bousquet*

* Random Features for Large-Scale Kernel Machines (NeurIPS 2007) 
  [[Paper](https://papers.nips.cc/paper_files/paper/2007/hash/013a006f03dbc5392effeb8f18fda755-Abstract.html)]<br>
  *Authors: Ali Rahimi, Benjamin Recht*

### ICML

* Batch Normalization: Accelerating Deep Network Training by Reducing Internal Covariate Shift (ICML 2015) 
  [[Paper](https://arxiv.org/abs/1502.03167)]<br>
  *Authors: Sergey Ioffe · Christian Szegedy*

* Trust Region Policy Optimization (ICML 2015) 
  [[Paper](https://arxiv.org/abs/1502.05477)]<br>
  *Authors: John Schulman · Sergey Levine · Pieter Abbeel · Michael Jordan · Philipp Moritz*

* Variational Inference with Normalizing Flows (ICML 2015) 
  [[Paper](https://arxiv.org/abs/1505.05770)]<br>
  *Authors: Danilo Jimenez Rezende · Shakir Mohamed*

* DeCAF: A Deep Convolutional Activation Feature for Generic Visual Recognition (ICML 2014) 
  [[Paper](https://arxiv.org/abs/1310.1531)]<br>
  *Authors: Jeff Donahue, Yangqing Jia, Oriol Vinyals, Judy Hoffman, Ning Zhang, Eric Tzeng, Trevor Darrell*

* Learning Fair Representations (ICML 2013) 
  [[Paper](https://proceedings.mlr.press/v28/zemel13.html)]<br>
  *Authors: Rich Zemel, Yu Wu, Kevin Swersky, Toni Pitassi, Cynthia Dwork*

* Poisoning Attacks Against Support Vector Machines (ICML 2012) 
  [[Paper](https://arxiv.org/abs/1206.6389)]<br>
  *Authors: Battista Biggio, Blaine Nelson, Pavel Laskov*

* Building high-level features using large scale unsupervised learning (ICML 2012) 
  [[Paper](https://arxiv.org/abs/1112.6209)]<br>
  *Authors: Quoc V. Le, Marc'Aurelio Ranzato, Rajat Monga, Matthieu Devin, Kai Chen, Greg S. Corrado, Jeff Dean, Andrew Y. Ng*

* On causal and anticausal learning (ICML 2012) 
  [[Paper](https://arxiv.org/abs/1206.6471)]<br>
  *Authors: Bernhard Schölkopf, Dominik Janzing, Jonas Peters, Eleni Sgouritsa, Kun Zhang, Joris Mooij*

### CVPR

* Going Deeper with Convolutions (CVPR 2015) 
  [[Paper](https://arxiv.org/abs/1409.4842)]<br>
  *Authors:  Christian Szegedy, Wei Liu, Yangqing Jia, Pierre Sermanet, Scott Reed, Dragomir Anguelov, Dumitru Erhan, Vincent Vanhoucke, Andrew Rabinovich*

* Fully Convolutional Networks for Semantic Segmentation (CVPR 2015) 
  [[Paper](https://arxiv.org/abs/1411.4038)]<br>
  *Authors:  Jonathan Long, Evan Shelhamer, Trevor Darrell*

* Rich feature hierarchies for accurate object detection and semantic segmentation (CVPR 2014) 
  [[Paper](https://arxiv.org/abs/1311.2524)]<br>
  *Authors: Ross Girshick, Jeff Donahue, Trevor Darrell, Jitendra Malik*

* Online Object Tracking: A Benchmark (CVPR 2013) 
  [[Paper](https://faculty.ucmerced.edu/mhyang/papers/cvpr13_benchmark.pdf)]<br>
  *Authors: Yi Wu, Jongwoo Lim, Ming-Hsuan Yang*

* Are We Ready for Autonomous Driving? The KITTI Vision Benchmark Suite (CVPR 2012) 
  [[Paper](https://www.cvlibs.net/publications/Geiger2012CVPR.pdf)]<br>
  *Authors: Andreas Geiger, Philip Lenz, Raquel Urtasun*

* Real-time human pose recognition in parts from single depth image (CVPR 2011) 
  [[Paper](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/BodyPartRecognition.pdf)]<br>
  *Authors: Jamie Shotton, Andrew Fitzgibbon, Mat Cook, Toby Sharp, Mark Finocchio, Richard Moore, Alex Kipman, Andrew Blake*

* Baby talk: Understanding and generating simple image descriptions (CVPR 2011) 
  [[Paper](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/BodyPartRecognition.pdf)]<br>
  *Authors: Girish Kulkarni, Visruth Premraj, Sagnik Dhar, Siming Li, Yejin Choi, Alexander C Berg, Tamara L Berg*

* Secrets of Optical Flow Estimation and Their Principles (CVPR 2010) 
  [[Paper](https://cs.brown.edu/people/dqsun/pubs/cvpr_2010_flow.pdf)]<br>
  *Authors: Deqing Sun, Stefan Roth, Michael J. Black*

* ImageNet: A large-scale hierarchical image database (CVPR 2009) 
  [[Paper](https://www.image-net.org/static_files/papers/imagenet_cvpr09.pdf)]<br>
  *Authors: Jia Deng, Wei Dong, Richard Socher, Li-Jia Li, Kai Li and Li Fei-Fei*

* A Discriminatively Trained, Multiscale, Deformable Part Model (CVPR 2008) 
  [[Paper](https://cs.brown.edu/people/pfelzens/papers/latent.pdf)]<br>
  *Authors: Pedro Felzenszwalb, David McAllester, Deva Ramanan*

* Accurate, Dense, and Robust Multi-View Stereopsis (CVPR 2007) 
  [[Paper](https://ieeexplore.ieee.org/document/5226635)]<br>
  *Authors: Yasutaka Furukawa, Jean Ponce*

* Object Retrieval with Large Vocabularies and Fast Spatial Matching (CVPR 2007) 
  [[Paper](https://ieeexplore.ieee.org/document/4270197)]<br>
  *Authors: James Philbin, Ondrej Chum, Michael Isard, Josef Sivic, Andrew Zisserman*

* Beyond Bags of Features: Spatial Pyramid Matching for Recognizing Natural Scene Categories (CVPR 2006) 
  [[Paper](https://ieeexplore.ieee.org/document/1641019)]<br>
  *Authors: S. Lazebnik, C. Schmid, J. Ponce*

* Scalable Recognition with a Vocabulary Tree (CVPR 2006) 
  [[Paper](https://ieeexplore.ieee.org/document/1641018)]<br>
  *Authors: D. Nister, H. Stewenius*

* Histograms of oriented gradients for human detection (CVPR 2005) 
  [[Paper](https://ieeexplore.ieee.org/document/1467360)]<br>
  *Authors: N. Dalal, B. Triggs*

* A non-local algorithm for image denoising (CVPR 2005) 
  [[Paper](https://ieeexplore.ieee.org/document/1467423)]<br>
  *Authors: A. Buades, B. Coll, J.-M. Morel*

* A performance evaluation of local descriptors (CVPR 2004) 
  [[Paper](https://ieeexplore.ieee.org/document/1498756)]<br>
  *Authors: K. Mikolajczyk, C. Schmid*

* Object Class Recognition by Unsupervised Scale-Invariant Learning (CVPR 2003) 
  [[Paper](https://ieeexplore.ieee.org/document/1211479)]<br>
  *Authors: R. Fergus, P. Perona, A. Zisserman*

### ICCV

* Delving Deep into Rectifiers: Surpassing Human-Level Performance on ImageNet Classification (ICCV 2015) 
  [[Paper](https://arxiv.org/abs/1502.01852)]<br>
  *Authors: Kaiming He, Xiangyu Zhang, Shaoqing Ren, Jian Sun*

* Fast R-CNN (ICCV 2015) 
  [[Paper](https://arxiv.org/abs/1504.08083)]<br>
  *Authors: Ross Girshick*

* Action Recognition With Improved Trajectories (ICCV 2013) 
  [[Paper](https://www.cv-foundation.org/openaccess/content_iccv_2013/papers/Wang_Action_Recognition_with_2013_ICCV_paper.pdf)]<br>
  *Authors: H. Wang and C. Schmid*

* ORB: An efficient alternative to SIFT or SURF (ICCV 2011) 
  [[Paper](https://ieeexplore.ieee.org/document/6126544)]<br>
  *Authors: E. Rublee, V. Rabaud, K. Konolige, G. Bradski*

* HMDB: A large video database for human motion recognition (ICCV 2011) 
  [[Paper](https://ieeexplore.ieee.org/document/6126543)]<br>
  *Authors: H. Kuehne, H. Jhuang, E. Garrote, T. Poggio, T. Serre*

* DTAM: Dense tracking and mapping in real-time (ICCV 2011) 
  [[Paper](https://ieeexplore.ieee.org/document/6126513)]<br>
  *Authors: R. Newcombe, S. Lovegrove, A. Davison*

* Building Rome in a Day (ICCV 2009) 
  [[Paper](https://ieeexplore.ieee.org/document/5459148)]<br>
  *Authors: S. Agarwal, N. Snavely, I. Simon, S. M. Seitz, R. Szeliski*

* Attribute and Simile Classifiers for Face Verification (ICCV 2009) 
  [[Paper](https://ieeexplore.ieee.org/document/5459250)]<br>
  *Authors: N. Kumar, A. C. Berg, P. N. Belhumeur, S. K. Nayar*

* Discovering objects and their location in images (ICCV 2005) 
  [[Paper](https://ieeexplore.ieee.org/document/1541280)]<br>
  *Authors: J. Sivic, B. Russell, A. Efros, A. Zisserman, and W. Freeman*

* The pyramid match kernel: Discriminative classification with sets of image features (ICCV 2005) 
  [[Paper](https://ieeexplore.ieee.org/document/1544890)]<br>
  *Authors: K. Grauman and T. Darrell*

* Actions as space-time shapes (ICCV 2005) 
  [[Paper](https://ieeexplore.ieee.org/document/1544882)]<br>
  *Authors: M. Blank, L. Gorelick, E. Shechtman, M. Irani, and R. Basri*

* Space-time interest points (ICCV 2003) 
  [[Paper](https://ieeexplore.ieee.org/document/1238378)]<br>
  *Authors: I. Laptev and T. Lindeberg*

* Recognizing action at a distance (ICCV 2003) 
  [[Paper](https://ieeexplore.ieee.org/document/1238420)]<br>
  *Authors: A. Efros, A. Berg, G. Mori, J. Malik*

* Video Google: A text retrieval approach to object matching in videos (ICCV 2003) 
  [[Paper](https://ieeexplore.ieee.org/document/1238663)]<br>
  *Authors: J. Sivic and A. Zisserman*

* Recognising panoramas (ICCV 2003) 
  [[Paper](https://ieeexplore.ieee.org/document/1238630)]<br>
  *Authors: M. Brown and D. Lowe*

* A Database of Human Segmented Natural Images and Its Application to Evaluating Segmentation Algorithms and Measuring Ecological Statistics (ICCV 2001) 
  [[Paper](https://ieeexplore.ieee.org/document/937655)]<br>
  *Authors: D. Martin, C. Fowlkes, D. Tal, J. Malik*

* Matching Shapes (ICCV 2001) 
  [[Paper](https://ieeexplore.ieee.org/abstract/document/937552)]<br>
  *Authors: S. Belongie, J. Malik, J. Puzicha*


### ECCV

* Microsoft COCO: Common Objects in Context (ECCV 2014) 
  [[Paper](https://arxiv.org/abs/1405.0312)]<br>
  *Authors: Tsung-Yi Lin, Michael Maire, Serge Belongie, Lubomir Bourdev, Ross Girshick, James Hays, Pietro Perona, Deva Ramanan, C. Lawrence Zitnick, Piotr Dollár*

* LSD-SLAM: Large-Scale Direct Monocular SLAM (ECCV 2014) 
  [[Paper](https://link.springer.com/chapter/10.1007/978-3-319-10605-2_54)]<br>
  *Authors: Jakob Engel, Thomas Schöps, Daniel Cremers*


* A Naturalistic Open Source Movie for Optical Flow Evaluation (ECCV 2012) 
  [[Paper](https://link.springer.com/chapter/10.1007/978-3-642-33783-3_44)]<br>
  *Authors: D. Butler, J. Wulff, G.Stanley, M. Black*

* Indoor Segmentation and Support Inference from RGBD Images (ECCV 2012) 
  [[Paper](https://link.springer.com/chapter/10.1007/978-3-642-33715-4_54)]<br>
  *Authors: N. Silberman, D. Hoiem, P. Kohli, R. Fergus*

* Improving the Fisher Kernel for Large-Scale Image Classification (ECCV 2010) 
  [[Paper](https://link.springer.com/chapter/10.1007/978-3-642-15561-1_11)]<br>
  *Authors: F. Perronnin, J. Sánchez, T. Mensink*

* Brief: Binary Robust Independent Elementary Features (ECCV 2010) 
  [[Paper](https://link.springer.com/chapter/10.1007/978-3-642-15561-1_56)]<br>
  *Authors: M. Calonder, V. Lepetit, C. Strecha, P. Fua*

* Hamming Embedding and Weak Geometric Consistency for Large Scale Image Search (ECCV 2008) 
  [[Paper](https://link.springer.com/chapter/10.1007/978-3-540-88682-2_24)]<br>
  *Authors: H. Jegou, M. Douze, and C. Schmid*

* Semi-supervised On-Line Boosting for Robust Tracking (ECCV 2008) 
  [[Paper](https://link.springer.com/chapter/10.1007/978-3-540-88682-2_19)]<br>
  *Authors: H. Grabner, C. Leistner, and H. Bischof*

* Surf: Speeded up robust features (ECCV 2006) 
  [[Paper](https://link.springer.com/chapter/10.1007/11744023_32)]<br>
  *Authors: H. Bay, T. Tuytelaars, L. Van Gool*

* Machine learning for high-speed corner detection (ECCV 2006) 
  [[Paper](https://link.springer.com/chapter/10.1007/11744023_34)]<br>
  *Authors: E. Rosten, T. Drummond*

* Face Recognition with Local Binary Patterns (ECCV 2004) 
  [[Paper](https://link.springer.com/chapter/10.1007/978-3-540-24670-1_36)]<br>
  *Authors: T. Ahonen, A. Hadid, M. Pietikainen*

* High Accuracy Optical Flow Estimation Based on a Theory for Warping (ECCV 2004) 
  [[Paper](https://link.springer.com/chapter/10.1007/978-3-540-24673-2_3)]<br>
  *Authors: T. Brox, A. Bruhn, N. Papenberg, J. Weickert*



## Acknowledgements

This repo builds on **SarahRastegar/Best-Papers-Top-Venues** ([link](https://github.com/SarahRastegar/Best-Papers-Top-Venues)). I extended it by adding more NLP venues (ACL, NAACL, EMNLP) and including the latest AAAI Best Papers for 2025 and 2026. I also plan to update this repo with research trend notes based on the papers in this collection.
