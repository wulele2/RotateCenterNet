# RotateCenterNet
CenterNet基础上实现旋转目标检测
本仓库将所有的遥感数据集：HRSC,SSDD++首先借助DatasetTransform文件夹内的脚本统一将标签转成了[cx,cy,w,h,theta]，theta属于[0,180)的形式，即长边表示法。
然后通过更改cfg的配置文件信息，便可进行训练。
另外，本人添加了可视化的脚本以及计算map的脚本。
好久没用了，有点儿乱。见谅。
