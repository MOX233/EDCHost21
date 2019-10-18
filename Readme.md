# EDCHost21

- v1.0：实时检测小球是否被小车抓住
- v2.0：基于小球计数判定得分
- v3.0：新规则(v1.4)

## 使用方法
- “开始”之前要先点一下场地的四个角校正坐标，从左上-右上-左下-右下。
- 使用颜色进行小车及小球位置的识别。使用的是HSV(Hue, Sat, Val)颜色空间：0是小球颜色，1和2分别是A、B车颜色；Hue1L和Hue1H是色调的上下限；Sat1L是饱和度的下限，没有上限；ValueL是明度的下限，没有上限；AreaL是有效面积的下限，没有上限。
- 切换小节时先单击“下一节”，再单击“开始”进入计时。
- 在“设置”中，可以切换串口端口号Port和摄像头编号Capture。
