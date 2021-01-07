用于复现论文代码
原地址：https://github.com/gjy3035/SCAR

## Tips

In this code, the validation is directly on the test set. Strictly speaking, it should be evaluated on the val set (randomly selected from the training set, which is adopted in the paper). Here, for a comparable reproduction (namely fixed splitting sets), this code directly adopts the test set for validation, which causes that the results of this code are better than that of our paper. If you use this repo for academic research, you need to select 10% training data (or other value) as validation set. 

## Citation
If you find this project is useful for your research, please cite:
```
@inproceedings{wang2019learning,
  title={Learning from Synthetic Data for Crowd Counting in the Wild},
  author={Wang, Qi and Gao, Junyu and Lin, Wei and Yuan, Yuan},
  booktitle={Proceedings of IEEE Conference on Computer Vision and Pattern Recognition (CVPR)},
  pages-{8198--8207},
  year={2019}
}
```
```
@article{gao2019c,
  title={C$^3$ Framework: An Open-source PyTorch Code for Crowd Counting},
  author={Gao, Junyu and Lin, Wei and Zhao, Bin and Wang, Dong and Gao, Chenyu and Wen, Jun},
  journal={arXiv preprint arXiv:1907.02724},
  year={2019}
}
```
