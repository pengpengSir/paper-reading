# 记录读过的论文
##  SOSP
#### [Kangaroo: Caching Billions of Tiny Objects on Flash](https://dl.acm.org/doi/pdf/10.1145/3477132.3483568)
- 目的: 高效、底层本缓存小对象
- DRAM + KLog + Kset
- **`RRIP`**: 缓存替换算法，使用几个bit来标识`object`是否使用过
- 论文解读: [知乎丁凯的论文解读](https://zhuanlan.zhihu.com/p/527696328)
