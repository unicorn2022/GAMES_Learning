[TOC]

# 十四、光线追踪2：使用AABB包围盒加速光线追踪

## 14.1	统一空间分区 Uniform Spatial Partitions

1. 找到包围盒

2. 将包围盒分为格子`Grid`

3. 如果某个格子与物体的表面相交，则标记该格子

   <img src="AssetMarkdown/image-20230321222357738.png" alt="image-20230321222357738" style="zoom:80%;" />

4. 将光线与格子求交