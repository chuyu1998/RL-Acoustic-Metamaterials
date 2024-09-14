# RL-RL-Acoustic-Metamaterials
This program constructs a multi-agent deep reinforcement learning model that enables the reverse design of acoustic metamaterials with customizable absorption coefficients.To facilitate user operation, we designed a MATLAB-APP program.For more details, please refer to the README file.
# 强化学习驱动的声学超材料逆向设计
# Reinforcement-Learning-Driven-Inverse-Design-of-Acoustic-Metamaterials  

## 简介/Introduction:
这个程序构建了一个多智能体深度强化学习模型，可以实现可定制任意吸声系数的声学超材料逆向设计。为了更方便用户操作，我们设计了一个MATLAB小程序。希望这个程序能够帮助声学超材料设计者和研究者更方便的进行设计和研究。  

This program constructs a multi-agent deep reinforcement learning model that enables the reverse design of acoustic metamaterials with customizable absorption coefficients.To facilitate user operation, we designed a MATLAB-APP program.It is hoped that this program can assist acoustic metamaterial designers and researchers in conducting their design and research more conveniently.  

## 使用条件/Usage Conditions：  
本程序基于matlab编写，使用版本为R2023b。  
This program is written in MATLAB, using version R2023b.

## 使用说明/Program Usage Instructions：  
1.点击***RL-RL-Acoustic-Metamaterials***即可自动在matlab中安装该APP;
2.打开并运行程序可以看到如**图1**所示的程序界面;  
3.可以点击坐标内任何位置，设置设计目标；也可以在右边手动输入设计目标的频率和吸声系数，如**图2**所示;
4.左边是一些可设置的参数，比如模型运行的回合数、厚度和状态误差的权重因子等;  
5.当然也可以保持默认状态，设定好之后可以点击***run model***;  
6.最后模型将评分最高的逆向设计结果参数展示在界面的下方，其吸声系数曲线会展示在坐标轴界面上，如**图3**所示。    

1.Click ***RL-RL-Acoustic-Metamaterials*** to automatically install the app in MATLAB;  
2.Opening and running the program will display the interface shown in **Figure 1**;     
3.You can click anywhere within the coordinates to set the design target; you can also manually enter the frequency and absorption coefficient of the design target on the right side, as shown in **Figure 2**;    
4.The left side contains several configurable parameters, such as the number of episodes for the model, thickness, and the weight factors for state error, etc;    
5.Of course, you can also keep the default settings, and after configuring, you can click ***run model***;    
6.Finally, the model displays the parameters of the highest-scoring inverse design results at the bottom of the interface, and its absorption coefficient curve will be shown on the coordinate axes, as illustrated in ***Figure 3***；

![image text](https://github.com/chuyu1998/RL-Acoustic-Metamaterials/blob/main/App_figure/program%20interface.png)  
**figure1 program interface**
![image text](https://github.com/chuyu1998/RL-Acoustic-Metamaterials/blob/main/App_figure/design%20objective-2.png)
**figure2 Design objectives**  
![image text](https://github.com/chuyu1998/RL-Acoustic-Metamaterials/blob/main/App_figure/Design%20results-2.png)
**figure3 Design result**  
