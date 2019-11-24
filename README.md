# transportX
大创项目  
项目应该包含
- 单片机部分
    - 单片机代码
    - 单片机板布局图
- 设备控制平台部分  
    考虑尝试Blazor或者前后全nodejs
- 可能的商用平台部分  
    考虑尝试Blazor或者前后全nodejs

1. 单片机  
单片机打算使用sipeed.  
功能需求有: 
    - 自主的严格避障
    - 打电话
    - 从服务器获取规划的路径 / 使用地图API规划路径, 自我位置获取主要依赖RTK
    - 记录最近的行动记录, 如果到达无信号的地带, 可沿原路返回  
2. 控制平台  
    - 记录设备状态
    - 与指定设备交流
    - 规划路径
