两个测试集均适配platemo 平台
CEC2017-BoundContrained测试集步骤 
前置步骤：[安装mex插件] (https://blog.csdn.net/M_try/article/details/88944673 得配环境 )

解压到PlatEMO\Problems\Single-objective optimization目录下
![image](https://github.com/user-attachments/assets/990ecf59-08b6-4fc0-a842-485ae874eb4e)

切到该路径文件路径下：
运行   mex cec17_func.cpp -DWINDOWS 成功则可以在 平台上使用
该问题的结果不是误差值f(x)-f(*) 而是f(x)。
例如F1 的最优结果是100 某算法结果105 要想算误差值得自己再手动计算105-100=5。
该问题为CEC2017-BoundContrained 优化问题 包含函数F1,F3-F30.F2因为不稳定 已经剔除。
参考链接 https://github.com/P-N-Suganthan/CEC2017-BoundContrained
论文链接 https://ieeexplore.ieee.org/document/7969456/

cec2020RW步骤：
解压到PlatEMO\Problems\Single-objective optimization目录下

![image](https://github.com/user-attachments/assets/990ecf59-08b6-4fc0-a842-485ae874eb4e)

参考链接 https://github.com/P-N-Suganthan/2020-RW-Constrained-Optimisation

使用情况：
![image](https://github.com/user-attachments/assets/c8f2bcce-49c7-4b4c-ba6d-5a56217b2ac7)


其中NAN是算法并没有找到没有不违背约束值的解，在函数F1中有具体演示看是否违背了约束解



改写不易 希望大佬点个star


