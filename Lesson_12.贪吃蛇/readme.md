# 贪吃蛇  

打工人忙里偷闲，按照自己的思路写了贪吃蛇。没有看网上的经典代码，可能存在很多BUG。
本程序的主要目的是帮助大家理解Qt编程思路。  

----- 

## 概述  

* 目录下resources为资源文件，保存了贪吃蛇所需的贴图  
* 使用按钮来表示贪吃蛇的每个单元，按钮贴图来区分蛇头、蛇身和食物
* 定时器溢出事件驱动按钮移动
* 将二维坐标转换为一维数组来方便判定是否位于蛇身上
* Tips：PyCharm 插件 Rainbow Brackets 真好用
