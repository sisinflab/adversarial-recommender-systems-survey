# Adversarial Machine Learning in Recommender Systems:Literature Review and Future Visions

A table of adversarial learning publications in recommender systems. This page will be ****periodically**** updated to include recent works. Please contact us if your work is not in the list. Let us know if your recent work is not in the list, we will be happy to include it!

The table is complement of the survey below.

[***A survey on Adversarial Recommender Systems: from Attack/Defense strategies to Generative Adversarial Networks*** ](https://arxiv.org/abs/2005.10322) 

```
@article{DBLP:journals/corr/abs-2005-10322,
    author = {Yashar Deldjoo and Tommaso {Di Noia} and Felice Antonio Merra},
    title = "A survey on Adversarial Recommender Systems: from Attack/Defense strategies to Generative Adversarial Networks",
    journal = "ACM Computing Surveys",
    year = "2021",
    keywords = "Recommender System, Adversarial Machine Learning,
    Literature Review",
    url       = {https://doi.org/10.1145/3439729},
    doi      = {10.1145/3439729}
}
```

[***Adversarial Machine Learning in Recommender Systems (AML-RecSys)***](https://doi.org/10.1145/3336191.3371877) Tutorial presented at WSDM@2020 [slides](https://github.com/sisinflab/amlrecsys-tutorial/blob/master/Tutorial-AML-RecSys-WSDM2020.pdf)

```
@inproceedings{DBLP:conf/wsdm/DeldjooNM20,
  author    = {Yashar Deldjoo and
               Tommaso Di Noia and
               Felice Antonio Merra},
  title     = {Adversarial Machine Learning in Recommender Systems (AML-RecSys)},
  booktitle = {{WSDM} '20: The Thirteenth {ACM} International Conference on Web Search
               and Data Mining, Houston, TX, USA, February 3-7, 2020},
  year      = {2020},
  url       = {https://doi.org/10.1145/3336191.3371877}
  }
```

## Papers

### ADVERSARIAL MACHINE LEARNING FOR SECURITY OF RS
| Year        | Title           | Type       |   Target Model     | Venue    | Link        |  Code      |
|-------|--------|--------|--------|-----------|---------------|---------|
|2021|**Adversarial Item Promotion: Vulnerabilities at the Core of Top-N Recommenders that Use Images to Address Cold Start**| Attack | DVBPR/VBPR/AMR | WWW| [Link](https://arxiv.org/abs/2006.01888)| [Code](https://github.com/liuzrcc/AIP)|
|2021|**A Black-Box Attack Model for Visually-Aware Recommender Systems**| Attack | VBPR/DeepStyle | WSDM | [Link](https://arxiv.org/pdf/2011.02701.pdf)| [Code](https://github.com/vis-rs-attack/code)|
|2020|**Assessing Perceptual and Recommendation Mutation of Adversarially-Poisoned Visual Recommenders**| Attack | VBPR/AMR | NeurIPS-WS | [Link](http://sisinflab.poliba.it/publications/2020/ADMM20/CR_WDCS_NeurIPS2020_Assessing_Perceptual_and_Recommendation_Mutation_of_Adversarialli_Poisoned_Visual_Recommenders.pdf)| [Code](Perceptual-Rec-Mutation-of-Adv-VRs)|
|2020| **Revisiting Adversarially Learned Injection Attacks Against Recommender Systems**| Attack | CF | RecSys | [Link](https://arxiv.org/abs/2008.04876)| [Code](https://github.com/graytowne/revisit_adv_rec)|
|2020|**Adversarial Learning for Recommendation: Applications for Security and Generative Tasks — Concept to Code**| Tutorial | BPR-MF | RecSys | [Link](https://dl.acm.org/doi/abs/10.1145/3383313.3411447)| [Hands-On](https://github.com/sisinflab/HandsOn-RecSys2020)|
|2020|**TAaMR: Targeted Adversarial Attack against Multimedia Recommender Systems**| Attack | VBPR/AMR | DSN-DSML | [Link](https://ieeexplore.ieee.org/document/9151572)| [Code](https://github.com/sisinflab/TAaMR)|
| 2020 | **Adversarial Training-Based Mean Bayesian Personalized Ranking for Recommender System** | Attack/Defense| BPR-MF | IEEE Access | [Link](https://doi.org/10.1109/ACCESS.2019.2963316) | | 
| 2020 | **Adversarial Learning to Compare: Self-Attentive Prospective Customer Recommendation in Location based Social Networks** | Attack/Defense | LBSN  | WSDM | [Link](https://dl.acm.org/doi/pdf/10.1145/3336191.3371841)| | 
| 2020 | **Privacy-Aware Recommendation with Private-Attribute Protection using Adversarial Learning** | GAN Defense | Attribute-Protection | WSDM | [Link](https://dl.acm.org/doi/abs/10.1145/3336191.3371832) | | 
| 2020 | **Adversarial Machine Learning in Recommender Systems (AML-RecSys)** | Tutorial |  | WSDM | [Link](https://dl.acm.org/doi/abs/10.1145/3336191.3371877) | |
| 2019 | **Adversarial Collaborative Auto-encoder for Top-N Recommendation** | Attack/Defense | CDAE | IJCNN | [Link](https://ieeexplore.ieee.org/document/8851902) | | 
| 2019 | **Adversarial Collaborative Neural Network for Robust Recommendation** | Attack/Defense | CDAE | SIGIR | [Link](https://dl.acm.org/citation.cfm?id=3331321) | | 
| 2019 | **Adversarial Training Towards Robust Multimedia Recommender System** | Attack/Defense | VBPR | TKDE | [Link](https://ieeexplore.ieee.org/document/8618394) | [Code](https://github.com/duxy-me/AMR)| 
| 2019 | **Enhancing the Robustness of Neural Collaborative Filtering Systems Under Malicious Attacks** | Attack/Defense | NCF | IEEE T Mutimedia | [Link](https://ieeexplore.ieee.org/document/8576563) | | 
| 2019 | **Adversarial tensor factorization for context-aware recommendation** | Attack/Defense | FM | RecSys | [Link](https://dl.acm.org/doi/10.1145/3298689.3346987) |  | 
| 2019 | **Adversarial attacks on an oblivious recommender** | GAN Attacks | Linear | RecSys | [Link](https://doi.org/10.1145/3298689.3347031) | | 
| 2019 | **Adversarial Sampling and Training for Semi-Supervised Information Retrieval** | Attack/Defense | MF | WWW |[Link](https://doi.org/10.1145/3308558.3313416) |  | 
| 2019 | **Domain adaptation in display advertising: an application for partner cold-start** | Defense | Adv. Reg. Deep Rec. | RecSys | [Link](https://dl.acm.org/doi/10.1145/3298689.3347004) | | 
| 2019 | **Adversarial Mahalanobis Distance-based Attentive Song Recommender for Automatic Playlist Continuation** | Attack//Defense | MDR | SIGIR | [Paper](https://doi.org/10.1145/3331184.3331234) | [Code](https://github.com/thanhdtran/MASR)| 
| 2018 | **Adversarial Personalized Ranking for Recommendation**  | Attack/Defense  |  BPR-MF | SIGIR | [Link](https://doi.org/10.1145/3209978.3209981) | [Code](https://github.com/hexiangnan/adversarial_personalized_ranking) |


### ADVERSARIAL LEARNING FOR GAN-BASED RECOMMENDATION
| Year        | Title           |   Rec. Model | Venue    | Link        |  Code |
|-------|--------|--------|-----------|---------------|-------|
|2020|**LARA: Attribute-to-feature Adversarial Learning for New-item Recommendation**| Hybrid | WSDM | [Link](https://doi.org/10.1145/3336191.3371805)||
|2019|**Collaborative Adversarial Autoencoders: An Effective Collaborative Filtering Model Under the GAN Framework**| Collaborative | IEEE Access | [Link](https://doi.org/10.1109/ACCESS.2019.2905876)||
|2019|**Collaborative Generative Adversarial Network for Recommendation Systems**| Collaborative |ICDE | [Link](https://doi.org/10.1109/ICDEW.2019.00-16)||
|2019|**Convolutional Adversarial Latent Factor Model for Recommender System**| Collaborative | AAAI | [Link](https://aaai.org/ocs/index.php/FLAIRS/FLAIRS19/paper/view/18200)||
|2019|**PD-GAN: Adversarial Learning for Personalized Diversity-Promoting Recommendation**| Collaborative | IJCAI | [Link](https://dl.acm.org/citation.cfm?id=3367471.3367579)||
|2019|**LambdaGAN: Generative Adversarial Nets for Recommendation Task with Lambda Strategy**| Collaborative |IJCNN | [Link](https://ieeexplore.ieee.org/document/8851869)||
|2019|**VAEGAN: A Collaborative Filtering Framework based on Adversarial Variational Autoencoders**| Collaborative |IJCAI | [Link](https://doi.org/10.24963/ijcai.2019/584)||
|2019|**RsyGAN: Generative Adversarial Network for Recommender Systems**| Collaborative | IJCNN | [Link](https://doi.org/10.1109/IJCNN.2019.8851727)||
|2019|**Adversarial Distillation (Transfer) for Efficient Recommendation with External Knowledge**| Hybrid |TIST | [Link](https://doi.org/10.1145/3281659)| |
|2019|**Adversarial Training for Review-Based Recommendations**|  | SIGIR | [Link](https://doi.org/10.1145/3331184.3331313)||
|2019|**Enhancing Collaborative Filtering with Generative Augmentation**| Hybrid | KDD | [Link](https://dl.acm.org/doi/10.1145/3292500.3330873)||
|2019|**APL: Adversarial Pairwise Learning for Recommender Systems**| Collaborative |Expert Syst. Appl. | [Link](https://www.sciencedirect.com/science/article/pii/S0957417418306742)|[Code](https://github.com/ZhongchuanSun/APL.)|
|2019|**Generating Reliable Friends via Adversarial Training to Improve Social Recommendation.**| Social | ICDM | [Link](https://doi.org/10.1109/ICDM.2019.00087)||
|2019|**Utilizing Generative Adversarial Networks for Recommendation based on Ratings and Reviews**| Collaborative | IJCNN | [Link](https://doi.org/10.1109/IJCNN.2019.8851822)||
|2019|**A Minimax Game for Generative and Discriminative Sample Models for Recommendation**| Hybrid | PAKDD | [Link](https://link.springer.com/chapter/10.1007/978-3-030-16145-3_33)||
|2019|**Leveraging Long and Short-Term Information in Content-Aware Movie Recommendation via Adversarial Training**| Time-aware | IEEE T CYBERNETICS | [Link](https://ieeexplore.ieee.org/document/8643032)||
|2019|**Generative Adversarial User Model for Reinforcement Learning Based Recommendation System**| CTR | ICML | [Link](http://proceedings.mlr.press/v97/chen19f/chen19f.pdf)|[Code](https://github.com/xinshi-chen/GenerativeAdversarialUserModel)|
|2019|**Adversarial Point-of-Interest Recommendation.**| POI | WWW | [Link](https://dl.acm.org/doi/10.1145/3308558.3313609)|[Code](https://github.com/APOIR2018/APOIR)|
|2019|**Deep Adversarial Social Recommendation**| Social | IJCAI | [Link](https://doi.org/10.24963/ijcai.2019/187)||
|2019|**Click Feedback-Aware Query Recommendation Using Adversarial Examples**| Query | WWW | [Link](https://doi.org/10.1145/3308558.3313412)||
|2019|**Scenery-Based Fashion Recommendation with Cross-Domain Geneartive Adverserial Networks**| Fashion | BIGCOMP | [Link](https://ieeexplore.ieee.org/document/8679117)||
|2019|**RecSys-DAN: Discriminative Adversarial Networks for Cross-Domain Recommender Systems**| Fashion | IEEE-TNNLS | [Link](https://ieeexplore.ieee.org/iel7/5962385/6104215/08698453.pdf)||
|2019|**CnGAN: Generative Adversarial Networks for Cross-network user preference generation for non-overlapped users**| Cross Domain | WWW | [Link](https://doi.org/10.1145/3308558.3313733)|[Code](https://dinry.github.io/CnGAN/)|
|2019|**C+GAN: Complementary Fashion Item Recommendation**| Fashion | KDD | [Link](https://arxiv.org/pdf/1906.05596)||
|2019|**Rating Augmentation with Generative Adversarial Networks towards Accurate Collaborative Filtering**| Collaborative | WWW | [Link](https://doi.org/10.1145/3308558.3313413)||
|2019|**Privacy and Fairness in Recommender Systems via Adversarial Training of User Representations**| Privacy |ICPRAM | [Link](https://doi.org/10.5220/0007361204760482)||
|2018|**CFGAN: A Generic Collaborative Filtering Framework based on Generative Adversarial Networks**| Collaborative | CIKM | [Link](https://doi.org/10.1145/3269206.3271743)|[Code](https://github.com/Coder-Yu/RecQ)|
|2018|**Adversarial Training of Deep Autoencoders Towards Recommendation Tasks**| Collaborative | IC-NIDC | [Link](https://doi.org/10.1109/ICNIDC.2018.8525831)||
|2018|**Generative Adversarial Network Based Heterogeneous Bibliographic Net Representation for Personalized Citation Rec** | Collaborative  | AAAI | [Link](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/16310)||
|2018|**GraphGAN: Graph Representation Learning With Generative Adversarial Nets**| Collaborative | AAAI | [Link](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/16611)|[Code](https://github.com/hwwang55/GraphGAN)|
|2018|**A Novel Personalized Citation Recommendation Approach Based on GAN**| Collaborative | ISMIS | [Link](https://doi.org/10.1007/978-3-030-01851-1_26)||
|2018|**Leveraging Reconstructive Profiles of Users and Items for Tag-Aware Recommendation**| Hybrid | ICDM | [Link](https://doi.org/10.1109/ICDMW.2018.00184)||
|2018|**Rating Prediction in Review-Based Recommendations via Adversarial Auto-Encoder.**| Hybrid |WI | [Link](https://doi.org/10.1109/WI.2018.00-96)||
|2018|**PLASTIC: Prioritize Long and Short-term Information in Top-n Recommendation using Adversarial Training.**| Sequence-aware |IJCAI  | [Link](https://doi.org/10.24963/ijcai.2018/511)||
|2018|**Using Adversarial Autoencoders for Multi-Modal Automatic Playlist Continuation**| Sequence-aware | RecSys | [Link](https://doi.org/10.1145/3267471.3267476)|[Code](https://github.com/lgalke/aae-recommender)|
|2018|**Multi-Modal Adversarial Autoencoders for Recommendations of Citations and Subject Labels.**| Sequence-aware |UMAP | [Link](https://doi.org/10.1145/3209219.3209236)|[Code](https://github.com/lgalke/aae-recommender)|
|2018|**Neural Memory Streaming Recommender Networks with Adversarial Training.**| Sequence-aware | KDD | [Link](https://doi.org/10.1145/3219819.3220004)||
|2018|**RecGAN: recurrent generative adversarial networks for recommendation systems**| Sequence-aware | RecSys | [Link](https://doi.org/10.1145/3240323.3240383)||
|2018|**Compatibility Family Learning for Item Recommendation and Generation**| Fashion | AAAI | [Link](https://doi.org/10.1109/icdh.2018.00040)|[Code]()|
|2018|**CRAFT: Complementary Recommendation by Adversarial Feature Transform**| Fashion |ECCV | [Link](https://doi.org/10.1007/978-3-030-11015-4_7)||
|2018|**An Adversarial Approach to Improve Long-Tail Performance in Neural Collaborative Filtering**| Collaborative | CIKM | [Link](https://doi.org/10.1145/3269206.3269264)||
|2017|**Augmented variational autoencoders for collaborative filtering with auxiliary information**| Collaborative | CIKM | [Link](https://doi.org/10.1145/3132847.3132972)||
|2017|**Visually-Aware Fashion Recommendation and Design with Generative Image Models**| Fashion | ICDM | [Link](https://doi.org/10.1007/978-3-030-11015-4_7)|[Code](https://github.com/kang205/DVBPR)|
|2017|**IRGAN: A Minimax Game for Unifying Generative and Discriminative Information Retrieval Models**| Collaborative | SIGIR | [Link](https://doi.org/10.1145/3077136.3080786)| [Code](https://github.com/hzhao/irgan)|

## Authors

This page is managed and maintained by:
* Felice Antonio Merra <felice.merra@poliba.it>
* Yashar Deldjoo <yashar.deldjoo@poliba.it>
* Tommaso Di Noia <tommaso.dinoia@poliba.it>
