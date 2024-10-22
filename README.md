# shp23dtile
背景：
cesiums开发者遇到大量点云数据时，shp转3dtile时较为复杂。
shp转3dtile格式有多个方法，cesiumlab是官方方法，耗时较长，且长期使用需要认证和付费。
基于GIS出身，我编写了一个小工具，喜欢请点个收藏。

English:
The shp to 3dtile is more complicated when cesiums developers encounter large amounts of point cloud data.
Based on the GIS origin, I wrote a small tool, like please click a Star.

步骤：

1.shp转las: shp2las.py

2.las转3dtile：
  安装py3dtiles安装包
  cmd：py3dtiles convert --input F:\vector.las --output tileset

暂未解决：
    无法保存shp文件的其他属性信息。


