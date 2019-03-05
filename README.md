# DeepClusterADMM
This repository is provided to reproduce the results of our paper "DeepCluster: A General Clustering Framework based on Deep Learning" on ECML/PKDD 2017.
All those softwares are implemented in MATLAB.

## Quick Start
To let you start the code quickly, we incorprated the pretrained weights of DAE.

Startup your MATLAB, and simply run 
```
demo
```
to see the basic performance of DeepCluster.

To dive into the implementation of DeepCluster. See
```
run_dkmeans.m
run_dgmm_full.m
```

## Make it better
If you have better implementations or better hyper-parameter settings, please pull your requests. 

## Notes
As there exists random initialization of clustering methods, so it is normal to have permissible error compared to the results as reported in the paper. 

## Bibtex
If you use this code please refer our paper. We appreciate it.
```
@inproceedings{tian2017deepcluster,
  title={Deepcluster: A general clustering framework based on deep learning},
  author={Tian, Kai and Zhou, Shuigeng and Guan, Jihong},
  booktitle={Joint European Conference on Machine Learning and Knowledge Discovery in Databases},
  pages={809--825},
  year={2017},
  organization={Springer}
}
```
