
# 规则包内容

1. GetBox_fc.rpk
把multipatch模型变成白模盒子。
2. GetBox_obj.rpk
根据输入的obj模型生成白模盒子。
3. 地下管线建模.rpk
@InLine
4. 管井建模(柱状).rpk
@InPoint
5. 管井建模(酒瓶状).rpk 
@InPoint
6. 管井（真实纹理）.rpk
@InPoint
7. UrbanDesigner.rpk
@InPolygon
建筑高度由几何中心向四周总体递减。
8. cleanupshape.rpk
大数据量时CE可能会闪退或假死。这个规则可在ArcGIS Pro执行，用来简化精模（multipatch）面片数，减少数据量。
9. 雨篦（真实纹理）.rpk
@InPoint

