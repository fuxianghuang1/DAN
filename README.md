# [IEEE TCSVT] DAN: Cross-Modal Cross-Domain Dual Alignment Network for RGB-Infrared Person Re-Identification

- The [paper](https://ieeexplore.ieee.org/document/9770780) can be accessed at IEEE Transactions on Circuits and Systems for Video Technology.
- The link to the synthetic data is [here](https://pan.baidu.com/s/1XqL0PQo8pIlvFkoXdoN64g?pwd=cp9y) The train/test split of synthetic data follows the settings of the original RegDB and SYSU.


If you find this code useful in your research then please cite


```bibtex
@article{fu2022cross,
  title={Cross-modal cross-domain dual alignment network for RGB-infrared person re-identification},
  author={Fu, Xiaowei and Huang, Fuxiang and Zhou, Yuhang and Ma, Huimin and Xu, Xin and Zhang, Lei},
  journal={IEEE Transactions on Circuits and Systems for Video Technology},
  volume={32},
  number={10},
  pages={6874--6887},
  year={2022},
  publisher={IEEE}
}

```


## Abstract
RGB-Infrared cross-modal person re-identification (Re-ID) has drawn increasing attention due to its application value in practice. Most of the current works rely on a supervised training manner. However, in real-world applications, manual collection of pair-wise RGB-Infrared (IR) person data is labor-intensive and time-consuming. Moreover, when a trained model is directly used in another domain, there is usually a significant performance drop. To overcome the above problems, we make the first attempt to transfer the learned model to a new RGB-IR domain which is unlabeled. The practical problem covers two kinds of challenges, i.e., cross-modal (RGB-Infrared) and cross-domain (different dataset) person Re-ID. Previous works have often considered only one of them either cross-modal or cross-domain. In this work, we propose a dual alignment network (DAN) to solve the RGB-Infrared cross-modal cross-domain person Re-ID problem. This network consists of three parts: Domain Adversarial Alignment component (DAA), Pseudo Label Generation module for target domain (PLG), and Cross-Modal Alignment component (CMA). These three modules complement and promote the model to learn domain-invariant and modality-invariant person representations. Further, we propose a protocol of cross-modal cross-domain person Re-ID by synthesizing target domains by adding random noise, adjusting the lighting intensity, and changing the background color, respectively. Experiments on real and synthetic datasets under the same cross-modalities across domains demonstrate the effectiveness of our method.
