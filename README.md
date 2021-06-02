# 1. 如何使用

进入`main_regularization.py`修改图片输入路径，目前主文件写作思路是给定一张建筑物二值分割结果图，首先进行联通域提取（无法解决粘连现象，这种前面可能要用实例分割），然后遍历每一个建筑物mask执行轮廓规则化。

# 2. 效果图

![xiaoguo](/Volumes/Seagate Expansion Drive/wbproject/qf/code/RS-building-regularization/output_data/all_out.jpg)