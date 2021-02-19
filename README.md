# QTool_Model-_By-_mmcww

总线-模块-生产树 量化工具
=========================

功能简介  
-----

1.基础量化功能:<br>
>>>>点击相应产物的图标将会生成合成路线树，在右侧 统计-产物 中设置 产物的每分钟产量，点击计算生成结果，<br>
>>>>在统计视图或树状图中查看计算结果（原料需求，产物/副产物统计，功率参考，工厂数量统计，分拣器数量参考），<br>
>>>>可以切换不同的配方，除树顶点外的其他产物可以切换为无配方<br>

2.模块化功能:<br>
>>>>将所有合成树中的某一配方模块化（或者手动添加），生成新的合成树，视图中其他树中对应的中间产物将由该树提供，<br>
>>>>在 统计-计算 中可以设置除模块必要需求之外的额外产量<br>
>>>>产物的比例：可以重复添加同样的树，并设置它们作为模块产物的比例(0%~100%)<br>
>>>>（如果有其他树需要该种原材料，将会按比例对多个同样的该产物分配需求），<br>
>>>>被设计用来协调同种产物多种配方的情况，统一输入后，执行计算将会对比例归一化处理，<br>
>>>>如果输入所有同种产物的比例之和为100%则归一化处理无误差。

3.模块总线化:
>>>>调整好各模块后，点击该按钮将会对视图中所有树进行排序，顺序为一级产物，二级产物......方便搭建总线结构的生产线

---------------------------------

快捷键  
------
		左ctrl按住+鼠标左键 = 切换配方  
		左Alt按住+鼠标左键 = 模块化配方  
		树状视图可以用鼠标滚轮放缩，鼠标右键按住拖动视图  
		右侧信息栏 鼠标停留在上方 滚轮可快速切换页面  
		点击空白处取消鼠标焦点后 q键打开/关闭信息 视图  
		取消鼠标焦点情况下 按回车执行计算  
		Backspace 清空重置  
		选中顶端产物 delete 删除整棵生产树
  
  效果图
  -------
  >>所有建筑10/min
  ![image](https://github.com/dsp-mod/QTool_Model_By_mmcww/blob/main/images/testv3_1.png)
  ![image](https://github.com/dsp-mod/QTool_Model_By_mmcww/blob/main/images/testv3_2.png)
  ![image](https://github.com/dsp-mod/QTool_Model_By_mmcww/blob/main/images/testv3_4.png)
  ![image](https://github.com/dsp-mod/QTool_Model_By_mmcww/blob/main/images/testv3_5.png)
  ![image](https://github.com/dsp-mod/QTool_Model_By_mmcww/blob/main/images/testv3_6.png)
  
  
  
  
