### 名称

高位占道停车检测

### 描述

划定视频源场景中的停车检测线区域、车位整体区域、具体车位区域，检测车辆进出各区域的信息并持续输出其停车、驶出的信息

### 类型

* [ ] 检测

* [ ] 分类

* [x] 融合

### 配置参数

| 参数名称 | 参数描述 | 默认值 |
| :---: | :---: | :---: |
| Confidence| 目标检测精准度阈值 | 0.5 |
| Draw_flags | 是否绘制对象框 | true |
| draw_zone_flags | 是否绘制布控区域框 | true |
| Detection_area | 停车检测线区域信息 | [] |
| Car_areas | 车位整体区域信息 | [] |
| Car_area | 具体车位区域信息 | [] |

### 输出结果

1 场景数据输出


2 跟踪数据输出

{"AttributesOutputJson":{"attr":{"color":"blue","park_area":"A","plate":"渝ADD1225","type":"car"},"height":336,"track_id":1,"width":396,"x":1067,"y":474},"DateTime":"2022-04-14 10:07:38","GPSPosition":"","CarImages":["BASE64","BASE64","BASE64"],"ObjectType":"car","CarState":"park"}