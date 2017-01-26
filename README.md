# RoutePlanner
A Route Planning System for logistics companies that could make a plan of the shortest route or the shortest time.
该项目旨在为物流公司货车规划最优行进路线，可按最短距离、最短时间两种方案进行规划，其次系统还能根据用户标注的路况（堵车级别：非常拥挤、较拥挤、一般、通畅）动态调整路线。

## Functions
用户可以在右侧的地图上任意标注仓库地址（黑白旗）和客户地址（橙色旗），在左侧输入配送的基本数据，选择规划方案，点击寻路，右侧地图上将同步模拟配送路线，即先从仓库出发，先后到达所有客户地址，最终返回仓库的过程，而在配送过程中用户可以对道路的堵车级别进行标注，系统能权衡当前路况、规划方案、当前所在位置、客户地址等多方面因素，自适应地规划出新的路线，并同步显示。

## Screenshot
![](http://yaochenkun.cn/wordpress/wp-content/uploads/2016/07/pathplan.jpg)
![](http://yaochenkun.cn/wordpress/wp-content/uploads/2016/07/pathplan2.jpg)

## Download and Run


## Environment and Configurations
1. 
2. 
3. 

## Key Points
1. Astar Algorithm(A星算法): 一种在图形平面上，有多个节点的路径，求出最低通过成本的算法。在本项目中用来启发式搜索任意两个节点间的最短路径。
2. TSP(旅行商问题): 从某个位置出发，依次拜访若干不同位置一次且仅一次，最终回到起始位置的问题。本项目算法原型可以抽象为TSP。
3. Genetic Algorithm(遗传算法): 遗传算法模拟自然选择和自然遗传过程中发生的繁殖、交叉和基因突变现象，在每次迭代中都保留一组候选解，并按某种指标从解群中选取较优的个体，利用遗传算子( 选择、交叉和变异) 对这些个体进行组合，产生新一代的候选解群，重复此过程，直到满足某种收敛指标为止。本项目采用该算法求解TSP，最终达到路径规划。

## For More
If you want to learn more about this program, you'd better refer to XX to have a further look.
