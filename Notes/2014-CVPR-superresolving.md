# Super-Resolving Noisy Images

2014 CVPR, Abhishek Singh, Fatih Porikli, Narendra Ahuja

### Main idea

Combine HR bersions of both noisy and denoised images --> part-recovery and part-synthesis of textures

### Algorithm

Convex combination (of over-smoothed and noisy) in different sub-bands: (1-A) * B(dn) + A * B(n)  
A = alpha * V * W

* V: Spatial Constraint: where to blend, variance Map estimation 
* W: which frequncies to blend, high enery sub-band
* alpha: weight, estimated by kurtosis

