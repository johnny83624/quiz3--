# Ship Target Tracking Algorithm Based on Adaptive Improvement Unscented Particle Filter

Abstract—Aiming at the impact of limited network transmission bandwidth and strong clutter interference on ship tracking, an adaptive unscented particle filter fusion method combined with adaptive bit quantization technology for ship tracking is studied.First of all, two clusters were performed using information such as the location of the radiation source and carrier frequency to achieve data compression and clutter suppression;Next, apply adaptive bit quantization technology to obtain random quantized observations of each tracking node to the moving ship.The process is modeled by the first-order Markov model with random noise, and the quantization error is used as the component of the system state estimation to establish a target tracking model with unknown variance of part of the process noise component.Finally, using the adaptive unscented particle filter as the basic filter, the Sage-Husa estimator is used to estimate and correct the statistical characteristics of unknown noise in real time, and a centralized multi-sensor fusion method for offshore ship tracking is derived.The simulation results show that the algorithm can effectively improve the fusion estimation accuracy of the quantization filter.

quiz3-黄凡
如果你希望嵌入一张图片，可以这么做：
 
![Yaktocat 的图片](https://octodex.github.com/images/yaktocat.png)
