# Learning-Aided 3D Mapping
---
A suite of algorithms for learning-aided mapping. Includes implementations of Gaussian process regression and Bayesian generalized kernel inference for occupancy prediction using test-data octrees. This framework also contains the components necessary to run OctoMap as a baseline.


## Overview
---
This implementation as it stands now is primarily intended to enable replication of these methods over a few datasets.

If you found this code useful, please consider citing the following:

Fast, accurate gaussian process occupancy maps via test-data octrees and nested Bayesian fusion ([PDF](http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7487232))
```
@INPROCEEDINGS{JWang-ICRA-16,
author={J. Wang and B. Englot},
booktitle={2016 IEEE International Conference on Robotics and Automation (ICRA)},
title={Fast, accurate gaussian process occupancy maps via test-data octrees and nested Bayesian fusion},
year={2016},
pages={1003-1010},
month={May},
}
```

Bayesian Generalized Kernel Inference for Occupancy Map Prediction ([PDF](http://personal.stevens.edu/~benglot/Doherty_Wang_Englot_ICRA_2017.pdf))
```
@INPROCEEDINGS{KDoherty-ICRA-17,
author={K. Doherty, J. Wang, and B. Englot},
booktitle={2017 IEEE International Conference on Robotics and Automation (ICRA)},
title={Bayesian Generalized Kernel Inference for Occupancy Map Prediction},
year={2017},
month={May},
}
```