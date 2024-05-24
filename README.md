# driving-scenario-platform
仿真场景平台的架构，平台主要用于：
1. 路测数据上云后的转录及仿真场景格式转换；
2. 仿真场景的管理，根据场景标签进行增删查改等；
3. 调用场景挖掘模块对场景源中的数据进行自动标注和场景挖掘；
4. 场景可视化（基于ThreeJS前端），并支持人工标注；
5. 构建仿真场景集，并对场景集进行增删查改和版本管理；
![alt text](https://github.com/XH-Yang-archive/driving-scenario-platform/blob/main/platform-architecture-1.png?raw=true)

仿真场景定义
1. 仿真场景文件基于proto格式，支持版本间的前后兼容；
2. 仿真场景根据数量集合，从大到小分为场景源、场景库、场景集，其关系如下图所示；
![alt text](https://github.com/XH-Yang-archive/driving-scenario-platform/blob/main/platform-architecture-2.png?raw=true)
