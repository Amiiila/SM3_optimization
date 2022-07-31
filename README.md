# SM3_optimization
do your best to optimize SM3 implementation (software)
## 循环展开
循环展开通过将循环体代码复制多次更好地实现数据预取，该方法牺牲了程序的尺寸，但可以加快程序的执行速度。
## 实验过程
SM3算法实现参考<https://blog.csdn.net/qq_43710705/article/details/103915133><br>
对其进行循环展开优化。
## 运行指导
SM3.py和SM3_optimization.py分别直接运行
## 结果展示
优化前：<br>
<img width="415" alt="image" src="https://user-images.githubusercontent.com/110109750/182010448-046f537a-e5ff-4005-8a84-7cded88edd51.png"><br>
优化后：<br>
<img width="416" alt="image" src="https://user-images.githubusercontent.com/110109750/182010456-e9f28ff4-e4df-4834-a823-eb57b2551b1e.png"><br>
可以看出优化效果不太理想
## 参考文献
[SM3的python实现](https://blog.csdn.net/qq_43710705/article/details/103915133)<br>
## 具体贡献说明
对SM3算法的优化均由本人编写
