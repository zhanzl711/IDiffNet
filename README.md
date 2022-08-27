# IDiffNet
### Usage:
1. Environment: I have tested this code with python3.7, tensorflow-gpu-1.15.4 
2. Run DiffNet: 
   1. Download the yelp data from this [link](https://drive.google.com/drive/folders/1hIkRDIVI87CUM4xFGjHMeipOlPz97ThX?usp=sharing), and unzip the directories in yelp data to the sub-directory named diffnet of your local clone repository.
   2. cd the sub-directory diffnet and execute the command `python entry.py --data_name=<data_name> --model_name=idiffnet --gpu=<gpu id>` 
3. If you have any available gpu device, you can specify the gpu id, or you can just ignore the gpu id. 

Following are the command examples:  
`python entry.py --data_name=yelp --model_name=idiffnet` 

### Citation:
```
The dataset flickr we use from this paper:
 @article{HASC2019,
  title={A Hierarchical Attention Model for Social Contextual Image Recommendation},
  author={Le, Wu and Lei, Chen and Richang, Hong and Yanjie, Fu and Xing, Xie and Meng, Wang},
  journal={IEEE Transactions on Knowledge and Data Engineering},
  year={2019}
 }

 The algorithm is from DiffNet and DiffNet++:
 @inproceedings{DiffNet2019.
 title={A Neural Influence Diffusion Model for Social Recommendation},
 author={Le Wu, Peijie Sun, Yanjie Fu, Richang Hong, Xiting Wang and Meng Wang},
 conference={42nd International ACM SIGIR Conference on Research and Development in Information Retrieval},
 year={2019}
 }

 @article{wu2020diffnet++,
  title={DiffNet++: A Neural Influence and Interest Diffusion Network for Social Recommendation},
  author={Wu, Le and Li, Junwei and Sun, Peijie and Ge, Yong and Wang, Meng},
  journal={arXiv preprint arXiv:2002.00844},
  year={2020}
 }
 
 We utilized the key technique in following paper to tackle the graph oversmoothing issue, and we have annotated
 the change in line 114 in diffnet/diffnet.py, if you want to konw more details, please refer to:
 @inproceedings{
 title={Revisiting Graph based Collaborative Filtering: A Linear Residual Graph Convolutional Network Approach},
 author={Lei Chen, Le Wu, Richang Hong, Kun Zhang, Meng Wang},
 conference={The 34th AAAI Conference on Artificial Intelligence (AAAI 2020)},
 year={2020}
 }
 ```
