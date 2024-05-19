# Early Stopping for Deep Image Prior (TMLR)

This is the official implementation of Early Stopping for Deep Image Prior, which has been accepted to the [*TMLR*](https://jmlr.org/tmlr/). You can find our paper via either [*OpenReview*](https://openreview.net/forum?id=231ZzrLC8X) or [*arXiv*](https://arxiv.org/abs/2112.06074).


## Dependencies

```
conda env create -f environment.yml
conda activate early-stopping
```

## Google Colab

Google Colab contains all the dependencies our algorithms need. Thus, you are able to run our code directly on Google Colab. Moreover, we recommend you to access the dataset above via Google Drive. After uploading the dataset, you can run DIP with ES-WMV in ES-WMV.ipynb and DIP with ES-EMV in ES-EMV.ipynb, respectively.

## Dataset

We provide a ready-to-use dataset under the folder `/Dataset` where there are 4 types of noises we used in our paper where "XXX_2" indicates "low noise level", "XXX_3" indicates "medium noise level", and "XXX_4" indicates "high noise level".

Alternatively, you can also create the dataset by yourself. The clean images can be downloaded [here](https://webpages.tuni.fi/foi/GCF-BM3D/index.html#ref_results). After you have the clean images, you can follow the [ImageNet-C protocol](https://github.com/hendrycks/robustness) (or write corruption functions by yourself) to create the corrupted images. For the parameters for each noise level, please check the Appendix of [our paper](https://arxiv.org/pdf/2112.06074.pdf).

## Citation/BibTex

```
@article{
wang2023early,
title={Early Stopping for Deep Image Prior},
author={Hengkang Wang and Taihui Li and Zhong Zhuang and Tiancong Chen and Hengyue Liang and Ju Sun},
journal={Transactions on Machine Learning Research},
issn={2835-8856},
year={2023},
url={https://openreview.net/forum?id=231ZzrLC8X},
note={}
}

@misc{wang2021early,
      title={Early Stopping for Deep Image Prior}, 
      author={Hengkang Wang and Taihui Li and Zhong Zhuang and Tiancong Chen and Hengyue Liang and Ju Sun},
      year={2021},
      eprint={2112.06074},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```
## Contact

- Hengkang Wang, wang9881@umn.edu, [https://scholar.google.com/citations?hl=en&user=APqDZvUAAAAJ](https://scholar.google.com/citations?hl=en&user=APqDZvUAAAAJ)
- Taihui Li, lixx5027@umn.edu, [https://taihui.github.io/](https://taihui.github.io/)
- Zhong Zhuang, zhuan143@umn.edu, [https://scholar.google.com/citations?user=rGGxUQEAAAAJ](https://scholar.google.com/citations?user=rGGxUQEAAAAJ)
- Tiancong Chen, chen6271@umn.edu, [https://sites.google.com/view/tiancong-chen](https://sites.google.com/view/tiancong-chen)
- Hengyue Liang, liang656@umn.edu, [https://hengyuel.github.io/](https://hengyuel.github.io/)
- Ju Sun, jusun@umn.edu, [https://sunju.org/](https://sunju.org/)
