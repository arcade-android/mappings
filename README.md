# ARCADE: Android API Protection Mapping 

[Precise Android API Protection Mapping Derivation and Reasoning]()

Yousra Aafer, Guanhong Tao, Jianjun Huang, Xiangyu Zhang, and Ninghui Li
To appear in Proceedings of 25th ACM SIGSAC Conference on Computer and Communications Security (CCS'18), October' 2018.


## Abstract

The Android research community has long focused on 
building an Android API permission specification, which
can be leveraged by app developers to determine the optimum set of 
permissions necessary for a correct and safe execution of their app.
However, while prominent existing efforts provide a good approximation 
of the permission specification, they suffer from a few shortcomings. 
Dynamic approaches
cannot generate complete results, although accurate for the particular
execution. In contrast, static approaches provide better coverage,
but produce imprecise mappings due to their lack of path-sensitivity. 
In fact, in light of Android's access control complexity, the approximations
 hardly abstract the actual co-relations between enforced protections. 
To address this, we propose to precisely derive Android protection specification
in a path-sensitive fashion, using a novel graph abstraction technique. 
We further showcase how we can apply the generated maps 
to tackle security issues through logical satisfiability reasoning.
Our constructed maps for 4 Android Open Source Project (AOSP) images highlight the significance of
our approach, as ~41% of APIs' protections cannot be correctly modeled 
without our technique. 

## Protection Mappings

[Android 6.0]()
[Android 7.0]()
[Android 7.1]()

### Contact

Email: yaafer at purdue dot edu
