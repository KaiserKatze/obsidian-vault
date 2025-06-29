1. [A Flexible New Technique for Camera Calibration](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/tr98-71.pdf)
	阅读中产生的疑问：
	- 光照的明暗，物体的高光、阴影，对于自校准有无影响？
	- 论文发表时间是1998年，当时说自校准方法尚不成熟，现在的情况如何呢？
	- 张正友提到了 Bill Triggs 的校准方法、 Liebowitz 和 Zisserman 的校准方法，有没有必要去跟踪这些方法的后续发展？
	- 有没有必要学习一下射影几何、光学？
	- 第4页底部 2.4 Geometric Interpretation 部分说，`This plane intersects the plane at infinity at a line`，这是什么意思？是指模型平面与像平面相交吗？
	- 第6页中间提到“当 $n=1$ 时”与“头部姿态识别程序”有什么联系？对我来说，思维有点太跳跃了.
	- 第6页末尾的 $\hat{m}$ 是一个映射吧？$R_i$ 是什么意思？是不是把旋转矩阵 $R$ 的列向量 $r_i$ 打错成大写字母了？【我想明白了，$R_i$ 表示第 $i$ 张图像对应的旋转矩阵】
	- 第9页 5.1 Computer Simulations 为什么说 $\gamma=1.09083$ 相当于 $89.95^\circ$ 呢？【已解决，见[[像轴偏度]]】
