## 定制化大屏

### 项目描述
定制化大屏（国家开发银行、大连银行、江西银行、湖南国税、甘肃国税等）。

### 项目周期
每个大屏开发周期大约1-2周。

### 技术描述
定制化大屏是以数据的可视化为主的单页面应用（主要Echarts为主扩展的一些业务上的应用组件，数值显示用到的countUp插件）
大屏功能模块：
* 业务墙
* 仪表盘式数值
* 地图散点图
* top排行
* ine、bar数据展示
* 数值动态跳动展示
* 数值翻牌展示。
使用的技术栈包含vue2.0、webpack3.0、echarts、canvas框架zrender和svg框架snag.svg，其中使用zrender和snag.svg实现了一些特殊功能，如展示各业务系统之间的流量和速度，通过snag,svg绘制路径并计算路径上各点坐标和切线角度，使用zrender绘制路径上的箭头，并控制其沿路径移动。

## 项目展示
