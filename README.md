#Datasets
Please click [here](https://drive.google.com/drive/folders/1TFpxSIdQclmbcSA3dw8tU1pmbZUcGl6m?usp=sharing) to download the datasets.\
Once you have the data, put it in a folder and share the folder path inside the code.\
If you have any suggestions, feel free to send a pull request.

# Dynamic VAEs with Generative Replay for Continual Zero-shot Learning
This is the official PyTorch implementation of [Dynamic VAEs with Generative Replay for Continual Zero-shot Learning](https://arxiv.org/abs/2102.03778). The paper has been accepted at CVPR, 2021 for Findings.
# Abstract 
Continual zero-shot learning(CZSL) is a new domain to classify objects sequentially the model has not seen during training. It is more suitable than zero-shot and continual learning approaches in real-case scenarios when data may come continually with only attributes for a few classes and attributes and features for other classes. Continual learning(CL) suffers from catastrophic forgetting, and zero-shot learning(ZSL) models cannot classify objects like state-of-the-art supervised classifiers due to lack of actual data(or features) during training. This paper proposes a novel continual zero-shot learning (DVGR-CZSL) model that grows in size with each task and uses generative replay to update itself with previously learned classes to avoid forgetting. We demonstrate our hybrid model(DVGR-CZSL) outperforms the baselines and is effective on several datasets, i.e., CUB, AWA1, AWA2, and aPY. We show our method is superior in task sequentially learning with ZSL(Zero-Shot Learning). We also discuss our results on the SUN dataset.

# Authors:
[Subhankar Ghosh](https://sites.google.com/view/subhankarghosh/home)(Indian Institute of Science)
# Citation
If using this code, parts of it, or developments from it, please cite our paper:
```
@article{ghosh2021adversarial,
  title={Adversarial Training of Variational Auto-encoders for Continual Zero-shot Learning},
  author={Ghosh, Subhankar},
  journal={arXiv preprint arXiv:2102.03778},
  year={2021}
}
```

# Questions/ Bugs
For questions and bugs, please contact the author Subhankar Ghosh via email [subhankarg@alum.iis.ac.in](mailto:x@x.com)
# License
This source code is released under The MIT License found in the [LICENSE](https://github.com/DVGR-CZSL/DVGR-CZSL/blob/main/LICENSE) file in the root directory of this source tree.


