* # 1 机器人通识
    <small> _目标：让同学对机器人和机器人学相关概念有基本的认识_ </small>
    * ## 1.1 关于机器人学
        * ### 1.1.1 简介
            * __机器人学__ _（英语：robotics）_ 是一项涵盖了机器人的 __设计、建造、运作、以及应用__ 的 __跨领域科技__ ，集合 __机械工程学、电机工程学、机械电子学、电子学、控制工程学、计算机工程学、软件工程学、资讯工程学、数学及生物工程学__ 等领域。这些科技催生出能够取代人力的自动化机器，在危险境或制造工厂运作，或塑造成外表、行为、心智的仿人机器人。现今许多机器人都是受到自然界的启发，致力于仿生机器人学领域的发展。
    * ## 1.2 关于机器人
        * ### 1.2.1 简介
            * __机器人__ _（英语：Robot）_ 包括一切模拟人类行为或思想与模拟其他生物的机械（如机器狗、机器猫等）。狭义上对机器人的定义还有很多分类法及争议，有些电脑程序甚至也被称为机器人。在当代工业中，机器人指能自动执行任务的人造机器设备，用以取代或协助人类工作，一般会是机电设备，由计算机程序或是电子电路控制。
            * 机器人的范围很广，可以是自主或是半自主的，可以从本田技研工业的ASIMO或是TOSY的TOPIO等拟人机器人到工业机器人，也包括多台一起动作的群机器人，其至是纳米机器人。借由模仿逼真的外观及自动化的动作，理想中的高仿真机器人是 __高级集成控制论、机械电子、计算机与人工智能、材料学__ 和 __仿生学__ 的产物，目前科学界正在向此方向研究开发。有关机器人的话题，常见于科幻作品中。
        * ### 1.2.2 附录
            * #### 不同形态机器人的宣传片展示
                * ##### 来自Boston Dynamics的人型机器人
                    <iframe src="//player.bilibili.com/player.html?aid=717482140&bvid=BV1JQ4y1m7ha&cid=391312742&p=1&autoplay=0&muted=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="ture" width="700px" height="472px" > </iframe>
                * ##### 来自ARX方舟无限的小型六自由度机械臂
                    <iframe src="//player.bilibili.com/player.html?aid=234804389&bvid=BV1L8411r7kM&cid=1303278223&p=1&autoplay=0&muted=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true" width="700px" height="472px" > </iframe>
                * ##### 来自TOE RM战队的平衡步兵
                    <iframe src="//player.bilibili.com/player.html?aid=576655087&bvid=BV1zz4y1G7N4&cid=1288058553&p=1&autoplay=0&muted=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true" width="700px" height="472px" > </iframe>
                    <iframe src="//player.bilibili.com/player.html?aid=597593654&bvid=BV1fB4y1S7vN&cid=749933315&p=1&autoplay=0&muted=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true" width="700px" height="472px"> </iframe>
                * ##### 来自Boston Dynamics的四足机器人SpotMini
                    <iframe src="//player.bilibili.com/player.html?aid=34035646&bvid=BV1ct411f7TJ&cid=59610157&p=1&autoplay=0&muted=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true" width="700px" height="472px"> </iframe>
    * ## 1.3 机器人的系统分析
        * ### 1.2.1机器人系统的组成
            * __三大部分__
                * 机械部分
                _包括机械传动结构、执行器（电机、气动/液压系统）_
                * 传感部分
                _包括压力传感器、摄像头、编码器、陀螺仪、激光雷达等_
                * 控制部分
                _包括控制电路，采样电路，嵌入式控制系统等_
            * __六个子系统__
                * 驱动系统
                * 机械结构系统
                * 感受系统
                * 机器人-环境交互系统
                * 人机交互系统和控制系统
    * ## 1.4 机器人学需要的技术栈 
        * ### 1.4.1 技术栈 
            * #### 机械方向 
                * 相对熟练地使用三维建模软件
                * 学会齿轮等基础传动系统
                * 学会轴系设计              
                * 学会使用三维建模软件做简单的应力分析
                * 学会使用三维建模软件做简单的轻量化设计
                * 学会连杆运动关系的计算并使用仿真软件优化传动结构
                * 学会设计复杂机械结构（如紧凑型行星减速器等）
            
            <small> _tip：以上排序由易向难（个人观点）_ </small>
            * #### 电控方向
                * 相对熟练地使用C语言
                * 学会嵌入式开发 Arduino
                * 对pid控制有基本认识
                * 学会嵌入式开发 stm32 hal库
                * 学会在stm32上使用freertos<br>
                <small> _这里有一个岔路_ </small>
                *（偏硬件）
                    * 相对熟练地使用立创eda/AD等电路设计软件
                    * 学会stm32最小系统板及其外围电路（如can协议收发）等设计
                    * 学会设计无刷电机驱动
                    * 学会高速线路layout和开关电源设计
                *（偏软件）
                    * 相对熟练地使用C++、Python
                    * 相对熟练地使用linux系统
                    * 学会使用ROS进行机器人控制系统设计
                    * 学会使用仿真环境进行机器人控制系统设计
                    * 学会机器视觉相关算法的实现
                    * 学会使用高级的机器人控制算法如LQR MPC VMC
                    * 学会SLAM相关算法的实现<br>
            
            <small> _tip：以上排序由易向难（个人观点）_ </small>
            * #### 数理基础
                * __微积分__、__线性代数__ 、__理论力学__
                * 概率论、图论、__多元微积分__
                * __最优估计__ 、微分几何 、计算几何、运筹学等<br>
            
            <small> _tip：画重点的个人认为使用频次较高_ </small>
        * ### 1.4.2 附录（推荐阅读）：
            * [电子入坑百科全书](https://www.emoe.xyz/all-about-electronics/#10-gt-gt)
            * [机器人工程师学习计划-知乎-YY硕](https://zhuanlan.zhihu.com/p/22266788)
    * ## 1.5 赠言
        

    