# uGis
 A webgis project by liguanzeng.

## 基于WebGIS的神农架金丝猴生境动态监测评价系统

### 所需数据（有待完善）：

1. 物联网数据
   1. 温度
   2. 湿度
2. 气象数据：降水等(找一下获取接口，彩云天气之类的)
3. 金丝猴分布点信息（需要将点数据矢量化）
4. 影像数据（选取适合进行生境识别的影像类型，并进行处理）

### 所需技术栈：

1. 表现层
   1. 地图api：leaflet
   2. 网页开发：
      1. 基础：前端3剑客
      2. 设计优化：Bootstrap
      3. 网页相应：Ajax
   3. 图表api：Echarts
2. 应用层
   - 浏览器
     1. 空间数据可视化：地图
     2. 属性数据可视化：图表
3. 服务层
   1. 地图服务
      - GeoSever
   2. 网页与数据服务
      1. Node.js
      2. Express框架
4. 数据层
   1. PostgreSQL数据库
   2. PostGIS空间数据引擎
   3. QGIS空间数据库管理

## 学习路径

### Leaflet的使用

1. 下载leflet的js包，放在工程文件夹下面；
2. 在工程文件夹下新建index.html文件；
3. 在html文件中通过相对路径引入leaflet的js文件和css文件。

> 注意：js文件为leaflet-src.js，不是leaflet.js